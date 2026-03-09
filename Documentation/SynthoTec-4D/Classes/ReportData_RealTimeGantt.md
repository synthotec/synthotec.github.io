---
layout : default
title : ReportData_RealTimeGantt
parent : Classes
---
# ReportData_RealTimeGantt [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_RealTimeGantt.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 16 Functions

## 📝 Description

Report dataset producing Gantt-style machine timeline blocks from RealTime cycle and downtime records. Adjacent blocks are merged, tool changes are flagged, and optional full-day production and pending fill blocks are added for Power Query Gantt chart visualisation.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.386Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [tryCombine](#trycombine) (2 params)
    - [getWeekStart](#getweekstart) (1 param) → `$WeekStartDate : Date`
    - [getBlockType](#getblocktype) (1 param) → `Text`
    - [generateProductionBlock](#generateproductionblock) (2 params) → `Object`
    - [fixCycleTime](#fixcycletime) (1 param) → `Real`
    - [populateFromRealTimeRecords](#populatefromrealtimerecords)
    - [processCombinedBlocksAndProduction](#processcombinedblocksandproduction)
    - [checkToolChange](#checktoolchange) (2 params)
    - [processBlocksForDateAndMachine](#processblocksfordateandmachine) (2 params)
    - [timeToSeconds](#timetoseconds) (1 param) → `Integer`
    - [isMachineRunning](#ismachinerunning) (1 param) → `Boolean`
    - [calculateStoppageStartDateTime](#calculatestoppagestartdatetime) (1 param) → `Text`
    - [getEndTimeForBlockOnDate](#getendtimeforblockondate) (2 params) → `Time`
    - [getNextBlockStartTime](#getnextblockstarttime) (2 params) → `Object`
    - [generatePendingBlocks](#generatependingblocks)
    - [createStoppageBlocks](#createstoppageblocks) (3 params)
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `LookBackDays` | `Integer` | `100` | Number of days to look back when loading RealTime stoppage records |
| `GenerateProductionBlocks` | `Boolean` | `True` | When True, adds a full-day production block for each date/machine combination |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Parameters : Object)
```

Loads machine stoppage events, combines adjacent blocks, flags tool changes, and optionally adds production and pending blocks for Gantt display

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### tryCombine {#trycombine}


```4d
Function tryCombine($Object : Object; $PreviousObject : Object)
```

Merges $Object into $PreviousObject if they are adjacent, same works order, block type, and combined duration is under 24h; marks previous as excluded

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Object` | `Object` | - | - |
| `$PreviousObject` | `Object` | - | - |

---

#### getWeekStart {#getweekstart}


```4d
Function getWeekStart($Date : Date) -> $WeekStartDate : Date
```

Returns the Monday date for the week containing $Date

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |

**Returns:** `Date`

---

#### getBlockType {#getblocktype}


```4d
Function getBlockType($RealTimeEntity : cs.RealTimeEntity) -> Text
```

Classifies a RealTime record as UNIDENTIFIED, WEEKEND, PLANNED, UNPLANNED, or a custom block type defined on the DownReasons entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeEntity` | `cs.RealTimeEntity` | - | - |

**Returns:** `Text`

---

#### generateProductionBlock {#generateproductionblock}


```4d
Function generateProductionBlock($Machine : Integer; $Date : Date) -> Object
```

Returns a PRODUCTION-type block object spanning the full day (midnight to midnight, or current time if today) for the given machine and date

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Machine` | `Integer` | - | - |
| `$Date` | `Date` | - | - |

**Returns:** `Object`

---

#### fixCycleTime {#fixcycletime}


```4d
Function fixCycleTime($RealTimeEntity : cs.RealTimeEntity) -> Real
```

Returns the cycle time adjusted by +1 second for records that end exactly at 23:59:59 or 05:59:59 to account for boundary rounding

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeEntity` | `cs.RealTimeEntity` | - | - |

**Returns:** `Real`

---

#### populateFromRealTimeRecords {#populatefromrealtimerecords}


```4d
Function populateFromRealTimeRecords
```

Queries RealTime stoppages within the lookback window and pushes formatted block objects into Collection

---

#### processCombinedBlocksAndProduction {#processcombinedblocksandproduction}


```4d
Function processCombinedBlocksAndProduction
```

Iterates each date/machine pair to combine adjacent blocks, detect tool changes, and insert production blocks

---

#### checkToolChange {#checktoolchange}


```4d
Function checkToolChange($Object : Object; $PreviousObject : Object)
```

Marks adjacent objects as TOOL CHANGE block type when the works order changes between them in the same day

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Object` | `Object` | - | - |
| `$PreviousObject` | `Object` | - | - |

---

#### processBlocksForDateAndMachine {#processblocksfordateandmachine}


```4d
Function processBlocksForDateAndMachine($EndDate : Date; $Machine : Integer)
```

Processes all blocks for a specific date and machine in chronological order, applying tool-change detection and block combining

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EndDate` | `Date` | - | - |
| `$Machine` | `Integer` | - | - |

---

#### timeToSeconds {#timetoseconds}


```4d
Function timeToSeconds($Time : Time) -> Integer
```

Converts a 4D Time value to total seconds (integer) using implicit Time-to-Integer coercion

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Time` | `Time` | - | - |

**Returns:** `Integer`

---

#### isMachineRunning {#ismachinerunning}


```4d
Function isMachineRunning($RealTimeMachinesEntity : cs.RealTimeMachinesEntity) -> Boolean
```

Returns True if the machine is actively running (AutoStatus enabled and last activity within 2 minutes)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |

**Returns:** `Boolean`

---

#### calculateStoppageStartDateTime {#calculatestoppagestartdatetime}


```4d
Function calculateStoppageStartDateTime($RealTimeMachinesEntity : cs.RealTimeMachinesEntity) -> Text
```

LastActivity is stored as a datetime string, return it as-is for StartDateTime

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |

**Returns:** `Text`

---

#### getEndTimeForBlockOnDate {#getendtimeforblockondate}


```4d
Function getEndTimeForBlockOnDate($BlockDate : Date; $BlockStartTime : Time) -> Time
```

Determine the end time based on date and block start time

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BlockDate` | `Date` | - | - |
| `$BlockStartTime` | `Time` | - | - |

**Returns:** `Time`

---

#### getNextBlockStartTime {#getnextblockstarttime}


```4d
Function getNextBlockStartTime($BlockDate : Date; $BlockStartTime : Time) -> Object
```

Determine next block's date and start time after the current block

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BlockDate` | `Date` | - | - |
| `$BlockStartTime` | `Time` | - | - |

**Returns:** `Object`

---

#### generatePendingBlocks {#generatependingblocks}


```4d
Function generatePendingBlocks
```

Generates PENDING-type stoppage blocks from the last known stoppage start until now for any currently-stopped enabled machines

---

#### createStoppageBlocks {#createstoppageblocks}


```4d
Function createStoppageBlocks($RealTimeMachinesEntity : cs.RealTimeMachinesEntity; $StartDate : Date; $StartTime : Time)
```

Creates one or more PENDING-type blocks spanning from the given start date/time until now, splitting at midnight and day-shift boundaries

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |
| `$StartDate` | `Date` | - | - |
| `$StartTime` | `Time` | - | - |

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_RealTimeGantt

---

*Generated from ReportData_RealTimeGantt.4dm*

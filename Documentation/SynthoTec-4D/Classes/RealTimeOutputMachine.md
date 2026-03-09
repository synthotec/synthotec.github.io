---
layout : default
title : RealTimeOutputMachine
parent : Classes
---
# RealTimeOutputMachine [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeOutputMachine.4dm)

📊 **Overview:** 10 Properties | 1 Constructor | 6 Functions | 16 Getters

## 📝 Description

Encapsulates real-time dashboard data for a single machine, calculating colour-coded status indicators, current works order details, average cycle time, running-slow flags, quantity made/scrapped, and downtime reason for display on the production dashboard.

🕐 *Last updated: 2026-03-09T14:45:31.072Z*

---

## 📑 Table of Contents

- [📋 Properties (10)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [ProcessColors](#processcolors)
    - [setPrimaryColors](#setprimarycolors) (2 params)
    - [setAlternatingColors](#setalternatingcolors) (2 params)
    - [setDateTimeColors](#setdatetimecolors) (2 params)
    - [setAlertColors](#setalertcolors) (2 params)
    - [setTimeRemainingText](#settimeremainingtext) (3 params)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [AlertsText](#alertstext) 🔍 → `Text`
    - [DeviceMaintenanceActive](#devicemaintenanceactive) 🔍 → `Boolean`
    - [MachineDisconnected](#machinedisconnected) 🔍 → `Boolean`
    - [MachineNumberText](#machinenumbertext) 🔍 → `Text`
    - [MachineRunning](#machinerunning) 🔍 → `Boolean`
    - [MouldStatusText](#mouldstatustext) 🔍 → `Text`
    - [PartNameText](#partnametext) 🔍 → `Text`
    - [PartsMadeText](#partsmadetext) 🔍 → `Text`
    - [PercentMade](#percentmade) 🔍 → `Real`
    - [PrimaryStatusText](#primarystatustext) 🔍 → `Text`
    - [ScrapText](#scraptext) 🔍 → `Text`
    - [SecondaryStatusText](#secondarystatustext) 🔍 → `Object`
    - [TimeRemainingText](#timeremainingtext) 🔍 → `Object`
    - [UnacknowledgedSensorExceptions](#unacknowledgedsensorexceptions) 🔍 → `Boolean`
    - [UnicodeSymbolsText](#unicodesymbolstext) 🔍 → `Text`
    - [WorksOrderIsOpen](#worksorderisopen) 🔍 → `Boolean`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | Machine being monitored |
| `WorksOrderEntity` | `cs.WorksOrderEntity` | - | Current works order on machine, can be Null if no order active |
| `ProductEntity` | `cs.ProductEntity` | - | Product being manufactured, Null if no order active |
| `ToolsEntity` | `cs.ToolsEntity` | - | Tool being used, Null if no order active |
| `DownReasonsEntity` | `cs.DownReasonsEntity` | - | Current downtime reason if machine stopped, otherwise Null |
| `AverageCycleTime` | `Real` | - | Average cycle time over recent cycles in seconds |
| `RunningSlow` | `Boolean` | - | True if average cycle time exceeds tool's target cycle time |
| `MachineWheelsEntity` | `cs.MachineWheelsEntity` | - | Machine wheel/priority configuration |
| `QuantityMade` | `Integer` | - | Total quantity produced on current works order |
| `QuantityScrapped` | `Integer` | - | Total quantity scrapped on current works order |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($RealTimeMachinesEntity : cs.RealTimeMachinesEntity)
```

Creates real-time output object for displaying machine status on dashboard, calculates colors and metrics

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |

---

## Functions {#functions}

### Regular Functions

#### ProcessColors {#processcolors}


```4d
Function ProcessColors
```

Determines background and foreground colors for machine display based on machine state, downtime, temperature exceptions, etc.

---

#### setPrimaryColors {#setprimarycolors}


```4d
Function setPrimaryColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

Sets primary background and foreground colors for machine card display

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BackgroundColor` | `Integer` | - | - |
| `$ForegroundColor` | `Integer` | - | - |

---

#### setAlternatingColors {#setalternatingcolors}


```4d
Function setAlternatingColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

Sets alternating row background and foreground colors for machine details display

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BackgroundColor` | `Integer` | - | - |
| `$ForegroundColor` | `Integer` | - | - |

---

#### setDateTimeColors {#setdatetimecolors}


```4d
Function setDateTimeColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

Sets datetime section background and foreground colors for status display

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BackgroundColor` | `Integer` | - | - |
| `$ForegroundColor` | `Integer` | - | - |

---

#### setAlertColors {#setalertcolors}


```4d
Function setAlertColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

Sets alert/exception background and foreground colors for warnings display

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BackgroundColor` | `Integer` | - | - |
| `$ForegroundColor` | `Integer` | - | - |

---

#### setTimeRemainingText {#settimeremainingtext}


```4d
Function setTimeRemainingText($Text : Text; $DateTime : Variant; $AdditionalSeconds : Real)
```

Sets time remaining display text with optional datetime and additional seconds offset for ETA calculation

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Text` | `Text` | - | - |
| `$DateTime` | `Variant` | - | - |
| `$AdditionalSeconds` | `Real` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### AlertsText {#alertstext}
 `[🔍 get only]`

```4d
Function get AlertsText -> Text
```

Returns formatted alerts text showing setter queue, connected/assigned temperature sensors; empty if no works order

**Returns:** `Text`

---

#### DeviceMaintenanceActive {#devicemaintenanceactive}
 `[🔍 get only]`

```4d
Function get DeviceMaintenanceActive -> Boolean
```

Returns true if device is in maintenance mode (negative DownReasonID); indicates scheduled downtime

**Returns:** `Boolean`

---

#### MachineDisconnected {#machinedisconnected}
 `[🔍 get only]`

```4d
Function get MachineDisconnected -> Boolean
```

Returns true if machine hasn't sent data pulse in 2+ minutes; indicates communication loss

**Returns:** `Boolean`

---

#### MachineNumberText {#machinenumbertext}
 `[🔍 get only]`

```4d
Function get MachineNumberText -> Text
```

Returns machine number as formatted string for display

**Returns:** `Text`

---

#### MachineRunning {#machinerunning}
 `[🔍 get only]`

```4d
Function get MachineRunning -> Boolean
```

Returns true if machine is actively running (AutoStatus true and recent activity within 2 minutes)

**Returns:** `Boolean`

---

#### MouldStatusText {#mouldstatustext}
 `[🔍 get only]`

```4d
Function get MouldStatusText -> Text
```

Returns mould status indicator: filled circle if closed, open circle with impressions per cycle if running

**Returns:** `Text`

---

#### PartNameText {#partnametext}
 `[🔍 get only]`

```4d
Function get PartNameText -> Text
```

Returns product name or trial indicator; shows 'MACHINE DISCONNECTED' or 'NO WORKS ORDER STARTED' if applicable

**Returns:** `Text`

---

#### PartsMadeText {#partsmadetext}
 `[🔍 get only]`

```4d
Function get PartsMadeText -> Text
```

Returns formatted text showing parts made vs production target; empty if no works order

**Returns:** `Text`

---

#### PercentMade {#percentmade}
 `[🔍 get only]`

```4d
Function get PercentMade -> Real
```

Returns production progress as decimal ratio (0-1) based on quantity made vs production target

**Returns:** `Real`

---

#### PrimaryStatusText {#primarystatustext}
 `[🔍 get only]`

```4d
Function get PrimaryStatusText -> Text
```

Returns primary status display text for machine card with emoji prefix/suffix; shows running, down reason, temperature alerts, or robot issues

**Returns:** `Text`

---

#### ScrapText {#scraptext}
 `[🔍 get only]`

```4d
Function get ScrapText -> Text
```

Returns formatted scrap quantity text with percentage if scrapped items exist; empty string if no works order

**Returns:** `Text`

---

#### SecondaryStatusText {#secondarystatustext}
 `[🔍 get only]`

```4d
Function get SecondaryStatusText -> $DateTimeObject : Object
```

Returns object with status text template and datetime for secondary status line (e.g., last activity, temperature exceptions)

**Returns:** `Object`

---

#### TimeRemainingText {#timeremainingtext}
 `[🔍 get only]`

```4d
Function get TimeRemainingText -> $DateTimeObject : Object
```

Returns object with time remaining text template and calculated ETA based on remaining production and cycle time

**Returns:** `Object`

---

#### UnacknowledgedSensorExceptions {#unacknowledgedsensorexceptions}
 `[🔍 get only]`

```4d
Function get UnacknowledgedSensorExceptions -> Boolean
```

Returns true if works order is open and has unacknowledged temperature sensor exceptions

**Returns:** `Boolean`

---

#### UnicodeSymbolsText {#unicodesymbolstext}
 `[🔍 get only]`

```4d
Function get UnicodeSymbolsText -> Text
```

Returns product emoji character if works order open; used for visual product identification

**Returns:** `Text`

---

#### WorksOrderIsOpen {#worksorderisopen}
 `[🔍 get only]`

```4d
Function get WorksOrderIsOpen -> Boolean
```

Returns true if machine is connected and has an open, running works order assigned

**Returns:** `Boolean`

---

---

*Generated from RealTimeOutputMachine.4dm*

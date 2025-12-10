---
layout : default
title : RealTimeOutputMachine
parent : Classes
---
# RealTimeOutputMachine [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeOutputMachine.4dm)

📊 **Overview:** 10 Properties | 1 Constructor | 6 Functions | 16 Getters

## 📝 Description

Creates real-time output object for displaying machine status on dashboard, calculates colors and metrics

🕐 *Last updated: 2025-12-10T11:45:24.149Z*

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

**Returns:** `Text`

---

#### DeviceMaintenanceActive {#devicemaintenanceactive}
 `[🔍 get only]`

```4d
Function get DeviceMaintenanceActive -> Boolean
```

**Returns:** `Boolean`

---

#### MachineDisconnected {#machinedisconnected}
 `[🔍 get only]`

```4d
Function get MachineDisconnected -> Boolean
```

**Returns:** `Boolean`

---

#### MachineNumberText {#machinenumbertext}
 `[🔍 get only]`

```4d
Function get MachineNumberText -> Text
```

**Returns:** `Text`

---

#### MachineRunning {#machinerunning}
 `[🔍 get only]`

```4d
Function get MachineRunning -> Boolean
```

**Returns:** `Boolean`

---

#### MouldStatusText {#mouldstatustext}
 `[🔍 get only]`

```4d
Function get MouldStatusText -> Text
```

**Returns:** `Text`

---

#### PartNameText {#partnametext}
 `[🔍 get only]`

```4d
Function get PartNameText -> Text
```

**Returns:** `Text`

---

#### PartsMadeText {#partsmadetext}
 `[🔍 get only]`

```4d
Function get PartsMadeText -> Text
```

**Returns:** `Text`

---

#### PercentMade {#percentmade}
 `[🔍 get only]`

```4d
Function get PercentMade -> Real
```

**Returns:** `Real`

---

#### PrimaryStatusText {#primarystatustext}
 `[🔍 get only]`

```4d
Function get PrimaryStatusText -> Text
```

**Returns:** `Text`

---

#### ScrapText {#scraptext}
 `[🔍 get only]`

```4d
Function get ScrapText -> Text
```

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

**Returns:** `Object`

---

#### UnacknowledgedSensorExceptions {#unacknowledgedsensorexceptions}
 `[🔍 get only]`

```4d
Function get UnacknowledgedSensorExceptions -> Boolean
```

**Returns:** `Boolean`

---

#### UnicodeSymbolsText {#unicodesymbolstext}
 `[🔍 get only]`

```4d
Function get UnicodeSymbolsText -> Text
```

**Returns:** `Text`

---

#### WorksOrderIsOpen {#worksorderisopen}
 `[🔍 get only]`

```4d
Function get WorksOrderIsOpen -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from RealTimeOutputMachine.4dm*

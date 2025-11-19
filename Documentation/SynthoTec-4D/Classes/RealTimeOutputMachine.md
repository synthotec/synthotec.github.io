---
layout : default
title : RealTimeOutputMachine
parent : Classes
---
# RealTimeOutputMachine [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeOutputMachine.4dm)

📊 **Overview:** 10 Properties | 1 Constructor | 6 Functions | 16 Getters

## 📝 Description

MARK:Primary Colors

🕐 *Last updated: 2025-11-19T21:53:03.980Z*

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
| `RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |
| `WorksOrderEntity` | `cs.WorksOrderEntity` | - | - |
| `ProductEntity` | `cs.ProductEntity` | - | - |
| `ToolsEntity` | `cs.ToolsEntity` | - | - |
| `DownReasonsEntity` | `cs.DownReasonsEntity` | - | - |
| `AverageCycleTime` | `Real` | - | - |
| `RunningSlow` | `Boolean` | - | - |
| `MachineWheelsEntity` | `cs.MachineWheelsEntity` | - | - |
| `QuantityMade` | `Integer` | - | - |
| `QuantityScrapped` | `Integer` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($RealTimeMachinesEntity : cs.RealTimeMachinesEntity)
```

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

MARK:Primary Colors

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

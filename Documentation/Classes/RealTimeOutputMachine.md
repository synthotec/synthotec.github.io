---
layout : default
title : RealTimeOutputMachine
parent : Classes
---
# RealTimeOutputMachine

📊 **Overview:** 10 Properties | 1 Constructor | 6 Functions | 16 Getters

## 📝 Description

🗨️ MARK:Primary Colors

🕐 *Last updated: 2025-11-13T14:26:50.687Z*

---

## 📑 Table of Contents

- [📋 Properties (10)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (6):**

- [ProcessColors](#processcolors)
- [setPrimaryColors](#setprimarycolors) (2 params)
- [setAlternatingColors](#setalternatingcolors) (2 params)
- [setDateTimeColors](#setdatetimecolors) (2 params)
- [setAlertColors](#setalertcolors) (2 params)
- [setTimeRemainingText](#settimeremainingtext) (3 params)

**🔍 Getters (16):**

- [SecondaryStatusText](#secondarystatustext) → `Object`
- [TimeRemainingText](#timeremainingtext) → `Object`
- [DeviceMaintenanceActive](#devicemaintenanceactive) → `Boolean`
- [MachineDisconnected](#machinedisconnected) → `Boolean`
- [MachineRunning](#machinerunning) → `Boolean`
- [WorksOrderIsOpen](#worksorderisopen) → `Boolean`
- [UnacknowledgedSensorExceptions](#unacknowledgedsensorexceptions) → `Boolean`
- [PrimaryStatusText](#primarystatustext) → `Text`
- [ScrapText](#scraptext) → `Text`
- [PartsMadeText](#partsmadetext) → `Text`
- [AlertsText](#alertstext) → `Text`
- [PercentMade](#percentmade) → `Real`
- [MouldStatusText](#mouldstatustext) → `Text`
- [MachineNumberText](#machinenumbertext) → `Text`
- [PartNameText](#partnametext) → `Text`
- [UnicodeSymbolsText](#unicodesymbolstext) → `Text`

---

## 📋 Properties

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

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

### 🔍 Getters

#### SecondaryStatusText {#secondarystatustext}
 `[🔍 getter]`

```4d
Function SecondaryStatusText -> $DateTimeObject : Object
```

**Returns:** `Object`

---

#### TimeRemainingText {#timeremainingtext}
 `[🔍 getter]`

```4d
Function TimeRemainingText -> $DateTimeObject : Object
```

**Returns:** `Object`

---

#### DeviceMaintenanceActive {#devicemaintenanceactive}
 `[🔍 getter]`

```4d
Function DeviceMaintenanceActive -> Boolean
```

**Returns:** `Boolean`

---

#### MachineDisconnected {#machinedisconnected}
 `[🔍 getter]`

```4d
Function MachineDisconnected -> Boolean
```

**Returns:** `Boolean`

---

#### MachineRunning {#machinerunning}
 `[🔍 getter]`

```4d
Function MachineRunning -> Boolean
```

**Returns:** `Boolean`

---

#### WorksOrderIsOpen {#worksorderisopen}
 `[🔍 getter]`

```4d
Function WorksOrderIsOpen -> Boolean
```

**Returns:** `Boolean`

---

#### UnacknowledgedSensorExceptions {#unacknowledgedsensorexceptions}
 `[🔍 getter]`

```4d
Function UnacknowledgedSensorExceptions -> Boolean
```

**Returns:** `Boolean`

---

#### PrimaryStatusText {#primarystatustext}
 `[🔍 getter]`

```4d
Function PrimaryStatusText -> Text
```

**Returns:** `Text`

---

#### ScrapText {#scraptext}
 `[🔍 getter]`

```4d
Function ScrapText -> Text
```

**Returns:** `Text`

---

#### PartsMadeText {#partsmadetext}
 `[🔍 getter]`

```4d
Function PartsMadeText -> Text
```

**Returns:** `Text`

---

#### AlertsText {#alertstext}
 `[🔍 getter]`

```4d
Function AlertsText -> Text
```

**Returns:** `Text`

---

#### PercentMade {#percentmade}
 `[🔍 getter]`

```4d
Function PercentMade -> Real
```

**Returns:** `Real`

---

#### MouldStatusText {#mouldstatustext}
 `[🔍 getter]`

```4d
Function MouldStatusText -> Text
```

**Returns:** `Text`

---

#### MachineNumberText {#machinenumbertext}
 `[🔍 getter]`

```4d
Function MachineNumberText -> Text
```

**Returns:** `Text`

---

#### PartNameText {#partnametext}
 `[🔍 getter]`

```4d
Function PartNameText -> Text
```

**Returns:** `Text`

---

#### UnicodeSymbolsText {#unicodesymbolstext}
 `[🔍 getter]`

```4d
Function UnicodeSymbolsText -> Text
```

**Returns:** `Text`

---

---

*Generated from RealTimeOutputMachine.4dm*

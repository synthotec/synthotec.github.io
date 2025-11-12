# RealTimeOutputMachine

## Description

MARK:Primary Colors

## Table of Contents

### Properties

- [RealTimeMachinesEntity](#realtimemachinesentity)
- [WorksOrderEntity](#worksorderentity)
- [ProductEntity](#productentity)
- [ToolsEntity](#toolsentity)
- [DownReasonsEntity](#downreasonsentity)
- [AverageCycleTime](#averagecycletime)
- [RunningSlow](#runningslow)
- [MachineWheelsEntity](#machinewheelsentity)
- [QuantityMade](#quantitymade)
- [QuantityScrapped](#quantityscrapped)

### Functions

- [constructor() [constructor]](#constructor)
- [ProcessColors()](#processcolors)
- [SecondaryStatusText() [getter]](#secondarystatustext)
- [TimeRemainingText() [getter]](#timeremainingtext)
- [setPrimaryColors()](#setprimarycolors)
- [setAlternatingColors()](#setalternatingcolors)
- [setDateTimeColors()](#setdatetimecolors)
- [setAlertColors()](#setalertcolors)
- [DeviceMaintenanceActive() [getter]](#devicemaintenanceactive)
- [MachineDisconnected() [getter]](#machinedisconnected)
- [MachineRunning() [getter]](#machinerunning)
- [WorksOrderIsOpen() [getter]](#worksorderisopen)
- [UnacknowledgedSensorExceptions() [getter]](#unacknowledgedsensorexceptions)
- [PrimaryStatusText() [getter]](#primarystatustext)
- [ScrapText() [getter]](#scraptext)
- [PartsMadeText() [getter]](#partsmadetext)
- [AlertsText() [getter]](#alertstext)
- [PercentMade() [getter]](#percentmade)
- [MouldStatusText() [getter]](#mouldstatustext)
- [MachineNumberText() [getter]](#machinenumbertext)
- [PartNameText() [getter]](#partnametext)
- [UnicodeSymbolsText() [getter]](#unicodesymbolstext)
- [setTimeRemainingText()](#settimeremainingtext)

---

## Properties

### RealTimeMachinesEntity {#realtimemachinesentity}

**Type:** `cs.RealTimeMachinesEntity`

---

### WorksOrderEntity {#worksorderentity}

**Type:** `cs.WorksOrderEntity`

---

### ProductEntity {#productentity}

**Type:** `cs.ProductEntity`

---

### ToolsEntity {#toolsentity}

**Type:** `cs.ToolsEntity`

---

### DownReasonsEntity {#downreasonsentity}

**Type:** `cs.DownReasonsEntity`

---

### AverageCycleTime {#averagecycletime}

**Type:** `Real`

---

### RunningSlow {#runningslow}

**Type:** `Boolean`

---

### MachineWheelsEntity {#machinewheelsentity}

**Type:** `cs.MachineWheelsEntity`

---

### QuantityMade {#quantitymade}

**Type:** `Integer`

---

### QuantityScrapped {#quantityscrapped}

**Type:** `Integer`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($RealTimeMachinesEntity : cs.RealTimeMachinesEntity)
```

---

### ProcessColors {#processcolors}


```4d
Function ProcessColors
```

MARK:Primary Colors

---

### SecondaryStatusText {#secondarystatustext}
 `[getter]`

```4d
Function SecondaryStatusText -> Object
```

**Returns:** `Object`

---

### TimeRemainingText {#timeremainingtext}
 `[getter]`

```4d
Function TimeRemainingText -> Object
```

**Returns:** `Object`

---

### setPrimaryColors {#setprimarycolors}


```4d
Function setPrimaryColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

---

### setAlternatingColors {#setalternatingcolors}


```4d
Function setAlternatingColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

---

### setDateTimeColors {#setdatetimecolors}


```4d
Function setDateTimeColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

---

### setAlertColors {#setalertcolors}


```4d
Function setAlertColors($BackgroundColor : Integer; $ForegroundColor : Integer)
```

---

### DeviceMaintenanceActive {#devicemaintenanceactive}
 `[getter]`

```4d
Function DeviceMaintenanceActive -> Boolean
```

**Returns:** `Boolean`

---

### MachineDisconnected {#machinedisconnected}
 `[getter]`

```4d
Function MachineDisconnected -> Boolean
```

**Returns:** `Boolean`

---

### MachineRunning {#machinerunning}
 `[getter]`

```4d
Function MachineRunning -> Boolean
```

**Returns:** `Boolean`

---

### WorksOrderIsOpen {#worksorderisopen}
 `[getter]`

```4d
Function WorksOrderIsOpen -> Boolean
```

**Returns:** `Boolean`

---

### UnacknowledgedSensorExceptions {#unacknowledgedsensorexceptions}
 `[getter]`

```4d
Function UnacknowledgedSensorExceptions -> Boolean
```

**Returns:** `Boolean`

---

### PrimaryStatusText {#primarystatustext}
 `[getter]`

```4d
Function PrimaryStatusText -> Text
```

**Returns:** `Text`

---

### ScrapText {#scraptext}
 `[getter]`

```4d
Function ScrapText -> Text
```

**Returns:** `Text`

---

### PartsMadeText {#partsmadetext}
 `[getter]`

```4d
Function PartsMadeText -> Text
```

**Returns:** `Text`

---

### AlertsText {#alertstext}
 `[getter]`

```4d
Function AlertsText -> Text
```

**Returns:** `Text`

---

### PercentMade {#percentmade}
 `[getter]`

```4d
Function PercentMade -> Real
```

**Returns:** `Real`

---

### MouldStatusText {#mouldstatustext}
 `[getter]`

```4d
Function MouldStatusText -> Text
```

**Returns:** `Text`

---

### MachineNumberText {#machinenumbertext}
 `[getter]`

```4d
Function MachineNumberText -> Text
```

**Returns:** `Text`

---

### PartNameText {#partnametext}
 `[getter]`

```4d
Function PartNameText -> Text
```

**Returns:** `Text`

---

### UnicodeSymbolsText {#unicodesymbolstext}
 `[getter]`

```4d
Function UnicodeSymbolsText -> Text
```

**Returns:** `Text`

---

### setTimeRemainingText {#settimeremainingtext}


```4d
Function setTimeRemainingText($Text : Text; $DateTime : Variant; $AdditionalSeconds : Real)
```

---

---

*Generated from RealTimeOutputMachine.4dm*
*Last updated: 2025-11-12T17:17:32.297Z*

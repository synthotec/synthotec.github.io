---
layout : default
title : RealTimeSelection
parent : Classes
---
# RealTimeSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSelection.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity selection of real-time production cycle records, providing a helper to collect and aggregate all temperature sensor data from the SensorData JSON field across all records in the selection.

**Extends:** `EntitySelection`

🕐 *Last updated: 2026-03-09T14:45:31.151Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getTemperatureSensors](#gettemperaturesensors) → `$TemperatureSensors : Collection`
    - [getTemperatureSensorZones](#gettemperaturesensorzones) → `$TemperatureSensorZones : Collection`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getTemperatureSensors {#gettemperaturesensors}


```4d
Function getTemperatureSensors -> $TemperatureSensors : Collection
```

Collects all temperature sensors from all RealTime entities in the selection

**Returns:** `Collection`

---

#### getTemperatureSensorZones {#gettemperaturesensorzones}


```4d
Function getTemperatureSensorZones -> $TemperatureSensorZones : Collection
```

Returns a collection of unique temperature sensor zones and indices from all sensors in the selection

**Returns:** `Collection`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - ORDA EntitySelection class for RealTime table

### � Related Classes

- [RealTime](RealTime.md) - ORDA DataClass class for RealTime table
- [RealTimeEntity](RealTimeEntity.md) - ORDA Entity class for RealTime table

### � Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from RealTimeSelection.4dm*

# RealTimeSensorExceptionsEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [PartsMade() [getter]](#partsmade)
- [Duration() [getter]](#duration)
- [getRealTimeSelection()](#getrealtimeselection)
- [getTemperatureSensors()](#gettemperaturesensors)
- [LowestCelciusTemperature() [getter]](#lowestcelciustemperature)
- [HighestCelciusTemperature() [getter]](#highestcelciustemperature)
- [sendEmail()](#sendemail)

---

## Functions

### PartsMade {#partsmade}
 `[local]` `[getter]`

```4d
Function PartsMade -> Integer
```

**Returns:** `Integer`

---

### Duration {#duration}
 `[local]` `[getter]`

```4d
Function Duration -> Time
```

**Returns:** `Time`

---

### getRealTimeSelection {#getrealtimeselection}
 `[local]`

```4d
Function getRealTimeSelection -> cs.RealTimeSelection
```

**Returns:** `cs.RealTimeSelection`

---

### getTemperatureSensors {#gettemperaturesensors}
 `[local]`

```4d
Function getTemperatureSensors($Zone : Integer) -> Collection
```

**Returns:** `Collection`

---

### LowestCelciusTemperature {#lowestcelciustemperature}
 `[local]` `[getter]`

```4d
Function LowestCelciusTemperature -> Real
```

**Returns:** `Real`

---

### HighestCelciusTemperature {#highestcelciustemperature}
 `[local]` `[getter]`

```4d
Function HighestCelciusTemperature -> Real
```

**Returns:** `Real`

---

### sendEmail {#sendemail}


```4d
Function sendEmail -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from RealTimeSensorExceptionsEntity.4dm*
*Last updated: 2025-11-12T17:17:32.308Z*

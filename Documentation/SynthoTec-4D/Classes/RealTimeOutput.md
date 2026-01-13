---
layout : default
title : RealTimeOutput
parent : Classes
---
# RealTimeOutput [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeOutput.4dm)

📊 **Overview:** 1 Constructor | 5 Getters

## 📝 Description

Returns collection of RealTimeOutputMachine objects for all enabled machines with current production state, tool status, and scrap data; refreshes from real-time table on each call

🕐 *Last updated: 2026-01-13T16:04:13.123Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [InfoTextBox](#infotextbox) 🔍 → `Object`
    - [Layout](#layout) 🔍 → `Object`
    - [Machines](#machines) 🔍 → `Collection`
    - [SecondarySummaryText](#secondarysummarytext) 🔍 → `Text`
    - [SummaryText](#summarytext) 🔍 → `Text`

---

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Initializes real-time output display object for machine production dashboard

---

## Functions {#functions}

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### InfoTextBox {#infotextbox}
 `[🔍 get only]`

```4d
Function get InfoTextBox -> $InfoTextBox : Object
```

Returns status information object for dashboard info box showing unacknowledged temperature sensor exceptions by machine, temperature targets, and operational warnings

**Returns:** `Object`

---

#### Layout {#layout}
 `[🔍 get only]`

```4d
Function get Layout -> $Layout : Object
```

Returns dashboard layout configuration object with rows and columns from settings; used to determine responsive grid layout for machine cards

**Returns:** `Object`

---

#### Machines {#machines}
 `[🔍 get only]`

```4d
Function get Machines -> $Collection : Collection
```

Returns collection of RealTimeOutputMachine objects for all enabled machines with current production state, tool status, and scrap data; refreshes from real-time table on each call

**Returns:** `Collection`

---

#### SecondarySummaryText {#secondarysummarytext}
 `[🔍 get only]`

```4d
Function get SecondarySummaryText -> $SecondarySummaryText : Text
```

Aggregates secondary machine production data and returns formatted text summary of setters awaiting, availability metrics, and scrap data; returns text with emoji indicators

**Returns:** `Text`

---

#### SummaryText {#summarytext}
 `[🔍 get only]`

```4d
Function get SummaryText -> $SummaryText : Text
```

Returns formatted text summary of production metrics: running/total machines, tool changes, cycle hours and downtime hours; aggregated from real-time records for current date

**Returns:** `Text`

---

---

*Generated from RealTimeOutput.4dm*

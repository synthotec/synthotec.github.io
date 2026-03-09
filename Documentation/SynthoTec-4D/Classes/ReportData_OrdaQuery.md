---
layout : default
title : ReportData_OrdaQuery
parent : Classes
---
# ReportData_OrdaQuery [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_OrdaQuery.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 1 Functions

## 📝 Description

Report dataset that executes a configurable ORDA query against any DataClass and maps entity attributes to named report columns. Supports optional query parameters, order-by clauses, and attribute path chaining for related entities.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.270Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getValueType](#getvaluetype) (1 param) → `Text`
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `DataClass` | `Text` | - | Name of the ORDA DataClass to query |
| `QueryText` | `Text` | `""` | ORDA query string; empty string queries all records |
| `QueryParameters` | `Object` | - | Named parameters for the QueryText placeholders |
| `ColumnObject` | `Object` | - | Maps output column names to entity attribute paths (e.g., {CustomerName: "CustomerEntity.Name"}) |
| `OrderByText` | *Not specified* | `""` | Optional order-by clause applied after querying (e.g., "Name ASC") |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Parameters : Object)
```

Executes an ORDA query against DataClass and populates Collection with row objects mapped by ColumnObject

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### getValueType {#getvaluetype}


```4d
Function getValueType($ValueType : Variant) -> Text
```

Maps a 4D value type constant to the corresponding ReportData type string (e.g., Is real -> "double")

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ValueType` | `Variant` | - | - |

**Returns:** `Text`

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_OrdaQuery

---

*Generated from ReportData_OrdaQuery.4dm*

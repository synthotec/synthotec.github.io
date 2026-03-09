---
layout : default
title : PriceImport
parent : Classes
---
# PriceImport [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PriceImport.4dm)

📊 **Overview:** 4 Properties | 1 Constructor | 1 Functions

## 📝 Description

Parses tab-delimited price schedule data pasted from the clipboard, auto-detecting column positions for item numbers, quantities, due dates, and other fields used in the procurement programme import workflow.

🕐 *Last updated: 2026-03-09T14:45:30.568Z*

---

## 📑 Table of Contents

- [📋 Properties (4)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [importPrices](#importprices) → `$Result : Object`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `PasteBoardText` | `Text` | - | Raw text from clipboard containing tabular data |
| `ColumnNames` | *Not specified* | `[]` | Collection of column header names |
| `DataLines` | *Not specified* | `[]` | Collection of data rows split by line breaks |
| `CellCollection` | *Not specified* | `[]` | Collection of parsed cell objects |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Imports tabular data from clipboard, prompting user to identify if first line contains headers

---

## Functions {#functions}

### Regular Functions

#### importPrices {#importprices}


```4d
Function importPrices -> $Result : Object
```

Parses clipboard data into collection of objects with column names as keys

**Returns:** `Object`

---

---

*Generated from PriceImport.4dm*

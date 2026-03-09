---
layout : default
title : Scrap
parent : Classes
---
# Scrap [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Scrap.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for scrap records, supporting creation of new scrap entries from a JSON payload sent via REST (e.g., from a barcode scanner), capturing works order, production date, scrap date, and reason.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.535Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [newFromJson](#newfromjson) (1 param) → `$ScrapEntity : cs.ScrapEntity`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### newFromJson {#newfromjson}


```4d
Function newFromJson($Json : Text) -> $ScrapEntity : cs.ScrapEntity
```

Creates a new scrap entity from a JSON string and saves it

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Json` | `Text` | - | - |

**Returns:** `cs.ScrapEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Scrap](../Tables/Scrap.md) - ORDA DataClass class for Scrap table

### � Forms

- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form

---

*Generated from Scrap.4dm*

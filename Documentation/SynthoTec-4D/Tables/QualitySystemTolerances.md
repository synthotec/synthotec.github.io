---
layout : default
title : QualitySystemTolerances
parent : Tables
---
# QualitySystemTolerances

📊 **Overview:** 7 Fields | 1 Indexes

## 📝 Description

🗨️ Configuration table defining acceptable tolerance ranges for quality measurements. Links to QualitySystemProcedures with min/max limits.

## ℹ️ Table Information

- **Table ID:** 107
- **UUID:** C3B026087195274EBE4A71B14374D159
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:07Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| System | `String` (255) | 🚫 Not Null | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| Type | `Long Integer` | 🚫 Not Null | - |
| Tolerance | `Real` | 🚫 Not Null | - |
| Machine | `Long Integer` | 🚫 Not Null | - |
| ModifiedBy | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [QualitySystemTolerances](../Forms/QualitySystemTolerances.md) - Data source for QualitySystemTolerances form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:07Z*

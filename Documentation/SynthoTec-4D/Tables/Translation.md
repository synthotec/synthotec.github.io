---
layout : default
title : Translation
parent : Tables
---
# Translation

📊 **Overview:** 5 Fields | 3 Indexes

## ℹ️ Table Information

- **Table ID:** 93
- **UUID:** FB3EF960B67EC1469BFEF51C80EEDF92
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:11Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Process | `String` (255) | 🚫 Not Null | - |
| OriginalText | `String` | 🚫 Not Null | - |
| TranslatedText | `String` | 🚫 Not Null | - |
| LastModified | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `OriginalText` | Keywords | regular | - |
| `Process` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📦 Classes

- [Translation](../Classes/Translation.md) - ORDA DataClass class for Translation table

### 📄 Forms

- [CalibrationProcedures](../Forms/CalibrationProcedures.md) - Data source for CalibrationProcedures form
- [TranslationManager](../Forms/TranslationManager.md) - Data source for TranslationManager form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:11Z*

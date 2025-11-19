---
layout : default
title : MaterialLog
parent : Tables
---
# MaterialLog

📊 **Overview:** 8 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 74
- **UUID:** 7B19F335B56E4242828DF5D0077F42E6
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:52Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| RMC | `Date` | 🚫 Not Null | - |
| MoveDate | `Integer` | 🚫 Not Null | - |
| From | `String` (255) | 🚫 Not Null | - |
| ToLocation | `String` (255) | 🚫 Not Null | - |
| Who | `String` (255) | 🚫 Not Null | - |
| PalletNumber | `Picture` | 🚫 Not Null | - |
| Qty | `Picture` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:52Z*

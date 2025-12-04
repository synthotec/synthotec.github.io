---
layout : default
title : EquipmentStock
parent : Tables
---
# EquipmentStock

📊 **Overview:** 4 Fields | 1 Indexes

## 📝 Description

🗨️ Inventory table tracking consumable equipment and supplies (gloves, tools, spare parts). Records stock levels and usage.

## ℹ️ Table Information

- **Table ID:** 70
- **UUID:** 7E8A79F83C60A542A51B1DB4FF1DE543
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:32Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Type | `String` (255) | 🚫 Not Null | - |
| Name | `String` (255) | 🚫 Not Null | - |
| Quantity | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [CapacityPlanning](../Forms/CapacityPlanning.md) - Data source for CapacityPlanning form
- [EquipmentStock](../Forms/EquipmentStock.md) - Data source for EquipmentStock form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:32Z*

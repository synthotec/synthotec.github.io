---
layout : default
title : CustomerContacts
parent : Tables
---
# CustomerContacts

📊 **Overview:** 4 Fields | 1 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 78
- **UUID:** 4BCC18B6E22B7B4CB1440CD3608A0D8D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:08:59Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| Email | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [CustomerContacts](../Classes/CustomerContacts.md) - DataClass class
- [CustomerContactsEntity](../Classes/CustomerContactsEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:59Z*

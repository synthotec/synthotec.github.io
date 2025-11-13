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
- **Generated:** 🕐 2025-11-13T02:36:14Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| Email | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Customer

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Email

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active |

### Detailed Information

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:14Z*

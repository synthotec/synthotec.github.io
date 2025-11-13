---
layout : default
title : CustomerOrderLog
parent : Tables
---
# CustomerOrderLog

📊 **Overview:** 9 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 77
- **UUID:** 8921E64C9227D341A45DA81DDEBEFC8F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:13Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PetesNo | `Date` | 🚫 Not Null | - |
| OurDelivery | `Integer` | 🚫 Not Null | - |
| CustomerDelivery | `Integer` | 🚫 Not Null | - |
| QtyOrdered | `Date` | 🚫 Not Null | - |
| QtyDelivered | `Date` | 🚫 Not Null | - |
| PartPrice | `Boolean` | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| ModifiedBy | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### PetesNo

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### OurDelivery

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CustomerDelivery

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### QtyOrdered

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### QtyDelivered

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PartPrice

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ModifiedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `PetesNo` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `PetesNo`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:13Z*

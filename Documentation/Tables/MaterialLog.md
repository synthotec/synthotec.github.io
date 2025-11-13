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
- **Generated:** 🕐 2025-11-13T02:36:11Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### RMC

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MoveDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### From

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToLocation

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Who

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PalletNumber

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Qty

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:11Z*

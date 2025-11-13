---
layout : default
title : Unique_Codes
parent : Tables
---
# Unique_Codes

📊 **Overview:** 8 Fields | 4 Indexes

## ℹ️ Table Information

- **Table ID:** 17
- **UUID:** 841927B91F0A984697E1A0A7E2C95BA9
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:09Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (4)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| TableNo | `Picture` | 🚫 Not Null | - |
| UniqueCode | `Date` | 🚫 Not Null | - |
| IsItMaster | `Real` | 🚫 Not Null | - |
| SearchParameter | `String` (11) | 🚫 Not Null | - |
| Display_b | `Real` | 🚫 Not Null | - |
| Label_s | `String` (32) | 🚫 Not Null | - |
| FieldNo_l | `Picture` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### TableNo

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### UniqueCode

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### IsItMaster

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### SearchParameter

**Properties:**

- **Type:** String (max length: 11)
- **Constraints:** 🚫 Never Null

---

#### Display_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Label_s

**Properties:**

- **Type:** String (max length: 32)
- **Constraints:** 🚫 Never Null

---

#### FieldNo_l

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |
| `IsItMaster` | Keywords | regular | - |
| `FieldNo_l` | Keywords | regular | - |
| `TableNo` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `IsItMaster`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `FieldNo_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `TableNo`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:09Z*

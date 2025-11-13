---
layout : default
title : Printing
parent : Tables
---
# Printing

📊 **Overview:** 7 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 15
- **UUID:** 46AB44AA8924F449BCCF65AD27E8BDC1
- **Primary Key:** 🔑 `Unique_ID`
- **Generated:** 🕐 2025-11-13T02:35:03Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Date` | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| User_Name | `String` (40) | 🚫 Not Null | - |
| Report | `String` (40) | 🚫 Not Null | - |
| Parameter1 | `String` (20) | 🚫 Not Null | - |
| Parameter2 | `String` (20) | 🚫 Not Null | - |
| labelpartno | `String` (30) | 🚫 Not Null | - |
| PrintDate_d | `Integer` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 Unique_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚠️ Mandatory, 🚫 Never Null

---

#### User_Name

**Properties:**

- **Type:** String (max length: 40)
- **Constraints:** 🚫 Never Null

---

#### Report

**Properties:**

- **Type:** String (max length: 40)
- **Constraints:** 🚫 Never Null

---

#### Parameter1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Parameter2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### labelpartno

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### PrintDate_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Unique_ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Unique_ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:03Z*

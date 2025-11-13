---
layout : default
title : Gauges
parent : Tables
---
# Gauges

📊 **Overview:** 8 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 23
- **UUID:** B84C6CC0E8E67246A59E39321DB56B95
- **Primary Key:** 🔑 `Unique_ID`
- **Generated:** 🕐 2025-11-13T02:35:14Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Picture` | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Product_ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Type | `String` (40) | 🚫 Not Null | - |
| DateLastChecked | `Integer` | 🚫 Not Null | - |
| LastCheckedbyWhom | `String` (50) | 🚫 Not Null | - |
| No_BetweenChecks | `Picture` | 🚫 Not Null | - |
| NoOfDaysUsage | `Picture` | 🚫 Not Null | - |
| NoOfDaysUsageLeft | `Picture` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 Unique_ID

**Properties:**

- **Type:** Picture
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚠️ Mandatory, 🚫 Never Null

---

#### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Type

**Properties:**

- **Type:** String (max length: 40)
- **Constraints:** 🚫 Never Null

---

#### DateLastChecked

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### LastCheckedbyWhom

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** 🚫 Never Null

---

#### No_BetweenChecks

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NoOfDaysUsage

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NoOfDaysUsageLeft

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Product_ID` | Keywords | regular | - |
| `Unique_ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Product_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Unique_ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `Product_ID` → `Product_ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:14Z*

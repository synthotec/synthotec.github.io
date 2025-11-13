---
layout : default
title : Forecast
parent : Tables
---
# Forecast

📊 **Overview:** 6 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 108
- **UUID:** 3D30ED9FCDC1D24697A8C1D1F6F01D55
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:41Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Date` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| ForecastYear | `Picture` | 🚫 Not Null | - |
| ForecastMonth | `Picture` | 🚫 Not Null | - |
| Quantity | `Date` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Customer

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ForecastYear

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### ForecastMonth

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ProductID` | Keywords | regular | - |
| `ForecastYear` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ForecastYear`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:41Z*

---
layout : default
title : ProductMaterialOptions
parent : Tables
---
# ProductMaterialOptions

📊 **Overview:** 6 Fields | 3 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 40
- **UUID:** 35B5E95C0975EB4583DCBCAD2723FA54
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:29Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Date` | 🚫 Not Null | - |
| MaterialID | `Date` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| CreatedDate | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

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

#### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### CreatedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CreatedDate

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
| `ProductID` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MaterialID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |

### Detailed Information

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:29Z*

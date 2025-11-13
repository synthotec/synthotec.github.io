---
layout : default
title : Location
parent : Tables
---
# Location

📊 **Overview:** 3 Fields | 2 Indexes | 1 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 121
- **UUID:** 44FBB6DE7626F84EA6B3129DC5AAA82E
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:53Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Name | `String` (255) | - | - |
| ParentLocationID | `String` | - | - |
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |

### Detailed Information

#### Name

**Properties:**

- **Type:** String (max length: 255)

---

#### ParentLocationID

**Properties:**

- **Type:** String

---

#### 🔑 ID

**Properties:**

- **Type:** String
- **Constraints:** 🔑 Primary Key, ✨ Unique

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ParentLocationID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ParentLocationID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `LocationEntity` | [Location](Location.md) | `ParentLocationID` → `ID` | Active |

### Detailed Information

#### LocationEntity

**Links to:** [Location](Location.md)

- **Source Field:** `ParentLocationID`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PalletSelection` | [Pallet](Pallet.md) | `LocationID` → `ID` | Active |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `LocationID` → `ID` | Active |

### Detailed Information

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** Active

---

#### MaterialStockSelection

**Links from:** [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:53Z*

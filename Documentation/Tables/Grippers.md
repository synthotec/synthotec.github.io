---
layout : default
title : Grippers
parent : Tables
---
# Grippers

📊 **Overview:** 9 Fields | 5 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 25
- **UUID:** 755FDB8A02ACFB4787F4589BA9B30BE2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:16Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Date` | 🚫 Not Null | - |
| Part_No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Machine_No | `Picture` | 🚫 Not Null | - |
| Head_No | `String` (10) | 🚫 Not Null | - |
| Gripper_Details | `String` (255) | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Cleaning_Details | `String` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Part_No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Machine_No

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Head_No

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### Gripper_Details

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Cleaning_Details

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Product_ID` | Keywords | regular | - |
| `ToolID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Part_No` | Keywords | regular | - |
| `Machine_No` | Keywords | regular | - |

### Detailed Information

- **Field:** `Product_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine_No`
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
*Generated at: 2025-11-13T02:35:16Z*

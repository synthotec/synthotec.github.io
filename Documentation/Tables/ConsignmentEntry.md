---
layout : default
title : ConsignmentEntry
parent : Tables
---
# ConsignmentEntry

📊 **Overview:** 27 Fields | 1 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 58
- **UUID:** 1D7F0D4EFE7DFD438D22AF0D3E4F1FCA
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:56Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (27)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StartDate | `Integer` | 🚫 Not Null | - |
| CustomerCode | `String` (255) | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| Week1 | `Date` | 🚫 Not Null | - |
| Week2 | `Date` | 🚫 Not Null | - |
| Week3 | `Date` | 🚫 Not Null | - |
| Week4 | `Date` | 🚫 Not Null | - |
| Week5 | `Date` | 🚫 Not Null | - |
| Week6 | `Date` | 🚫 Not Null | - |
| Week7 | `Date` | 🚫 Not Null | - |
| Week8 | `Date` | 🚫 Not Null | - |
| Week9 | `Date` | 🚫 Not Null | - |
| Week10 | `Date` | 🚫 Not Null | - |
| Week11 | `Date` | 🚫 Not Null | - |
| Week12 | `Date` | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| CustomerRef | `String` (255) | 🚫 Not Null | - |
| Week13 | `Date` | 🚫 Not Null | - |
| Week14 | `Date` | 🚫 Not Null | - |
| Week15 | `Date` | 🚫 Not Null | - |
| Week16 | `Date` | 🚫 Not Null | - |
| Week17 | `Date` | 🚫 Not Null | - |
| Week18 | `Date` | 🚫 Not Null | - |
| Week19 | `Date` | 🚫 Not Null | - |
| Week20 | `Date` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### StartDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CustomerCode

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week1

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week2

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week3

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week4

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week5

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week6

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week7

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week8

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week9

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week10

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week11

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week12

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Archived

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### PartName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CustomerRef

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Week13

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week14

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week15

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week16

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week17

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week18

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week19

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Week20

**Properties:**

- **Type:** Date
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
*Generated at: 2025-11-13T02:35:56Z*

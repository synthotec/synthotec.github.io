---
layout : default
title : MaterialStock
parent : Tables
---
# MaterialStock

📊 **Overview:** 12 Fields | 7 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 48
- **UUID:** C11E4B61162CA04E8020762F66A8FC50
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:47Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| MaterialID | `Date` | 🚫 Not Null | - |
| RMC | `Date` | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| Quantity | `Boolean` | 🚫 Not Null | - |
| PalletNumber | `Date` | 🚫 Not Null | - |
| MaterialName | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| LastMoveDate | `Integer` | 🚫 Not Null | - |
| Comment | `String` (125) | 🚫 Not Null | - |
| LocationID | `String` | - | - |
| LabelsPrinted | `Real` | - | - |
| SheetsPrinted | `Real` | - | - |

### Detailed Information

#### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RMC

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Location

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Quantity

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### PalletNumber

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MaterialName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### LastMoveDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Comment

**Properties:**

- **Type:** String (max length: 125)
- **Constraints:** 🚫 Never Null

---

#### LocationID

**Properties:**

- **Type:** String

---

#### LabelsPrinted

**Properties:**

- **Type:** Real

---

#### SheetsPrinted

**Properties:**

- **Type:** Real

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `LabelsPrinted` | Keywords | regular | - |
| `LocationID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `PalletNumber` | Keywords | regular | - |
| `SheetsPrinted` | Keywords | regular | - |
| `RMC` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

### Detailed Information

- **Field:** `LabelsPrinted`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `LocationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PalletNumber`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `SheetsPrinted`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RMC`
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
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active |
| `LocationEntity` | [Location](Location.md) | `LocationID` → `ID` | Active |

### Detailed Information

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### RMCEntity

**Links to:** [RMC](RMC.md)

- **Source Field:** `RMC`
- **Destination Field:** `RMCNo_l`
- **State:** Active

---

#### LocationEntity

**Links to:** [Location](Location.md)

- **Source Field:** `LocationID`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:47Z*

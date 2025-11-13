---
layout : default
title : MaterialStockTake
parent : Tables
---
# MaterialStockTake

📊 **Overview:** 12 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 53
- **UUID:** A38A78E19EE7594CADD598417056C9D4
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:51Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| StockTakeDate | `Integer` | 🚫 Not Null | - |
| RMC | `Date` | 🚫 Not Null | - |
| MatID | `Picture` | 🚫 Not Null | - |
| Bags | `Boolean` | 🚫 Not Null | - |
| AmountKG | `Boolean` | 🚫 Not Null | - |
| RMCID | `Date` | 🚫 Not Null | - |
| MaterialName | `String` (255) | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| CountedBy | `String` (255) | 🚫 Not Null | - |
| PrimaryStockTake | `Real` | 🚫 Not Null | - |
| SavedTimeStamp | `String` (255) | - | - |

### Detailed Information

#### StockTakeDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### RMC

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MatID

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Bags

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### AmountKG

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### RMCID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MaterialName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Location

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### CountedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PrimaryStockTake

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### SavedTimeStamp

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MatID` | Keywords | regular | - |
| `StockTakeDate` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `PrimaryStockTake` | Keywords | regular | - |

### Detailed Information

- **Field:** `MatID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `StockTakeDate`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PrimaryStockTake`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active |

### Detailed Information

#### RMCEntity

**Links to:** [RMC](RMC.md)

- **Source Field:** `RMC`
- **Destination Field:** `RMCNo_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:51Z*

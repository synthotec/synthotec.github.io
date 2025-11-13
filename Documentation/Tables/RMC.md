---
layout : default
title : RMC
parent : Tables
---
# RMC

📊 **Overview:** 12 Fields | 4 Indexes | 2 Many-to-One Relations | 6 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 27
- **UUID:** 888FFBDAC9DEBA469795A94E15901BAE
- **Primary Key:** 🔑 `RMCNo_l`
- **Generated:** 🕐 2025-11-13T02:35:18Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (6)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **RMCNo_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MaterialID_l | `Date` | 🚫 Not Null | - |
| RMCDate_d | `Integer` | 🚫 Not Null | - |
| BatchNo_s | `String` (25) | 🚫 Not Null | - |
| Quantity_l | `Date` | 🚫 Not Null | - |
| OrderNo_l | `Date` | 🚫 Not Null | - |
| Name_s | `String` (30) | 🚫 Not Null | - |
| Remarks_s | `String` (20) | 🚫 Not Null | - |
| CofA_BLOB | `Unknown (18)` | 🚫 Not Null | - |
| CofA_Filename | `String` (255) | 🚫 Not Null | - |
| CofA_Requested | `Integer` | 🚫 Not Null | - |
| PurchaseInfoID | `Date` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 RMCNo_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### MaterialID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RMCDate_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### BatchNo_s

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Quantity_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### OrderNo_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Name_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Remarks_s

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CofA_BLOB

**Properties:**

- **Type:** Unknown (18)
- **Constraints:** 🚫 Never Null

---

#### CofA_Filename

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CofA_Requested

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### PurchaseInfoID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MaterialID_l` | Keywords | regular | - |
| `PurchaseInfoID` | Keywords | regular | - |
| `RMCNo_l` | Keywords | regular | ✨ Yes |
| `RMCDate_d` | Keywords | regular | - |

### Detailed Information

- **Field:** `MaterialID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PurchaseInfoID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RMCNo_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RMCDate_d`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID_l` → `Unique_ID` | Active |
| `PurchaseInfoEntity` | [PurchaseInfo](PurchaseInfo.md) | `PurchaseInfoID` → `UniqueID_l` | Active |

### Detailed Information

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID_l`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### PurchaseInfoEntity

**Links to:** [PurchaseInfo](PurchaseInfo.md)

- **Source Field:** `PurchaseInfoID`
- **Destination Field:** `UniqueID_l`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PurchaseReceiptsSelection` | [PurchaseReceipts](PurchaseReceipts.md) | `RMC` → `RMCNo_l` | Active |
| `MaterialStockTakeSelection` | [MaterialStockTake](MaterialStockTake.md) | `RMC` → `RMCNo_l` | Active |
| `MaterialCheckHistorySelection1` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC1` → `RMCNo_l` | Active |
| `MaterialCheckHistorySelection2` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC2` → `RMCNo_l` | Active |
| `MaterialCheckHistorySelection3` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC3` → `RMCNo_l` | Active |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `RMC` → `RMCNo_l` | Active |

### Detailed Information

#### PurchaseReceiptsSelection

**Links from:** [PurchaseReceipts](PurchaseReceipts.md)

- **Source Table:** `PurchaseReceipts`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialStockTakeSelection

**Links from:** [MaterialStockTake](MaterialStockTake.md)

- **Source Table:** `MaterialStockTake`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialCheckHistorySelection1

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialCheckHistorySelection2

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialCheckHistorySelection3

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialStockSelection

**Links from:** [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:18Z*

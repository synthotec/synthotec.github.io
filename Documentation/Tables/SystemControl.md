---
layout : default
title : SystemControl
parent : Tables
---
# SystemControl

📊 **Overview:** 13 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 28
- **UUID:** 033E20DBAC212B4389E5C70620881ED8
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:19Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| NSKLabelsPerSet_l | `Date` | 🚫 Not Null | - |
| NoOfPackers_l | `Date` | 🚫 Not Null | - |
| WIPStockValuePC_i | `Picture` | 🚫 Not Null | - |
| QuarantinedStockValuePC_i | `Picture` | 🚫 Not Null | - |
| ReturnedStockValuePC_i | `Picture` | 🚫 Not Null | - |
| FinishedStockValuePC_i | `Picture` | 🚫 Not Null | - |
| MaxPOCost_r | `Boolean` | 🚫 Not Null | - |
| POLimitGroup_s | `String` (30) | 🚫 Not Null | - |
| ThreeMnthStkChk | `Real` | 🚫 Not Null | - |
| OldNew_RouteCardLayout | `Real` | 🚫 Not Null | - |
| gross_wgt_label | `Real` | 🚫 Not Null | - |
| Machine_Hourly_Rate | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### NSKLabelsPerSet_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### NoOfPackers_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WIPStockValuePC_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### QuarantinedStockValuePC_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### ReturnedStockValuePC_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### FinishedStockValuePC_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MaxPOCost_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### POLimitGroup_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### ThreeMnthStkChk

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### OldNew_RouteCardLayout

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### gross_wgt_label

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Machine_Hourly_Rate

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:19Z*

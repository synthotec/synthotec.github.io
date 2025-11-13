---
layout : default
title : PurchaseReceipts
parent : Tables
---
# PurchaseReceipts

📊 **Overview:** 8 Fields | 3 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 109
- **UUID:** BE29EC2C2AE9BF4496D0A54958A42DA5
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:27Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PurchaseInfoID | `Date` | 🚫 Not Null | - |
| DateReceived | `Integer` | 🚫 Not Null | - |
| QuantityRecieved | `Boolean` | 🚫 Not Null | - |
| ReceivedBy | `String` (255) | 🚫 Not Null | - |
| ProofOfReceiptFile | `Unknown (18)` | 🚫 Not Null | - |
| ProofOfReceiptName | `String` (255) | 🚫 Not Null | - |
| RMC | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `RMC` | Keywords | regular | - |
| `PurchaseInfoID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `PurchaseInfoEntity` | [PurchaseInfo](PurchaseInfo.md) | `PurchaseInfoID` → `UniqueID_l` | Active | - |
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:27Z*

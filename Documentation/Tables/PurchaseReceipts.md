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
- **Generated:** 🕐 2025-11-13T02:36:42Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### PurchaseInfoID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DateReceived

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### QuantityRecieved

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### ReceivedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ProofOfReceiptFile

**Properties:**

- **Type:** Unknown (18)
- **Constraints:** 🚫 Never Null

---

#### ProofOfReceiptName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### RMC

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `RMC` | Keywords | regular | - |
| `PurchaseInfoID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RMC`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PurchaseInfoID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `PurchaseInfoEntity` | [PurchaseInfo](PurchaseInfo.md) | `PurchaseInfoID` → `UniqueID_l` | Active |
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active |

### Detailed Information

#### PurchaseInfoEntity

**Links to:** [PurchaseInfo](PurchaseInfo.md)

- **Source Field:** `PurchaseInfoID`
- **Destination Field:** `UniqueID_l`
- **State:** Active

---

#### RMCEntity

**Links to:** [RMC](RMC.md)

- **Source Field:** `RMC`
- **Destination Field:** `RMCNo_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:42Z*

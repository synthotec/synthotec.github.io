---
layout : default
title : Pallet
parent : Tables
---
# Pallet

📊 **Overview:** 28 Fields | 12 Indexes | 4 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 71
- **UUID:** 33A92733465ACC42A746A5DD7A56B429
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:08Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (28)
- [🔍 Indexes](#-indexes) (12)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Location | `Date` | 🚫 Not Null | - |
| WO1 | `Date` | 🚫 Not Null | - |
| WO1Qty | `Date` | 🚫 Not Null | - |
| WO2 | `Date` | 🚫 Not Null | - |
| WO2Qty | `Date` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| Created | `Integer` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| Transfer | `Real` | 🚫 Not Null | - |
| CreationTime | `Long Integer` | 🚫 Not Null | - |
| AdviceNote | `Date` | 🚫 Not Null | - |
| OrderID | `Date` | 🚫 Not Null | - |
| Printed | `Real` | 🚫 Not Null | - |
| Verified | `Real` | 🚫 Not Null | - |
| NewSystem | `Real` | 🚫 Not Null | - |
| VerifiedBy | `String` (255) | 🚫 Not Null | - |
| PrintedBy | `String` (255) | 🚫 Not Null | - |
| Completed | `Real` | 🚫 Not Null | - |
| LocationID | `String` | - | - |
| LocatedBy | `String` (255) | - | - |
| OrderPickRequestID | `Date` | - | - |
| CofCID | `Date` | - | - |
| UUID | `String` | ✨ Unique | - |
| Version | `Picture` | 🚫 Not Null | - |
| Despatched | `Real` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |
| LastMigration | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Location

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WO1

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WO1Qty

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WO2

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WO2Qty

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Created

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CreatedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Transfer

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CreationTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### AdviceNote

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### OrderID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Printed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Verified

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NewSystem

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### VerifiedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PrintedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### LocationID

**Properties:**

- **Type:** String

---

#### LocatedBy

**Properties:**

- **Type:** String (max length: 255)

---

#### OrderPickRequestID

**Properties:**

- **Type:** Date

---

#### CofCID

**Properties:**

- **Type:** Date

---

#### UUID

**Properties:**

- **Type:** String
- **Constraints:** ✨ Unique

---

#### Version

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Despatched

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

#### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Version` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Despatched` | Keywords | regular | - |
| `OrderPickRequestID` | Keywords | regular | - |
| `CofCID` | Keywords | regular | - |
| `Verified` | Keywords | regular | - |
| `UUID` | Keywords | regular | ✨ Yes |
| `ProductID` | Keywords | regular | - |
| `Printed` | Keywords | regular | - |
| `Completed` | Keywords | regular | - |
| `LocationID` | Keywords | regular | - |
| `NewSystem` | Keywords | regular | - |

### Detailed Information

- **Field:** `Version`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Despatched`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `OrderPickRequestID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `CofCID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Verified`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `UUID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Printed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Completed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `LocationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `NewSystem`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |
| `LocationEntity` | [Location](Location.md) | `LocationID` → `ID` | Active |
| `OrderPickRequestEntity` | [OrderPickRequest](OrderPickRequest.md) | `OrderPickRequestID` → `ID` | Active |
| `CofCEntity` | [CofC](CofC.md) | `CofCID` → `Cert_Of_Conformance_No` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### LocationEntity

**Links to:** [Location](Location.md)

- **Source Field:** `LocationID`
- **Destination Field:** `ID`
- **State:** Active

---

#### OrderPickRequestEntity

**Links to:** [OrderPickRequest](OrderPickRequest.md)

- **Source Field:** `OrderPickRequestID`
- **Destination Field:** `ID`
- **State:** Active

---

#### CofCEntity

**Links to:** [CofC](CofC.md)

- **Source Field:** `CofCID`
- **Destination Field:** `Cert_Of_Conformance_No`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `PalletID` → `ID` | Active |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `RelatedUUID` → `UUID` | Active |

### Detailed Information

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `PalletID`
- **This Table Field:** `ID`
- **State:** Active

---

#### PrintJobSelection

**Links from:** [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:08Z*

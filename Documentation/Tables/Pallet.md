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
- **Generated:** 🕐 2025-11-13T16:08:52Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (28)
- [🔍 Indexes](#-indexes) (12)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (3)

---

## 📋 Fields

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

## 🔍 Indexes

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

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |
| `LocationEntity` | [Location](Location.md) | `LocationID` → `ID` | Active | - |
| `OrderPickRequestEntity` | [OrderPickRequest](OrderPickRequest.md) | `OrderPickRequestID` → `ID` | Active | - |
| `CofCEntity` | [CofC](CofC.md) | `CofCID` → `Cert_Of_Conformance_No` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `PalletID` → `ID` | Active | - |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `RelatedUUID` → `UUID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Pallet](../Classes/Pallet.md) - DataClass class
- [PalletEntity](../Classes/PalletEntity.md) - Entity class
- [PalletSelection](../Classes/PalletSelection.md) - EntitySelection class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:52Z*

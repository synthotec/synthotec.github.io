---
layout : default
title : BoxLabels
parent : Tables
---
# BoxLabels

📊 **Overview:** 36 Fields | 19 Indexes | 8 Many-to-One Relations

## 📝 Description

🗨️ Testing boxlabels manual comment

## ℹ️ Table Information

- **Table ID:** 76
- **UUID:** 0B40C76291EE2E44AC3F733AD8213391
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:38Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (36)
- [🔍 Indexes](#-indexes) (19)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (8)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (7)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| BoxNumber | `Long Integer` | 🚫 Not Null | - |
| RouteCard | `Integer` | 🚫 Not Null | - |
| PackedBy | `String` (255) | 🚫 Not Null | - |
| Date | `Date` | 🚫 Not Null | - |
| Time | `Time` | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| Parts | `Long Integer` | 🚫 Not Null | - |
| Shift | `Long Integer` | 🚫 Not Null | - |
| WORC | `Long Integer` | 🚫 Not Null | - |
| Mandrels | `Integer` | 🚫 Not Null | - |
| NotMade | `Boolean` | 🚫 Not Null | - |
| NotMadeWho | `String` (255) | 🚫 Not Null | - |
| TimeToPack | `Real` | 🚫 Not Null | - |
| StockInput | `Boolean` | 🚫 Not Null | - |
| TimeProcessed | `Boolean` | 🚫 Not Null | - |
| StandardHours | `Real` | 🚫 Not Null | - |
| ShiftDate | `Long Integer` | 🚫 Not Null | - |
| PartBoxCode | `String` (5) | 🚫 Not Null | - |
| LinkedBoxID | `Long Integer` | 🚫 Not Null | - |
| RemoveFromStock | `Boolean` | 🚫 Not Null | - |
| StockRemovedBy | `String` | 🚫 Not Null | - |
| PalletID | `Long Integer` | 🚫 Not Null | - |
| WhenAddedToPallet | `String` (255) | - | - |
| OrderPickRequestID | `Long Integer` | - | - |
| Version | `Integer` | - | - |
| CofCID | `Long Integer` | - | - |
| Stock_LocationID | `Long Integer` | - | - |
| Comments | `String` | - | - |
| StatusUpdatedStaffID | `Long Integer` | - | - |
| StatusUpdatedWhen | `String` (255) | - | - |
| UUID | `String` | - | - |
| MigrationID | `Long Integer` | - | - |
| LastMigration | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `PalletID` | Keywords | regular | - |
| `WorksOrder` | Cluster | regular | - |
| `UUID` | Keywords | regular | - |
| `ToolID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Shift` | Keywords | regular | - |
| `StockRemovedBy` | Keywords | regular | - |
| `RemoveFromStock` | Cluster | regular | - |
| `Stock_LocationID` | Keywords | regular | - |
| `LinkedBoxID` | Keywords | regular | - |
| `TimeProcessed` | Keywords | regular | - |
| `PackedBy` | Keywords | regular | - |
| `CofCID` | Keywords | regular | - |
| `Version` | Keywords | regular | - |
| `StockInput` | Cluster | regular | - |
| `OrderPickRequestID` | Keywords | regular | - |
| `ShiftDate` | Keywords | regular | - |
| `PartBoxCode` | Keywords | regular | - |
| `NotMade` | Cluster | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `LinkedBoxLabelsEntity` | [BoxLabels](BoxLabels.md) | `LinkedBoxID` → `ID` | Active | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `PalletEntity` | [Pallet](Pallet.md) | `PalletID` → `ID` | Active | - |
| `OrderPickRequestEntity` | [OrderPickRequest](OrderPickRequest.md) | `OrderPickRequestID` → `ID` | Active | - |
| `CofCEntity` | [CofC](CofC.md) | `CofCID` → `Cert_Of_Conformance_No` | Active | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `Stock_LocationID` → `StockLocationID_l` | Active | - |
| `StatusUpdatedStaffEntity` | [Staff](Staff.md) | `StatusUpdatedStaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [BoxLabels](../Classes/BoxLabels.md) - ORDA DataClass class for BoxLabels table
- [BoxLabelsEntity](../Classes/BoxLabelsEntity.md) - ORDA Entity class for BoxLabels table

### 📄 Forms

- [%2Atest](../Forms/%2Atest.md) - Data source for %2Atest form
- [%2Atest1](../Forms/%2Atest1.md) - Data source for %2Atest1 form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [Warehouse](../Forms/Warehouse.md) - Data source for Warehouse form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:38Z*

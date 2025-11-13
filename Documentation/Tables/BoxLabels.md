---
layout : default
title : BoxLabels
parent : Tables
---
# BoxLabels

📊 **Overview:** 36 Fields | 19 Indexes | 8 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 76
- **UUID:** 0B40C76291EE2E44AC3F733AD8213391
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:08:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (36)
- [🔍 Indexes](#-indexes) (19)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (8)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| BoxNumber | `Date` | 🚫 Not Null | - |
| RouteCard | `Picture` | 🚫 Not Null | - |
| PackedBy | `String` (255) | 🚫 Not Null | - |
| Date | `Integer` | 🚫 Not Null | - |
| Time | `Long Integer` | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Parts | `Date` | 🚫 Not Null | - |
| Shift | `Date` | 🚫 Not Null | - |
| WORC | `Date` | 🚫 Not Null | - |
| Mandrels | `Picture` | 🚫 Not Null | - |
| NotMade | `Real` | 🚫 Not Null | - |
| NotMadeWho | `String` (255) | 🚫 Not Null | - |
| TimeToPack | `Boolean` | 🚫 Not Null | - |
| StockInput | `Real` | 🚫 Not Null | - |
| TimeProcessed | `Real` | 🚫 Not Null | - |
| StandardHours | `Boolean` | 🚫 Not Null | - |
| ShiftDate | `Date` | 🚫 Not Null | - |
| PartBoxCode | `String` (5) | 🚫 Not Null | - |
| LinkedBoxID | `Date` | 🚫 Not Null | - |
| RemoveFromStock | `Real` | 🚫 Not Null | - |
| StockRemovedBy | `String` | 🚫 Not Null | - |
| PalletID | `Date` | 🚫 Not Null | - |
| WhenAddedToPallet | `String` (255) | - | - |
| OrderPickRequestID | `Date` | - | - |
| Version | `Picture` | - | - |
| CofCID | `Date` | - | - |
| Stock_LocationID | `Date` | - | - |
| Comments | `String` | - | - |
| StatusUpdatedStaffID | `Date` | - | - |
| StatusUpdatedWhen | `String` (255) | - | - |
| UUID | `String` | - | - |
| MigrationID | `Date` | - | - |
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

- [BoxLabels](../Classes/BoxLabels.md) - DataClass class
- [BoxLabelsEntity](../Classes/BoxLabelsEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:57Z*

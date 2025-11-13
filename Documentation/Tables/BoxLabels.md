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
- **Generated:** 🕐 2025-11-13T02:36:12Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (36)
- [🔍 Indexes](#-indexes) (19)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (8)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BoxNumber

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RouteCard

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### PackedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Time

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Parts

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Shift

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WORC

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Mandrels

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NotMade

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NotMadeWho

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### TimeToPack

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### StockInput

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### TimeProcessed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StandardHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### ShiftDate

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PartBoxCode

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### LinkedBoxID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RemoveFromStock

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StockRemovedBy

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### PalletID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WhenAddedToPallet

**Properties:**

- **Type:** String (max length: 255)

---

#### OrderPickRequestID

**Properties:**

- **Type:** Date

---

#### Version

**Properties:**

- **Type:** Picture

---

#### CofCID

**Properties:**

- **Type:** Date

---

#### Stock_LocationID

**Properties:**

- **Type:** Date

---

#### Comments

**Properties:**

- **Type:** String

---

#### StatusUpdatedStaffID

**Properties:**

- **Type:** Date

---

#### StatusUpdatedWhen

**Properties:**

- **Type:** String (max length: 255)

---

#### UUID

**Properties:**

- **Type:** String

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

### Detailed Information

- **Field:** `PalletID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `UUID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Shift`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `StockRemovedBy`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RemoveFromStock`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `Stock_LocationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `LinkedBoxID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `TimeProcessed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PackedBy`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `CofCID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Version`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `StockInput`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `OrderPickRequestID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ShiftDate`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PartBoxCode`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `NotMade`
  - **Kind:** regular
  - **Type:** Cluster

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |
| `LinkedBoxLabelsEntity` | [BoxLabels](BoxLabels.md) | `LinkedBoxID` → `ID` | Active |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |
| `PalletEntity` | [Pallet](Pallet.md) | `PalletID` → `ID` | Active |
| `OrderPickRequestEntity` | [OrderPickRequest](OrderPickRequest.md) | `OrderPickRequestID` → `ID` | Active |
| `CofCEntity` | [CofC](CofC.md) | `CofCID` → `Cert_Of_Conformance_No` | Active |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `Stock_LocationID` → `StockLocationID_l` | Active |
| `StatusUpdatedStaffEntity` | [Staff](Staff.md) | `StatusUpdatedStaffID` → `StaffID` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### LinkedBoxLabelsEntity

**Links to:** [BoxLabels](BoxLabels.md)

- **Source Field:** `LinkedBoxID`
- **Destination Field:** `ID`
- **State:** Active

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

#### PalletEntity

**Links to:** [Pallet](Pallet.md)

- **Source Field:** `PalletID`
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

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `Stock_LocationID`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

#### StatusUpdatedStaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StatusUpdatedStaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:12Z*

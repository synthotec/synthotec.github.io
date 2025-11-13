---
layout : default
title : Material
parent : Tables
---
# Material

📊 **Overview:** 26 Fields | 9 Indexes | 3 Many-to-One Relations | 11 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 11
- **UUID:** 13EE0980326D984887426E4CEDD50A30
- **Primary Key:** 🔑 `Unique_ID`
- **Generated:** 🕐 2025-11-13T02:34:58Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (26)
- [🔍 Indexes](#-indexes) (9)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (11)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MaterialName | `String` (80) | 🚫 Not Null | - |
| Customers Name | `String` (35) | 🚫 Not Null | - |
| In Stock | `Date` | 🚫 Not Null | - |
| Supplier Code | `String` (3) | 🚫 Not Null | - |
| Supplier Name | `String` (25) | 🚫 Not Null | - |
| Current | `Real` | 🚫 Not Null | - |
| Short Name | `String` (35) | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| Colour_l | `Date` | 🚫 Not Null | - |
| Manufacturer_s | `String` (20) | 🚫 Not Null | - |
| UsageMatID | `Date` | 🚫 Not Null | - |
| SafetyStockTarget | `Picture` | 🚫 Not Null | - |
| BOM_Price | `Boolean` | 🚫 Not Null | - |
| LossPercent | `Boolean` | 🚫 Not Null | - |
| UsageMatID2 | `Date` | 🚫 Not Null | - |
| UsageMatID2Percent | `Boolean` | 🚫 Not Null | - |
| Calendar_Price | `Boolean` | 🚫 Not Null | - |
| UsageMatID3 | `Date` | 🚫 Not Null | - |
| UsageMatID3Percent | `Boolean` | 🚫 Not Null | - |
| FontColour | `Date` | 🚫 Not Null | - |
| BOM_Comment | `String` (255) | 🚫 Not Null | - |
| SharedMaterialSource | `Real` | 🚫 Not Null | - |
| LeadTimeDays | `Date` | - | - |
| MigrationID | `Date` | - | - |
| LastMigration | `String` (255) | - | - |

### Detailed Information

#### 🔑 Unique_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null, 🔒 Not Modifiable

---

#### MaterialName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Customers Name

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### In Stock

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Supplier Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### Supplier Name

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Current

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Short Name

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Colour_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Manufacturer_s

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### UsageMatID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SafetyStockTarget

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### BOM_Price

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### LossPercent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### UsageMatID2

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### UsageMatID2Percent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Calendar_Price

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### UsageMatID3

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### UsageMatID3Percent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### FontColour

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BOM_Comment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### SharedMaterialSource

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### LeadTimeDays

**Properties:**

- **Type:** Date

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
| `UsageMatID3` | Keywords | regular | - |
| `UsageMatID` | Keywords | regular | - |
| `Current` | Keywords | regular | - |
| `Archive` | Keywords | regular | - |
| `MigrationID` | Keywords | regular | - |
| `UsageMatID2` | Keywords | regular | - |
| `MaterialName` | Keywords | regular | - |
| `Unique_ID` | Keywords | regular | ✨ Yes |
| `Customers Name` | Keywords | regular | - |

### Detailed Information

- **Field:** `UsageMatID3`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `UsageMatID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Current`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archive`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MigrationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `UsageMatID2`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MaterialName`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Unique_ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customers Name`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `UsageMat1Entity` | [Material](Material.md) | `UsageMatID` → `Unique_ID` | Active |
| `UsageMat2Entity` | [Material](Material.md) | `UsageMatID2` → `Unique_ID` | Active |
| `UsageMat3Entity` | [Material](Material.md) | `UsageMatID3` → `Unique_ID` | Active |

### Detailed Information

#### UsageMat1Entity

**Links to:** [Material](Material.md)

- **Source Field:** `UsageMatID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### UsageMat2Entity

**Links to:** [Material](Material.md)

- **Source Field:** `UsageMatID2`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### UsageMat3Entity

**Links to:** [Material](Material.md)

- **Source Field:** `UsageMatID3`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Material_ID` → `Unique_ID` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Material_ID` → `Unique_ID` | Active |
| `RMCSelection` | [RMC](RMC.md) | `MaterialID_l` → `Unique_ID` | Active |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `MatID` → `Unique_ID` | Active |
| `BOMSelection` | [BOM](BOM.md) | `MaterialID` → `Unique_ID` | Active |
| `MaterialCheckHistorySelection` | [MaterialCheckHistory](MaterialCheckHistory.md) | `MaterialID` → `Unique_ID` | Active |
| `PlanningWheelSelection` | [PlanningWheel](PlanningWheel.md) | `MaterialID` → `Unique_ID` | Active |
| `ProductMaterialOptionsSelection` | [ProductMaterialOptions](ProductMaterialOptions.md) | `MaterialID` → `Unique_ID` | Active |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `MaterialID` → `Unique_ID` | Active |
| `ProductSelection` | [Product](Product.md) | `DefMatID` → `Unique_ID` | Active |
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `MaterialID` → `Unique_ID` | Active |

### Detailed Information

#### Customer_OrderSelection

**Links from:** [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### RMCSelection

**Links from:** [RMC](RMC.md)

- **Source Table:** `RMC`
- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### WheelCalendarSelection

**Links from:** [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### BOMSelection

**Links from:** [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### MaterialCheckHistorySelection

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### PlanningWheelSelection

**Links from:** [PlanningWheel](PlanningWheel.md)

- **Source Table:** `PlanningWheel`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### ProductMaterialOptionsSelection

**Links from:** [ProductMaterialOptions](ProductMaterialOptions.md)

- **Source Table:** `ProductMaterialOptions`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### MaterialStockSelection

**Links from:** [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### ProductSelection

**Links from:** [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### WorksOrderSelection

**Links from:** [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:58Z*

---
layout : default
title : Customer
parent : Tables
---
# Customer

📊 **Overview:** 56 Fields | 7 Indexes | 2 Many-to-One Relations | 8 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 1
- **UUID:** 29D34E506C4DF7418EA055008A0624CE
- **Primary Key:** 🔑 `Customer_Code`
- **Generated:** 🕐 2025-11-13T02:34:14Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (56)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (8)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Customer_Code** | `String` (3) | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Cust Name | `String` (35) | ⚠️ Required, 🚫 Not Null | - |
| Cust Addr1 | `String` (35) | 🚫 Not Null | - |
| Cust Addr2 | `String` (35) | 🚫 Not Null | - |
| Cust Addr3 | `String` (35) | 🚫 Not Null | - |
| Cust Addr4 | `String` (35) | 🚫 Not Null | - |
| Cust Postcode | `String` (20) | 🚫 Not Null | - |
| Cust Phone1 | `String` (20) | 🚫 Not Null | - |
| Cust Fax | `String` (20) | 🚫 Not Null | - |
| Cust Contact1 | `String` (20) | 🚫 Not Null | - |
| Email1 | `String` (80) | 🚫 Not Null | - |
| Cust Notes | `String` | 🚫 Not Null | - |
| Cust Cum Ord | `Boolean` | 🚫 Not Null | - |
| Cust Inv Date | `Integer` | 🚫 Not Null | - |
| Cust Label1 | `String` (25) | ⚠️ Required, 🚫 Not Null | - |
| Cust Label2 | `String` (25) | 🚫 Not Null | - |
| Cust label3 | `String` (25) | 🚫 Not Null | - |
| Acknowledgement | `Real` | 🚫 Not Null | - |
| Acknow Contact | `String` (30) | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| CustContact2 | `String` (20) | 🚫 Not Null | - |
| CustPhone2 | `String` (20) | 🚫 Not Null | - |
| CustPosition1 | `String` (20) | 🚫 Not Null | - |
| CustPosition2 | `String` (20) | 🚫 Not Null | - |
| Email2 | `String` (80) | 🚫 Not Null | - |
| CofCRequired_b | `Real` | 🚫 Not Null | - |
| DeliveryAddress_txt | `String` | 🚫 Not Null | - |
| SupplierCode | `String` (30) | 🚫 Not Null | - |
| DeliveryDays | `Picture` | 🚫 Not Null | - |
| CustPosition3 | `String` (20) | 🚫 Not Null | - |
| CustPosition4 | `String` (20) | 🚫 Not Null | - |
| CustPosition5 | `String` (20) | 🚫 Not Null | - |
| CustPosition6 | `String` (20) | 🚫 Not Null | - |
| CustContact3 | `String` (20) | 🚫 Not Null | - |
| CustContact4 | `String` (20) | 🚫 Not Null | - |
| CustContact5 | `String` (20) | 🚫 Not Null | - |
| CustContact6 | `String` (20) | 🚫 Not Null | - |
| CustPhone3 | `String` (20) | 🚫 Not Null | - |
| CustPhone4 | `String` (20) | 🚫 Not Null | - |
| CustPhone5 | `String` (20) | 🚫 Not Null | - |
| CustPhone6 | `String` (20) | 🚫 Not Null | - |
| Email3 | `String` (80) | 🚫 Not Null | - |
| Email4 | `String` (80) | 🚫 Not Null | - |
| Email5 | `String` (80) | 🚫 Not Null | - |
| Email6 | `String` (80) | 🚫 Not Null | - |
| BoxesPerPallet | `Boolean` | 🚫 Not Null | - |
| OrderEmail | `String` (255) | 🚫 Not Null | - |
| PalletTransportCost | `Boolean` | 🚫 Not Null | - |
| TransportComment | `String` (255) | 🚫 Not Null | - |
| RequiresMaterialCofA | `Real` | - | - |
| NtnSnrLocationCode | `String` (255) | - | - |
| Consignment | `Real` | 🚫 Not Null | - |
| ConsignmentLocationID | `Date` | - | - |
| MigrationID | `String` | - | - |
| LastMigration | `String` (255) | - | - |
| TransportInstructionFileID | `Date` | - | - |

### Detailed Information

#### 🔑 Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚠️ Mandatory, 🚫 Never Null, 🔒 Not Modifiable

---

#### Cust Name

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Cust Addr1

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Addr2

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Addr3

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Addr4

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Postcode

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Cust Phone1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Cust Fax

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Cust Contact1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Email1

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Cust Notes

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Cust Cum Ord

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Cust Inv Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Cust Label1

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Cust Label2

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Cust label3

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Acknowledgement

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Acknow Contact

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CustContact2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Email2

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### CofCRequired_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DeliveryAddress_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### SupplierCode

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### DeliveryDays

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### CustPosition3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Email3

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Email4

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Email5

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Email6

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### BoxesPerPallet

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### OrderEmail

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PalletTransportCost

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TransportComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### RequiresMaterialCofA

**Properties:**

- **Type:** Real

---

#### NtnSnrLocationCode

**Properties:**

- **Type:** String (max length: 255)

---

#### Consignment

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ConsignmentLocationID

**Properties:**

- **Type:** Date

---

#### MigrationID

**Properties:**

- **Type:** String

---

#### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

#### TransportInstructionFileID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Customer_Code` | Keywords | regular | ✨ Yes |
| `Cust Addr3` | Keywords | regular | - |
| `Consignment` | Keywords | regular | - |
| `NtnSnrLocationCode` | Keywords | regular | - |
| `MigrationID` | Keywords | regular | - |
| `Archive` | Keywords | regular | - |
| `ConsignmentLocationID` | Keywords | regular | - |

### Detailed Information

- **Field:** `Customer_Code` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Cust Addr3`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Consignment`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `NtnSnrLocationCode`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MigrationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archive`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ConsignmentLocationID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `ConsignmentLocationID` → `StockLocationID_l` | Active |
| `TransportInstructionFileEntity` | [File](File.md) | `TransportInstructionFileID` → `ID` | Active |

### Detailed Information

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `ConsignmentLocationID`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

#### TransportInstructionFileEntity

**Links to:** [File](File.md)

- **Source Field:** `TransportInstructionFileID`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `Customer_Code` → `Customer_Code` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Customer Code` → `Customer_Code` | Active |
| `PickRequestSelection` | [PickRequest](PickRequest.md) | `Customer` → `Customer_Code` | Active |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Customer_Code` → `Customer_Code` | Active |
| `ApprovalsSelection` | [Approvals](Approvals.md) | `Customer` → `Customer_Code` | Active |
| `BOMSelection` | [BOM](BOM.md) | `Customer` → `Customer_Code` | Active |
| `CustomerContactsSelection` | [CustomerContacts](CustomerContacts.md) | `Customer` → `Customer_Code` | Active |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `Customer` → `Customer_Code` | Active |

### Detailed Information

#### WorksOrderSelection

**Links from:** [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### PickRequestSelection

**Links from:** [PickRequest](PickRequest.md)

- **Source Table:** `PickRequest`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### Customer_OrderSelection

**Links from:** [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### ApprovalsSelection

**Links from:** [Approvals](Approvals.md)

- **Source Table:** `Approvals`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### BOMSelection

**Links from:** [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### CustomerContactsSelection

**Links from:** [CustomerContacts](CustomerContacts.md)

- **Source Table:** `CustomerContacts`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### ProductPackagingSelection

**Links from:** [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:14Z*

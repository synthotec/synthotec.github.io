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
- **Generated:** 🕐 2025-11-13T23:17:42Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (56)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (8)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Customer_Code** | `String` (3) | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null, ��� Not Modifiable | - |
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

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Customer_Code` | Keywords | regular | ✨ Yes |
| `Cust Addr3` | Keywords | regular | - |
| `Consignment` | Keywords | regular | - |
| `NtnSnrLocationCode` | Keywords | regular | - |
| `MigrationID` | Keywords | regular | - |
| `Archive` | Keywords | regular | - |
| `ConsignmentLocationID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `ConsignmentLocationID` → `StockLocationID_l` | Active | - |
| `TransportInstructionFileEntity` | [File](File.md) | `TransportInstructionFileID` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `Customer_Code` → `Customer_Code` | Active | - |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Customer Code` → `Customer_Code` | Active | - |
| `PickRequestSelection` | [PickRequest](PickRequest.md) | `Customer` → `Customer_Code` | Active | - |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Customer_Code` → `Customer_Code` | Active | - |
| `ApprovalsSelection` | [Approvals](Approvals.md) | `Customer` → `Customer_Code` | Active | - |
| `BOMSelection` | [BOM](BOM.md) | `Customer` → `Customer_Code` | Active | - |
| `CustomerContactsSelection` | [CustomerContacts](CustomerContacts.md) | `Customer` → `Customer_Code` | Active | - |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `Customer` → `Customer_Code` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:42Z*

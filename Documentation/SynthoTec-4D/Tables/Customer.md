---
layout : default
title : Customer
parent : Tables
---
# Customer

📊 **Overview:** 56 Fields | 7 Indexes | 2 Many-to-One Relations | 8 One-to-Many Relations

## 📝 Description

🗨️ Master data table storing customer information including contact details, addresses, and configuration settings. Used as the central reference for customer orders, works orders, and product options.

## ℹ️ Table Information

- **Table ID:** 1
- **UUID:** 29D34E506C4DF7418EA055008A0624CE
- **Primary Key:** 🔑 `Customer_Code`
- **Generated:** 🕐 2025-12-04T14:33:30Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (56)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (8)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (13)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Customer_Code** | `String` (3) | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null, ��� Not Modifiable | Primary key - Unique 3-character customer identifier code. Non-modifiable after creation. |
| Cust Name | `String` (35) | ⚠️ Required, 🚫 Not Null | Company name of the customer. Maximum 35 characters, mandatory field. |
| Cust Addr1 | `String` (35) | 🚫 Not Null | First line of customer's billing address. |
| Cust Addr2 | `String` (35) | 🚫 Not Null | Second line of customer's billing address. |
| Cust Addr3 | `String` (35) | 🚫 Not Null | Third line of customer's billing address (indexed for search). |
| Cust Addr4 | `String` (35) | 🚫 Not Null | Fourth line of customer's billing address. |
| Cust Postcode | `String` (20) | 🚫 Not Null | Postal code for customer's billing address. |
| Cust Phone1 | `String` (20) | 🚫 Not Null | Primary phone number for the customer. |
| Cust Fax | `String` (20) | 🚫 Not Null | Fax number for the customer (legacy field). |
| Cust Contact1 | `String` (20) | 🚫 Not Null | Name of primary contact person at customer's organization. |
| Email1 | `String` (80) | 🚫 Not Null | Email address for primary contact person. |
| Cust Notes | `String` | 🚫 Not Null | Free-text notes and comments about the customer. Unlimited length. |
| Cust Cum Ord | `Real` | 🚫 Not Null | Cumulative order value total for this customer. |
| Cust Inv Date | `Date` | 🚫 Not Null | Date of last invoice sent to this customer. |
| Cust Label1 | `String` (25) | ⚠️ Required, 🚫 Not Null | Primary label format/template name for customer shipments. Mandatory field. |
| Cust Label2 | `String` (25) | 🚫 Not Null | Secondary label format/template name for customer shipments. |
| Cust label3 | `String` (25) | 🚫 Not Null | Tertiary label format/template name for customer shipments. |
| Acknowledgement | `Boolean` | 🚫 Not Null | Flag indicating whether order acknowledgements should be sent to this customer. |
| Acknow Contact | `String` (30) | 🚫 Not Null | Name of contact person who should receive order acknowledgements. |
| Archive | `Boolean` | 🚫 Not Null | Flag indicating whether customer is archived (inactive). Indexed for filtering. |
| CustContact2 | `String` (20) | 🚫 Not Null | Name of secondary contact person at customer's organization. |
| CustPhone2 | `String` (20) | 🚫 Not Null | Phone number for secondary contact person. |
| CustPosition1 | `String` (20) | 🚫 Not Null | Job title/position of primary contact person. |
| CustPosition2 | `String` (20) | 🚫 Not Null | Job title/position of secondary contact person. |
| Email2 | `String` (80) | 🚫 Not Null | Email address for secondary contact person. |
| CofCRequired_b | `Boolean` | 🚫 Not Null | Flag indicating whether Certificate of Conformance is required for this customer's orders. |
| DeliveryAddress_txt | `String` | 🚫 Not Null | Complete delivery address if different from billing address. Unlimited length. |
| SupplierCode | `String` (30) | 🚫 Not Null | Code used to identify this customer as a supplier in their own system. |
| DeliveryDays | `Integer` | 🚫 Not Null | Standard number of days for delivery to this customer. |
| CustPosition3 | `String` (20) | 🚫 Not Null | Job title/position of third contact person. |
| CustPosition4 | `String` (20) | 🚫 Not Null | Job title/position of fourth contact person. |
| CustPosition5 | `String` (20) | 🚫 Not Null | Job title/position of fifth contact person. |
| CustPosition6 | `String` (20) | 🚫 Not Null | Job title/position of sixth contact person. |
| CustContact3 | `String` (20) | 🚫 Not Null | Name of third contact person at customer's organization. |
| CustContact4 | `String` (20) | 🚫 Not Null | Name of fourth contact person at customer's organization. |
| CustContact5 | `String` (20) | 🚫 Not Null | Name of fifth contact person at customer's organization. |
| CustContact6 | `String` (20) | 🚫 Not Null | Name of sixth contact person at customer's organization. |
| CustPhone3 | `String` (20) | 🚫 Not Null | Phone number for third contact person. |
| CustPhone4 | `String` (20) | 🚫 Not Null | Phone number for fourth contact person. |
| CustPhone5 | `String` (20) | 🚫 Not Null | Phone number for fifth contact person. |
| CustPhone6 | `String` (20) | 🚫 Not Null | Phone number for sixth contact person. |
| Email3 | `String` (80) | 🚫 Not Null | Email address for third contact person. |
| Email4 | `String` (80) | 🚫 Not Null | Email address for fourth contact person. |
| Email5 | `String` (80) | 🚫 Not Null | Email address for fifth contact person. |
| Email6 | `String` (80) | 🚫 Not Null | Email address for sixth contact person. |
| BoxesPerPallet | `Real` | 🚫 Not Null | Standard number of boxes per pallet for this customer's shipments. |
| OrderEmail | `String` (255) | 🚫 Not Null | Email address for sending order confirmations and updates. |
| PalletTransportCost | `Real` | 🚫 Not Null | Cost per pallet for transport to this customer. |
| TransportComment | `String` (255) | 🚫 Not Null | Special transport instructions or notes for deliveries to this customer. |
| RequiresMaterialCofA | `Boolean` | - | Flag indicating whether Material Certificate of Analysis is required for this customer. |
| NtnSnrLocationCode | `String` (255) | - | NTN-SNR specific location code for this customer. Indexed for quick lookup. |
| Consignment | `Boolean` | 🚫 Not Null | Flag indicating whether customer uses consignment stock model. Indexed for filtering. |
| ConsignmentLocationID | `Long Integer` | - | Foreign key to Stock_Location table for consignment stock location. Indexed, relates to Stock_LocationEntity. |
| MigrationID | `String` | - | Unique identifier from legacy system for data migration tracking. Indexed. |
| LastMigration | `String` (255) | - | Timestamp or identifier of last migration/sync operation for this record. |
| TransportInstructionFileID | `Long Integer` | - | Foreign key to File table for attached transport instruction document. Relates to TransportInstructionFileEntity. |

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

## 🔗 Related Items

### 📦 Classes

- [Customer](../Classes/Customer.md) - ORDA DataClass class for Customer table
- [CustomerEntity](../Classes/CustomerEntity.md) - ORDA Entity class for Customer table

### 📄 Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [BOM_CustomerTransport](../Forms/BOM_CustomerTransport.md) - Data source for BOM_CustomerTransport form
- [ConfirmOrderDates](../Forms/ConfirmOrderDates.md) - Data source for ConfirmOrderDates form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [PackingListGenerator](../Forms/PackingListGenerator.md) - Data source for PackingListGenerator form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:30Z*

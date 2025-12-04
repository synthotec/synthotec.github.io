---
layout : default
title : Stock_Location
parent : Tables
---
# Stock_Location

📊 **Overview:** 6 Fields | 4 Indexes | 5 One-to-Many Relations

## 📝 Description

🗨️ Master data table defining physical storage locations for inventory (warehouses, bays, consignment sites). Used by Finished_Stock and Stock_Movement for location tracking.

## ℹ️ Table Information

- **Table ID:** 29
- **UUID:** 916903B13AB83B4A9937B1348364CCA9
- **Primary Key:** 🔑 `StockLocationID_l`
- **Generated:** 🕐 2025-12-04T14:33:55Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (5)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (9)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **StockLocationID_l** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Location_Name_s | `String` (30) | 🚫 Not Null | - |
| Is_Consignment_b | `Boolean` | 🚫 Not Null | - |
| Location_Code_s | `String` (5) | 🚫 Not Null | - |
| DeafultPackingLocation_b | `Boolean` | 🚫 Not Null | - |
| DespatchLocation | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Is_Consignment_b` | Keywords | regular | - |
| `DeafultPackingLocation_b` | Keywords | regular | - |
| `DespatchLocation` | Keywords | regular | - |
| `StockLocationID_l` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `Stock_MovementSelection` | [Stock_Movement](Stock_Movement.md) | `To_Location_l` → `StockLocationID_l` | Active | - |
| `Finished_StockSelection` | [Finished_Stock](Finished_Stock.md) | `LocationID_l` → `StockLocationID_l` | Active | - |
| `CofCSelection` | [CofC](CofC.md) | `LocationID_l` → `StockLocationID_l` | Active | - |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `Stock_LocationID` → `StockLocationID_l` | Active | - |
| `CustomerSelection` | [Customer](Customer.md) | `ConsignmentLocationID` → `StockLocationID_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Stock_Location](../Classes/Stock_Location.md) - ORDA DataClass class for Stock_Location table
- [Stock_LocationEntity](../Classes/Stock_LocationEntity.md) - ORDA Entity class for Stock_Location table

### 📄 Forms

- [%2AStockControl](../Forms/%2AStockControl.md) - Data source for %2AStockControl form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [EDIgenerator](../Forms/EDIgenerator.md) - Data source for EDIgenerator form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PalletTransfer](../Forms/PalletTransfer.md) - Data source for PalletTransfer form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form
- [StockAtLocation](../Forms/StockAtLocation.md) - Data source for StockAtLocation form
- [StockMovements](../Forms/StockMovements.md) - Data source for StockMovements form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:55Z*

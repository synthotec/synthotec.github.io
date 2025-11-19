---
layout : default
title : Stock_Location
parent : Tables
---
# Stock_Location

📊 **Overview:** 6 Fields | 4 Indexes | 5 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 29
- **UUID:** 916903B13AB83B4A9937B1348364CCA9
- **Primary Key:** 🔑 `StockLocationID_l`
- **Generated:** 🕐 2025-11-13T23:18:09Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (5)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **StockLocationID_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Location_Name_s | `String` (30) | 🚫 Not Null | - |
| Is_Consignment_b | `Real` | 🚫 Not Null | - |
| Location_Code_s | `String` (5) | 🚫 Not Null | - |
| DeafultPackingLocation_b | `Real` | 🚫 Not Null | - |
| DespatchLocation | `Real` | 🚫 Not Null | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:09Z*

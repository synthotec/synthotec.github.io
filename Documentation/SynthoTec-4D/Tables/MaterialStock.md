---
layout : default
title : MaterialStock
parent : Tables
---
# MaterialStock

📊 **Overview:** 12 Fields | 7 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 48
- **UUID:** C11E4B61162CA04E8020762F66A8FC50
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:25Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| MaterialID | `Date` | 🚫 Not Null | - |
| RMC | `Date` | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| Quantity | `Boolean` | 🚫 Not Null | - |
| PalletNumber | `Date` | 🚫 Not Null | - |
| MaterialName | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| LastMoveDate | `Integer` | 🚫 Not Null | - |
| Comment | `String` (125) | 🚫 Not Null | - |
| LocationID | `String` | - | - |
| LabelsPrinted | `Real` | - | - |
| SheetsPrinted | `Real` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `LabelsPrinted` | Keywords | regular | - |
| `LocationID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `PalletNumber` | Keywords | regular | - |
| `SheetsPrinted` | Keywords | regular | - |
| `RMC` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active | - |
| `LocationEntity` | [Location](Location.md) | `LocationID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:25Z*

---
layout : default
title : EquipmentProfiles
parent : Tables
---
# EquipmentProfiles

📊 **Overview:** 18 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 59
- **UUID:** D8188042DA7A3C488CA350345D55AAE2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:33Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Tool_ID | `Date` | 🚫 Not Null | - |
| Machine | `Picture` | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| RobotHead | `String` (255) | 🚫 Not Null | - |
| Grippers | `String` (255) | 🚫 Not Null | - |
| TargetCycleTime | `Boolean` | 🚫 Not Null | - |
| OverallOEE | `Boolean` | 🚫 Not Null | - |
| PalletLayout | `Picture` | 🚫 Not Null | - |
| MandrelCount | `Picture` | 🚫 Not Null | - |
| CagesPerMandrel | `Picture` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| BoxesPerPallet | `Boolean` | 🚫 Not Null | - |
| HandLoad | `Real` | 🚫 Not Null | - |
| HandLoadContainer | `String` (255) | 🚫 Not Null | - |
| ContainerCount | `String` (255) | 🚫 Not Null | - |
| ApprovedDate | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:33Z*

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
- **Generated:** 🕐 2025-12-03T16:24:07Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Tool_ID | `Long Integer` | 🚫 Not Null | - |
| Machine | `Integer` | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| RobotHead | `String` (255) | 🚫 Not Null | - |
| Grippers | `String` (255) | 🚫 Not Null | - |
| TargetCycleTime | `Real` | 🚫 Not Null | - |
| OverallOEE | `Real` | 🚫 Not Null | - |
| PalletLayout | `Picture` | 🚫 Not Null | - |
| MandrelCount | `Integer` | 🚫 Not Null | - |
| CagesPerMandrel | `Integer` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| BoxesPerPallet | `Real` | 🚫 Not Null | - |
| HandLoad | `Boolean` | 🚫 Not Null | - |
| HandLoadContainer | `String` (255) | 🚫 Not Null | - |
| ContainerCount | `String` (255) | 🚫 Not Null | - |
| ApprovedDate | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [EquipmentProfiles](../Forms/EquipmentProfiles.md) - Data source for EquipmentProfiles form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:07Z*

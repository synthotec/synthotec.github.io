---
layout : default
title : NonConformance
parent : Tables
---
# NonConformance

📊 **Overview:** 49 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 19
- **UUID:** 0EF85BE67B5AB047BDF434F47974C7C3
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:33Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (49)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Reference_No | `String` (15) | ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Tool_ID | `Long Integer` | 🚫 Not Null | - |
| Date | `Date` | 🚫 Not Null | - |
| NatureOfConcern | `String` | 🚫 Not Null | - |
| Reply_Due | `String` (30) | 🚫 Not Null | - |
| Responded_On | `Date` | 🚫 Not Null | - |
| Completed_Yes | `Boolean` | 🚫 Not Null | - |
| Completed_No | `Boolean` | 🚫 Not Null | - |
| Is_A_PQI | `Boolean` | 🚫 Not Null | - |
| Type_Of_Concern | `String` (15) | 🚫 Not Null | - |
| Part_IssueLevel | `String` (5) | 🚫 Not Null | - |
| Works_Order_No | `Long Integer` | 🚫 Not Null | - |
| ConcernRecdBy | `String` (20) | 🚫 Not Null | - |
| ConcernRecdDate | `Date` | 🚫 Not Null | - |
| WIP_Quantity | `Long Integer` | 🚫 Not Null | - |
| WIP_Location | `String` (15) | 🚫 Not Null | - |
| WIP_Status | `String` (9) | 🚫 Not Null | - |
| WIP_ActionTaken | `String` | 🚫 Not Null | - |
| WIP_Signed | `String` (20) | 🚫 Not Null | - |
| WIP_Date | `Date` | 🚫 Not Null | - |
| Stock_Quantity | `Long Integer` | 🚫 Not Null | - |
| Stock_Location | `String` (15) | 🚫 Not Null | - |
| Stock_Status | `String` (9) | 🚫 Not Null | - |
| Stock_ActionTaken | `String` | 🚫 Not Null | - |
| Stock_Signed | `String` (15) | 🚫 Not Null | - |
| Stock_Date | `Date` | 🚫 Not Null | - |
| CauseofConcern | `String` | 🚫 Not Null | - |
| NoofInternalPQI | `Integer` | 🚫 Not Null | - |
| NoofExternalPQI | `Integer` | 🚫 Not Null | - |
| Recurrence_Action | `String` | 🚫 Not Null | - |
| QualityImprove_Action | `String` | 🚫 Not Null | - |
| QualityImprove_Sign | `String` (15) | 🚫 Not Null | - |
| QualityImprove_Date | `Date` | 🚫 Not Null | - |
| Customer | `String` (3) | 🚫 Not Null | - |
| CauseOfNonDetection_txt | `String` | 🚫 Not Null | - |
| ActionNonDetection_txt | `String` | 🚫 Not Null | - |
| Recurrence_Signed | `String` (15) | 🚫 Not Null | - |
| Recurrence_Date | `Date` | 🚫 Not Null | - |
| ActionNonDetection_Signed | `String` (15) | 🚫 Not Null | - |
| ActionNonDetection_Date | `Date` | 🚫 Not Null | - |
| Effective_Action | `String` | 🚫 Not Null | - |
| Effective_Signed | `String` (15) | 🚫 Not Null | - |
| Effective_Date | `Date` | 🚫 Not Null | - |
| Field_44 | `String` (255) | - | - |
| FMEA | `String` | 🚫 Not Null | - |
| FMEA_Signed | `String` (255) | 🚫 Not Null | - |
| FMEA_Date | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| CreateWorkRequest | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Tool_ID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Is_A_PQI` | Keywords | regular | - |
| `Reference_No` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `Tool_ID` → `Tool_ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:33Z*

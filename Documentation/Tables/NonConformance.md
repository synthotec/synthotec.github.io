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
- **Generated:** 🕐 2025-11-13T02:35:11Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (49)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Reference_No | `String` (15) | ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Tool_ID | `Date` | 🚫 Not Null | - |
| Date | `Integer` | 🚫 Not Null | - |
| NatureOfConcern | `String` | 🚫 Not Null | - |
| Reply_Due | `String` (30) | 🚫 Not Null | - |
| Responded_On | `Integer` | 🚫 Not Null | - |
| Completed_Yes | `Real` | 🚫 Not Null | - |
| Completed_No | `Real` | 🚫 Not Null | - |
| Is_A_PQI | `Real` | 🚫 Not Null | - |
| Type_Of_Concern | `String` (15) | 🚫 Not Null | - |
| Part_IssueLevel | `String` (5) | 🚫 Not Null | - |
| Works_Order_No | `Date` | 🚫 Not Null | - |
| ConcernRecdBy | `String` (20) | 🚫 Not Null | - |
| ConcernRecdDate | `Integer` | 🚫 Not Null | - |
| WIP_Quantity | `Date` | 🚫 Not Null | - |
| WIP_Location | `String` (15) | 🚫 Not Null | - |
| WIP_Status | `String` (9) | 🚫 Not Null | - |
| WIP_ActionTaken | `String` | 🚫 Not Null | - |
| WIP_Signed | `String` (20) | 🚫 Not Null | - |
| WIP_Date | `Integer` | 🚫 Not Null | - |
| Stock_Quantity | `Date` | 🚫 Not Null | - |
| Stock_Location | `String` (15) | 🚫 Not Null | - |
| Stock_Status | `String` (9) | 🚫 Not Null | - |
| Stock_ActionTaken | `String` | 🚫 Not Null | - |
| Stock_Signed | `String` (15) | 🚫 Not Null | - |
| Stock_Date | `Integer` | 🚫 Not Null | - |
| CauseofConcern | `String` | 🚫 Not Null | - |
| NoofInternalPQI | `Picture` | 🚫 Not Null | - |
| NoofExternalPQI | `Picture` | 🚫 Not Null | - |
| Recurrence_Action | `String` | 🚫 Not Null | - |
| QualityImprove_Action | `String` | 🚫 Not Null | - |
| QualityImprove_Sign | `String` (15) | 🚫 Not Null | - |
| QualityImprove_Date | `Integer` | 🚫 Not Null | - |
| Customer | `String` (3) | 🚫 Not Null | - |
| CauseOfNonDetection_txt | `String` | 🚫 Not Null | - |
| ActionNonDetection_txt | `String` | 🚫 Not Null | - |
| Recurrence_Signed | `String` (15) | 🚫 Not Null | - |
| Recurrence_Date | `Integer` | 🚫 Not Null | - |
| ActionNonDetection_Signed | `String` (15) | 🚫 Not Null | - |
| ActionNonDetection_Date | `Integer` | 🚫 Not Null | - |
| Effective_Action | `String` | 🚫 Not Null | - |
| Effective_Signed | `String` (15) | 🚫 Not Null | - |
| Effective_Date | `Integer` | 🚫 Not Null | - |
| Field_44 | `String` (255) | - | - |
| FMEA | `String` | 🚫 Not Null | - |
| FMEA_Signed | `String` (255) | 🚫 Not Null | - |
| FMEA_Date | `Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| CreateWorkRequest | `Real` | 🚫 Not Null | - |

### Detailed Information

#### Reference_No

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** ✨ Unique, ⚠️ Mandatory, 🚫 Never Null

---

#### Tool_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### NatureOfConcern

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Reply_Due

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Responded_On

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Completed_Yes

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Completed_No

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Is_A_PQI

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Type_Of_Concern

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### Part_IssueLevel

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ConcernRecdBy

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### ConcernRecdDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### WIP_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WIP_Location

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### WIP_Status

**Properties:**

- **Type:** String (max length: 9)
- **Constraints:** 🚫 Never Null

---

#### WIP_ActionTaken

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### WIP_Signed

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### WIP_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Stock_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Stock_Location

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### Stock_Status

**Properties:**

- **Type:** String (max length: 9)
- **Constraints:** 🚫 Never Null

---

#### Stock_ActionTaken

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Stock_Signed

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### Stock_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CauseofConcern

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### NoofInternalPQI

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NoofExternalPQI

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Recurrence_Action

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### QualityImprove_Action

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### QualityImprove_Sign

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### QualityImprove_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Customer

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### CauseOfNonDetection_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### ActionNonDetection_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Recurrence_Signed

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### Recurrence_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ActionNonDetection_Signed

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### ActionNonDetection_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Effective_Action

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Effective_Signed

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### Effective_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Field_44

**Properties:**

- **Type:** String (max length: 255)

---

#### FMEA

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### FMEA_Signed

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FMEA_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### CreateWorkRequest

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Tool_ID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Is_A_PQI` | Keywords | regular | - |
| `Reference_No` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Tool_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Is_A_PQI`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Reference_No` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `Tool_ID` → `Tool_ID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:11Z*

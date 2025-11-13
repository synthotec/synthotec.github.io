---
layout : default
title : ToolMaintenanceLog
parent : Tables
---
# ToolMaintenanceLog

📊 **Overview:** 9 Fields | 1 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 105
- **UUID:** 1F02089890EA3F489FED75E8E2877B11
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:38Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| ToolID | `Date` | 🚫 Not Null | - |
| MaintenanceDate | `Integer` | 🚫 Not Null | - |
| MaintenanceTime | `Long Integer` | 🚫 Not Null | - |
| MaintenanceWho | `String` (255) | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| CycleCount | `Date` | 🚫 Not Null | - |
| BypassCountReset | `Real` | 🚫 Not Null | - |
| WorkRequestID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** String
- **Constraints:** 🔑 Primary Key, ✨ Unique

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MaintenanceDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### MaintenanceTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### MaintenanceWho

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Comments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CycleCount

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BypassCountReset

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### WorkRequestID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |
| `WorkRequestsEntity` | [WorkRequests](WorkRequests.md) | `WorkRequestID` → `ID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

#### WorkRequestsEntity

**Links to:** [WorkRequests](WorkRequests.md)

- **Source Field:** `WorkRequestID`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:38Z*

---
layout : default
title : Approvals
parent : Tables
---
# Approvals

📊 **Overview:** 13 Fields | 2 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 62
- **UUID:** 6588D29DE7A2FE44BEEA0304F247C2A0
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:00Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| FullApproval | `Real` | 🚫 Not Null | - |
| ApprovalType | `String` (255) | 🚫 Not Null | - |
| ConditionalApproval | `Real` | 🚫 Not Null | - |
| ConditionalUntil | `Integer` | 🚫 Not Null | - |
| Issue | `String` (255) | 🚫 Not Null | - |
| BypassApproval | `Real` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| ApprovedBy | `String` (255) | 🚫 Not Null | - |
| ApprovedWhen | `Integer` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Customer

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FullApproval

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ApprovalType

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ConditionalApproval

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ConditionalUntil

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Issue

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### BypassApproval

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Comments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ApprovedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ApprovedWhen

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:00Z*

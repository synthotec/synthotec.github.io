---
layout : default
title : ToolNotice
parent : Tables
---
# ToolNotice

📊 **Overview:** 10 Fields | 2 Indexes | 3 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 134
- **UUID:** 6950DFACF3DA9842AF4C96E83B43790D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:25Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (10)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Date` | - | - |
| CreationTimestamp | `String` (255) | - | - |
| StaffID | `Date` | - | - |
| ProductionHold | `Real` | - | - |
| Active | `Real` | - | - |
| RunsActiveFor | `Date` | - | - |
| NoticeText | `String` (255) | - | - |
| DeactivatedStaffID | `Date` | - | - |
| DeactivatedTimestamp | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ToolID

**Properties:**

- **Type:** Date

---

#### CreationTimestamp

**Properties:**

- **Type:** String (max length: 255)

---

#### StaffID

**Properties:**

- **Type:** Date

---

#### ProductionHold

**Properties:**

- **Type:** Real

---

#### Active

**Properties:**

- **Type:** Real

---

#### RunsActiveFor

**Properties:**

- **Type:** Date

---

#### NoticeText

**Properties:**

- **Type:** String (max length: 255)

---

#### DeactivatedStaffID

**Properties:**

- **Type:** Date

---

#### DeactivatedTimestamp

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ToolID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |
| `DeactivatedStaffEntity` | [Staff](Staff.md) | `DeactivatedStaffID` → `StaffID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

#### DeactivatedStaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `DeactivatedStaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolNoticeWorksOrderSelection` | [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md) | `ToolNoticeID` → `ToolID` | Active |

### Detailed Information

#### ToolNoticeWorksOrderSelection

**Links from:** [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)

- **Source Table:** `ToolNoticeWorksOrder`
- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:25Z*

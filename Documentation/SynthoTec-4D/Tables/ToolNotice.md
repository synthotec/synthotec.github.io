---
layout : default
title : ToolNotice
parent : Tables
---
# ToolNotice

📊 **Overview:** 10 Fields | 2 Indexes | 3 Many-to-One Relations | 1 One-to-Many Relations

## 📝 Description

🗨️ Alert table flagging tool issues, damage, or required actions. Notifies staff of tool problems requiring attention or repair.

## ℹ️ Table Information

- **Table ID:** 134
- **UUID:** 6950DFACF3DA9842AF4C96E83B43790D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:33Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (10)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Long Integer` | - | - |
| CreationTimestamp | `String` (255) | - | - |
| StaffID | `Long Integer` | - | - |
| ProductionHold | `Boolean` | - | - |
| Active | `Boolean` | - | - |
| RunsActiveFor | `Long Integer` | - | - |
| NoticeText | `String` (255) | - | - |
| DeactivatedStaffID | `Long Integer` | - | - |
| DeactivatedTimestamp | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ToolID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |
| `DeactivatedStaffEntity` | [Staff](Staff.md) | `DeactivatedStaffID` → `StaffID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ToolNoticeWorksOrderSelection` | [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md) | `ToolNoticeID` → `ToolID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ToolNotice](../Classes/ToolNotice.md) - ORDA DataClass class for ToolNotice table
- [ToolNoticeEntity](../Classes/ToolNoticeEntity.md) - ORDA Entity class for ToolNotice table

### 📄 Forms

- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:33Z*

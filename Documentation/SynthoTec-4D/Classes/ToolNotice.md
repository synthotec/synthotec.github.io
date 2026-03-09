---
layout : default
title : ToolNotice
parent : Classes
---
# ToolNotice [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolNotice.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for tool notice records, supporting UI-based creation of notices and production holds for specific tools. A notice can limit production via a configurable number of remaining runs before it becomes inactive.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.742Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [create](#create) (1 param) → `$ToolNoticeEntity : cs.ToolNoticeEntity` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### create {#create}
 `[🖥️ local]`

```4d
Function create($ToolsEntity : cs.ToolsEntity) -> $ToolNoticeEntity : cs.ToolNoticeEntity
```

Creates a new tool notice or production hold through UI entry form, returns created entity or Null if cancelled

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `cs.ToolNoticeEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolNotice](../Tables/ToolNotice.md) - ORDA DataClass class for ToolNotice table

### � Related Classes

- [ToolNoticeEntity](ToolNoticeEntity.md) - ORDA Entity class for ToolNotice table

### � Forms

- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from ToolNotice.4dm*

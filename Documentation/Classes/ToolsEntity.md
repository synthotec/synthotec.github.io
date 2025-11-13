---
layout : default
title : ToolsEntity
parent : Classes
---
# ToolsEntity

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T23:17:39.242Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

**🔍 Getters (1):**

- [NextToolChangeText](#nexttoolchangetext) → `Text`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ToolsEntity) -> $Collection : Collection
```

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ToolsEntity)
```

return

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolsEntity` | - | - |

---

### 🔍 Getters

#### NextToolChangeText {#nexttoolchangetext}
 `[🔍 getter]`

```4d
Function NextToolChangeText -> Text
```

**Returns:** `Text`

---

## 🔗 Related Items

### 🗂️ Tables

- [Tools](../Tables/Tools.md) - Source table for this ORDA class

### � Related Classes

- [Tools](Tools.md) - ORDA DataClass class for Tools table

---

*Generated from ToolsEntity.4dm*

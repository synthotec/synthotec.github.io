---
layout : default
title : ToolsEntity
parent : Classes
---
# ToolsEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolsEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:45:51.202Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Properties (Getters/Setters/Query/OrderBy)**
    - [NextToolChangeText](#nexttoolchangetext) 🔍 → `Text`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

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

### Properties (Getters/Setters/Query/OrderBy)

#### NextToolChangeText {#nexttoolchangetext}
 `[🔍 get only]`

```4d
Function get NextToolChangeText -> Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Tools](../Tables/Tools.md) - Source table for this ORDA class

### � Related Classes

- [Tools](Tools.md) - ORDA DataClass class for Tools table

---

*Generated from ToolsEntity.4dm*

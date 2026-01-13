---
layout : default
title : PackingInstructionFiles
parent : Classes
---
# PackingInstructionFiles [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PackingInstructionFiles.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:12.238Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getLatest](#getlatest) (1 param) → `cs.PackingInstructionFilesEntity`
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getLatest {#getlatest}


```4d
Function getLatest($ProductID : Integer) -> cs.PackingInstructionFilesEntity
```

Returns the latest version of packing instructions for the specified product

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductID` | `Integer` | - | - |

**Returns:** `cs.PackingInstructionFilesEntity`

---

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns migration settings for PackingInstructionFiles with linking disabled

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [PackingInstructionFiles](../Tables/PackingInstructionFiles.md) - ORDA DataClass class for PackingInstructionFiles table

### � Related Classes

- [PackingInstructionFilesEntity](PackingInstructionFilesEntity.md) - ORDA Entity class for PackingInstructionFiles table

### � Forms

- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form

---

*Generated from PackingInstructionFiles.4dm*

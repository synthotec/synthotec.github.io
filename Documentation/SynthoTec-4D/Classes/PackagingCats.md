---
layout : default
title : PackagingCats
parent : Classes
---
# PackagingCats [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PackagingCats.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for packaging category records, used to classify the types of packaging materials used in despatch. Supports entity migration with linking enabled by category name.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.140Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns configuration for entity migration including linking settings and remote datastore selection

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [PackagingCats](../Tables/PackagingCats.md) - ORDA DataClass class for PackagingCats table

### � Related Classes

- [PackagingCatsEntity](PackagingCatsEntity.md) - ORDA Entity class for PackagingCats table

### � Forms

- [PC_List](../Forms/PC_List.md) - Data source for PC_List form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form

---

*Generated from PackagingCats.4dm*

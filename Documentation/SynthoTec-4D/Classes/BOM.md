---
layout : default
title : BOM
parent : Classes
---
# BOM [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/BOM.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for Bill of Materials records, defining the material composition and cost breakdown of each product. Supports entity migration (linking disabled).

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:28.997Z*

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

Returns configuration settings for entity migration (linking disabled for this dataclass)

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [BOM](../Tables/BOM.md) - ORDA DataClass class for BOM table

### � Related Classes

- [BOMEntity](BOMEntity.md) - ORDA Entity class for BOM table

### � Forms

- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form

---

*Generated from BOM.4dm*

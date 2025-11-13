---
layout : default
title : EntityMigrationRule
parent : Classes
---
# EntityMigrationRule

📊 **Overview:** 2 Properties | 1 Constructor | 6 Functions

🕐 *Last updated: 2025-11-13T21:44:51.128Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor)

**⚙️ Regular Functions (6):**

- [overwrite](#overwrite) (1 param) → `cs.EntityMigrationRule`
- [fillIfBlank](#fillifblank) (1 param) → `cs.EntityMigrationRule`
- [addFormula](#addformula) (3 params) → `cs.EntityMigrationRule`
- [addCriteria](#addcriteria) (1 param) → `cs.EntityMigrationRule`
- [addEntity](#addentity) (4 params) → `cs.EntityMigrationRule`
- [apply](#apply) (2 params)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `FormulaObjectCollection` | *Not specified* | `[]` | - |
| `CriteriaCollection` | *Not specified* | `[]` | - |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

### ⚙️ Regular Functions

#### overwrite {#overwrite}


```4d
Function overwrite($PropertyName : Text) -> cs.EntityMigrationRule
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PropertyName` | `Text` | - | - |

**Returns:** `cs.EntityMigrationRule`

---

#### fillIfBlank {#fillifblank}


```4d
Function fillIfBlank($PropertyName : Text) -> cs.EntityMigrationRule
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PropertyName` | `Text` | - | - |

**Returns:** `cs.EntityMigrationRule`

---

#### addFormula {#addformula}


```4d
Function addFormula($Formula : 4D.Function; $SecondParameter : Variant; $CheckProperty : Text) -> cs.EntityMigrationRule
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Formula` | `4D.Function` | - | - |
| `$SecondParameter` | `Variant` | - | - |
| `$CheckProperty` | `Text` | - | - |

**Returns:** `cs.EntityMigrationRule`

---

#### addCriteria {#addcriteria}


```4d
Function addCriteria($Formula : 4D.Function) -> cs.EntityMigrationRule
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Formula` | `4D.Function` | - | - |

**Returns:** `cs.EntityMigrationRule`

---

#### addEntity {#addentity}


```4d
Function addEntity($DataClass : 4D.DataClass; $LocalEntity : 4D.Entity; $Formula : 4D.Function; $Sync : Boolean) -> cs.EntityMigrationRule
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DataClass` | `4D.DataClass` | - | - |
| `$LocalEntity` | `4D.Entity` | - | - |
| `$Formula` | `4D.Function` | - | - |
| `$Sync` | `Boolean` | - | - |

**Returns:** `cs.EntityMigrationRule`

---

#### apply {#apply}


```4d
Function apply($LocalEntity : 4D.Entity; $RemoteEntity : 4D.Entity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LocalEntity` | `4D.Entity` | - | - |
| `$RemoteEntity` | `4D.Entity` | - | - |

---

---

*Generated from EntityMigrationRule.4dm*

---
layout : default
title : EntityMigrationRule
parent : Classes
---
# EntityMigrationRule [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/EntityMigrationRule.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 6 Functions

## 📝 Description

Defines a set of field-level rules for migrating an entity from a remote datastore to the local datastore. Supports overwrite, fill-if-blank, custom formula, and related-entity link operations, and can be chained for fluent rule composition.

🕐 *Last updated: 2026-03-09T14:45:29.545Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [overwrite](#overwrite) (1 param) → `cs.EntityMigrationRule`
    - [fillIfBlank](#fillifblank) (1 param) → `cs.EntityMigrationRule`
    - [addFormula](#addformula) (3 params) → `cs.EntityMigrationRule`
    - [addCriteria](#addcriteria) (1 param) → `cs.EntityMigrationRule`
    - [addEntity](#addentity) (4 params) → `cs.EntityMigrationRule`
    - [apply](#apply) (2 params)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `FormulaObjectCollection` | `Collection` | `[]` | Collection of formula objects to apply during migration |
| `CriteriaCollection` | `Collection` | `[]` | Collection of criteria formulas to evaluate before applying rules |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Creates a new entity migration rule with empty formula and criteria collections

---

## Functions {#functions}

### Regular Functions

#### overwrite {#overwrite}


```4d
Function overwrite($PropertyName : Text) -> cs.EntityMigrationRule
```

Adds rule to overwrite remote property with local property value unconditionally

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

Adds rule to fill remote property only if blank using local property value

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

Adds a custom formula to the migration rule with optional second parameter and property check

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

Adds a criteria formula that must return true for migration rules to be applied

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

Adds a related entity to the migration rule, optionally syncing it first, then applies formula with remote entity

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

Applies all formulas in this rule to sync data from local to remote entity after checking criteria

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LocalEntity` | `4D.Entity` | - | - |
| `$RemoteEntity` | `4D.Entity` | - | - |

---

---

*Generated from EntityMigrationRule.4dm*

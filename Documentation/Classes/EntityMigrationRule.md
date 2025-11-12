# EntityMigrationRule

## Table of Contents

### Properties

- [FormulaObjectCollection](#formulaobjectcollection)
- [CriteriaCollection](#criteriacollection)

### Functions

- [overwrite()](#overwrite)
- [fillIfBlank()](#fillifblank)
- [addFormula()](#addformula)
- [addCriteria()](#addcriteria)
- [addEntity()](#addentity)
- [apply()](#apply)

---

## Properties

### FormulaObjectCollection {#formulaobjectcollection}

**Type:** *Not specified*

**Default Value:** `[]`

---

### CriteriaCollection {#criteriacollection}

**Type:** *Not specified*

**Default Value:** `[]`

---

## Functions

### overwrite {#overwrite}


```4d
Function overwrite($PropertyName : Text) -> cs.EntityMigrationRule
```

**Returns:** `cs.EntityMigrationRule`

---

### fillIfBlank {#fillifblank}


```4d
Function fillIfBlank($PropertyName : Text) -> cs.EntityMigrationRule
```

**Returns:** `cs.EntityMigrationRule`

---

### addFormula {#addformula}


```4d
Function addFormula($Formula : 4D.Function; $SecondParameter : Variant; $CheckProperty : Text) -> cs.EntityMigrationRule
```

**Returns:** `cs.EntityMigrationRule`

---

### addCriteria {#addcriteria}


```4d
Function addCriteria($Formula : 4D.Function) -> cs.EntityMigrationRule
```

**Returns:** `cs.EntityMigrationRule`

---

### addEntity {#addentity}


```4d
Function addEntity($DataClass : 4D.DataClass; $LocalEntity : 4D.Entity; $Formula : 4D.Function; $Sync : Boolean) -> cs.EntityMigrationRule
```

**Returns:** `cs.EntityMigrationRule`

---

### apply {#apply}


```4d
Function apply($LocalEntity : 4D.Entity; $RemoteEntity : 4D.Entity)
```

---

---

*Generated from EntityMigrationRule.4dm*
*Last updated: 2025-11-12T17:04:21.645Z*

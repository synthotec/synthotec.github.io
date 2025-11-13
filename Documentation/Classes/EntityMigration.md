---
layout : default
title : EntityMigration
parent : Classes
---
# EntityMigration

📊 **Overview:** 6 Properties | 1 Constructor | 10 Functions | 7 Getters

## 📝 Description

🗨️ Initialize migration manager for a specific dataclass with optional remote selection for linking

🕐 *Last updated: 2025-11-13T13:39:35.713Z*

---

## 📑 Table of Contents

### 📋 Properties (6)

- [_RemoteDataStore](#remotedatastore) : `4D.DataStoreImplementation`
- [_DataClass](#dataclass) : `4D.DataClass`
- [LinkFunctionCancelled](#linkfunctioncancelled)
- [RemoteDataClass](#remotedataclass) : `4D.DataClass`
- [LinkRemoteSelection](#linkremoteselection) : `4D.EntitySelection`
- [Loading](#loading) : `cs.Loading`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Regular Functions (10):**

- [sync](#sync) (2 params) → `4D.Entity`
- [_functionsExistChecks](#_functionsexistchecks)
- [create](#create) (2 params) → `4D.Entity`
- [link](#link) (2 params) → `4D.Entity`
- [get](#get) (3 params) → `4D.Entity`
- [LinkDisplayPropertyValue](#linkdisplaypropertyvalue) (1 param) → `Variant`
- [updateLoading](#updateloading) (2 params)
- [startTransactions](#starttransactions)
- [validateTransactions](#validatetransactions)
- [cancelTransactions](#canceltransactions)

**🔍 Getters (7):**

- [NewEntityPropertyFormulas](#newentitypropertyformulas) → `Collection`
- [LinkDisplayProperty](#linkdisplayproperty) → `Text`
- [LinkAdditionalInfoProperty](#linkadditionalinfoproperty) → `Text`
- [LinkingEnabled](#linkingenabled) → `Boolean`
- [_MigrationSettings](#_migrationsettings) → `Object`
- [DataClassName](#dataclassname) → `Text`
- [MigrationPropertyExists](#migrationpropertyexists) → `Boolean`

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_RemoteDataStore` | `4D.DataStoreImplementation` | `DataStore(2)` | Remote datastore connection for migration target |
| `_DataClass` | `4D.DataClass` | - | Local dataclass being migrated |
| `LinkFunctionCancelled` | *Not specified* | `False` | Flag indicating user cancelled the link dialog |
| `RemoteDataClass` | `4D.DataClass` | - | Remote dataclass corresponding to local dataclass |
| `LinkRemoteSelection` | `4D.EntitySelection` | - | Remote entities available for linking |
| `Loading` | `cs.Loading` | - | Loading indicator for migration progress |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($DataClass : 4D.DataClass; $LinkRemoteSelection : 4D.EntitySelection)
```

Initialize migration manager for a specific dataclass with optional remote selection for linking

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DataClass` | `4D.DataClass` | - | - |
| `$LinkRemoteSelection` | `4D.EntitySelection` | - | - |

---

### ⚙️ Regular Functions

#### sync {#sync}


```4d
Function sync($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Synchronize local entity with remote entity, applying migration rules to update remote properties

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Entity` | `4D.Entity` | - | - |
| `$PreventSync` | `Boolean` | - | - |

**Returns:** `4D.Entity`

---

#### _functionsExistChecks {#_functionsexistchecks}


```4d
Function _functionsExistChecks
```

Development helper function to verify required migration functions exist on entity classes

---

#### create {#create}


```4d
Function create($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Create a new remote entity from local entity, applying initial property formulas

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Entity` | `4D.Entity` | - | - |
| `$PreventSync` | `Boolean` | - | - |

**Returns:** `4D.Entity`

---

#### link {#link}


```4d
Function link($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Prompt user to link local entity to existing remote entity or create new one

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Entity` | `4D.Entity` | - | - |
| `$PreventSync` | `Boolean` | - | - |

**Returns:** `4D.Entity`

---

#### get {#get}


```4d
Function get($Entity : 4D.Entity; $LinkEntity : Boolean; $PreventSync : Boolean) -> 4D.Entity
```

Retrieve remote entity by MigrationID, optionally linking if not found

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Entity` | `4D.Entity` | - | - |
| `$LinkEntity` | `Boolean` | - | - |
| `$PreventSync` | `Boolean` | - | - |

**Returns:** `4D.Entity`

---

#### LinkDisplayPropertyValue {#linkdisplaypropertyvalue}


```4d
Function LinkDisplayPropertyValue($Entity : 4D.Entity) -> Variant
```

Get the display value for an entity, using LinkDisplayProperty or primary key

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Entity` | `4D.Entity` | - | - |

**Returns:** `Variant`

---

#### updateLoading {#updateloading}


```4d
Function updateLoading($LoadingText : Text; $Entity : 4D.Entity)
```

Update migration progress log with color-coded status messages

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LoadingText` | `Text` | - | - |
| `$Entity` | `4D.Entity` | - | - |

---

#### startTransactions {#starttransactions}


```4d
Function startTransactions
```

Begin transactions on both local and remote datastores

---

#### validateTransactions {#validatetransactions}


```4d
Function validateTransactions
```

Commit transactions on both local and remote datastores

---

#### cancelTransactions {#canceltransactions}


```4d
Function cancelTransactions
```

Rollback transactions on both local and remote datastores

---

### 🔍 Getters

#### NewEntityPropertyFormulas {#newentitypropertyformulas}
 `[🔍 getter]`

```4d
Function NewEntityPropertyFormulas -> Collection
```

Collection of formulas to apply when creating new remote entities

**Returns:** `Collection`

---

#### LinkDisplayProperty {#linkdisplayproperty}
 `[🔍 getter]`

```4d
Function LinkDisplayProperty -> Text
```

Property name to display when linking entities

**Returns:** `Text`

---

#### LinkAdditionalInfoProperty {#linkadditionalinfoproperty}
 `[🔍 getter]`

```4d
Function LinkAdditionalInfoProperty -> Text
```

Additional property to show during linking for context

**Returns:** `Text`

---

#### LinkingEnabled {#linkingenabled}
 `[🔍 getter]`

```4d
Function LinkingEnabled -> Boolean
```

Whether interactive linking is enabled for this migration

**Returns:** `Boolean`

---

#### _MigrationSettings {#_migrationsettings}
 `[🔍 getter]`

```4d
Function _MigrationSettings -> Object
```

Migration settings from the dataclass's getMigrationSettings function

**Returns:** `Object`

---

#### DataClassName {#dataclassname}
 `[🔍 getter]`

```4d
Function DataClassName -> Text
```

Name of the local dataclass being migrated

**Returns:** `Text`

---

#### MigrationPropertyExists {#migrationpropertyexists}
 `[🔍 getter]`

```4d
Function MigrationPropertyExists -> Boolean
```

Check if the dataclass has a MigrationID property

**Returns:** `Boolean`

---

---

*Generated from EntityMigration.4dm*

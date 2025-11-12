# EntityMigration

## Description

Initialize migration manager for a specific dataclass with optional remote selection for linking

## Table of Contents

### Properties

- [_RemoteDataStore](#remotedatastore)
- [_DataClass](#dataclass)
- [LinkFunctionCancelled](#linkfunctioncancelled)
- [RemoteDataClass](#remotedataclass)
- [LinkRemoteSelection](#linkremoteselection)
- [Loading](#loading)

### Functions

- [sync()](#sync)
- [_functionsExistChecks()](#_functionsexistchecks)
- [create()](#create)
- [link()](#link)
- [get()](#get)
- [NewEntityPropertyFormulas() [getter]](#newentitypropertyformulas)
- [LinkDisplayProperty() [getter]](#linkdisplayproperty)
- [LinkAdditionalInfoProperty() [getter]](#linkadditionalinfoproperty)
- [LinkDisplayPropertyValue()](#linkdisplaypropertyvalue)
- [LinkingEnabled() [getter]](#linkingenabled)
- [_MigrationSettings() [getter]](#_migrationsettings)
- [DataClassName() [getter]](#dataclassname)
- [MigrationPropertyExists() [getter]](#migrationpropertyexists)
- [updateLoading()](#updateloading)
- [startTransactions()](#starttransactions)
- [validateTransactions()](#validatetransactions)
- [cancelTransactions()](#canceltransactions)

---

## Properties

### _RemoteDataStore {#remotedatastore}

**Type:** `4D.DataStoreImplementation`

**Default Value:** `DataStore(2)`

Remote datastore connection for migration target

---

### _DataClass {#dataclass}

**Type:** `4D.DataClass`

Local dataclass being migrated

---

### LinkFunctionCancelled {#linkfunctioncancelled}

**Type:** *Not specified*

**Default Value:** `False`

Flag indicating user cancelled the link dialog

---

### RemoteDataClass {#remotedataclass}

**Type:** `4D.DataClass`

Remote dataclass corresponding to local dataclass

---

### LinkRemoteSelection {#linkremoteselection}

**Type:** `4D.EntitySelection`

Remote entities available for linking

---

### Loading {#loading}

**Type:** `cs.Loading`

Loading indicator for migration progress

---

## Functions

### sync {#sync}


```4d
Function sync($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Synchronize local entity with remote entity, applying migration rules to update remote properties

**Note:** Test 2

**Parameters:**

- `$Entity` (4D.Entity): Test
- `$PreventSync` (Boolean)

**Returns:** `4D.Entity`

---

### _functionsExistChecks {#_functionsexistchecks}


```4d
Function _functionsExistChecks
```

Development helper function to verify required migration functions exist on entity classes

---

### create {#create}


```4d
Function create($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Create a new remote entity from local entity, applying initial property formulas

**Returns:** `4D.Entity`

---

### link {#link}


```4d
Function link($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Prompt user to link local entity to existing remote entity or create new one

**Returns:** `4D.Entity`

---

### get {#get}


```4d
Function get($Entity : 4D.Entity; $LinkEntity : Boolean; $PreventSync : Boolean) -> 4D.Entity
```

Retrieve remote entity by MigrationID, optionally linking if not found

**Returns:** `4D.Entity`

---

### NewEntityPropertyFormulas {#newentitypropertyformulas}
 `[getter]`

```4d
Function NewEntityPropertyFormulas -> Collection
```

Collection of formulas to apply when creating new remote entities

**Returns:** `Collection`

---

### LinkDisplayProperty {#linkdisplayproperty}
 `[getter]`

```4d
Function LinkDisplayProperty -> Text
```

Property name to display when linking entities

**Returns:** `Text`

---

### LinkAdditionalInfoProperty {#linkadditionalinfoproperty}
 `[getter]`

```4d
Function LinkAdditionalInfoProperty -> Text
```

Additional property to show during linking for context

**Returns:** `Text`

---

### LinkDisplayPropertyValue {#linkdisplaypropertyvalue}


```4d
Function LinkDisplayPropertyValue($Entity : 4D.Entity) -> Variant
```

Get the display value for an entity, using LinkDisplayProperty or primary key

**Returns:** `Variant`

---

### LinkingEnabled {#linkingenabled}
 `[getter]`

```4d
Function LinkingEnabled -> Boolean
```

Whether interactive linking is enabled for this migration

**Returns:** `Boolean`

---

### _MigrationSettings {#_migrationsettings}
 `[getter]`

```4d
Function _MigrationSettings -> Object
```

Migration settings from the dataclass's getMigrationSettings function

**Returns:** `Object`

---

### DataClassName {#dataclassname}
 `[getter]`

```4d
Function DataClassName -> Text
```

Name of the local dataclass being migrated

**Returns:** `Text`

---

### MigrationPropertyExists {#migrationpropertyexists}
 `[getter]`

```4d
Function MigrationPropertyExists -> Boolean
```

Check if the dataclass has a MigrationID property

**Returns:** `Boolean`

---

### updateLoading {#updateloading}


```4d
Function updateLoading($LoadingText : Text; $Entity : 4D.Entity)
```

Update migration progress log with color-coded status messages

---

### startTransactions {#starttransactions}


```4d
Function startTransactions
```

Begin transactions on both local and remote datastores

---

### validateTransactions {#validatetransactions}


```4d
Function validateTransactions
```

Commit transactions on both local and remote datastores

---

### cancelTransactions {#canceltransactions}


```4d
Function cancelTransactions
```

Rollback transactions on both local and remote datastores

---

---

*Generated from EntityMigration.4dm*
*Last updated: 2025-11-12T17:04:21.636Z*

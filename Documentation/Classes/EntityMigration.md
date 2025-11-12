# EntityMigration

## Description

Initialize migration manager for a specific dataclass with optional remote selection for linking

## Properties

|Name|Type|Default|Description|
|:---|:---|:---|:---|
|`_RemoteDataStore`|`4D.DataStoreImplementation`|`DataStore(2)`|Remote datastore connection for migration target|
|`_DataClass`|`4D.DataClass`||Local dataclass being migrated|
|`LinkFunctionCancelled`||`False`|Flag indicating user cancelled the link dialog|
|`RemoteDataClass`|`4D.DataClass`||Remote dataclass corresponding to local dataclass|
|`LinkRemoteSelection`|`4D.EntitySelection`||Remote entities available for linking|
|`Loading`|`cs.Loading`||Loading indicator for migration progress|

## Functions

### sync

```4d
Function sync($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Synchronize local entity with remote entity, applying migration rules to update remote properties

**Returns:** `4D.Entity`

---

### _functionsExistChecks

```4d
Function _functionsExistChecks
```

Development helper function to verify required migration functions exist on entity classes

---

### create

```4d
Function create($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Create a new remote entity from local entity, applying initial property formulas

**Returns:** `4D.Entity`

---

### link

```4d
Function link($Entity : 4D.Entity; $PreventSync : Boolean) -> 4D.Entity
```

Prompt user to link local entity to existing remote entity or create new one

**Returns:** `4D.Entity`

---

### get

```4d
Function get($Entity : 4D.Entity; $LinkEntity : Boolean; $PreventSync : Boolean) -> 4D.Entity
```

Retrieve remote entity by MigrationID, optionally linking if not found

**Returns:** `4D.Entity`

---

### NewEntityPropertyFormulas `[getter]`

```4d
Function NewEntityPropertyFormulas -> Collection
```

Collection of formulas to apply when creating new remote entities

**Returns:** `Collection`

---

### LinkDisplayProperty `[getter]`

```4d
Function LinkDisplayProperty -> Text
```

Property name to display when linking entities

**Returns:** `Text`

---

### LinkAdditionalInfoProperty `[getter]`

```4d
Function LinkAdditionalInfoProperty -> Text
```

Additional property to show during linking for context

**Returns:** `Text`

---

### LinkDisplayPropertyValue

```4d
Function LinkDisplayPropertyValue($Entity : 4D.Entity) -> Variant
```

Get the display value for an entity, using LinkDisplayProperty or primary key

**Returns:** `Variant`

---

### LinkingEnabled `[getter]`

```4d
Function LinkingEnabled -> Boolean
```

Whether interactive linking is enabled for this migration

**Returns:** `Boolean`

---

### _MigrationSettings `[getter]`

```4d
Function _MigrationSettings -> Object
```

Migration settings from the dataclass's getMigrationSettings function

**Returns:** `Object`

---

### DataClassName `[getter]`

```4d
Function DataClassName -> Text
```

Name of the local dataclass being migrated

**Returns:** `Text`

---

### MigrationPropertyExists `[getter]`

```4d
Function MigrationPropertyExists -> Boolean
```

Check if the dataclass has a MigrationID property

**Returns:** `Boolean`

---

### updateLoading

```4d
Function updateLoading($LoadingText : Text; $Entity : 4D.Entity)
```

Update migration progress log with color-coded status messages

---

### startTransactions

```4d
Function startTransactions
```

Begin transactions on both local and remote datastores

---

### validateTransactions

```4d
Function validateTransactions
```

Commit transactions on both local and remote datastores

---

### cancelTransactions

```4d
Function cancelTransactions
```

Rollback transactions on both local and remote datastores

---

---

*Generated from EntityMigration.4dm*
*Last updated: 2025-11-12T16:28:02.646Z*

---
layout : default
title : DataStore
parent : Classes
---
# DataStore [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/DataStore.4dm)

📊 **Overview:** 19 Functions

## 📝 Description

Custom DataStoreImplementation providing utility methods that extend the standard 4D datastore. Currently provides a helper to find all entities with duplicate values for a specified attribute across any DataClass.

**Extends:** `DataStoreImplementation`

🕐 *Last updated: 2026-03-09T14:45:29.318Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getDuplicateValueEntities](#getduplicatevalueentities) (2 params) → `$DuplicateEntitySelection : 4D.EntitySelection` 🖥️
    - [applyFormulasToSelection](#applyformulastoselection) (3 params) → `$LockedEntityCollection : Collection` 🖥️
    - [lockEntitySelection](#lockentityselection) (2 params) → `$LockedSelectionObject : Object` 🖥️
    - [unlockEntitySelection](#unlockentityselection) (1 param) 🖥️
    - [lockEntity](#lockentity) (2 params) → `$Success : Boolean` 🖥️
    - [getTablePrimaryKeyField](#gettableprimarykeyfield) (1 param) → `Pointer` 🖥️
    - [getRelation](#getrelation) (2 params) → `$relatedEntityOrEntitySelection : Variant` 🖥️
    - [getRelationName](#getrelationname) (3 params) → `$relationName : Text`
    - [updateClientFiles](#updateclientfiles) → `Boolean`
    - [stringTest](#stringtest) (1 param) → `Boolean`
    - [echoTest](#echotest) (1 param) → `Variant`
    - [blobTest](#blobtest) (1 param) → `Integer`
    - [_getUpdateFolder](#_getupdatefolder) → `4D.Folder`
    - [updateServer](#updateserver) (1 param) → `Object`
    - [testA](#testa) → `Object`
    - [testB](#testb) → `Object`
    - [unpackServerUpdate](#unpackserverupdate) → `Boolean`
    - [_updateServer](#_updateserver) 🖥️
    - [_unpackServerUpdate->$UpdateFolder](#_unpackserverupdate->$updatefolder) → `4D.Folder` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getDuplicateValueEntities {#getduplicatevalueentities}
 `[🖥️ local]`

```4d
Function getDuplicateValueEntities($DataClass : 4D.DataClass; $DataClassAttribute : Object) -> $DuplicateEntitySelection : 4D.EntitySelection
```

Returns entity selection containing all entities with duplicate values for the specified attribute

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DataClass` | `4D.DataClass` | - | - |
| `$DataClassAttribute` | `Object` | - | - |

**Returns:** `4D.EntitySelection`

---

#### applyFormulasToSelection {#applyformulastoselection}
 `[🖥️ local]`

```4d
Function applyFormulasToSelection($EntitySelection : 4D.EntitySelection; $FormulaOrFormulaCollection : Variant; $FormulaParamsCollection : Collection) -> $LockedEntityCollection : Collection
```

Applies formula(s) to each entity in selection, locks entities during update, returns collection of locked entities

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntitySelection` | `4D.EntitySelection` | - | - |
| `$FormulaOrFormulaCollection` | `Variant` | - | - |
| `$FormulaParamsCollection` | `Collection` | - | - |

**Returns:** `Collection`

---

#### lockEntitySelection {#lockentityselection}
 `[🖥️ local]`

```4d
Function lockEntitySelection($EntitySelection : 4D.EntitySelection; $LockIfErrorOccurs : Boolean) -> $LockedSelectionObject : Object
```

Locks all entities in selection, returns object with locked entities collection and success status

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntitySelection` | `4D.EntitySelection` | - | - |
| `$LockIfErrorOccurs` | `Boolean` | - | - |

**Returns:** `Object`

---

#### unlockEntitySelection {#unlockentityselection}
 `[🖥️ local]`

```4d
Function unlockEntitySelection($LockedSelectionObject : Object)
```

Unlocks all entities in the locked selection object's collection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LockedSelectionObject` | `Object` | - | - |

---

#### lockEntity {#lockentity}
 `[🖥️ local]`

```4d
Function lockEntity($Entity : 4D.Entity; $DisplayWarning : Boolean) -> $Success : Boolean
```

Locks a single entity with reload if stamp changed, optionally displays warning dialog on failure

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Entity` | `4D.Entity` | - | - |
| `$DisplayWarning` | `Boolean` | - | - |

**Returns:** `Boolean`

---

#### getTablePrimaryKeyField {#gettableprimarykeyfield}
 `[🖥️ local]`

```4d
Function getTablePrimaryKeyField($TablePointerOrNumber : Variant) -> Pointer
```

Returns a pointer to the primary key field of the specified table (accepts pointer or table number)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TablePointerOrNumber` | `Variant` | - | - |

**Returns:** `Pointer`

---

#### getRelation {#getrelation}
 `[🖥️ local]`

```4d
Function getRelation($entityOrEntitySelection : Variant; $destinationTable : 4D.DataClass) -> $relatedEntityOrEntitySelection : Variant
```

Returns related entity or entity selection from source to destination table via ORDA relationship

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$entityOrEntitySelection` | `Variant` | - | - |
| `$destinationTable` | `4D.DataClass` | - | - |

**Returns:** `Variant`

---

#### getRelationName {#getrelationname}


```4d
Function getRelationName($sourceTableClass : 4D.Class; $destinationTableClass : 4D.Class; $supressNoRelationWarning : Boolean) -> $relationName : Text
```

Returns the attribute name representing the relationship between source and destination tables

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$sourceTableClass` | `4D.Class` | - | - |
| `$destinationTableClass` | `4D.Class` | - | - |
| `$supressNoRelationWarning` | `Boolean` | - | - |

**Returns:** `Text`

---

#### updateClientFiles {#updateclientfiles}


```4d
Function updateClientFiles -> Boolean
```

Updates client files on network share from extracted ClientUpdate folder; returns true if successful with rollback on failure

**Returns:** `Boolean`

---

#### stringTest {#stringtest}


```4d
Function stringTest($Text : Text) -> Boolean
```

Test endpoint for string parameter passing; returns true (used for REST API testing)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Text` | `Text` | - | - |

**Returns:** `Boolean`

---

#### echoTest {#echotest}


```4d
Function echoTest($Variant : Variant) -> Variant
```

Test endpoint for variant parameter passing and return value; echoes input back unchanged (used for REST API testing)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Variant` | `Variant` | - | - |

**Returns:** `Variant`

---

#### blobTest {#blobtest}


```4d
Function blobTest($Blob : Blob) -> Integer
```

Test endpoint for blob parameter passing; returns blob size in bytes (used for REST API testing)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Blob` | `Blob` | - | - |

**Returns:** `Integer`

---

#### _getUpdateFolder {#_getupdatefolder}


```4d
Function _getUpdateFolder -> 4D.Folder
```

Returns the update folder path from settings; used as root for ServerUpdate and ClientUpdate operations

**Returns:** `4D.Folder`

---

#### updateServer {#updateserver}


```4d
Function updateServer($RestartServer : Boolean) -> Object
```

Asynchronously performs server update via background worker; returns shared object with status/success/running properties

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestartServer` | `Boolean` | - | - |

**Returns:** `Object`

---

#### testA {#testa}


```4d
Function testA -> Object
```

Test function for worker signal mechanism; returns server update worker signal object (development/debugging)

**Returns:** `Object`

---

#### testB {#testb}


```4d
Function testB -> Object
```

Test function for storage object access; returns copy of entire Storage object (development/debugging)

**Returns:** `Object`

---

#### unpackServerUpdate {#unpackserverupdate}


```4d
Function unpackServerUpdate -> Boolean
```

Triggers server update unpacking via background worker signal; waits for completion and returns success status

**Returns:** `Boolean`

---

#### _updateServer {#_updateserver}
 `[🖥️ local]`

```4d
Function _updateServer
```

Internal worker process that manages server update queue; listens for unpacking signals and processes updates in loop

---

#### _unpackServerUpdate->$UpdateFolder {#_unpackserverupdate->$updatefolder}
 `[🖥️ local]`

```4d
Function _unpackServerUpdate->$UpdateFolder -> 4D.Folder
```

Extracts server and client zip archives to update folders; copies certificates to server update folder for SSL/TLS

**Returns:** `4D.Folder`

---

## Related Items {#related-items}

### � Related Classes

- [DataStoreImplementation](DataStoreImplementation.md) - Base class for DataStore X

---

*Generated from DataStore.4dm*

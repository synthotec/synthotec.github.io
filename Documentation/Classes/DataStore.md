# DataStore

**Extends:** `DataStoreImplementation`

## Table of Contents

### Functions

- [getDuplicateValueEntities()](#getduplicatevalueentities)
- [applyFormulasToSelection()](#applyformulastoselection)
- [lockEntitySelection()](#lockentityselection)
- [unlockEntitySelection()](#unlockentityselection)
- [lockEntity()](#lockentity)
- [getTablePrimaryKeyField()](#gettableprimarykeyfield)
- [getRelation()](#getrelation)
- [getRelationName()](#getrelationname)
- [updateClientFiles()](#updateclientfiles)
- [stringTest()](#stringtest)
- [echoTest()](#echotest)
- [blobTest()](#blobtest)
- [_getUpdateFolder()](#_getupdatefolder)
- [updateServer()](#updateserver)
- [testA()](#testa)
- [testB()](#testb)
- [unpackServerUpdate()](#unpackserverupdate)
- [_updateServer()](#_updateserver)
- [_unpackServerUpdate->$UpdateFolder()](#_unpackserverupdate->$updatefolder)

---

## Functions

### getDuplicateValueEntities {#getduplicatevalueentities}
 `[local]`

```4d
Function getDuplicateValueEntities($DataClass : 4D.DataClass; $DataClassAttribute : Object) -> 4D.EntitySelection
```

**Returns:** `4D.EntitySelection`

---

### applyFormulasToSelection {#applyformulastoselection}
 `[local]`

```4d
Function applyFormulasToSelection($EntitySelection : 4D.EntitySelection; $FormulaOrFormulaCollection : Variant; $FormulaParamsCollection : Collection) -> Collection
```

**Returns:** `Collection`

---

### lockEntitySelection {#lockentityselection}
 `[local]`

```4d
Function lockEntitySelection($EntitySelection : 4D.EntitySelection; $LockIfErrorOccurs : Boolean) -> Object
```

**Returns:** `Object`

---

### unlockEntitySelection {#unlockentityselection}
 `[local]`

```4d
Function unlockEntitySelection($LockedSelectionObject : Object)
```

---

### lockEntity {#lockentity}
 `[local]`

```4d
Function lockEntity($Entity : 4D.Entity; $DisplayWarning : Boolean) -> Boolean
```

**Returns:** `Boolean`

---

### getTablePrimaryKeyField {#gettableprimarykeyfield}
 `[local]`

```4d
Function getTablePrimaryKeyField($TablePointerOrNumber : Variant) -> Pointer
```

**Returns:** `Pointer`

---

### getRelation {#getrelation}
 `[local]`

```4d
Function getRelation($entityOrEntitySelection : Variant; $destinationTable : 4D.DataClass) -> Variant
```

**Returns:** `Variant`

---

### getRelationName {#getrelationname}


```4d
Function getRelationName($sourceTableClass : 4D.Class; $destinationTableClass : 4D.Class; $supressNoRelationWarning : Boolean) -> Text
```

**Returns:** `Text`

---

### updateClientFiles {#updateclientfiles}
 `[exposed]`

```4d
Function updateClientFiles -> Boolean
```

**Returns:** `Boolean`

---

### stringTest {#stringtest}
 `[exposed]`

```4d
Function stringTest($Text : Text) -> Boolean
```

**Returns:** `Boolean`

---

### echoTest {#echotest}
 `[exposed]`

```4d
Function echoTest($Variant : Variant) -> Variant
```

**Returns:** `Variant`

---

### blobTest {#blobtest}
 `[exposed]`

```4d
Function blobTest($Blob : Blob) -> Integer
```

**Returns:** `Integer`

---

### _getUpdateFolder {#_getupdatefolder}


```4d
Function _getUpdateFolder -> 4D.Folder
```

**Returns:** `4D.Folder`

---

### updateServer {#updateserver}
 `[exposed]`

```4d
Function updateServer($RestartServer : Boolean) -> Object
```

**Returns:** `Object`

---

### testA {#testa}
 `[exposed]`

```4d
Function testA -> Object
```

**Returns:** `Object`

---

### testB {#testb}
 `[exposed]`

```4d
Function testB -> Object
```

**Returns:** `Object`

---

### unpackServerUpdate {#unpackserverupdate}
 `[exposed]`

```4d
Function unpackServerUpdate -> Boolean
```

**Returns:** `Boolean`

---

### _updateServer {#_updateserver}
 `[local]`

```4d
Function _updateServer
```

---

### _unpackServerUpdate->$UpdateFolder {#_unpackserverupdate->$updatefolder}
 `[local]`

```4d
Function _unpackServerUpdate->$UpdateFolder -> 4D.Folder
```

**Returns:** `4D.Folder`

---

---

*Generated from DataStore.4dm*
*Last updated: 2025-11-12T17:17:31.494Z*

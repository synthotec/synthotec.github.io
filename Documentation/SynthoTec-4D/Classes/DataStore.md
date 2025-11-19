---
layout : default
title : DataStore
parent : Classes
---
# DataStore [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/DataStore.4dm)

📊 **Overview:** 19 Functions

**Extends:** `DataStoreImplementation`

🕐 *Last updated: 2025-11-19T15:47:08.019Z*

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
---

## Functions {#functions}

### Regular Functions

#### getDuplicateValueEntities {#getduplicatevalueentities}
 `[🖥️ local]`

```4d
Function getDuplicateValueEntities($DataClass : 4D.DataClass; $DataClassAttribute : Object) -> $DuplicateEntitySelection : 4D.EntitySelection
```

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

**Returns:** `Boolean`

---

#### stringTest {#stringtest}


```4d
Function stringTest($Text : Text) -> Boolean
```

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

**Returns:** `4D.Folder`

---

#### updateServer {#updateserver}


```4d
Function updateServer($RestartServer : Boolean) -> Object
```

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

**Returns:** `Object`

---

#### testB {#testb}


```4d
Function testB -> Object
```

**Returns:** `Object`

---

#### unpackServerUpdate {#unpackserverupdate}


```4d
Function unpackServerUpdate -> Boolean
```

**Returns:** `Boolean`

---

#### _updateServer {#_updateserver}
 `[🖥️ local]`

```4d
Function _updateServer
```

---

#### _unpackServerUpdate->$UpdateFolder {#_unpackserverupdate->$updatefolder}
 `[🖥️ local]`

```4d
Function _unpackServerUpdate->$UpdateFolder -> 4D.Folder
```

**Returns:** `4D.Folder`

---

---

*Generated from DataStore.4dm*

---
layout : default
title : BoxLabelsEntity
parent : Classes
---
# BoxLabelsEntity

📊 **Overview:** 10 Functions | 19 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T12:58:33.494Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (10):**

- [getStatesCollection](#getstatescollection) → `Collection`
- [ModifyStatus](#modifystatus) 🖥️
- [AddComment](#addcomment) (2 params) 🖥️
- [query PartBox](#query partbox) (1 param)
- [query Despatched](#query despatched) (1 param)
- [removeFromPallet](#removefrompallet) → `Boolean`
- [getNextBoxPacked](#getnextboxpacked) → `cs.BoxLabelsEntity` 🖥️
- [generateQR](#generateqr) → `Picture` 🖥️
- [getMigrationRules](#getmigrationrules) (1 param) → `Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

**🔍 Getters (19):**

- [NetWeightKg](#netweightkg) → `Real`
- [GrossWeightKg](#grossweightkg) → `Real`
- [CurrentStatus](#currentstatus) → `Object`
- [StatusText](#statustext) → `Text`
- [PartsFromOtherWorksOrders->$Text](#partsfromotherworksorders->$text) → `Text`
- [BoxNumberColor](#boxnumbercolor) → `Integer`
- [AdviceNote](#advicenote) → `Integer`
- [BoxQuantityDisplay](#boxquantitydisplay) → `Text`
- [PackedByDisplay](#packedbydisplay) → `Text`
- [BoxNumberDisplay](#boxnumberdisplay) → `Text`
- [RouteCardColor](#routecardcolor) → `Integer`
- [PartBox](#partbox) → `Boolean`
- [Despatched](#despatched) → `Boolean`
- [linkedBoxesQuantity](#linkedboxesquantity) → `Integer`
- [totalBoxQuantity](#totalboxquantity) → `Integer`
- [partBoxSkipped](#partboxskipped) → `Boolean`
- [toolIsRunning](#toolisrunning) → `Boolean`
- [HasMigrationID](#hasmigrationid) → `Boolean`
- [TestProduct](#testproduct) → `cs.ProductEntity`

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getStatesCollection {#getstatescollection}


```4d
Function getStatesCollection -> Collection
```

**Returns:** `Collection`

---

#### ModifyStatus {#modifystatus}
 `[🖥️ local]`

```4d
Function ModifyStatus
```

---

#### AddComment {#addcomment}
 `[🖥️ local]`

```4d
Function AddComment($Comment : Text; $StaffEntity : cs.StaffEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Comment` | `Text` | - | - |
| `$StaffEntity` | `cs.StaffEntity` | - | - |

---

#### query PartBox {#query partbox}


```4d
Function query PartBox($QueryEventObject : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

#### query Despatched {#query despatched}


```4d
Function query Despatched($QueryEventObject : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

#### removeFromPallet {#removefrompallet}


```4d
Function removeFromPallet -> Boolean
```

**Returns:** `Boolean`

---

#### getNextBoxPacked {#getnextboxpacked}
 `[🖥️ local]`

```4d
Function getNextBoxPacked -> cs.BoxLabelsEntity
```

**Returns:** `cs.BoxLabelsEntity`

---

#### generateQR {#generateqr}
 `[🖥️ local]`

```4d
Function generateQR -> Picture
```

**Returns:** `Picture`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.BoxLabelsEntity) -> Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.BoxLabelsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.BoxLabelsEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.BoxLabelsEntity` | - | - |

---

### 🔍 Getters

#### NetWeightKg {#netweightkg}
 `[🖥️ local, 🔍 getter]`

```4d
Function NetWeightKg -> Real
```

**Returns:** `Real`

---

#### GrossWeightKg {#grossweightkg}
 `[🖥️ local, 🔍 getter]`

```4d
Function GrossWeightKg -> Real
```

**Returns:** `Real`

---

#### CurrentStatus {#currentstatus}
 `[🔍 getter]`

```4d
Function CurrentStatus -> Object
```

**Returns:** `Object`

---

#### StatusText {#statustext}
 `[🔍 getter]`

```4d
Function StatusText -> Text
```

**Returns:** `Text`

---

#### PartsFromOtherWorksOrders->$Text {#partsfromotherworksorders->$text}
 `[🔍 getter]`

```4d
Function PartsFromOtherWorksOrders->$Text -> Text
```

**Returns:** `Text`

---

#### BoxNumberColor {#boxnumbercolor}
 `[🔍 getter]`

```4d
Function BoxNumberColor -> Integer
```

**Returns:** `Integer`

---

#### AdviceNote {#advicenote}
 `[🔍 getter]`

```4d
Function AdviceNote -> Integer
```

**Returns:** `Integer`

---

#### BoxQuantityDisplay {#boxquantitydisplay}
 `[🔍 getter]`

```4d
Function BoxQuantityDisplay -> Text
```

**Returns:** `Text`

---

#### PackedByDisplay {#packedbydisplay}
 `[🔍 getter]`

```4d
Function PackedByDisplay -> Text
```

**Returns:** `Text`

---

#### BoxNumberDisplay {#boxnumberdisplay}
 `[🔍 getter]`

```4d
Function BoxNumberDisplay -> Text
```

**Returns:** `Text`

---

#### RouteCardColor {#routecardcolor}
 `[🔍 getter]`

```4d
Function RouteCardColor -> Integer
```

**Returns:** `Integer`

---

#### PartBox {#partbox}
 `[🔍 getter]`

```4d
Function PartBox -> Boolean
```

**Returns:** `Boolean`

---

#### Despatched {#despatched}
 `[🔍 getter]`

```4d
Function Despatched -> Boolean
```

**Returns:** `Boolean`

---

#### linkedBoxesQuantity {#linkedboxesquantity}
 `[🖥️ local, 🔍 getter]`

```4d
Function linkedBoxesQuantity -> Integer
```

**Returns:** `Integer`

---

#### totalBoxQuantity {#totalboxquantity}
 `[🖥️ local, 🔍 getter]`

```4d
Function totalBoxQuantity -> Integer
```

**Returns:** `Integer`

---

#### partBoxSkipped {#partboxskipped}
 `[🖥️ local, 🔍 getter]`

```4d
Function partBoxSkipped -> Boolean
```

**Returns:** `Boolean`

---

#### toolIsRunning {#toolisrunning}
 `[🖥️ local, 🔍 getter]`

```4d
Function toolIsRunning -> Boolean
```

**Returns:** `Boolean`

---

#### HasMigrationID {#hasmigrationid}
 `[🖥️ local, 🔍 getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

#### TestProduct {#testproduct}
 `[🔍 getter]`

```4d
Function TestProduct -> cs.ProductEntity
```

**Returns:** `cs.ProductEntity`

---

## 🔗 Related Items

### 🗂️ Used By Tables

- [BoxLabels](../Tables/BoxLabels.md) - Entity class

---

*Generated from BoxLabelsEntity.4dm*

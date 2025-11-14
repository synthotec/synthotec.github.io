---
layout : default
title : BoxLabelsEntity
parent : Classes
---
# BoxLabelsEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/BoxLabelsEntity.4dm)

📊 **Overview:** 8 Functions | 19 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:45:49.690Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getStatesCollection](#getstatescollection) → `Collection`
    - [ModifyStatus](#modifystatus) 🖥️
    - [AddComment](#addcomment) (2 params) 🖥️
    - [removeFromPallet](#removefrompallet) → `$Success : Boolean`
    - [getNextBoxPacked](#getnextboxpacked) → `cs.BoxLabelsEntity` 🖥️
    - [generateQR](#generateqr) → `Picture` 🖥️
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Properties (Getters/Setters/Query/OrderBy)**
    - [AdviceNote](#advicenote) 🔍 → `Integer`
    - [BoxNumberColor](#boxnumbercolor) 🔍 → `Integer`
    - [BoxNumberDisplay](#boxnumberdisplay) 🔍 → `Text`
    - [BoxQuantityDisplay](#boxquantitydisplay) 🔍 → `Text`
    - [CurrentStatus](#currentstatus) 🔍 → `Object`
    - [Despatched](#despatched) 🔍 🔎 → `Boolean`
    - [GrossWeightKg](#grossweightkg) 🔍 → `Real`
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
    - [linkedBoxesQuantity](#linkedboxesquantity) 🔍 → `Integer`
    - [NetWeightKg](#netweightkg) 🔍 → `Real`
    - [PackedByDisplay](#packedbydisplay) 🔍 → `Text`
    - [PartBox](#partbox) 🔍 🔎 → `Boolean`
    - [partBoxSkipped](#partboxskipped) 🔍 → `Boolean`
    - [PartsFromOtherWorksOrders->$Text](#partsfromotherworksorders->$text) 🔍 → `Text`
    - [RouteCardColor](#routecardcolor) 🔍 → `Integer`
    - [StatusText](#statustext) 🔍 → `Text`
    - [TestProduct](#testproduct) 🔍 → `cs.ProductEntity`
    - [toolIsRunning](#toolisrunning) 🔍 → `Boolean`
    - [totalBoxQuantity](#totalboxquantity) 🔍 → `Integer`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

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

#### removeFromPallet {#removefrompallet}


```4d
Function removeFromPallet -> $Success : Boolean
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
Function getMigrationRules($RemoteEntity : cs.BoxLabelsEntity) -> $Collection : Collection
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

### Properties (Getters/Setters/Query/OrderBy)

#### AdviceNote {#advicenote}
 `[🔍 get only]`

```4d
Function get AdviceNote -> Integer
```

**Returns:** `Integer`

---

#### BoxNumberColor {#boxnumbercolor}
 `[🔍 get only]`

```4d
Function get BoxNumberColor -> Integer
```

**Returns:** `Integer`

---

#### BoxNumberDisplay {#boxnumberdisplay}
 `[🔍 get only]`

```4d
Function get BoxNumberDisplay -> Text
```

**Returns:** `Text`

---

#### BoxQuantityDisplay {#boxquantitydisplay}
 `[🔍 get only]`

```4d
Function get BoxQuantityDisplay -> Text
```

**Returns:** `Text`

---

#### CurrentStatus {#currentstatus}
 `[🔍 get only]`

```4d
Function get CurrentStatus -> Object
```

**Returns:** `Object`

---

#### Despatched {#despatched}
 `[🔍 get, 🔎 query]`

```4d
Function get Despatched -> Boolean
Function query Despatched($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Boolean`

---

#### GrossWeightKg {#grossweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get GrossWeightKg -> Real
```

**Returns:** `Real`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

#### linkedBoxesQuantity {#linkedboxesquantity}
 `[🔍 get only, 🖥️ local]`

```4d
Function get linkedBoxesQuantity -> Integer
```

**Returns:** `Integer`

---

#### NetWeightKg {#netweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get NetWeightKg -> Real
```

**Returns:** `Real`

---

#### PackedByDisplay {#packedbydisplay}
 `[🔍 get only]`

```4d
Function get PackedByDisplay -> Text
```

**Returns:** `Text`

---

#### PartBox {#partbox}
 `[🔍 get, 🔎 query]`

```4d
Function get PartBox -> Boolean
Function query PartBox($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Boolean`

---

#### partBoxSkipped {#partboxskipped}
 `[🔍 get only, 🖥️ local]`

```4d
Function get partBoxSkipped -> Boolean
```

**Returns:** `Boolean`

---

#### PartsFromOtherWorksOrders->$Text {#partsfromotherworksorders->$text}
 `[🔍 get only]`

```4d
Function get PartsFromOtherWorksOrders->$Text -> Text
```

**Returns:** `Text`

---

#### RouteCardColor {#routecardcolor}
 `[🔍 get only]`

```4d
Function get RouteCardColor -> Integer
```

**Returns:** `Integer`

---

#### StatusText {#statustext}
 `[🔍 get only]`

```4d
Function get StatusText -> Text
```

**Returns:** `Text`

---

#### TestProduct {#testproduct}
 `[🔍 get only]`

```4d
Function get TestProduct -> cs.ProductEntity
```

**Returns:** `cs.ProductEntity`

---

#### toolIsRunning {#toolisrunning}
 `[🔍 get only, 🖥️ local]`

```4d
Function get toolIsRunning -> Boolean
```

**Returns:** `Boolean`

---

#### totalBoxQuantity {#totalboxquantity}
 `[🔍 get only, 🖥️ local]`

```4d
Function get totalBoxQuantity -> Integer
```

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [BoxLabels](../Tables/BoxLabels.md) - Source table for this ORDA class

### � Related Classes

- [BoxLabels](BoxLabels.md) - ORDA DataClass class for BoxLabels table

---

*Generated from BoxLabelsEntity.4dm*

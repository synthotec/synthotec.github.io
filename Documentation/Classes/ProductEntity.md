---
layout : default
title : ProductEntity
parent : Classes
---
# ProductEntity

📊 **Overview:** 12 Functions | 3 Getters | 1 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T16:58:15.051Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (12):**

- [query OurPartName](#query ourpartname) (1 param) 🖥️
- [getRobotHeadList](#getrobotheadlist) (1 param) → `Text` 🖥️
- [getMainTool](#getmaintool) → `cs.ToolsEntity` 🖥️
- [getPreviousPickRequestQuantity](#getpreviouspickrequestquantity) (2 params) → `Integer` 🖥️
- [getFinishedStock](#getfinishedstock) → `Integer` 🖥️
- [getQuarantinedStock](#getquarantinedstock) → `Integer` 🖥️
- [getWIP](#getwip) → `Integer` 🖥️
- [getPlannedProduction](#getplannedproduction) (1 param) → `Integer` 🖥️
- [getPickRequestedQuantity](#getpickrequestedquantity) → `Integer` 🖥️
- [getAvailableStock](#getavailablestock) (2 params) → `Integer` 🖥️
- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

**🔍 Getters (3):**

- [Emoji](#emoji) → `Text`
- [MainToolRegrind](#maintoolregrind) → `Boolean`
- [HasMigrationID](#hasmigrationid) → `Boolean`

**✏️ Setters (1):**

- [MainToolRegrind](#maintoolregrind) (1 param)

### 🔗 Related Items

- [Tables](#️-tables) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### query OurPartName {#query ourpartname}
 `[🖥️ local]`

```4d
Function query OurPartName($QueryEventObject : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

#### getRobotHeadList {#getrobotheadlist}
 `[🖥️ local]`

```4d
Function getRobotHeadList($Machine : Integer) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Machine` | `Integer` | - | - |

**Returns:** `Text`

---

#### getMainTool {#getmaintool}
 `[🖥️ local]`

```4d
Function getMainTool -> cs.ToolsEntity
```

**Returns:** `cs.ToolsEntity`

---

#### getPreviousPickRequestQuantity {#getpreviouspickrequestquantity}
 `[🖥️ local]`

```4d
Function getPreviousPickRequestQuantity($PickRequestEntity : cs.PickRequestEntity; $OrderPickRequestEntity : cs.OrderPickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |
| `$OrderPickRequestEntity` | `cs.OrderPickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### getFinishedStock {#getfinishedstock}
 `[🖥️ local]`

```4d
Function getFinishedStock -> Integer
```

**Returns:** `Integer`

---

#### getQuarantinedStock {#getquarantinedstock}
 `[🖥️ local]`

```4d
Function getQuarantinedStock -> Integer
```

**Returns:** `Integer`

---

#### getWIP {#getwip}
 `[🖥️ local]`

```4d
Function getWIP -> Integer
```

**Returns:** `Integer`

---

#### getPlannedProduction {#getplannedproduction}
 `[🖥️ local]`

```4d
Function getPlannedProduction($DespatchDate : Date) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DespatchDate` | `Date` | - | - |

**Returns:** `Integer`

---

#### getPickRequestedQuantity {#getpickrequestedquantity}
 `[🖥️ local]`

```4d
Function getPickRequestedQuantity -> Integer
```

**Returns:** `Integer`

---

#### getAvailableStock {#getavailablestock}
 `[🖥️ local]`

```4d
Function getAvailableStock($PickRequestEntity : cs.PickRequestEntity; $OrderPickRequestEntity : cs.OrderPickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |
| `$OrderPickRequestEntity` | `cs.OrderPickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ProductEntity) -> $Collection : Collection
```

/////////////////////////////////////////////////////////////////////////////////////

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ProductEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductEntity` | - | - |

---

### 🔍 Getters

#### Emoji {#emoji}
 `[🖥️ local, 🔍 getter]`

```4d
Function Emoji -> Text
```

**Returns:** `Text`

---

#### MainToolRegrind {#maintoolregrind}
 `[🖥️ local, 🔍 getter]`

```4d
Function MainToolRegrind -> Boolean
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

### ✏️ Setters

#### MainToolRegrind {#maintoolregrind}
 `[🖥️ local, ✏️ setter]`

```4d
Function MainToolRegrind($MainToolRegrind : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MainToolRegrind` | `Boolean` | - | - |

---

## 🔗 Related Items

### 🗂️ Tables

- [Product](../Tables/Product.md) - Source table

---

*Generated from ProductEntity.4dm*

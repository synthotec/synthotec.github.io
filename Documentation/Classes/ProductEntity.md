---
layout : default
title : ProductEntity
parent : Classes
---
# ProductEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductEntity.4dm)

📊 **Overview:** 11 Functions | 3 Getters | 1 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:53:01.154Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
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
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Emoji](#emoji) 🔍 → `Text`
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
    - [MainToolRegrind](#maintoolregrind) 🔍 ✏️ → `Boolean`
    - [OurPartName](#ourpartname) 🔎
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

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

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Emoji {#emoji}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Emoji -> Text
```

**Returns:** `Text`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

#### MainToolRegrind {#maintoolregrind}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get MainToolRegrind -> Boolean
Function set MainToolRegrind($MainToolRegrind : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$MainToolRegrind` | `Boolean` | - |

**Returns:** `Boolean`

---

#### OurPartName {#ourpartname}
 `[🔎 query only, 🖥️ local]`

```4d
Function query OurPartName($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Product](../Tables/Product.md) - Source table for this ORDA class

### � Related Classes

- [Product](Product.md) - ORDA DataClass class for Product table

---

*Generated from ProductEntity.4dm*

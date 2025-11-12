# ProductEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [Emoji() [getter]](#emoji)
- [query OurPartName()](#query ourpartname)
- [getRobotHeadList()](#getrobotheadlist)
- [getMainTool()](#getmaintool)
- [MainToolRegrind() [getter]](#maintoolregrind)
- [MainToolRegrind() [setter]](#maintoolregrind)
- [getPreviousPickRequestQuantity()](#getpreviouspickrequestquantity)
- [getFinishedStock()](#getfinishedstock)
- [getQuarantinedStock()](#getquarantinedstock)
- [getWIP()](#getwip)
- [getPlannedProduction()](#getplannedproduction)
- [getPickRequestedQuantity()](#getpickrequestedquantity)
- [getAvailableStock()](#getavailablestock)
- [getMigrationRules()](#getmigrationrules)
- [syncMigrationSelections()](#syncmigrationselections)
- [HasMigrationID() [getter]](#hasmigrationid)

---

## Functions

### Emoji {#emoji}
 `[local]` `[getter]`

```4d
Function Emoji -> Text
```

**Returns:** `Text`

---

### query OurPartName {#query ourpartname}
 `[local]`

```4d
Function query OurPartName($QueryEventObject : Object)
```

---

### getRobotHeadList {#getrobotheadlist}
 `[local]`

```4d
Function getRobotHeadList($Machine : Integer) -> Text
```

**Returns:** `Text`

---

### getMainTool {#getmaintool}
 `[local]`

```4d
Function getMainTool -> cs.ToolsEntity
```

**Returns:** `cs.ToolsEntity`

---

### MainToolRegrind {#maintoolregrind}
 `[local]` `[getter]`

```4d
Function MainToolRegrind -> Boolean
```

**Returns:** `Boolean`

---

### MainToolRegrind {#maintoolregrind}
 `[local]` `[setter]`

```4d
Function MainToolRegrind($MainToolRegrind : Boolean)
```

---

### getPreviousPickRequestQuantity {#getpreviouspickrequestquantity}
 `[local]`

```4d
Function getPreviousPickRequestQuantity($PickRequestEntity : cs.PickRequestEntity; $OrderPickRequestEntity : cs.OrderPickRequestEntity) -> Integer
```

**Returns:** `Integer`

---

### getFinishedStock {#getfinishedstock}
 `[local]`

```4d
Function getFinishedStock -> Integer
```

**Returns:** `Integer`

---

### getQuarantinedStock {#getquarantinedstock}
 `[local]`

```4d
Function getQuarantinedStock -> Integer
```

**Returns:** `Integer`

---

### getWIP {#getwip}
 `[local]`

```4d
Function getWIP -> Integer
```

**Returns:** `Integer`

---

### getPlannedProduction {#getplannedproduction}
 `[local]`

```4d
Function getPlannedProduction($DespatchDate : Date) -> Integer
```

**Returns:** `Integer`

---

### getPickRequestedQuantity {#getpickrequestedquantity}
 `[local]`

```4d
Function getPickRequestedQuantity -> Integer
```

**Returns:** `Integer`

---

### getAvailableStock {#getavailablestock}
 `[local]`

```4d
Function getAvailableStock($PickRequestEntity : cs.PickRequestEntity; $OrderPickRequestEntity : cs.OrderPickRequestEntity) -> Integer
```

**Returns:** `Integer`

---

### getMigrationRules {#getmigrationrules}
 `[local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ProductEntity) -> Collection
```

/////////////////////////////////////////////////////////////////////////////////////

**Returns:** `Collection`

---

### syncMigrationSelections {#syncmigrationselections}
 `[local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ProductEntity)
```

---

### HasMigrationID {#hasmigrationid}
 `[local]` `[getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from ProductEntity.4dm*
*Last updated: 2025-11-12T17:17:32.184Z*

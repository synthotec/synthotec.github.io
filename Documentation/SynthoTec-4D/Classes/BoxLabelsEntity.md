---
layout : default
title : BoxLabelsEntity
parent : Classes
---
# BoxLabelsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/BoxLabelsEntity.4dm)

📊 **Overview:** 8 Functions | 19 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:11.072Z*

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
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
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

Returns collection of possible box label states: In Stock, Not Made, Removed From Stock

**Returns:** `Collection`

---

#### ModifyStatus {#modifystatus}
 `[🖥️ local]`

```4d
Function ModifyStatus
```

Allows user to modify box status (In Stock/Not Made/Removed) with validation and permission checks

---

#### AddComment {#addcomment}
 `[🖥️ local]`

```4d
Function AddComment($Comment : Text; $StaffEntity : cs.StaffEntity)
```

Adds a timestamped comment to the box label's comment history with staff member attribution

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

Removes this box from pallet assignment; locks box, clears PalletEntity link, and saves

**Returns:** `Boolean`

---

#### getNextBoxPacked {#getnextboxpacked}
 `[🖥️ local]`

```4d
Function getNextBoxPacked -> cs.BoxLabelsEntity
```

Returns next box with same tool that was packed after this one; used for box sequence tracking

**Returns:** `cs.BoxLabelsEntity`

---

#### generateQR {#generateqr}
 `[🖥️ local]`

```4d
Function generateQR -> Picture
```

Generates QR code picture from box label data (ID, product, quantity, works order); used for barcode labels

**Returns:** `Picture`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.BoxLabelsEntity) -> $Collection : Collection
```

Returns collection of EntityMigrationRule objects defining how to merge this box label with remote during sync

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

Synchronizes entity selection references after migration merge; updates foreign key references to maintain data integrity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.BoxLabelsEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### AdviceNote {#advicenote}
 `[🔍 get only]`

```4d
Function get AdviceNote -> Integer
```

Returns advice note number from Certificate of Conformance or Pallet assignment; used for despatch tracking

**Returns:** `Integer`

---

#### BoxNumberColor {#boxnumbercolor}
 `[🔍 get only]`

```4d
Function get BoxNumberColor -> Integer
```

Returns color code for box number display based on status (NotMade, RemoveFromStock, LinkedBoxes, or PartBox)

**Returns:** `Integer`

---

#### BoxNumberDisplay {#boxnumberdisplay}
 `[🔍 get only]`

```4d
Function get BoxNumberDisplay -> Text
```

Returns formatted box number text; shows box number or part box code, with linked box code if applicable

**Returns:** `Text`

---

#### BoxQuantityDisplay {#boxquantitydisplay}
 `[🔍 get only]`

```4d
Function get BoxQuantityDisplay -> Text
```

Returns formatted box quantity text; shows total quantity or "parts + extras" if linked box included

**Returns:** `Text`

---

#### CurrentStatus {#currentstatus}
 `[🔍 get only]`

```4d
Function get CurrentStatus -> Object
```

Returns current status with text, background color, and foreground color based on box state

**Returns:** `Object`

---

#### Despatched {#despatched}
 `[🔍 get, 🔎 query]`

```4d
Function get Despatched -> Boolean
Function query Despatched($QueryEventObject : Object)
```

Returns true if box has been despatched (has CoC or is on despatched pallet)

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

Calculates gross weight (net weight + 1kg for packaging: 800g box + 200g bags)

**Returns:** `Real`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

Returns true if box has valid migration ID (non-null and non-zero); indicates entity was involved in sync operation

**Returns:** `Boolean`

---

#### linkedBoxesQuantity {#linkedboxesquantity}
 `[🔍 get only, 🖥️ local]`

```4d
Function get linkedBoxesQuantity -> Integer
```

Returns total quantity from all linked/chained boxes; follows linked box chain to leaf

**Returns:** `Integer`

---

#### NetWeightKg {#netweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get NetWeightKg -> Real
```

Calculates the net weight in kilograms based on part weight and total quantity

**Returns:** `Real`

---

#### PackedByDisplay {#packedbydisplay}
 `[🔍 get only]`

```4d
Function get PackedByDisplay -> Text
```

Returns formatted text with packing staff name and datetime for box label display

**Returns:** `Text`

---

#### PartBox {#partbox}
 `[🔍 get, 🔎 query]`

```4d
Function get PartBox -> Boolean
Function query PartBox($QueryEventObject : Object)
```

Returns true if this is a part box (PartBoxCode is not empty); used to identify extra/remainder boxes

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

Returns true if next packed box exists; indicates more boxes of this tool were packed

**Returns:** `Boolean`

---

#### PartsFromOtherWorksOrders->$Text {#partsfromotherworksorders->$text}
 `[🔍 get only]`

```4d
Function get PartsFromOtherWorksOrders->$Text -> Text
```

Returns formatted text listing quantities of parts from other works orders in linked box chain (e.g., '12345: 50')

**Returns:** `Text`

---

#### RouteCardColor {#routecardcolor}
 `[🔍 get only]`

```4d
Function get RouteCardColor -> Integer
```

Returns rotating color code for route card number (7 colors) for visual grouping in listbox

**Returns:** `Integer`

---

#### StatusText {#statustext}
 `[🔍 get only]`

```4d
Function get StatusText -> Text
```

Returns formatted status text with staff name and timestamp when status was last updated; empty if no update recorded

**Returns:** `Text`

---

#### TestProduct {#testproduct}
 `[🔍 get only]`

```4d
Function get TestProduct -> cs.ProductEntity
```

Returns the product entity associated with this box label; exposed for testing purposes

**Returns:** `cs.ProductEntity`

---

#### toolIsRunning {#toolisrunning}
 `[🔍 get only, 🖥️ local]`

```4d
Function get toolIsRunning -> Boolean
```

Returns true if works order for this tool's product is still in packing phase

**Returns:** `Boolean`

---

#### totalBoxQuantity {#totalboxquantity}
 `[🔍 get only, 🖥️ local]`

```4d
Function get totalBoxQuantity -> Integer
```

Returns total quantity including this box and all linked boxes; used for pallet/shipment totals

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [BoxLabels](../Tables/BoxLabels.md) - ORDA Entity class for BoxLabels table

### � Related Classes

- [BoxLabels](BoxLabels.md) - ORDA DataClass class for BoxLabels table

### � Forms

- [%2Atest](../Forms/%2Atest.md) - Data source for %2Atest form
- [%2Atest1](../Forms/%2Atest1.md) - Data source for %2Atest1 form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [Warehouse](../Forms/Warehouse.md) - Data source for Warehouse form

---

*Generated from BoxLabelsEntity.4dm*

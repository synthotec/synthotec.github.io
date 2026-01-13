---
layout : default
title : LocationEntity
parent : Classes
---
# LocationEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/LocationEntity.4dm)

📊 **Overview:** 6 Functions | 6 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:12.069Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [CheckRelated](#checkrelated) (1 param) → `Boolean` 🖥️
    - [printQRSheet](#printqrsheet) (2 params) 🖥️
    - [printLabel](#printlabel) (1 param) 🖥️
    - [generateQR](#generateqr) → `Picture` 🖥️
    - [getStockListboxCollection](#getstocklistboxcollection) → `$StockListboxCollection : Collection` 🖥️
    - [removeLocation](#removelocation) → `Boolean` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [DisplayName](#displayname) 🔍 → `Text`
    - [HasStock](#hasstock) 🔍 → `Boolean`
    - [Level](#level) 🔍 → `Integer`
    - [ListBoxDisplayName](#listboxdisplayname) 🔍 → `Text`
    - [ListboxMetaExpression](#listboxmetaexpression) 🔍 → `Object`
    - [SortOrder](#sortorder) 🔍 → `Text`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### CheckRelated {#checkrelated}
 `[🖥️ local]`

```4d
Function CheckRelated($LocationID : Text) -> Boolean
```

Returns true if specified LocationID exists anywhere in this location's parent hierarchy

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LocationID` | `Text` | - | - |

**Returns:** `Boolean`

---

#### printQRSheet {#printqrsheet}
 `[🖥️ local]`

```4d
Function printQRSheet($PageSize : Text; $ShowPrintSettings : Boolean)
```

Prints a QR code sheet for this location using specified page size

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PageSize` | `Text` | - | - |
| `$ShowPrintSettings` | `Boolean` | - | - |

---

#### printLabel {#printlabel}
 `[🖥️ local]`

```4d
Function printLabel($ShowPrintSettings : Boolean)
```

Prints a location barcode label with QR code

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ShowPrintSettings` | `Boolean` | - | - |

---

#### generateQR {#generateqr}
 `[🖥️ local]`

```4d
Function generateQR -> Picture
```

Generates QR code picture containing location barcode data as JSON

**Returns:** `Picture`

---

#### getStockListboxCollection {#getstocklistboxcollection}
 `[🖥️ local]`

```4d
Function getStockListboxCollection -> $StockListboxCollection : Collection
```

Returns collection of stock listbox objects for all pallets and material stock at this location

**Returns:** `Collection`

---

#### removeLocation {#removelocation}
 `[🖥️ local]`

```4d
Function removeLocation -> Boolean
```

Deletes this location after validation (no sub-locations, no stock, user confirmation), returns success status

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### DisplayName {#displayname}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DisplayName -> $DisplayName : Text
```

Returns full location path with » separators (e.g., "Warehouse » Aisle 1 » Shelf A")

**Returns:** `Text`

---

#### HasStock {#hasstock}
 `[🔍 get only]`

```4d
Function get HasStock -> Boolean
```

Returns true if location has any pallets or material stock assigned to it

**Returns:** `Boolean`

---

#### Level {#level}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Level -> $Level : Integer
```

Returns hierarchy depth level (0=root, 1=first level, etc.)

**Returns:** `Integer`

---

#### ListBoxDisplayName {#listboxdisplayname}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ListBoxDisplayName -> $ListBoxDisplayName : Text
```

Returns location name indented with tabs based on hierarchy level for listbox display

**Returns:** `Text`

---

#### ListboxMetaExpression {#listboxmetaexpression}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ListboxMetaExpression -> $ListboxMetaExpression : Object
```

Returns styling object for listbox row (font weight, background color based on hierarchy level)

**Returns:** `Object`

---

#### SortOrder {#sortorder}
 `[🔍 get only, 🖥️ local]`

```4d
Function get SortOrder -> $SortOrder : Text
```

Returns tab-delimited hierarchy path for sorting locations in tree structure

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Location](../Tables/Location.md) - ORDA Entity class for Location table

### � Related Classes

- [Location](Location.md) - ORDA DataClass class for Location table

### � Forms

- [LocationManager](../Forms/LocationManager.md) - Data source for LocationManager form

---

*Generated from LocationEntity.4dm*

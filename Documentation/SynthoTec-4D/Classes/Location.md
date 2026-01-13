---
layout : default
title : Location
parent : Classes
---
# Location [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Location.4dm)

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:12.047Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getUsingScanner](#getusingscanner) (1 param) → `cs.LocationEntity`
    - [newLocation](#newlocation) (1 param) → `$LocationEntity : cs.LocationEntity` 🖥️
    - [restClearStockLocation](#restclearstocklocation) (1 param) → `Object`
    - [restSetStockLocation](#restsetstocklocation) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getUsingScanner {#getusingscanner}


```4d
Function getUsingScanner($ScannerObject : Object) -> cs.LocationEntity
```

Returns LocationEntity from scanner object if it contains a valid location barcode, otherwise Null

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ScannerObject` | `Object` | - | - |

**Returns:** `cs.LocationEntity`

---

#### newLocation {#newlocation}
 `[🖥️ local]`

```4d
Function newLocation($ParentLocationEntity : cs.LocationEntity) -> $LocationEntity : cs.LocationEntity
```

Creates a new location with user-entered name, optionally under a parent location

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ParentLocationEntity` | `cs.LocationEntity` | - | - |

**Returns:** `cs.LocationEntity`

---

#### restClearStockLocation {#restclearstocklocation}


```4d
Function restClearStockLocation($RestPostDataObject : Object) -> Object
```

REST endpoint to clear location assignment from a pallet or material stock record

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restSetStockLocation {#restsetstocklocation}


```4d
Function restSetStockLocation($RestPostDataObject : Object) -> Object
```

REST endpoint to assign a location to a pallet or material stock record using scanner or manual selection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Location](../Tables/Location.md) - ORDA DataClass class for Location table

### � Related Classes

- [LocationEntity](LocationEntity.md) - ORDA Entity class for Location table

### � Forms

- [LocationManager](../Forms/LocationManager.md) - Data source for LocationManager form

---

*Generated from Location.4dm*

---
layout : default
title : Location
parent : Classes
---
# Location

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T12:58:34.010Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (4):**

- [getUsingScanner](#getusingscanner) (1 param) → `cs.LocationEntity`
- [newLocation](#newlocation) (1 param) → `cs.LocationEntity` 🖥️
- [restClearStockLocation](#restclearstocklocation) (1 param) → `Object`
- [restSetStockLocation](#restsetstocklocation) (1 param) → `Object`

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getUsingScanner {#getusingscanner}


```4d
Function getUsingScanner($ScannerObject : Object) -> cs.LocationEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ScannerObject` | `Object` | - | - |

**Returns:** `cs.LocationEntity`

---

#### newLocation {#newlocation}
 `[🖥️ local]`

```4d
Function newLocation($ParentLocationEntity : cs.LocationEntity) -> cs.LocationEntity
```

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

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## 🔗 Related Items

### 📦 Related Classes

- [Location](Location.md) - DataClass class
- [LocationEntity](LocationEntity.md) - Entity class

### 🗂️ Used By Tables

- [Location](../Tables/Location.md) - DataClass class

---

*Generated from Location.4dm*

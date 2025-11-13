---
layout : default
title : Location
parent : Classes
---
# Location

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T16:13:50.579Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (4):**

- [getUsingScanner](#getusingscanner) (1 param) → `cs.LocationEntity`
- [newLocation](#newlocation) (1 param) → `$LocationEntity : cs.LocationEntity` 🖥️
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
Function newLocation($ParentLocationEntity : cs.LocationEntity) -> $LocationEntity : cs.LocationEntity
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

---

*Generated from Location.4dm*

---
layout : default
title : LocationEntity
parent : Classes
---
# LocationEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/LocationEntity.4dm)

📊 **Overview:** 5 Functions | 5 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:07:28.212Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [CheckRelated](#checkrelated) (1 param) → `Boolean` 🖥️
  - [printQRSheet](#printqrsheet) (2 params) 🖥️
  - [printLabel](#printlabel) (1 param) 🖥️
  - [generateQR](#generateqr) → `Picture` 🖥️
  - [getStockListboxCollection](#getstocklistboxcollection) → `$StockListboxCollection : Collection` 🖥️
  - [SortOrder](#sortorder) → `Text`
  - [ListBoxDisplayName](#listboxdisplayname) → `Text`
  - [DisplayName](#displayname) → `Text`
  - [ListboxMetaExpression](#listboxmetaexpression) → `Object`
  - [Level](#level) → `Integer`
- [🔗 Related Items](#related-items)
---

## Functions {#functions}

### Regular Functions

#### CheckRelated {#checkrelated}
 `[🖥️ local]`

```4d
Function CheckRelated($LocationID : Text) -> Boolean
```

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

**Returns:** `Picture`

---

#### getStockListboxCollection {#getstocklistboxcollection}
 `[🖥️ local]`

```4d
Function getStockListboxCollection -> $StockListboxCollection : Collection
```

**Returns:** `Collection`

---

### Getters

#### SortOrder {#sortorder}
 `[🖥️ local, 🔍 getter]`

```4d
Function SortOrder -> $SortOrder : Text
```

**Returns:** `Text`

---

#### ListBoxDisplayName {#listboxdisplayname}
 `[🖥️ local, 🔍 getter]`

```4d
Function ListBoxDisplayName -> $ListBoxDisplayName : Text
```

**Returns:** `Text`

---

#### DisplayName {#displayname}
 `[🖥️ local, 🔍 getter]`

```4d
Function DisplayName -> $DisplayName : Text
```

**Returns:** `Text`

---

#### ListboxMetaExpression {#listboxmetaexpression}
 `[🖥️ local, 🔍 getter]`

```4d
Function ListboxMetaExpression -> $ListboxMetaExpression : Object
```

**Returns:** `Object`

---

#### Level {#level}
 `[🖥️ local, 🔍 getter]`

```4d
Function Level -> $Level : Integer
```

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Location](../Tables/Location.md) - Source table for this ORDA class

### � Related Classes

- [Location](Location.md) - ORDA DataClass class for Location table

---

*Generated from LocationEntity.4dm*

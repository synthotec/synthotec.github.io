---
layout : default
title : LocationEntity
parent : Classes
---
# LocationEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/LocationEntity.4dm)

📊 **Overview:** 5 Functions | 5 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:35:58.714Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [CheckRelated](#checkrelated) (1 param) → `Boolean` 🖥️
  - [printQRSheet](#printqrsheet) (2 params) 🖥️
  - [printLabel](#printlabel) (1 param) 🖥️
  - [generateQR](#generateqr) → `Picture` 🖥️
  - [getStockListboxCollection](#getstocklistboxcollection) → `$StockListboxCollection : Collection` 🖥️
  - [DisplayName](#displayname) 🔍 → `Text`
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

### Properties (Getters/Setters/Query/OrderBy)

#### DisplayName {#displayname}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DisplayName -> $DisplayName : Text
```

**Returns:** `Text`

---

#### Level {#level}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Level -> $Level : Integer
```

**Returns:** `Integer`

---

#### ListBoxDisplayName {#listboxdisplayname}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ListBoxDisplayName -> $ListBoxDisplayName : Text
```

**Returns:** `Text`

---

#### ListboxMetaExpression {#listboxmetaexpression}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ListboxMetaExpression -> $ListboxMetaExpression : Object
```

**Returns:** `Object`

---

#### SortOrder {#sortorder}
 `[🔍 get only, 🖥️ local]`

```4d
Function get SortOrder -> $SortOrder : Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Location](../Tables/Location.md) - Source table for this ORDA class

### � Related Classes

- [Location](Location.md) - ORDA DataClass class for Location table

---

*Generated from LocationEntity.4dm*

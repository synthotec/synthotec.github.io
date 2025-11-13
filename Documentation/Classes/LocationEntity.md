---
layout : default
title : LocationEntity
parent : Classes
---
# LocationEntity

📊 **Overview:** 5 Functions | 5 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T02:24:48.241Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (5):**

- [CheckRelated](#checkrelated) (1 param) → `Boolean` 🖥️
- [printQRSheet](#printqrsheet) (2 params) 🖥️
- [printLabel](#printlabel) (1 param) 🖥️
- [generateQR](#generateqr) → `Picture` 🖥️
- [getStockListboxCollection](#getstocklistboxcollection) → `Collection` 🖥️

**🔍 Getters (5):**

- [SortOrder](#sortorder) → `Text`
- [ListBoxDisplayName](#listboxdisplayname) → `Text`
- [DisplayName](#displayname) → `Text`
- [ListboxMetaExpression](#listboxmetaexpression) → `Object`
- [Level](#level) → `Integer`

---

## ⚙️ Functions

### ⚙️ Regular Functions

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
Function getStockListboxCollection -> Collection
```

**Returns:** `Collection`

---

### 🔍 Getters

#### SortOrder {#sortorder}
 `[🖥️ local, 🔍 getter]`

```4d
Function SortOrder -> Text
```

**Returns:** `Text`

---

#### ListBoxDisplayName {#listboxdisplayname}
 `[🖥️ local, 🔍 getter]`

```4d
Function ListBoxDisplayName -> Text
```

**Returns:** `Text`

---

#### DisplayName {#displayname}
 `[🖥️ local, 🔍 getter]`

```4d
Function DisplayName -> Text
```

**Returns:** `Text`

---

#### ListboxMetaExpression {#listboxmetaexpression}
 `[🖥️ local, 🔍 getter]`

```4d
Function ListboxMetaExpression -> Object
```

**Returns:** `Object`

---

#### Level {#level}
 `[🖥️ local, 🔍 getter]`

```4d
Function Level -> Integer
```

**Returns:** `Integer`

---

---

*Generated from LocationEntity.4dm*

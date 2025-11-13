---
layout : default
title : Translation
parent : Classes
---
# Translation

📊 **Overview:** 4 Functions | 2 Getters

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T16:46:52.960Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (4):**

- [pushProcess](#pushprocess) (1 param) 🖥️
- [popProcess](#popprocess) 🖥️
- [translate](#translate) (2 params) → `Text` 🖥️
- [translateFormObjects](#translateformobjects) (1 param) 🖥️

**🔍 Getters (2):**

- [CurrentProcess](#currentprocess) → `Text`
- [_TranslationProcessCollection](#_translationprocesscollection) → `Collection`

### 🔗 Related Items

- [Tables](#️-tables) (1)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### pushProcess {#pushprocess}
 `[🖥️ local]`

```4d
Function pushProcess($Process : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Process` | `Text` | - | - |

---

#### popProcess {#popprocess}
 `[🖥️ local]`

```4d
Function popProcess
```

---

#### translate {#translate}
 `[🖥️ local]`

```4d
Function translate($Text : Text; $TranslationProcess : Text) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Text` | `Text` | - | - |
| `$TranslationProcess` | `Text` | - | - |

**Returns:** `Text`

---

#### translateFormObjects {#translateformobjects}
 `[🖥️ local]`

```4d
Function translateFormObjects($TranslationProcess : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TranslationProcess` | `Text` | - | - |

---

### 🔍 Getters

#### CurrentProcess {#currentprocess}
 `[🖥️ local, 🔍 getter]`

```4d
Function CurrentProcess -> Text
```

**Returns:** `Text`

---

#### _TranslationProcessCollection {#_translationprocesscollection}
 `[🖥️ local, 🔍 getter]`

```4d
Function _TranslationProcessCollection -> Collection
```

**Returns:** `Collection`

---

## 🔗 Related Items

### 🗂️ Tables

- [Translation](../Tables/Translation.md) - Source table

---

*Generated from Translation.4dm*

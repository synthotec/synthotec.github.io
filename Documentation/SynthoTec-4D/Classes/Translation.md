---
layout : default
title : Translation
parent : Classes
---
# Translation [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Translation.4dm)

📊 **Overview:** 4 Functions | 2 Getters

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:53:01.583Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [pushProcess](#pushprocess) (1 param) 🖥️
    - [popProcess](#popprocess) 🖥️
    - [translate](#translate) (2 params) → `Text` 🖥️
    - [translateFormObjects](#translateformobjects) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [_TranslationProcessCollection](#_translationprocesscollection) 🔍 → `Collection`
    - [CurrentProcess](#currentprocess) 🔍 → `Text`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

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

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### _TranslationProcessCollection {#_translationprocesscollection}
 `[🔍 get only, 🖥️ local]`

```4d
Function get _TranslationProcessCollection -> Collection
```

**Returns:** `Collection`

---

#### CurrentProcess {#currentprocess}
 `[🔍 get only, 🖥️ local]`

```4d
Function get CurrentProcess -> Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Translation](../Tables/Translation.md) - Source table for this ORDA class

---

*Generated from Translation.4dm*

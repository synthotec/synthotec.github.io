---
layout : default
title : Translation
parent : Classes
---
# Translation [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Translation.4dm)

📊 **Overview:** 4 Functions | 2 Getters

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:13.699Z*

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

Pushes a new translation process onto the process stack

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

Pops the current translation process from the process stack

---

#### translate {#translate}
 `[🖥️ local]`

```4d
Function translate($Text : Text; $TranslationProcess : Text) -> Text
```

Returns translated text if available and user has permission, otherwise returns original text

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

Translates all form objects in the current form for the specified process (legacy method)

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

Returns or initializes the translation process collection with current process name

**Returns:** `Collection`

---

#### CurrentProcess {#currentprocess}
 `[🔍 get only, 🖥️ local]`

```4d
Function get CurrentProcess -> Text
```

Returns the name of the current translation process from the process collection

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Translation](../Tables/Translation.md) - ORDA DataClass class for Translation table

### � Forms

- [CalibrationProcedures](../Forms/CalibrationProcedures.md) - Data source for CalibrationProcedures form
- [TranslationManager](../Forms/TranslationManager.md) - Data source for TranslationManager form

---

*Generated from Translation.4dm*

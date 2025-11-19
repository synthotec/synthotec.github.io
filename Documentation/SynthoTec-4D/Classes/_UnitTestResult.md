---
layout : default
title : _UnitTestResult
parent : Classes
---
# _UnitTestResult [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/_UnitTestResult.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 3 Getters

🕐 *Last updated: 2025-11-19T15:47:10.304Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [StatusEmoji](#statusemoji) 🔍 → `Text`
    - [TestFormulaParametersText->$TestFormulaParametersText](#testformulaparameterstext->$testformulaparameterstext) 🔍 → `Text`
    - [TestFormulaText](#testformulatext) 🔍 → `Text`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `UnitTest` | `cs.UnitTest` | - | - |
| `Success; ErrorOccurred` | `Boolean` | - | - |
| `StackTrace` | `Collection` | - | - |
| `TestFormula` | `4D.Function` | - | - |
| `TestFormulaParameters` | `Collection` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

## Functions {#functions}

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### StatusEmoji {#statusemoji}
 `[🔍 get only]`

```4d
Function get StatusEmoji -> Text
```

**Returns:** `Text`

---

#### TestFormulaParametersText->$TestFormulaParametersText {#testformulaparameterstext->$testformulaparameterstext}
 `[🔍 get only]`

```4d
Function get TestFormulaParametersText->$TestFormulaParametersText -> Text
```

**Returns:** `Text`

---

#### TestFormulaText {#testformulatext}
 `[🔍 get only]`

```4d
Function get TestFormulaText -> Text
```

**Returns:** `Text`

---

---

*Generated from _UnitTestResult.4dm*

---
layout : default
title : _UnitTestResult
parent : Classes
---
# _UnitTestResult [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/_UnitTestResult.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 3 Getters

🕐 *Last updated: 2025-11-13T23:49:47.756Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#-properties)
- [🏗️ Constructor](#-constructor)
- [⚙️ Functions](#️-functions)
  - [TestFormulaText](#testformulatext) → `Text`
  - [TestFormulaParametersText->$TestFormulaParametersText](#testformulaparameterstext->$testformulaparameterstext) → `Text`
  - [StatusEmoji](#statusemoji) → `Text`
---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `UnitTest` | `cs.UnitTest` | - | - |
| `Success; ErrorOccurred` | `Boolean` | - | - |
| `StackTrace` | `Collection` | - | - |
| `TestFormula` | `4D.Function` | - | - |
| `TestFormulaParameters` | `Collection` | - | - |

## 🏗️ Constructor

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

## ⚙️ Functions

#### TestFormulaText {#testformulatext}
 `[🔍 getter]`

```4d
Function TestFormulaText -> Text
```

**Returns:** `Text`

---

#### TestFormulaParametersText->$TestFormulaParametersText {#testformulaparameterstext->$testformulaparameterstext}
 `[🔍 getter]`

```4d
Function TestFormulaParametersText->$TestFormulaParametersText -> Text
```

**Returns:** `Text`

---

#### StatusEmoji {#statusemoji}
 `[🔍 getter]`

```4d
Function StatusEmoji -> Text
```

**Returns:** `Text`

---

---

*Generated from _UnitTestResult.4dm*

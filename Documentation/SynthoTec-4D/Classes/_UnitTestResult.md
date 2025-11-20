---
layout : default
title : _UnitTestResult
parent : Classes
---
# _UnitTestResult [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/_UnitTestResult.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 3 Getters

## 📝 Description

Returns the source code of the test formula as text

🕐 *Last updated: 2025-11-20T14:23:51.107Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
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
| `UnitTest` | `cs.UnitTest` | - | Reference to the parent unit test instance |
| `Success` | `Boolean` | - | Indicates if the test passed successfully |
| `ErrorOccurred` | `Boolean` | - | Indicates if an error occurred during test execution |
| `StackTrace` | `Collection` | - | Collection of stack trace information if an error occurred |
| `TestFormula` | `4D.Function` | - | The formula that was executed for this test |
| `TestFormulaParameters` | `Collection` | - | Parameters passed to the test formula |

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

Returns an emoji indicating test status: ❗ for error, ✅ for success, ⚠️ for failure

**Returns:** `Text`

---

#### TestFormulaParametersText->$TestFormulaParametersText {#testformulaparameterstext->$testformulaparameterstext}
 `[🔍 get only]`

```4d
Function get TestFormulaParametersText->$TestFormulaParametersText -> Text
```

Returns a formatted string representation of the test formula parameters as "[param1; param2; ...]"

**Returns:** `Text`

---

#### TestFormulaText {#testformulatext}
 `[🔍 get only]`

```4d
Function get TestFormulaText -> Text
```

Returns the source code of the test formula as text

**Returns:** `Text`

---

---

*Generated from _UnitTestResult.4dm*

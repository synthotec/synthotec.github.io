---
layout : default
title : UnitTest
parent : Classes
---
# UnitTest [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/UnitTest.4dm)

📊 **Overview:** 3 Properties | 1 Constructor | 2 Functions | 1 Getters

🕐 *Last updated: 2025-11-14T00:07:29.088Z*

---

## 📑 Table of Contents

- [📋 Properties (3)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - [evaluate](#evaluate) (2 params) → `$UnitTestResult : cs._UnitTestResult`
  - [displayResultsAlert](#displayresultsalert)
  - [Success](#success) → `Boolean`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Description; Process` | `Text` | - | - |
| `UnitTestResults` | `Collection` | - | - |
| `FailedTestCount` | `Integer` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Description : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Description` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### evaluate {#evaluate}


```4d
Function evaluate($TestFormula : 4D.Function; $TestFormulaParameters : Collection) -> $UnitTestResult : cs._UnitTestResult
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TestFormula` | `4D.Function` | - | - |
| `$TestFormulaParameters` | `Collection` | - | - |

**Returns:** `cs._UnitTestResult`

---

#### displayResultsAlert {#displayresultsalert}


```4d
Function displayResultsAlert
```

---

### Getters

#### Success {#success}
 `[🔍 getter]`

```4d
Function Success -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from UnitTest.4dm*

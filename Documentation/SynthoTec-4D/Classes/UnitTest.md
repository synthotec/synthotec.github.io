---
layout : default
title : UnitTest
parent : Classes
---
# UnitTest [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/UnitTest.4dm)

📊 **Overview:** 4 Properties | 1 Constructor | 2 Functions | 1 Getters

## 📝 Description

Creates a new unit test suite with the specified description

🕐 *Last updated: 2025-12-10T11:45:24.547Z*

---

## 📑 Table of Contents

- [📋 Properties (4)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [evaluate](#evaluate) (2 params) → `$UnitTestResult : cs._UnitTestResult`
    - [displayResultsAlert](#displayresultsalert)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Success](#success) 🔍 → `Boolean`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Description` | `Text` | - | Description of the unit test suite |
| `Process` | `Text` | - | Name of the process running the test |
| `UnitTestResults` | `Collection` | - | Collection of individual test results |
| `FailedTestCount` | `Integer` | - | Count of tests that failed |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Description : Text)
```

Creates a new unit test suite with the specified description

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

Executes a test formula with parameters and records the result

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

Displays an alert with test results summary and details for each test

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Success {#success}
 `[🔍 get only]`

```4d
Function get Success -> Boolean
```

Returns true if all tests passed, false if any failed, Null if no tests run

**Returns:** `Boolean`

---

---

*Generated from UnitTest.4dm*

---
layout : default
title : UnitTest
parent : Classes
---
# UnitTest

📊 **Overview:** 3 Properties | 1 Constructor | 2 Functions | 1 Getters

🕐 *Last updated: 2025-11-13T13:39:36.731Z*

---

## 📑 Table of Contents

### 📋 Properties (3)

- [Description; Process](#description; process) : `Text`
- [UnitTestResults](#unittestresults) : `Collection`
- [FailedTestCount](#failedtestcount) : `Integer`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (2):**

- [evaluate](#evaluate) (2 params) → `cs._UnitTestResult`
- [displayResultsAlert](#displayresultsalert)

**🔍 Getters (1):**

- [Success](#success) → `Boolean`

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Description; Process` | `Text` | - | - |
| `UnitTestResults` | `Collection` | - | - |
| `FailedTestCount` | `Integer` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

#### evaluate {#evaluate}


```4d
Function evaluate($TestFormula : 4D.Function; $TestFormulaParameters : Collection) -> cs._UnitTestResult
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

### 🔍 Getters

#### Success {#success}
 `[🔍 getter]`

```4d
Function Success -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from UnitTest.4dm*

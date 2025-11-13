---
layout : default
title : UnitTest
parent : Classes
---
# UnitTest

## Table of Contents

### Properties

- [Description; Process](#description; process)
- [UnitTestResults](#unittestresults)
- [FailedTestCount](#failedtestcount)

### Functions

- [constructor() [constructor]](#constructor)
- [evaluate()](#evaluate)
- [Success() [getter]](#success)
- [displayResultsAlert()](#displayresultsalert)

---

## Properties

### Description; Process {#description; process}

**Type:** `Text`

---

### UnitTestResults {#unittestresults}

**Type:** `Collection`

---

### FailedTestCount {#failedtestcount}

**Type:** `Integer`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($Description : Text)
```

---

### evaluate {#evaluate}


```4d
Function evaluate($TestFormula : 4D.Function; $TestFormulaParameters : Collection) -> cs._UnitTestResult
```

**Returns:** `cs._UnitTestResult`

---

### Success {#success}
 `[getter]`

```4d
Function Success -> Boolean
```

**Returns:** `Boolean`

---

### displayResultsAlert {#displayresultsalert}


```4d
Function displayResultsAlert
```

---

---

*Generated from UnitTest.4dm*
*Last updated: 2025-11-13T00:30:43.134Z*

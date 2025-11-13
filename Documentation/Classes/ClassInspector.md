---
layout : default
title : ClassInspector
parent : Classes
---
# ClassInspector

📊 **Overview:** 10 Properties | 1 Constructor | 13 Functions

## 📝 Description

🗨️ ClassInspector - Analyzes 4D class files and extracts comprehensive metadata
Usage: var $Inspector : cs.ClassInspector := cs.ClassInspector.new($File)

🕐 *Last updated: 2025-11-13T00:47:52.095Z*

---

## 📑 Table of Contents

### 📋 Properties (10)

- [ClassName](#classname) : `Text`
- [SuperClass](#superclass) : `Text`
- [ClassAutoComment](#classautocomment) : `Text`
- [ClassManualComment](#classmanualcomment) : `Text`
- [Properties](#properties) : `Collection`
- [Functions](#functions) : `Collection`
- [Source](#source) : `Text`
- [OutputFolder](#outputfolder) : `4D.Folder`
- [ExistingJSON](#existingjson) : `Object`
- [Changes](#changes) : `Collection`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Functions (13):**

- [_parse](#_parse)
- [_extractInlineComment](#_extractinlinecomment) (1 param) → `Text`
- [_removeInlineComment](#_removeinlinecomment) (1 param) → `Text`
- [_extractParameterComments](#_extractparametercomments) (2 params) → `Object`
- [_loadExistingJSON](#_loadexistingjson)
- [_mergeExistingPropertyComment](#_mergeexistingpropertycomment) (1 param)
- [_mergeExistingClassComment](#_mergeexistingclasscomment)
- [_mergeExistingFunctionComment](#_mergeexistingfunctioncomment) (1 param)
- [_mergeExistingParameterComment](#_mergeexistingparametercomment) (2 params)
- [_recordChange](#_recordchange) (1 param)
- [toObject](#toobject) → `Object`
- [toJSON](#tojson) → `Text`
- [saveToFile](#savetofile) → `4D.File`

---

## 📋 Properties

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `ClassName` | `Text` | - | ClassInspector - Analyzes 4D class files and ex... |
| `SuperClass` | `Text` | - |  |
| `ClassAutoComment` | `Text` | - | Comment extracted from top of class file |
| `ClassManualComment` | `Text` | - | User-entered class documentation |
| `Properties` | `Collection` | - | Collection of property objects |
| `Functions` | `Collection` | - | Collection of function objects |
| `Source` | `Text` | - |  |
| `OutputFolder` | `4D.Folder` | - | Folder for JSON output |
| `ExistingJSON` | `Object` | - | Previously saved JSON for comment merging |
| `Changes` | `Collection` | - | List of changes detected |

### Detailed Information

#### ClassName {#classname}

**Type:** `Text`

ClassInspector - Analyzes 4D class files and extracts comprehensive metadata
Usage: var $Inspector : cs.ClassInspector := cs.ClassInspector.new($File)

---

#### SuperClass {#superclass}

**Type:** `Text`

---

#### ClassAutoComment {#classautocomment}

**Type:** `Text`

Comment extracted from top of class file

---

#### ClassManualComment {#classmanualcomment}

**Type:** `Text`

User-entered class documentation

---

#### Properties {#properties}

**Type:** `Collection`

Collection of property objects

---

#### Functions {#functions}

**Type:** `Collection`

Collection of function objects

---

#### Source {#source}

**Type:** `Text`

---

#### OutputFolder {#outputfolder}

**Type:** `4D.Folder`

Folder for JSON output

---

#### ExistingJSON {#existingjson}

**Type:** `Object`

Previously saved JSON for comment merging

---

#### Changes {#changes}

**Type:** `Collection`

List of changes detected

---

## ⚙️ Functions

### 🏗️ Constructors

### ⚙️ Regular Functions

---

*Generated from ClassInspector.4dm*

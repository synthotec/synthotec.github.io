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

🕐 *Last updated: 2025-11-13T13:39:35.455Z*

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

**⚙️ Regular Functions (13):**

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

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `ClassName` | `Text` | - | ClassInspector - Analyzes 4D class files and extracts comprehensive metadata
Usage: var $Inspector : cs.ClassInspector := cs.ClassInspector.new($File) |
| `SuperClass` | `Text` | - | - |
| `ClassAutoComment` | `Text` | - | Comment extracted from top of class file |
| `ClassManualComment` | `Text` | - | User-entered class documentation |
| `Properties` | `Collection` | - | Collection of property objects |
| `Functions` | `Collection` | - | Collection of function objects |
| `Source` | `Text` | - | - |
| `OutputFolder` | `4D.Folder` | - | Folder for JSON output |
| `ExistingJSON` | `Object` | - | Previously saved JSON for comment merging |
| `Changes` | `Collection` | - | List of changes detected |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($File : 4D.File)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$File` | `4D.File` | - | - |

---

### ⚙️ Regular Functions

#### _parse {#_parse}


```4d
Function _parse
```

Main parsing function - processes the entire class file

---

#### _extractInlineComment {#_extractinlinecomment}


```4d
Function _extractInlineComment($Line : Text) -> Text
```

Extract inline comment from a line (everything after //)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

**Returns:** `Text`

---

#### _removeInlineComment {#_removeinlinecomment}


```4d
Function _removeInlineComment($Line : Text) -> Text
```

Remove inline comment from a line

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

**Returns:** `Text`

---

#### _extractParameterComments {#_extractparametercomments}


```4d
Function _extractParameterComments($Lines : Collection; $FuncStartIdx : Integer) -> Object
```

Extract parameter comments from lines following function declaration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Lines` | `Collection` | - | - |
| `$FuncStartIdx` | `Integer` | - | - |

**Returns:** `Object`

---

#### _loadExistingJSON {#_loadexistingjson}


```4d
Function _loadExistingJSON
```

Load existing JSON file to preserve comments

---

#### _mergeExistingPropertyComment {#_mergeexistingpropertycomment}


```4d
Function _mergeExistingPropertyComment($Prop : Object)
```

Merge existing property comment if available

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Prop` | `Object` | - | - |

---

#### _mergeExistingClassComment {#_mergeexistingclasscomment}


```4d
Function _mergeExistingClassComment
```

Merge existing class comment if available

---

#### _mergeExistingFunctionComment {#_mergeexistingfunctioncomment}


```4d
Function _mergeExistingFunctionComment($Func : Object)
```

Merge existing function comment if available

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Func` | `Object` | - | - |

---

#### _mergeExistingParameterComment {#_mergeexistingparametercomment}


```4d
Function _mergeExistingParameterComment($Param : Object; $FunctionName : Text)
```

Merge existing parameter comment if available

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Param` | `Object` | - | - |
| `$FunctionName` | `Text` | - | - |

---

#### _recordChange {#_recordchange}


```4d
Function _recordChange($ChangeDescription : Text)
```

Record a change

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ChangeDescription` | `Text` | - | - |

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Export to JSON object

**Returns:** `Object`

---

#### toJSON {#tojson}


```4d
Function toJSON -> Text
```

Export to JSON string

**Returns:** `Text`

---

#### saveToFile {#savetofile}


```4d
Function saveToFile -> 4D.File
```

Save JSON to file in Documentation\json\Classes folder

**Returns:** `4D.File`

---

---

*Generated from ClassInspector.4dm*

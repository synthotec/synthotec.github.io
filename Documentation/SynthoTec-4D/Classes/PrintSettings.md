---
layout : default
title : PrintSettings
parent : Classes
---
# PrintSettings [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrintSettings.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 5 Functions

🕐 *Last updated: 2025-11-19T18:10:06.974Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#properties)
- [🏗️ Constructor](#constructor) (4 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [display](#display) → `$Accepted : Boolean`
    - [load](#load) (2 params) → `cs.PrintSettings`
    - [save](#save) (1 param) → `cs.PrintSettings`
    - [apply](#apply) → `$Success : Boolean`
    - [restore](#restore) → `$Success : Boolean`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | - |
| `Paper` | `Text` | - | - |
| `Orientation` | `Integer` | - | - |
| `Copies` | `Integer` | - | - |
| `CurrentPrinter` | `Text` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($UseSystemDefaultPrinter : Boolean; $Paper : Text; $Copies : Integer; $Orientation : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$UseSystemDefaultPrinter` | `Boolean` | - | - |
| `$Paper` | `Text` | - | - |
| `$Copies` | `Integer` | - | - |
| `$Orientation` | `Integer` | - | - |

---

## Functions {#functions}

### Regular Functions

#### display {#display}


```4d
Function display -> $Accepted : Boolean
```

**Returns:** `Boolean`

---

#### load {#load}


```4d
Function load($SettingName : Text; $LoadCopyCount : Boolean) -> cs.PrintSettings
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SettingName` | `Text` | - | - |
| `$LoadCopyCount` | `Boolean` | - | - |

**Returns:** `cs.PrintSettings`

---

#### save {#save}


```4d
Function save($SettingName : Text) -> cs.PrintSettings
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SettingName` | `Text` | - | - |

**Returns:** `cs.PrintSettings`

---

#### apply {#apply}


```4d
Function apply -> $Success : Boolean
```

**Returns:** `Boolean`

---

#### restore {#restore}


```4d
Function restore -> $Success : Boolean
```

**Returns:** `Boolean`

---

---

*Generated from PrintSettings.4dm*

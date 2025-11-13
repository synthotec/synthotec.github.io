---
layout : default
title : PrintSettings
parent : Classes
---
# PrintSettings

📊 **Overview:** 5 Properties | 1 Constructor | 5 Functions

🕐 *Last updated: 2025-11-13T02:47:33.065Z*

---

## 📑 Table of Contents

### 📋 Properties (5)

- [Name](#name) : `Text`
- [Paper](#paper) : `Text`
- [Orientation](#orientation) : `Integer`
- [Copies](#copies) : `Integer`
- [CurrentPrinter](#currentprinter) : `Text`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (4 params)

**⚙️ Functions (5):**

- [display](#display) → `Boolean`
- [load](#load) (2 params) → `cs.PrintSettings`
- [save](#save) (1 param) → `cs.PrintSettings`
- [apply](#apply) → `Boolean`
- [restore](#restore) → `Boolean`

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | - |
| `Paper` | `Text` | - | - |
| `Orientation` | `Integer` | - | - |
| `Copies` | `Integer` | - | - |
| `CurrentPrinter` | `Text` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

#### display {#display}


```4d
Function display -> Boolean
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
Function apply -> Boolean
```

**Returns:** `Boolean`

---

#### restore {#restore}


```4d
Function restore -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from PrintSettings.4dm*

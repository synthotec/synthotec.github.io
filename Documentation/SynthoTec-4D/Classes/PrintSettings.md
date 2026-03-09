---
layout : default
title : PrintSettings
parent : Classes
---
# PrintSettings [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrintSettings.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 5 Functions

## 📝 Description

Stores print configuration (printer name, paper size, orientation, and copy count) for applying to a 4D printing session. Can optionally default to the current system printer and saves/restores the active printer around the print job.

🕐 *Last updated: 2026-03-09T14:45:30.630Z*

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
| `Name` | `Text` | - | Name of the printer to use |
| `Paper` | `Text` | - | Paper size/format name |
| `Orientation` | `Integer` | - | Page orientation: 1=Portrait, 2=Landscape |
| `Copies` | `Integer` | - | Number of copies to print |
| `CurrentPrinter` | `Text` | - | Name of printer that was active before applying settings |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($UseSystemDefaultPrinter : Boolean; $Paper : Text; $Copies : Integer; $Orientation : Integer)
```

Creates print settings object with optional default values, optionally using system default printer

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

Displays a dialog for user to select printer settings, returns true if accepted

**Returns:** `Boolean`

---

#### load {#load}


```4d
Function load($SettingName : Text; $LoadCopyCount : Boolean) -> cs.PrintSettings
```

Loads print settings from user-specific settings storage, optionally including copy count

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

Saves current print settings to user-specific settings storage

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

Applies these print settings to 4D print system, saves current printer for restoration

**Returns:** `Boolean`

---

#### restore {#restore}


```4d
Function restore -> $Success : Boolean
```

Restores the printer that was active before apply() was called

**Returns:** `Boolean`

---

---

*Generated from PrintSettings.4dm*

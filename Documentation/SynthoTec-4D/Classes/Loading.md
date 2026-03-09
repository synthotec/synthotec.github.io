---
layout : default
title : Loading
parent : Classes
---
# Loading [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Loading.4dm)

📊 **Overview:** 1 Properties | 1 Constructor | 2 Functions

## 📝 Description

Manages a loading indicator window using a shared object for inter-process communication. Tracks progress percentage, elapsed time, and update count, allowing a background process to display and update a progress dialog.

🕐 *Last updated: 2026-03-09T14:45:29.928Z*

---

## 📑 Table of Contents

- [📋 Properties (1)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [stop](#stop)
    - [update](#update) (2 params)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `SharedObject` | `Object` | - | Shared object for inter-process communication with loading window |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($LoadingText : Text; $LoadingProgress : Real)
```

Initialize loading dialog with text and optional progress percentage

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LoadingText` | `Text` | - | - |
| `$LoadingProgress` | `Real` | - | - |

---

## Functions {#functions}

### Regular Functions

#### stop {#stop}


```4d
Function stop
```

Close the loading dialog window

---

#### update {#update}


```4d
Function update($LoadingText : Text; $LoadingProgress : Real)
```

Update loading dialog text and optional progress percentage

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LoadingText` | `Text` | - | - |
| `$LoadingProgress` | `Real` | - | - |

---

---

*Generated from Loading.4dm*

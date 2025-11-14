---
layout : default
title : SelectionLock
parent : Classes
---
# SelectionLock [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/SelectionLock.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions

🕐 *Last updated: 2025-11-14T00:18:21.265Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - [displayAlert](#displayalert) (2 params)
  - [unlock](#unlock)
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `LockedEntityCollection; FailedLockObjectCollection` | `Collection` | - | - |
| `Success` | `Boolean` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($EntitySelectionCollection : Collection; $UnlockOnError : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntitySelectionCollection` | `Collection` | - | - |
| `$UnlockOnError` | `Boolean` | - | - |

---

## Functions {#functions}

### Regular Functions

#### displayAlert {#displayalert}


```4d
Function displayAlert($Unlock : Boolean; $DisplayForAllEntities : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Unlock` | `Boolean` | - | - |
| `$DisplayForAllEntities` | `Boolean` | - | - |

---

#### unlock {#unlock}


```4d
Function unlock
```

---

---

*Generated from SelectionLock.4dm*

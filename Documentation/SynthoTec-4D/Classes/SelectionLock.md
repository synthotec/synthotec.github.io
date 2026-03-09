---
layout : default
title : SelectionLock
parent : Classes
---
# SelectionLock [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/SelectionLock.4dm)

📊 **Overview:** 3 Properties | 1 Constructor | 2 Functions

## 📝 Description

Attempts to acquire 4D entity locks on multiple entity selections simultaneously, tracking which entities locked successfully and which failed. Optionally unlocks all on failure to maintain consistency.

🕐 *Last updated: 2026-03-09T14:45:31.547Z*

---

## 📑 Table of Contents

- [📋 Properties (3)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [displayAlert](#displayalert) (2 params)
    - [unlock](#unlock)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `LockedEntityCollection` | `Collection` | - | Collection of successfully locked entities |
| `FailedLockObjectCollection` | `Collection` | - | Collection of lock failure objects with entity references |
| `Success` | `Boolean` | - | True if all entities locked successfully |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($EntitySelectionCollection : Collection; $UnlockOnError : Boolean)
```

Attempts to lock all entities in provided entity selections, optionally unlocking all on failure

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

Displays alert for each failed lock, optionally unlocking all locked entities first

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

Unlocks all successfully locked entities in the collection

---

---

*Generated from SelectionLock.4dm*

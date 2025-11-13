---
layout : default
title : SelectionLock
parent : Classes
---
# SelectionLock

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions

🕐 *Last updated: 2025-11-13T13:39:36.529Z*

---

## 📑 Table of Contents

### 📋 Properties (2)

- [LockedEntityCollection; FailedLockObjectCollection](#lockedentitycollection; failedlockobjectcollection) : `Collection`
- [Success](#success) : `Boolean`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Regular Functions (2):**

- [displayAlert](#displayalert) (2 params)
- [unlock](#unlock)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `LockedEntityCollection; FailedLockObjectCollection` | `Collection` | - | - |
| `Success` | `Boolean` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

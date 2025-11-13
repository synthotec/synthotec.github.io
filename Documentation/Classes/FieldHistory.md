---
layout : default
title : FieldHistory
parent : Classes
---
# FieldHistory

📊 **Overview:** 3 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T14:26:49.981Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (3):**

- [ClassicListboxClickedEvent](#classiclistboxclickedevent) 🖥️
- [display](#display) (4 params) 🖥️
- [triggerLog](#triggerlog) (2 params) 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### ClassicListboxClickedEvent {#classiclistboxclickedevent}
 `[🖥️ local]`

```4d
Function ClassicListboxClickedEvent
```

---

#### display {#display}
 `[🖥️ local]`

```4d
Function display($FieldPointer : Pointer; $PrimaryKey : Integer; $ForeignDataClass : 4D.DataClass; $ForeignFormula : 4D.Function)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FieldPointer` | `Pointer` | - | - |
| `$PrimaryKey` | `Integer` | - | - |
| `$ForeignDataClass` | `4D.DataClass` | - | - |
| `$ForeignFormula` | `4D.Function` | - | - |

---

#### triggerLog {#triggerlog}
 `[🖥️ local]`

```4d
Function triggerLog($FieldPointerCollection : Collection; $ChangedBy : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FieldPointerCollection` | `Collection` | - | - |
| `$ChangedBy` | `Text` | - | - |

---

---

*Generated from FieldHistory.4dm*

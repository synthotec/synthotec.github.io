---
layout : default
title : FieldHistory
parent : Classes
---
# FieldHistory [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/FieldHistory.4dm)

📊 **Overview:** 3 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-19T18:12:02.835Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [ClassicListboxClickedEvent](#classiclistboxclickedevent) 🖥️
    - [display](#display) (4 params) 🖥️
    - [triggerLog](#triggerlog) (2 params) 🖥️
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

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

## Related Items {#related-items}

### 🗂️ Tables

- [FieldHistory](../Tables/FieldHistory.md) - ORDA DataClass class for FieldHistory table

### � Forms

- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from FieldHistory.4dm*

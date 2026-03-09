---
layout : default
title : FieldHistory
parent : Classes
---
# FieldHistory [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/FieldHistory.4dm)

📊 **Overview:** 3 Functions

## 📝 Description

DataClass for field history (audit trail) records. Handles Alt+Click events on selection-based listboxes to display the change history for the clicked field using the current record's table and field context.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.687Z*

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

Handles Alt+Click on listbox to display field history for the clicked cell

---

#### display {#display}
 `[🖥️ local]`

```4d
Function display($FieldPointer : Pointer; $PrimaryKey : Integer; $ForeignDataClass : 4D.DataClass; $ForeignFormula : 4D.Function)
```

Displays field history in a popup window for the specified field and record

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

Logs field changes to FieldHistory table when triggered on save (creates history record for each changed field)

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

---
layout : default
title : Staff
parent : Classes
---
# Staff [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Staff.4dm)

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-19T21:53:04.240Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getUsingKeyfob](#getusingkeyfob) (2 params) → `$StaffEntity : cs.StaffEntity` 🖥️
    - [getCurrentUser](#getcurrentuser) → `cs.StaffEntity` 🖥️
    - [getNonArchived](#getnonarchived) → `cs.StaffSelection` 🖥️
    - [newUsingEntry](#newusingentry) → `cs.StaffEntity` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getUsingKeyfob {#getusingkeyfob}
 `[🖥️ local]`

```4d
Function getUsingKeyfob($ShowWarning : Boolean; $KeyFob : Text) -> $StaffEntity : cs.StaffEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ShowWarning` | `Boolean` | - | - |
| `$KeyFob` | `Text` | - | - |

**Returns:** `cs.StaffEntity`

---

#### getCurrentUser {#getcurrentuser}
 `[🖥️ local]`

```4d
Function getCurrentUser -> cs.StaffEntity
```

**Returns:** `cs.StaffEntity`

---

#### getNonArchived {#getnonarchived}
 `[🖥️ local]`

```4d
Function getNonArchived -> cs.StaffSelection
```

**Returns:** `cs.StaffSelection`

---

#### newUsingEntry {#newusingentry}
 `[🖥️ local]`

```4d
Function newUsingEntry -> cs.StaffEntity
```

**Returns:** `cs.StaffEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - ORDA DataClass class for Staff table

### � Related Classes

- [StaffEntity](StaffEntity.md) - ORDA Entity class for Staff table

### � Forms

- [AddWorkRequest](../Forms/AddWorkRequest.md) - Data source for AddWorkRequest form
- [ConfirmOrderDates](../Forms/ConfirmOrderDates.md) - Data source for ConfirmOrderDates form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [PermissionManager](../Forms/PermissionManager.md) - Data source for PermissionManager form
- [PurchaseOrders](../Forms/PurchaseOrders.md) - Data source for PurchaseOrders form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form
- [Staff](../Forms/Staff.md) - Data source for Staff form
- [StaffLogin](../Forms/StaffLogin.md) - Data source for StaffLogin form
- [StaffMessaging](../Forms/StaffMessaging.md) - Data source for StaffMessaging form
- [ToolMaintenanceLog](../Forms/ToolMaintenanceLog.md) - Data source for ToolMaintenanceLog form
- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from Staff.4dm*

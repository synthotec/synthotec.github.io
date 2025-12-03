---
layout : default
title : DownTime
parent : Forms
---
# DownTime [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/DownTime)

📊 **Overview:** 22 Objects | 5 Types | 2 Pages | 16 Events | 44 Object Methods

## 📝 Description

🗨️ Production downtime analysis and categorization form. Displays downtime events from the RealTime table and allows operators to assign reasons for stoppages. Features week-by-week navigation with daily filtering, machine-specific filtering, and category-based reason selection. Users right-click downtime records to assign reasons from a hierarchical menu (Category > Reason). Supports management of down reasons including adding new reasons, editing existing ones, and toggling archived reasons. The 'Update Last 8 Days' button recalculates recent downtime data. Critical for tracking production efficiency and identifying bottlenecks.

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/method.4dm) |
| **Object Methods** | 44 |
| **Generated** | 🕐 2025-12-03T16:38:20.328Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (22)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (8)

---

## 🎯 Form Events

This form handles **16** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ❌ |
| `onValidate` | ✅ | `onClick` | ✅ |
| `onDoubleClick` | ✅ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ✅ |
| `onBeginDragOver` | ✅ | `onDragOver` | ✅ |
| `onDrop` | ✅ | `onAfterKeystroke` | ✅ |
| `onMenuSelect` | ✅ | `onPluginArea` | ✅ |
| `onAfterEdit` | ✅ | `onTimer` | ✅ |
| `onBoundVariableChange` | ✅ | `onPageChange` | ✅ |
| `onBeforeDataEntry` | ❌ | `onLoadRecord` | ❌ |
| `onAfterSort` | ❌ | `onSelectionChange` | ❌ |
| `onDataChange` | ✅ | `onExpand` | ❌ |
| `onCollapse` | ❌ | `onBeforeKeystroke` | ❌ |
| `onOpenDetail` | ❌ | `onCloseDetail` | ❌ |
| `onResize` | ❌ | `onActivate` | ❌ |
| `onDeactivate` | ❌ | `onOpenExternalLink` | ❌ |
| `onWindowOpeningDenied` | ❌ | `onScroll` | ❌ |
| `onCloseBox` | ❌ | `onDeleteAction` | ❌ |
| `onRowResize` | ❌ | `onAlternativeClick` | ❌ |
| `onLongClick` | ❌ | `onMouseEnter` | ❌ |
| `onMouseLeave` | ❌ | `onMouseMove` | ❌ |

## 🧩 Form Objects

### Interactive Objects by Page

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| downtimeListBox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.RealTimeSelection | [downtimeListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/downtimeListBox.4dm) |
| reasonsListBox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.DownReasonsSelection | [reasonsListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/reasonsListBox.4dm) |
| categoryDropdown | - | 📥 dropdown | ✅ | ✅ | ❌ | Form:C1466.CategoryDropdownObject | [categoryDropdown.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/categoryDropdown.4dm) |
| editReasonButton | EDIT | 🔘 button | ✅ | ✅ | ❌ | - | [editReasonButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/editReasonButton.4dm) |
| addReasonButton | ADD NEW DOWNREASON | 🔘 button | ✅ | ✅ | ❌ | - | [addReasonButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/addReasonButton.4dm) |
| machineFilterListBox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.MachineCollection | [machineFilterListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/machineFilterListBox.4dm) |
| weekDropdown | - | 📥 dropdown | ✅ | ✅ | ❌ | Form:C1466.WeekDropdownObject | [weekDropdown.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/weekDropdown.4dm) |
| mondayButton | MON | 🔘 button | ✅ | ✅ | ❌ | - | [mondayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/mondayButton.4dm) |
| tuesdayButton | TUE | 🔘 button | ✅ | ✅ | ❌ | - | [tuesdayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/tuesdayButton.4dm) |
| wednesdayButton | WED | 🔘 button | ✅ | ✅ | ❌ | - | [wednesdayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/wednesdayButton.4dm) |
| thursdayButton | THUR | 🔘 button | ✅ | ✅ | ❌ | - | [thursdayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/thursdayButton.4dm) |
| fridayButton | FRI | 🔘 button | ✅ | ✅ | ❌ | - | [fridayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/fridayButton.4dm) |
| saturdayButton | SAT | 🔘 button | ✅ | ✅ | ❌ | - | [saturdayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/saturdayButton.4dm) |
| sundayButton | SUN | 🔘 button | ✅ | ✅ | ❌ | - | [sundayButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/sundayButton.4dm) |
| selectedDateDisplay | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.SelectedDate | - |
| updateWeekButton | UPDATE LAST 8 DAYS | 🔘 button | ✅ | ✅ | ❌ | - | [updateWeekButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/updateWeekButton.4dm) |
| showUnidentifiedButton | SHOW ALL UNIDENTIFIED FOR WEEK | 🔘 button | ✅ | ✅ | ❌ | - | [showUnidentifiedButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/showUnidentifiedButton.4dm) |
| previousWeekButton | PREV | 🔘 button | ✅ | ✅ | ❌ | - | [previousWeekButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/previousWeekButton.4dm) |
| nextWeekButton | NEXT | 🔘 button | ✅ | ✅ | ❌ | - | [nextWeekButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/nextWeekButton.4dm) |
| refreshButton | REFRESH | 🔘 button | ✅ | ✅ | ❌ | - | [refreshButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/refreshButton.4dm) |
| updateDateButton | UPDATE SELECTED DATE | 🔘 button | ✅ | ✅ | ❌ | - | [updateDateButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/updateDateButton.4dm) |
| showArchivedCheckbox | Show Archived Down Reasons | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.ShowArchivedReasons | [showArchivedCheckbox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/showArchivedCheckbox.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - Data source for DownTime form
- [DownReasons](../Tables/DownReasons.md) - Data source for DownTime form
- [RealTimeMachines](../Tables/RealTimeMachines.md) - Data source for DownTime form
- [PlanningWheel](../Tables/PlanningWheel.md) - Data source for DownTime form
- [Works_Order](../Tables/Works_Order.md) - Data source for DownTime form
- [RTSUM](../Tables/RTSUM.md) - Data source for DownTime form
- [FieldHistory](../Tables/FieldHistory.md) - Data source for DownTime form
- [WorksOrder](../Tables/WorksOrder.md) - Data source for DownTime form

---

*Generated from form.4DForm*

---
layout : default
title : MaterialCalendar
parent : Forms
---
# MaterialCalendar [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/MaterialCalendar)

📊 **Overview:** 17 Objects | 7 Types | 2 Pages | 16 Events | 13 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/method.4dm) |
| **Object Methods** | 13 |
| **Generated** | 🕐 2025-11-14T16:53:02.455Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (17)

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
| Button | Refresh Data | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Button.4dm) |
| Button3 | Toggle Kgs / £s | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Button3.4dm) |
| Button2 | Generate Excel File | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Button2.4dm) |
| Button1 | Jump To Date | 🔘 button | ✅ | ❌ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Button1.4dm) |
| Check Box | Use Regrind (Refresh to see changes) | ☑️ checkbox | ✅ | ✅ | ❌ | bUseRegrind | - |
| MatCalList | - | 📋 listbox | ✅ | ✅ | ❌ | MatCalList | [MatCalList.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/MatCalList.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/List%20Box1.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | SelectedCellInfo+" Usage" | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | SelectedCellInfo+" Deliveries" | - |
| Check Box1 | Include Offsite Material | ☑️ checkbox | ✅ | ✅ | ❌ | MaterialCalendar_IncludeOffsite | [Check Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Check%20Box1.4dm) |
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | MaterialCalendar_Search | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/SearchPicker.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | Form:C1466.StockTakeDates | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Text | Use Stock Take From | 📄 text | ✅ | ✅ | ❌ | - | - |
| ChangeCalendarDaysButton | Button | 🔘 button | ✅ | ✅ | ❌ | - | [ChangeCalendarDaysButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/ChangeCalendarDaysButton.4dm) |
| ChangeOrderWindowButton | Button | 🔘 button | ✅ | ✅ | ❌ | - | [ChangeOrderWindowButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/ChangeOrderWindowButton.4dm) |
| Check Box2 | Show orders with no dates (on call off) as being delivered today | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.DeliverNoDatesToday | [Check Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCalendar/ObjectMethods/Check%20Box2.4dm) |

---

*Generated from form.4DForm*

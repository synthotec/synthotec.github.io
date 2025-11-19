---
layout : default
title : Scheduler
parent : Forms
---
# Scheduler [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/Scheduler)

📊 **Overview:** 20 Objects | 5 Types | 4 Pages | 4 Events | 21 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/method.4dm) |
| **Object Methods** | 21 |
| **Generated** | 🕐 2025-11-19T20:54:38.284Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (4)
- [🧩 Form Objects](#-form-objects) (20)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (8)

---

## 🎯 Form Events

This form handles **4** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ❌ |
| `onValidate` | ❌ | `onClick` | ❌ |
| `onDoubleClick` | ❌ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ❌ |
| `onBeginDragOver` | ❌ | `onDragOver` | ❌ |
| `onDrop` | ✅ | `onAfterKeystroke` | ❌ |
| `onMenuSelect` | ❌ | `onPluginArea` | ❌ |
| `onAfterEdit` | ❌ | `onTimer` | ✅ |
| `onBoundVariableChange` | ❌ | `onPageChange` | ✅ |
| `onBeforeDataEntry` | ❌ | `onLoadRecord` | ❌ |
| `onAfterSort` | ❌ | `onSelectionChange` | ❌ |
| `onDataChange` | ❌ | `onExpand` | ❌ |
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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Button1 | Shutdowns | 🔘 button | ✅ | ❌ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button1.4dm) |
| List Box6 | - | 📋 listbox | ✅ | ✅ | ❌ | Scheduler_Listbox3 | [List Box6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/List%20Box6.4dm) |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | MCList | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/List%20Box2.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | Scheduler_Listbox1 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/List%20Box1.4dm) |
| Button5 | Plan | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button5.4dm) |
| List Box5 | - | 📋 listbox | ✅ | ❌ | ❌ | ConflictListBox | - |
| Button6 | UPDATE MATERIAL | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button6.4dm) |
| Button7 | SCHEDULE VARIABLES | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button7.4dm) |
| List Box7 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ProductSelection | [List Box7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/List%20Box7.4dm) |
| Form.SearchText | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Search | [Form.SearchText.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Form.SearchText.4dm) |
| Form.SearchClear | ❌ | 🔘 button | ✅ | ❌ | ❌ | - | [Form.SearchClear.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Form.SearchClear.4dm) |
| Form.SearchButton | 🔎 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Form.SearchButton.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box4 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box | [List Box4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/List%20Box4.4dm) |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vInfo | [Variable3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Variable3.4dm) |
| Button | Refresh | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button.4dm) |
| Button2 | Update Screen | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button2.4dm) |
| Button3 | Clear | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button3.4dm) |
| Button4 | Insert Date | 🔘 button | ✅ | ✅ | ❌ | WriteLocked | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Button4.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | Schedule_TextToModify | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Scheduler/ObjectMethods/Popup%20Dropdown%20List.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - Data source for Scheduler form
- [MachineWheels](../Tables/MachineWheels.md) - Data source for Scheduler form
- [PlanningWheel](../Tables/PlanningWheel.md) - Data source for Scheduler form
- [Material](../Tables/Material.md) - Data source for Scheduler form
- [Product](../Tables/Product.md) - Data source for Scheduler form
- [Tools](../Tables/Tools.md) - Data source for Scheduler form
- [WheelCalendar](../Tables/WheelCalendar.md) - Data source for Scheduler form
- [lockEntity](../Tables/lockEntity.md) - Data source for Scheduler form

---

*Generated from form.4DForm*

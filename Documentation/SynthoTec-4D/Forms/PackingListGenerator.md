---
layout : default
title : PackingListGenerator
parent : Forms
---
# PackingListGenerator [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/PackingListGenerator)

📊 **Overview:** 12 Objects | 6 Types | 2 Pages | 16 Events | 8 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/method.4dm) |
| **Object Methods** | 8 |
| **Generated** | 🕐 2025-12-03T16:38:20.420Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (12)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (2)

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
| Scrollable Area | - | 📋 listbox | ✅ | ✅ | ❌ | - | [Scrollable Area.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/Scrollable%20Area.4dm) |
| Scrollable Area1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [Scrollable Area1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/Scrollable%20Area1.4dm) |
| Button | Generate | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/Button.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | PackingList_DateType | - |
| Button1 | Select All Customers | 🔘 button | ✅ | ✅ | ❌ | Button | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/Button1.4dm) |
| Button2 | Remove All Customers | 🔘 button | ✅ | ✅ | ❌ | Button | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/Button2.4dm) |
| PopupDate | - | 🔲 subform | ✅ | ✅ | ❌ | vStartDate | [PopupDate.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/PopupDate.4dm) |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vStartDate | - |
| PopupDate1 | - | 🔲 subform | ✅ | ✅ | ❌ | vEndDate | [PopupDate1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/PopupDate1.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vEndDate | - |
| Button3 | Close | 🔘 button | ✅ | ✅ | ❌ | Button | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackingListGenerator/ObjectMethods/Button3.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Customer](../Tables/Customer.md) - Data source for PackingListGenerator form
- [Customer_Order](../Tables/Customer_Order.md) - Data source for PackingListGenerator form

---

*Generated from form.4DForm*

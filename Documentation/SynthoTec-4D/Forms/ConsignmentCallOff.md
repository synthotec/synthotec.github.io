---
layout : default
title : ConsignmentCallOff
parent : Forms
---
# ConsignmentCallOff [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ConsignmentCallOff)

📊 **Overview:** 14 Objects | 6 Types | 2 Pages | 16 Events | 9 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/method.4dm) |
| **Object Methods** | 9 |
| **Generated** | 🕐 2025-11-14T16:53:02.361Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (14)

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
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | CallOffList | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/List%20Box.4dm) |
| Button | ADD ITEMS TO ADVICE NOTE FOR THIS DATE | 🔘 button | ✅ | ✅ | ❌ | ButtonNormal | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Button.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | vLocations | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| Button1 | EXIT | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Button1.4dm) |
| Button2 | CREATE ADVICE NOTE | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Button2.4dm) |
| Button3 | PRINT ADVICE NOTE | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Button3.4dm) |
| DateEntry | - | 🔲 subform | ✅ | ✅ | ❌ | vConMoveDate | [DateEntry.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/DateEntry.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | - |
| Button4 | ADD ITEMS TO ADVICE NOTE FOR THIS DATE - NSK | 🔘 button | ✅ | ✅ | ❌ | ButtonNSK | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Button4.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vWarning | - |
| Text | Step 1
Select Location

Step 2
Create Advice Note

Step 3
Choose a process date at the bottom left of this screen

Step 4
Select a product and type a qty to consume.

Step 5
Add items to advice note

(Do for each product)

Finally, Print Advice Note
 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button5 | Report Parser | 🔘 button | ✅ | ✅ | ❌ | Button5 | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConsignmentCallOff/ObjectMethods/Button5.4dm) |
| Field | - | 📝 input | ✅ | ✅ | ❌ | [Advice_Note:9]Advice_Note_No:1 | - |
| Text1 | Advice Note | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*

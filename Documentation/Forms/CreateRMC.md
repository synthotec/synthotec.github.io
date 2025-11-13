---
layout : default
title : CreateRMC
parent : Forms
---
# CreateRMC [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CreateRMC)

📊 **Overview:** 25 Objects | 7 Types | 2 Pages | 15 Events | 10 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 10 |
| **Generated** | 🕐 2025-11-13T16:35:16.554Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (25)

---

## 🎯 Form Events

This form handles **15** of **44** possible events:

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

#### Page 1

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text8 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | 📥 dropdown | ✅ | ✅ | ❌ | CreateRMC_Materials | - |
| CreateRMC_DateEntry | 🔲 subform | ✅ | ✅ | ❌ | Form:C1466.Date | [CreateRMC_DateEntry.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/CreateRMC_DateEntry.4dm) |
| Input | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Batch | - |
| Text4 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input2 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Quantity | [Input2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Input2.4dm) |
| Text6 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input3 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.FileName | - |
| Button | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Button.4dm) |
| Input5 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Containers | [Input5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Input5.4dm) |
| Text7 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input7 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ContainerQty | [Input7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Input7.4dm) |
| List Box | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/List%20Box.4dm) |
| Text | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button1 | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Button1.4dm) |
| Text5 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input1 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.PO | [Input1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Input1.4dm) |
| Text9 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input4 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ReceivedBy | - |
| Check Box | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.NotDelivered | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Check%20Box.4dm) |
| List Box1 | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.PurchaseInfoEntitySelection | - |
| Button2 | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CreateRMC/ObjectMethods/Button2.4dm) |

---

*Generated from form.4DForm*

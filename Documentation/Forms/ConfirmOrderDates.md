---
layout : default
title : ConfirmOrderDates
parent : Forms
---
# ConfirmOrderDates [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ConfirmOrderDates)

📊 **Overview:** 22 Objects | 4 Types | 2 Pages | 16 Events | 7 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 7 |
| **Generated** | 🕐 2025-11-13T16:07:49.847Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (22)

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

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable | 📝 input | ✅ | ✅ | ❌ | oReceived | - |
| Text1 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | 📝 input | ✅ | ✅ | ❌ | oRequested | - |
| Text2 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable2 | 📝 input | ✅ | ✅ | ❌ | oRequired | - |
| Text3 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable3 | 📝 input | ✅ | ✅ | ❌ | oReadyStatus | - |
| Text4 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable4 | 📝 input | ✅ | ✅ | ❌ | oDespatch | [Variable4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/Variable4.4dm) |
| PopupDate | 🔲 subform | ✅ | ✅ | ❌ | oDespatch | [PopupDate.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/PopupDate.4dm) |
| Variable5 | 📝 input | ✅ | ✅ | ❌ | oDays | [Variable5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/Variable5.4dm) |
| PopupDate3 | 🔲 subform | ✅ | ✅ | ❌ | oArrival | [PopupDate3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/PopupDate3.4dm) |
| Button | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/Button.4dm) |
| Variable6 | 📝 input | ✅ | ✅ | ❌ | oArrival | [Variable6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/Variable6.4dm) |
| Text5 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text6 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable7 | 📝 input | ✅ | ✅ | ❌ | String:C10(oRequested-oReceived)+" Days / "+String:C10(Round:C94((oRequested-oReceived)/7; 1))+" Weeks" | - |
| Variable8 | 📝 input | ✅ | ✅ | ❌ | String:C10(oRequired-oReceived)+" Days / "+String:C10(Round:C94((oRequired-oReceived)/7; 1))+" Weeks" | - |
| Variable9 | 📝 input | ✅ | ✅ | ❌ | String:C10(oDespatch-oReceived)+" Days / "+String:C10(Round:C94((oDespatch-oReceived)/7; 1))+" Weeks" | - |
| Variable10 | 📝 input | ✅ | ✅ | ❌ | String:C10(oArrival-oReceived)+" Days / "+String:C10(Round:C94((oArrival-oReceived)/7; 1))+" Weeks" | - |
| Variable11 | 📝 input | ✅ | ✅ | ❌ | oLeadTimeNotice | [Variable11.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ConfirmOrderDates/ObjectMethods/Variable11.4dm) |

---

*Generated from form.4DForm*

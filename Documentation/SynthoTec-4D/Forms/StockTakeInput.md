---
layout : default
title : StockTakeInput
parent : Forms
---
# StockTakeInput [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/StockTakeInput)

📊 **Overview:** 18 Objects | 5 Types | 2 Pages | 16 Events | 10 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/method.4dm) |
| **Object Methods** | 10 |
| **Generated** | 🕐 2025-11-14T16:53:02.597Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (18)

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
| Text | RMC | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | Container ID | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | Number of Bags | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable33 | - | 📝 input | ✅ | ✅ | ❌ | StockTakeInput_RMC | [Variable33.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Variable33.4dm) |
| Variable34 | - | 📝 input | ✅ | ✅ | ❌ | vRMCID | - |
| Variable35 | - | 📝 input | ✅ | ✅ | ❌ | vBags | [Variable35.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Variable35.4dm) |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vMaterialAmount | - |
| Button1 | Save | 🔘 button | ✅ | ✅ | ❌ | Button | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Button1.4dm) |
| Button3 | DELETE SELECTED LINE | 🔘 button | ✅ | ✅ | ❌ | DELETESELECTEDITEM | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Button3.4dm) |
| Button12 | Add Stock From Warehouse | 🔘 button | ✅ | ✅ | ❌ | Button | [Button12.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Button12.4dm) |
| Button | Add Realtime Used | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Button.4dm) |
| Check Box | STOCK IN TRANIT | ☑️ checkbox | ✅ | ❌ | ❌ | transit | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Check%20Box.4dm) |
| Variable53 | - | 📝 input | ✅ | ✅ | ❌ | vMaterialName | - |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | StockTakeInput_Listbox1 | - |
| Text3 | Kg | 📄 text | ✅ | ✅ | ❌ | - | - |
| Check Box1 | Add to previous stock take | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.AddToPreviousStockTake | [Check Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Check%20Box1.4dm) |
| Button2 | Add Scanned Results | 🔘 button | ✅ | ✅ | ❌ | Button | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Button2.4dm) |
| Button4 | 📅 Set Next STock Take Date | 🔘 button | ✅ | ✅ | ❌ | Button | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StockTakeInput/ObjectMethods/Button4.4dm) |

---

*Generated from form.4DForm*

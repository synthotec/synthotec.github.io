---
layout : default
title : OrderOverview
parent : Forms
---
# OrderOverview [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/OrderOverview)

📊 **Overview:** 28 Objects | 5 Types | 2 Pages | 16 Events | 8 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/method.4dm) |
| **Object Methods** | 8 |
| **Generated** | 🕐 2025-11-14T16:53:02.488Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (28)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (9)

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
| Variable | - | 📝 input | ✅ | ✅ | ❌ | pSearch | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/Variable.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | List Box | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/List%20Box.4dm) |
| MainBox1 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | [MainBox1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/MainBox1.4dm) |
| Text | STOCK AT SYNTHOTEC | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | STOCK OFFSITE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | QUARANTINED STOCK | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | WIP | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vSYN | - |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vOFF | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vQUAR | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | vWIP | - |
| Text4 |                                 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text5 | TOTAL | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | vTotal | - |
| Text6 | Parts Per Box | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text7 | Parts Per Hour | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text8 | USED SINCE LAST BILL | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | vBox | - |
| Variable7 | - | 📝 input | ✅ | ✅ | ❌ | vPPH | - |
| Variable8 | - | 📝 input | ✅ | ✅ | ❌ | vUSED | - |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box2 | - |
| Text11 | DAILY STOCK BALANCE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button | Display Stock Movements | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/Button.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/List%20Box1.4dm) |
| List Box3 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box3 | [List Box3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/List%20Box3.4dm) |
| List Box4 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box | [List Box4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/List%20Box4.4dm) |
| Text9 | Customer Drill Down | 📄 text | ✅ | ✅ | ❌ | - | - |
| Check Box | Prioritize Standard Orders | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.PrioritizeStandardOrders | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderOverview/ObjectMethods/Check%20Box.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - Data source for OrderOverview form
- [CustomerOrderLog](../Tables/CustomerOrderLog.md) - Data source for OrderOverview form
- [Finished_Stock](../Tables/Finished_Stock.md) - Data source for OrderOverview form
- [Product](../Tables/Product.md) - Data source for OrderOverview form
- [Permissions](../Tables/Permissions.md) - Data source for OrderOverview form
- [lockEntity](../Tables/lockEntity.md) - Data source for OrderOverview form
- [Stock_Location](../Tables/Stock_Location.md) - Data source for OrderOverview form
- [FieldHistory](../Tables/FieldHistory.md) - Data source for OrderOverview form
- [Product_Option](../Tables/Product_Option.md) - Data source for OrderOverview form

---

*Generated from form.4DForm*

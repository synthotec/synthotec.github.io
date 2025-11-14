---
layout : default
title : CustomerOrders
parent : Forms
---
# CustomerOrders [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CustomerOrders)

📊 **Overview:** 14 Objects | 4 Types | 2 Pages | 3 Events | 14 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/method.4dm) |
| **Object Methods** | 14 |
| **Generated** | 🕐 2025-11-14T00:18:22.177Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (3)
- [🧩 Form Objects](#-form-objects) (14)

---

## 🎯 Form Events

This form handles **3** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ❌ |
| `onValidate` | ❌ | `onClick` | ✅ |
| `onDoubleClick` | ❌ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ❌ |
| `onBeginDragOver` | ❌ | `onDragOver` | ❌ |
| `onDrop` | ❌ | `onAfterKeystroke` | ❌ |
| `onMenuSelect` | ❌ | `onPluginArea` | ❌ |
| `onAfterEdit` | ❌ | `onTimer` | ❌ |
| `onBoundVariableChange` | ❌ | `onPageChange` | ❌ |
| `onBeforeDataEntry` | ❌ | `onLoadRecord` | ❌ |
| `onAfterSort` | ❌ | `onSelectionChange` | ❌ |
| `onDataChange` | ❌ | `onExpand` | ❌ |
| `onCollapse` | ❌ | `onBeforeKeystroke` | ❌ |
| `onOpenDetail` | ❌ | `onCloseDetail` | ❌ |
| `onResize` | ❌ | `onActivate` | ❌ |
| `onDeactivate` | ❌ | `onOpenExternalLink` | ❌ |
| `onWindowOpeningDenied` | ❌ | `onScroll` | ❌ |
| `onCloseBox` | ✅ | `onDeleteAction` | ❌ |
| `onRowResize` | ❌ | `onAlternativeClick` | ❌ |
| `onLongClick` | ❌ | `onMouseEnter` | ❌ |
| `onMouseLeave` | ❌ | `onMouseMove` | ❌ |

## 🧩 Form Objects

### Interactive Objects by Page

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Variable11 | New | 🔘 button | ✅ | ✅ | ❌ | bNew | [Variable11.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Variable11.4dm) |
| Button1 | Sort | 🔘 button | ✅ | ✅ | ❌ | CUST_SortCustOrders_l_b | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button1.4dm) |
| Button2 | Finish | 🔘 button | ✅ | ❌ | ❌ | CUST_FinishCustOrders_l_b | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button2.4dm) |
| Button4 | Reports | 🔘 button | ✅ | ✅ | ❌ | CUST_Report_l_b | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button4.4dm) |
| Button6 | Completed | 🔘 button | ✅ | ✅ | ❌ | CUST_Completed_l_b | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button6.4dm) |
| Button7 | Search | 🔘 button | ✅ | ✅ | ❌ | CUSO_Search_l_b | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button7.4dm) |
| Button8 | Delete | 🔘 button | ✅ | ✅ | ❌ | CUSO_Delete_l_b | [Button8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button8.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/List%20Box.4dm) |
| Button3 | Refresh | 🔘 button | ✅ | ✅ | ❌ | Refresh | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Button3.4dm) |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | CustomerOrders_OrderFilter | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| Popup Drop down List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | aParts | [Popup Drop down List2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Popup%20Drop%20down%20List2.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/List%20Box1.4dm) |
| Radio Button | Standard Orders | 🔘 radio | ✅ | ✅ | ❌ | vStandard | [Radio Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Radio%20Button.4dm) |
| Radio Button1 | Consignment Requirements | 🔘 radio | ✅ | ✅ | ❌ | vConsignment | [Radio Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrders/ObjectMethods/Radio%20Button1.4dm) |

---

*Generated from form.4DForm*

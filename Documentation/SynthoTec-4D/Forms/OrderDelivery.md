---
layout : default
title : OrderDelivery
parent : Forms
---
# OrderDelivery [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/OrderDelivery)

📊 **Overview:** 40 Objects | 6 Types | 3 Pages | 17 Events | 14 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/method.4dm) |
| **Object Methods** | 14 |
| **Generated** | 🕐 2025-12-03T16:38:20.411Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (17)
- [🧩 Form Objects](#-form-objects) (40)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (8)

---

## 🎯 Form Events

This form handles **17** of **44** possible events:

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
| `onCloseBox` | ✅ | `onDeleteAction` | ❌ |
| `onRowResize` | ❌ | `onAlternativeClick` | ❌ |
| `onLongClick` | ❌ | `onMouseEnter` | ❌ |
| `onMouseLeave` | ❌ | `onMouseMove` | ❌ |

## 🧩 Form Objects

### Interactive Objects by Page

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | vCustomerCodes | [Popup Dropdown List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Popup%20Dropdown%20List1.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | DespatchLocations | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| List Box3 | - | 📋 listbox | ✅ | ✅ | ❌ | vS | [List Box3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/List%20Box3.4dm) |
| Button1 | 🏁 Finish Advice Note | 🔘 button | ✅ | ✅ | ❌ | bFinish | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Button1.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/List%20Box1.4dm) |
| Popup Dropdown List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | vTransport | [Popup Dropdown List2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Popup%20Dropdown%20List2.4dm) |
| Variable8 | - | 📝 input | ✅ | ✅ | ❌ | vArrival | - |
| PopupDate | - | 🔲 subform | ✅ | ✅ | ❌ | vArrival | [PopupDate.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/PopupDate.4dm) |
| List Box4 | - | 📋 listbox | ✅ | ✅ | ❌ | - | - |
| List Box5 | - | 📋 listbox | ✅ | ✅ | ❌ | - | - |
| Button | 🚚 Despatch Selected Parts | 🔘 button | ✅ | ✅ | ❌ | DeliverButton | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Button.4dm) |
| Text3 | Part Name | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | Order # | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text5 | Batch # | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | OrderDelivery_PartName | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | OrderDelivery_OrderNumber | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | vBatch | - |
| Text7 | Quantity Required | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text8 | Quantity Selected | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text9 | Quantity Remaining | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | vRequired | - |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | vMarkedToSend | - |
| Variable7 | - | 📝 input | ✅ | ✅ | ❌ | vRequired-vMarkedToSend | - |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | "Advice Note #" | - |
| Text6 | Despatch Summary | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text | Stock Without Pallet IDs | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | Stock With Pallet IDs | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | Despatch Location | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | OrderDelivery_AdviceNote | - |
| Text10 | Customer | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text11 | Estimated Arrival Date | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text12 | Transport | 📄 text | ✅ | ✅ | ❌ | - | - |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | - | - |
| Text14 | Advice Note Summary | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button2 | 📂 Open Existing Advice Note | 🔘 button | ✅ | ✅ | ❌ | bAdd | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Button2.4dm) |
| Button3 | 🖊️ Modify Order Quantity | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Button3.4dm) |
| Text15 | Confirmed Despatch | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List3 | - | 📥 dropdown | ✅ | ✅ | ❌ | OrderDelivery_DespatchDates | [Popup Dropdown List3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/OrderDelivery/ObjectMethods/Popup%20Dropdown%20List3.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text13 | SELECT AN ORDER TO DESPATCH PARTS | 📄 text | ✅ | ✅ | ❌ | - | - |

## 🔗 Related Items

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - Data source for OrderDelivery form
- [Customer](../Tables/Customer.md) - Data source for OrderDelivery form
- [CofC](../Tables/CofC.md) - Data source for OrderDelivery form
- [Finished_Stock](../Tables/Finished_Stock.md) - Data source for OrderDelivery form
- [Pallet](../Tables/Pallet.md) - Data source for OrderDelivery form
- [Advice_Note](../Tables/Advice_Note.md) - Data source for OrderDelivery form
- [Product](../Tables/Product.md) - Data source for OrderDelivery form
- [WorksOrder](../Tables/WorksOrder.md) - Data source for OrderDelivery form

---

*Generated from form.4DForm*

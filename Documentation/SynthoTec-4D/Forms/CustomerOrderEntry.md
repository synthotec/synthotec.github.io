---
layout : default
title : CustomerOrderEntry
parent : Forms
---
# CustomerOrderEntry [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CustomerOrderEntry)

📊 **Overview:** 35 Objects | 5 Types | 4 Pages | 16 Events | 22 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: fixed, Y: variable |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/method.4dm) |
| **Object Methods** | 22 |
| **Generated** | 🕐 2025-12-03T16:38:20.312Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (35)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (5)

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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| listbox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Customers | [listbox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/listbox.4dm) |
| listbox1 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Products | [listbox1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/listbox1.4dm) |
| Form.SaveButton | 💾 SAVE CUSTOMER ORDER | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SaveButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.SaveButton.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | Form:C1466.Tools.CollectionObject() | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Form.OrderNumber | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.OrderNumber | [Form.OrderNumber.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.OrderNumber.4dm) |
| Form.BatchNumber | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.BatchNumber | [Form.BatchNumber.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.BatchNumber.4dm) |
| Form.Quantity | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Quantity | [Form.Quantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.Quantity.4dm) |
| Input3 | - | 📝 input | ✅ | ✅ | ❌ | String:C10(Form:C1466.BoxQuantity; "#,###,###,##0")+" ("+String:C10(Round:C94(Form:C1466.Quantity/Form:C1466.BoxQuantity; 1))+" Boxes)" | - |
| Text1 | TOOL NUMBER | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | CUSTOMER ORDER NUMBER | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | BATCH NUMBER | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | QUANTITY ORDERED | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text5 | BOX QUANTITY | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input5 | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.SelectedProductOption.Currency+String:C10(Round:C94((Form:C1466.SelectedProductOption.Price/Form:C1466.SelectedProductOption.PriceQuantity)*Form:C1466.Quantity; 2); "###,###,##0.00") | - |
| Text7 | ORDER VALUE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text8 | RECEIVED DATE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text9 | REQUESTED DATE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text10 | DESPATCH DATE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.DateReceived | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.DateReceived | [Form.DateReceived.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateReceived.4dm) |
| Form.DateReceivedEntry | 📅 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateReceivedEntry.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateReceivedEntry.4dm) |
| Form.DateRequested | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.DateRequested | [Form.DateRequested.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateRequested.4dm) |
| Form.DateRequestedEntry | 📅 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateRequestedEntry.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateRequestedEntry.4dm) |
| Form.DateDespatch | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.DateDespatch | [Form.DateDespatch.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateDespatch.4dm) |
| Form.DateDespatchEntry_picker | 📅 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateDespatchEntry_picker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateDespatchEntry_picker.4dm) |
| Button4 | ✏️ | 🔘 button | ✅ | ✅ | ❌ | - | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Button4.4dm) |
| Form.Product_Options | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Product_Options | [Form.Product_Options.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.Product_Options.4dm) |
| Form.OrderNumber_lock | 🔐 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.OrderNumber_lock.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.OrderNumber_lock.4dm) |
| Form.DateReceived_lock | 🔓 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateReceived_lock.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateReceived_lock.4dm) |
| listbox3 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.OrderHistory | [listbox3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/listbox3.4dm) |
| Form.BatchNumber_lock | 🔐 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.BatchNumber_lock.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.BatchNumber_lock.4dm) |
| Form.DateRequested_lock | 🔓 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateRequested_lock.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateRequested_lock.4dm) |
| Form.DateDespatch_lock | 🔓 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateDespatch_lock.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateDespatch_lock.4dm) |
| Form.DateDespatchEntry_transport | 🚚 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.DateDespatchEntry_transport.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerOrderEntry/ObjectMethods/Form.DateDespatchEntry_transport.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text11 | SELECT A CUSTOMER AND PRODUCT | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text6 | SELECT A TOOL AND PRICE OPTION | 📄 text | ✅ | ✅ | ❌ | - | - |

## 🔗 Related Items

### 🗂️ Tables

- [Product_Option](../Tables/Product_Option.md) - Data source for CustomerOrderEntry form
- [Customer](../Tables/Customer.md) - Data source for CustomerOrderEntry form
- [Customer_Order](../Tables/Customer_Order.md) - Data source for CustomerOrderEntry form
- [Product](../Tables/Product.md) - Data source for CustomerOrderEntry form
- [Tools](../Tables/Tools.md) - Data source for CustomerOrderEntry form

---

*Generated from form.4DForm*

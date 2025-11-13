---
layout : default
title : %2AStockControl
parent : Forms
---
# %2AStockControl [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/%2AStockControl)

📊 **Overview:** 41 Objects | 7 Types | 3 Pages | 16 Events | 29 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: fixed, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 29 |
| **Generated** | 🕐 2025-11-13T16:07:03.013Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (41)

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

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Form.ProductListBox | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Products | [Form.ProductListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.ProductListBox.4dm) |
| Form.WorksOrderListBox | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.WorksOrders | [Form.WorksOrderListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.WorksOrderListBox.4dm) |
| listbox2 | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Stock.GetStockEntitySelection() | [listbox2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/listbox2.4dm) |
| Text | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | 📥 dropdown | ✅ | ✅ | ❌ | StockControl_QuarantineNew | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Text1 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input | 📝 input | ✅ | ✅ | ❌ | Form:C1466.QuarantineReason | [Input.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Input.4dm) |
| Button | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button.4dm) |
| Text2 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input1 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Stock.GetQuarantinedQuantity() | - |
| Form.AdjustmentFromText | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List1 | 📥 dropdown | ✅ | ✅ | ❌ | StockControl_MoveFrom | [Popup Dropdown List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Popup%20Dropdown%20List1.4dm) |
| Form.AdjustmentToText | 📄 text | ✅ | ✅ | ❌ | - | - |
| StockControl_MoveTo | 📥 dropdown | ✅ | ✅ | ❌ | StockControl_MoveTo | [StockControl_MoveTo.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/StockControl_MoveTo.4dm) |
| Form.CancelButton | 🔘 button | ✅ | ✅ | ❌ | ⬆️ | [Form.CancelButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.CancelButton.4dm) |
| Text6 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.QuarantineQuantity | 📝 input | ✅ | ✅ | ❌ | Form:C1466.QuarantineQuantity | [Form.QuarantineQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.QuarantineQuantity.4dm) |
| Button5 | 🔘 button | ✅ | ✅ | ❌ | - | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button5.4dm) |
| Text7 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.ReleaseQuantity | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ReleaseQuantity | [Form.ReleaseQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.ReleaseQuantity.4dm) |
| Button6 | 🔘 button | ✅ | ✅ | ❌ | - | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button6.4dm) |
| Text8 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.ScrapQuantity | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ScrapQuantity | [Form.ScrapQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.ScrapQuantity.4dm) |
| Form.AdjustButton | 🔘 button | ✅ | ✅ | ❌ | - | [Form.AdjustButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.AdjustButton.4dm) |
| Form.AdjustText | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.AdjustmentQuantity | 📝 input | ✅ | ✅ | ❌ | Form:C1466.AdjustmentQuantity | [Form.AdjustmentQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.AdjustmentQuantity.4dm) |
| Button2 | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button2.4dm) |
| Button3 | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button3.4dm) |
| Button7 | 🔘 button | ✅ | ✅ | ❌ | - | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button7.4dm) |
| Button8 | 🔘 button | ✅ | ✅ | ❌ | - | [Button8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button8.4dm) |
| Button9 | 🔘 button | ✅ | ✅ | ❌ | - | [Button9.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button9.4dm) |
| Button10 | 🔘 button | ✅ | ✅ | ❌ | - | [Button10.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button10.4dm) |
| Button11 | 🔘 button | ✅ | ✅ | ❌ | - | [Button11.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button11.4dm) |
| Form.SaveButton | 🔘 button | ✅ | ✅ | ❌ | ⬆️ | [Form.SaveButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SaveButton.4dm) |
| Form.SearchText | 📝 input | ✅ | ✅ | ❌ | Form:C1466.PartSearch | [Form.SearchText.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SearchText.4dm) |
| Form.SearchClear | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchClear.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SearchClear.4dm) |
| Form.SearchButton | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SearchButton.4dm) |
| Radio Button | 🔘 radio | ✅ | ✅ | ❌ | Form:C1466.MakeStockAdjustment | [Radio Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Radio%20Button.4dm) |
| Radio Button1 | 🔘 radio | ✅ | ✅ | ❌ | Form:C1466.MakeStockMovement | [Radio Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Radio%20Button1.4dm) |

#### Page 1

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text5 | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*

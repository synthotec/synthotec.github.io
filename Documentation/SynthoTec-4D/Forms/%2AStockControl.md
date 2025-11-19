---
layout : default
title : %2AStockControl
parent : Forms
---
# %2AStockControl [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/%2AStockControl)

📊 **Overview:** 41 Objects | 7 Types | 3 Pages | 16 Events | 29 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: fixed, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/method.4dm) |
| **Object Methods** | 29 |
| **Generated** | 🕐 2025-11-19T20:54:38.063Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (41)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (6)

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
| Form.ProductListBox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Products | [Form.ProductListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.ProductListBox.4dm) |
| Form.WorksOrderListBox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.WorksOrders | [Form.WorksOrderListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.WorksOrderListBox.4dm) |
| listbox2 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Stock.GetStockEntitySelection() | [listbox2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/listbox2.4dm) |
| Text | NEW STOCK WILL GO INTO | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | StockControl_QuarantineNew | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Text1 | REASON FOR QUARANTINE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.QuarantineReason | [Input.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Input.4dm) |
| Button | 🚧 QUARANTINE FINISHED GOODS | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button.4dm) |
| Text2 | QUARANTINED STOCK | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input1 | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Stock.GetQuarantinedQuantity() | - |
| Form.AdjustmentFromText | ADJUST / MOVE STOCK FROM | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | StockControl_MoveFrom | [Popup Dropdown List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Popup%20Dropdown%20List1.4dm) |
| Form.AdjustmentToText | MOVE STOCK TO | 📄 text | ✅ | ✅ | ❌ | - | - |
| StockControl_MoveTo | - | 📥 dropdown | ✅ | ✅ | ❌ | StockControl_MoveTo | [StockControl_MoveTo.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/StockControl_MoveTo.4dm) |
| Form.CancelButton | ❌ CANCEL CHANGES | 🔘 button | ✅ | ✅ | ❌ | ⬆️ | [Form.CancelButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.CancelButton.4dm) |
| Text6 | QUANTITY TO QUARANTINE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.QuarantineQuantity | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.QuarantineQuantity | [Form.QuarantineQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.QuarantineQuantity.4dm) |
| Button5 | 📦 RELEASE QUARANTINED STOCK | 🔘 button | ✅ | ✅ | ❌ | - | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button5.4dm) |
| Text7 | QUANTITY TO RELEASE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.ReleaseQuantity | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ReleaseQuantity | [Form.ReleaseQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.ReleaseQuantity.4dm) |
| Button6 | 🗑️ SCRAP QUARANTINED STOCK | 🔘 button | ✅ | ✅ | ❌ | - | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button6.4dm) |
| Text8 | QUANTITY TO SCRAP | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.ScrapQuantity | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ScrapQuantity | [Form.ScrapQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.ScrapQuantity.4dm) |
| Form.AdjustButton | ✏️ MAKE STOCK ADJUSTMENT | 🔘 button | ✅ | ✅ | ❌ | - | [Form.AdjustButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.AdjustButton.4dm) |
| Form.AdjustText | STOCK ADJUSTMENT QUANTITY | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.AdjustmentQuantity | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.AdjustmentQuantity | [Form.AdjustmentQuantity.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.AdjustmentQuantity.4dm) |
| Button2 | ⬆️ | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button2.4dm) |
| Button3 | ⬆️ | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button3.4dm) |
| Button7 | ❌ | 🔘 button | ✅ | ✅ | ❌ | - | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button7.4dm) |
| Button8 | ⬆️ | 🔘 button | ✅ | ✅ | ❌ | - | [Button8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button8.4dm) |
| Button9 | ❌ | 🔘 button | ✅ | ✅ | ❌ | - | [Button9.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button9.4dm) |
| Button10 | ❌ | 🔘 button | ✅ | ✅ | ❌ | - | [Button10.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button10.4dm) |
| Button11 | ❌ | 🔘 button | ✅ | ✅ | ❌ | - | [Button11.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Button11.4dm) |
| Form.SaveButton | ✔️ SAVE CHANGES | 🔘 button | ✅ | ✅ | ❌ | ⬆️ | [Form.SaveButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SaveButton.4dm) |
| Form.SearchText | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.PartSearch | [Form.SearchText.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SearchText.4dm) |
| Form.SearchClear | ❌ | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchClear.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SearchClear.4dm) |
| Form.SearchButton | 🔎 | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Form.SearchButton.4dm) |
| Radio Button | ✏️Adjust Stock | 🔘 radio | ✅ | ✅ | ❌ | Form:C1466.MakeStockAdjustment | [Radio Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Radio%20Button.4dm) |
| Radio Button1 | ➡️Move Stock | 🔘 radio | ✅ | ✅ | ❌ | Form:C1466.MakeStockMovement | [Radio Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AStockControl/ObjectMethods/Radio%20Button1.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text5 | SELECT A WORKS ORDER TO MODIFY THE STOCK | 📄 text | ✅ | ✅ | ❌ | - | - |

## 🔗 Related Items

### 🗂️ Tables

- [Product](../Tables/Product.md) - Data source for %2AStockControl form
- [StockControl_MoveFrom-1](../Tables/StockControl_MoveFrom-1.md) - Data source for %2AStockControl form
- [StockControl_MoveTo-1](../Tables/StockControl_MoveTo-1.md) - Data source for %2AStockControl form
- [Finished_Stock](../Tables/Finished_Stock.md) - Data source for %2AStockControl form
- [WorksOrder](../Tables/WorksOrder.md) - Data source for %2AStockControl form
- [Stock_Location](../Tables/Stock_Location.md) - Data source for %2AStockControl form

---

*Generated from form.4DForm*

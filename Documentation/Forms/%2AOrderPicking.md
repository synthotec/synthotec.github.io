---
layout : default
title : %2AOrderPicking
parent : Forms
---
# %2AOrderPicking [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/%2AOrderPicking)

📊 **Overview:** 13 Objects | 4 Types | 4 Pages | 15 Events | 10 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/method.4dm) |
| **Object Methods** | 10 |
| **Generated** | 🕐 2025-11-14T16:45:51.903Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (13)

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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input | - | 📝 input | ✅ | ✅ | ❌ | _Text("PICK REQUEST #:1").parse(Form:C1466.PickRequestEntity.ID) | - |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.PickedStockListboxObject.Collection | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/List%20Box2.4dm) |
| List Box3 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.WorksOrderSummaryListboxCollection | - |
| PickRequestDespatchButton | 🚚 Despatch Pick Request | 🔘 button | ✅ | ✅ | ❌ | - | [PickRequestDespatchButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/PickRequestDespatchButton.4dm) |
| PickRequestListBox | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.PickRequestSelection | [PickRequestListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/PickRequestListBox.4dm) |
| Button | ➕ New Pick Request | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/Button.4dm) |
| PickRequestSubmitButton | 📩 Submit Pick Request | 🔘 button | ✅ | ✅ | ❌ | - | [PickRequestSubmitButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/PickRequestSubmitButton.4dm) |
| Button1 | 🔃 Refresh | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/Button1.4dm) |
| PickRequestTransportInstructionsButton | 📖 Transport Instructions | 🔘 button | ✅ | ✅ | ❌ | - | [PickRequestTransportInstructionsButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/PickRequestTransportInstructionsButton.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Customer_OrderSelection | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/List%20Box1.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text | SELECT OR CREATE A PICK REQUEST TO VIEW PRODUCTS AND ORDERS | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| PickRequestAddMovementButton | ↪️ Add Movement Request | 🔘 button | ✅ | ✅ | ❌ | - | [PickRequestAddMovementButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/PickRequestAddMovementButton.4dm) |
| List Box4 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.Customer_OrderSelection | [List Box4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AOrderPicking/ObjectMethods/List%20Box4.4dm) |

---

*Generated from form.4DForm*

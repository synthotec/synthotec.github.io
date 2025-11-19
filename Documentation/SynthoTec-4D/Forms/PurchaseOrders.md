---
layout : default
title : PurchaseOrders
parent : Forms
---
# PurchaseOrders [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/PurchaseOrders)

📊 **Overview:** 19 Objects | 5 Types | 4 Pages | 16 Events | 15 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/method.4dm) |
| **Object Methods** | 15 |
| **Generated** | 🕐 2025-11-19T20:54:38.246Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (19)
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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ❌ | ❌ | PO_Detail_Listbox | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/List%20Box1.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | QueryBox | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Variable.4dm) |
| vDesc | - | 📝 input | ✅ | ❌ | ❌ | vDesc | - |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | PurchaseOrder_WhoList | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | PurchaseOrder_WhatList | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| EditButton | ✎ Edit Purchase Order | 🔘 button | ✅ | ❌ | ❌ | Button | [EditButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/EditButton.4dm) |
| Button1 | 🆕 New Purchase Order | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Button1.4dm) |
| Variable1 | - | 📝 input | ✅ | ❌ | ❌ | PurchaseDesc | - |
| Text | Search | 📄 text | ✅ | ✅ | ❌ | - | - |
| PrintButton | Print Purchase Order | 🔘 button | ✅ | ❌ | ❌ | Button | [PrintButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/PrintButton.4dm) |
| Button3 | 🏬 Modify Suppliers | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Button3.4dm) |
| Button4 | - | 🔘 button | ✅ | ❌ | ❌ | Button2 | - |
| UnlockButton | 🔓 Unlock Purchase Order | 🔘 button | ✅ | ✅ | ❌ | Button | [UnlockButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/UnlockButton.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | XBOX | [Variable2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Variable2.4dm) |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.SelectedPurchaseInfoEntity.PurchaseReceiptsSelection | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/List%20Box2.4dm) |
| Button | 🧾 Record a receipt of goods or services | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PurchaseOrders/ObjectMethods/Button.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input | - | 📝 input | ✅ | ✅ | ❌ | "Select a Purchase Order" | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input1 | - | 📝 input | ✅ | ✅ | ❌ | "Select a Purchase Order line to see the full description and book / view receipts" | - |

## 🔗 Related Items

### 🗂️ Tables

- [Purchases](../Tables/Purchases.md) - Data source for PurchaseOrders form
- [PurchaseInfo](../Tables/PurchaseInfo.md) - Data source for PurchaseOrders form
- [Suppliers](../Tables/Suppliers.md) - Data source for PurchaseOrders form
- [NominalCodes](../Tables/NominalCodes.md) - Data source for PurchaseOrders form
- [Staff](../Tables/Staff.md) - Data source for PurchaseOrders form

---

*Generated from form.4DForm*

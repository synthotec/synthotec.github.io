---
layout : default
title : WarehouseOptions
parent : Forms
---
# WarehouseOptions [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/WarehouseOptions)

📊 **Overview:** 8 Objects | 4 Types | 2 Pages | 16 Events | 6 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/method.4dm) |
| **Object Methods** | 6 |
| **Generated** | 🕐 2025-11-14T16:53:02.639Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (8)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (2)

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
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vxSearch | [Variable1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/ObjectMethods/Variable1.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | X | [Variable2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/ObjectMethods/Variable2.4dm) |
| Text | Right click a line for options | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | GetDBVariable("*test3"; False:C215) ? "test3" : (Form:C1466.SelectedProductEntity=Null:C1517 ? "" : (Form:C1466.SelectedProductEntity.EmojisEntity=Null:C1517 ? "" : Form:C1466.SelectedProductEntity.EmojisEntity.Emoji)+"\r"+(Form:C1466.SelectedProductEntity.PalletMethodsEntity=Null:C1517 ? "" : Form:C1466.SelectedProductEntity.PalletMethodsEntity.Symbol)) | - |
| ClearArchivedButton | Clear Symbols from Archived Products | 🔘 button | ✅ | ✅ | ❌ | - | [ClearArchivedButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/ObjectMethods/ClearArchivedButton.4dm) |
| AddMissingButton | Set Products Without Symbols | 🔘 button | ✅ | ✅ | ❌ | - | [AddMissingButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/ObjectMethods/AddMissingButton.4dm) |
| EmojiManagerButton | Open Symbol Manager | 🔘 button | ✅ | ✅ | ❌ | - | [EmojiManagerButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/ObjectMethods/EmojiManagerButton.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ProductSelection | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/WarehouseOptions/ObjectMethods/List%20Box1.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Product](../Tables/Product.md) - Data source for WarehouseOptions form
- [PalletMethods](../Tables/PalletMethods.md) - Data source for WarehouseOptions form

---

*Generated from form.4DForm*

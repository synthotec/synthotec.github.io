---
layout : default
title : MaterialOptions
parent : Forms
---
# MaterialOptions [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/MaterialOptions)

📊 **Overview:** 9 Objects | 5 Types | 2 Pages | 16 Events | 7 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/method.4dm) |
| **Object Methods** | 7 |
| **Generated** | 🕐 2025-11-19T20:54:38.197Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (9)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (4)

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
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | vPartSearch | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/SearchPicker.4dm) |
| SearchPicker1 | - | 🔲 subform | ✅ | ✅ | ❌ | vMaterialSearch | [SearchPicker1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/SearchPicker1.4dm) |
| Button2 | Delete Selected Material Option | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/Button2.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/List%20Box1.4dm) |
| Button | Add Missing Materials | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/Button.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | aMaterialNames | - |
| Button1 | Add Selected Material Option To Product | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialOptions/ObjectMethods/Button1.4dm) |
| Text | Double click a line to change the default material | 📄 text | ✅ | ✅ | ❌ | - | - |

## 🔗 Related Items

### 🗂️ Tables

- [Product](../Tables/Product.md) - Data source for MaterialOptions form
- [ProductMaterialOptions](../Tables/ProductMaterialOptions.md) - Data source for MaterialOptions form
- [Material](../Tables/Material.md) - Data source for MaterialOptions form
- [PlanningWheel](../Tables/PlanningWheel.md) - Data source for MaterialOptions form

---

*Generated from form.4DForm*

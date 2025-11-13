---
layout : default
title : PackagingOptions
parent : Forms
---
# PackagingOptions [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/PackagingOptions)

📊 **Overview:** 11 Objects | 5 Types | 3 Pages | 16 Events | 10 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/method.4dm) |
| **Object Methods** | 10 |
| **Generated** | 🕐 2025-11-13T23:49:49.467Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (11)

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
| Button2 | Delete Selected Packaging Option | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/Button2.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/List%20Box1.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | aMaterialNames | - |
| Button1 | Add Selected Packaging Option To Product | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/Button1.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vHeader | - |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | Form:C1466.TypeDropdownObject | [Popup Dropdown List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/Popup%20Dropdown%20List1.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/List%20Box.4dm) |
| SearchPicker1 | - | 🔲 subform | ✅ | ✅ | ❌ | vMaterialSearch | [SearchPicker1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/SearchPicker1.4dm) |
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | vPartSearch | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/SearchPicker.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.CustomerSelection | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/List%20Box2.4dm) |
| Button | Update Boxes / Pallet Quantity | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PackagingOptions/ObjectMethods/Button.4dm) |

---

*Generated from form.4DForm*

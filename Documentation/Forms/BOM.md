---
layout : default
title : BOM
parent : Forms
---
# BOM [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/BOM)

📊 **Overview:** 10 Objects | 4 Types | 2 Pages | 17 Events | 8 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/method.4dm) |
| **Object Methods** | 8 |
| **Generated** | 🕐 2025-11-14T00:18:22.115Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (17)
- [🧩 Form Objects](#-form-objects) (10)
- [📸 Screenshots](#-screenshots) (1)
  - [BOM Management Screen](#bom-management-screen)

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

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | MasterList | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/List%20Box.4dm) |
| Button1 | Update | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/Button1.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/List%20Box1.4dm) |
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | vSearch | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/SearchPicker.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | BOM_AddProductCustomers | - |
| SearchPicker1 | - | 🔲 subform | ✅ | ✅ | ❌ | BOM_AddProductFilter | [SearchPicker1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/SearchPicker1.4dm) |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | BOM_AddProductArray | - |
| Button | Add Product + Customer Line | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/Button.4dm) |
| Button2 | Cancel Changes | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/Button2.4dm) |
| Button3 | Save Changes | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/BOM/ObjectMethods/Button3.4dm) |

## 📸 Screenshots

### BOM Management Screen {#bom-management-screen}

![BOM Management Screen](Images/BOM-1.png)

Main view showing the Bill of Materials interface with listbox for parts selection and management controls.

---

---

*Generated from form.4DForm*

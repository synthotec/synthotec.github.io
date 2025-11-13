---
layout : default
title : SupplierDocumentationAdd
parent : Forms
---
# SupplierDocumentationAdd [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/SupplierDocumentationAdd)

📊 **Overview:** 10 Objects | 4 Types | 2 Pages | 16 Events | 3 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SupplierDocumentationAdd/method.4dm) |
| **Object Methods** | 3 |
| **Generated** | 🕐 2025-11-13T23:29:29.826Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (10)

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
| Text | Document Type | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | SupplierDoc_TypeArray | - |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vDocumentReference | - |
| Button2 | Paste File | 🔘 button | ✅ | ❌ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SupplierDocumentationAdd/ObjectMethods/Button2.4dm) |
| Button | Select File | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SupplierDocumentationAdd/ObjectMethods/Button.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vValidUntil | - |
| Button1 | Save Supplier Documentation | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SupplierDocumentationAdd/ObjectMethods/Button1.4dm) |
| Text1 | Document Reference | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vFileName | - |
| Text2 | Document Valid Until | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*

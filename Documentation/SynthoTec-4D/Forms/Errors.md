---
layout : default
title : Errors
parent : Forms
---
# Errors [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/Errors)

📊 **Overview:** 6 Objects | 2 Types | 2 Pages | 15 Events | 2 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Errors/method.4dm) |
| **Object Methods** | 2 |
| **Generated** | 🕐 2025-11-14T16:53:02.412Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (6)

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

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ErrorSelection | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Errors/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ErrorDetailSelection | - |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ErrorDetailEntity.ErrorObject.Stack | - |
| List Box3 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ErrorDetailEntity.ErrorObject.CallChain | - |
| Input | - | 📝 input | ✅ | ✅ | ❌ | JSON Stringify:C1217(Form:C1466.CurrentStackTrace; *) | - |
| Input1 | - | 📝 input | ✅ | ✅ | ❌ | JSON Stringify:C1217(Form:C1466.ErrorDetailEntity.ErrorObject.DebugInfo || ""; *) | - |

---

*Generated from form.4DForm*

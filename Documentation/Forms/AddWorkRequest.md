---
layout : default
title : AddWorkRequest
parent : Forms
---
# AddWorkRequest [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/AddWorkRequest)

📊 **Overview:** 17 Objects | 5 Types | 2 Pages | 16 Events | 7 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/method.4dm) |
| **Object Methods** | 7 |
| **Generated** | 🕐 2025-11-14T16:36:00.413Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (17)

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
| Text1 | Machine | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | Description | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text | Type | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | Priority | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | tRemain | - |
| Button1 | CANCEL | 🔘 button | ✅ | ✅ | ❌ | Button | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/Button1.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | Fault | - |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vDesc | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/Variable.4dm) |
| Popup Drop down List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | AddWorkRequest_PriorityArray | - |
| Field | - | 📝 input | ✅ | ✅ | ❌ | vComment | [Field.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/Field.4dm) |
| Button | SAVE REQUEST | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/Button.4dm) |
| Text4 | Category | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Drop down List3 | - | 📥 dropdown | ✅ | ✅ | ❌ | Category | [Popup Drop down List3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/Popup%20Drop%20down%20List3.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vUnit | - |
| Text5 | Tool | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | AddWorkRequest_ToolArray | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | AddWorkRequest_ToolSearch | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/AddWorkRequest/ObjectMethods/SearchPicker.4dm) |

---

*Generated from form.4DForm*

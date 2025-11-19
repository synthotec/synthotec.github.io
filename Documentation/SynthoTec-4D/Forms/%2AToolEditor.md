---
layout : default
title : %2AToolEditor
parent : Forms
---
# %2AToolEditor [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/%2AToolEditor)

📊 **Overview:** 9 Objects | 6 Types | 2 Pages | 16 Events | 9 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/method.4dm) |
| **Object Methods** | 9 |
| **Generated** | 🕐 2025-11-19T20:54:38.084Z |

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

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | ToolEditorListBox | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/List%20Box.4dm) |
| Button | Refresh Data | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/Button.4dm) |
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | ToolEditor_SearchText | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/SearchPicker.4dm) |
| Check Box | Hide Archived Products | ☑️ checkbox | ✅ | ✅ | ❌ | HideArchivedProducts | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/Check%20Box.4dm) |
| Check Box1 | Hide Archived Tools | ☑️ checkbox | ✅ | ✅ | ❌ | HideArchivedTools | [Check Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/Check%20Box1.4dm) |
| Input | - | 📝 input | ✅ | ✅ | ❌ | FloatingSymbol | [Input.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/Input.4dm) |
| Text | CTRL + CLICK A CELL TO VIEW ITS HISTORY | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button1 | Cancel Changes | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/Button1.4dm) |
| Button2 | Save Changes | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AToolEditor/ObjectMethods/Button2.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Tools](../Tables/Tools.md) - Data source for %2AToolEditor form
- [Product](../Tables/Product.md) - Data source for %2AToolEditor form
- [Material](../Tables/Material.md) - Data source for %2AToolEditor form
- [Emojis](../Tables/Emojis.md) - Data source for %2AToolEditor form

---

*Generated from form.4DForm*

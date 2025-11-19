---
layout : default
title : ToolManager
parent : Forms
---
# ToolManager [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ToolManager)

📊 **Overview:** 12 Objects | 4 Types | 2 Pages | 16 Events | 11 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/method.4dm) |
| **Object Methods** | 11 |
| **Generated** | 🕐 2025-11-14T16:53:02.619Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (12)

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
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vGripperInfo | - |
| Button1 | Print List | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Button1.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | List Box | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/List%20Box.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vSearch | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Variable.4dm) |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | xbox | [Variable1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Variable1.4dm) |
| Button | Allow Editing | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Button.4dm) |
| Button2 | Hot Half Manager | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Button2.4dm) |
| Button3 | Force Update Cycle Counts | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Button3.4dm) |
| Check Box | Show Archived Tools | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.IncludeArchived | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Check%20Box.4dm) |
| Input | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ToolsEntity=Null:C1517 ? "Tool Notices" : _Text("Tool Notices for Tool :1 (:2)").parse(Form:C1466.ToolsEntity.Tool_No; Form:C1466.ToolsEntity.ProduictEntity.OurPartName) | - |
| Button4 | ➕New Tool Notice | 🔘 button | ✅ | ✅ | ❌ | - | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/Button4.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ToolNoticeSelection | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolManager/ObjectMethods/List%20Box1.4dm) |

---

*Generated from form.4DForm*

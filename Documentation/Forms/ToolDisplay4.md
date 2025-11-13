---
layout : default
title : ToolDisplay4
parent : Forms
---
# ToolDisplay4 [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ToolDisplay4)

📊 **Overview:** 42 Objects | 7 Types | 3 Pages | 16 Events | 20 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | - |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 3 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/method.4dm) |
| **Object Methods** | 20 |
| **Generated** | 🕐 2025-11-13T23:49:49.589Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (42)

---

## 🎯 Form Events

This form handles **16** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ✅ |
| `onValidate` | ✅ | `onClick` | ✅ |
| `onDoubleClick` | ✅ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ✅ |
| `onBeginDragOver` | ❌ | `onDragOver` | ✅ |
| `onDrop` | ✅ | `onAfterKeystroke` | ✅ |
| `onMenuSelect` | ✅ | `onPluginArea` | ✅ |
| `onAfterEdit` | ❌ | `onTimer` | ✅ |
| `onBoundVariableChange` | ❌ | `onPageChange` | ❌ |
| `onBeforeDataEntry` | ❌ | `onLoadRecord` | ❌ |
| `onAfterSort` | ❌ | `onSelectionChange` | ✅ |
| `onDataChange` | ✅ | `onExpand` | ❌ |
| `onCollapse` | ❌ | `onBeforeKeystroke` | ❌ |
| `onOpenDetail` | ❌ | `onCloseDetail` | ❌ |
| `onResize` | ✅ | `onActivate` | ❌ |
| `onDeactivate` | ❌ | `onOpenExternalLink` | ❌ |
| `onWindowOpeningDenied` | ❌ | `onScroll` | ❌ |
| `onCloseBox` | ✅ | `onDeleteAction` | ❌ |
| `onRowResize` | ❌ | `onAlternativeClick` | ❌ |
| `onLongClick` | ❌ | `onMouseEnter` | ❌ |
| `onMouseLeave` | ❌ | `onMouseMove` | ❌ |

## 🧩 Form Objects

### Interactive Objects by Page

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Button2 | Detail | 🔘 button | ✅ | ✅ | ❌ | bToolHistory | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button2.4dm) |
| Button4 | Edit | 🔘 button | ✅ | ✅ | ❌ | bbEdit | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button4.4dm) |
| Button6 | New | 🔘 button | ✅ | ✅ | ❌ | bNew | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button6.4dm) |
| Button7 | Search | 🔘 button | ✅ | ✅ | ❌ | bSearch | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button7.4dm) |
| Button3 | Reports | 🔘 button | ✅ | ✅ | ❌ | bReports | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button3.4dm) |
| Button8 | Labels | 🔘 button | ✅ | ✅ | ❌ | bLabels | [Button8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button8.4dm) |
| Button5 | OK | 🔘 button | ✅ | ✅ | ❌ | bAccept | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button5.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Variable | - | 📝 input | ✅ | ✅ | ❌ | pQuery | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | xBox | [Variable2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable2.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | - |
| Button1 | Select Part | 🔘 button | ✅ | ✅ | ❌ | bReports | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button1.4dm) |
| Text46 | Current | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text48 | Archived | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text50 | All | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text | Search | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | pQuery | [Variable3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable3.4dm) |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | xBox | [Variable4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable4.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox1 | - |
| Variable183 | - | 🔘 button | ✅ | ✅ | ❌ | bselection | [Variable183.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable183.4dm) |
| Button10 | Move. History | 🔘 button | ✅ | ✅ | ❌ | Button | [Button10.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button10.4dm) |
| Button9 | Stock Levels | 🔘 button | ✅ | ✅ | ❌ | Button | [Button9.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button9.4dm) |
| Button | Cust. Orders | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Button.4dm) |
| Variable7 | - | 📝 input | ✅ | ❌ | ❌ | vPartNo | [Variable7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable7.4dm) |
| Text5 | Current | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text7 | Archived | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text8 | All | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable50 | - | 🔘 button | ✅ | ✅ | ❌ | bToolLog | [Variable50.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolDisplay4/ObjectMethods/Variable50.4dm) |
| Text38 | To Tools | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text175 | Select Tool | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | Search | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*

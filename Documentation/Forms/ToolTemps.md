---
layout : default
title : ToolTemps
parent : Forms
---
# ToolTemps [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ToolTemps)

📊 **Overview:** 13 Objects | 4 Types | 2 Pages | 15 Events | 11 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 11 |
| **Generated** | 🕐 2025-11-13T16:07:03.363Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (13)

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

#### Page 0 (Visible on All Pages)

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ToolsSelection | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/List%20Box.4dm) |
| RealTimeSensorExceptionsListBox | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.RealTimeSensorExceptionsSelection | [RealTimeSensorExceptionsListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/RealTimeSensorExceptionsListBox.4dm) |
| Form.RealTimeSelection | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.RealTimeSelection | - |
| Form.SearchText | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Search | [Form.SearchText.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/Form.SearchText.4dm) |
| Form.SearchClear | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchClear.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/Form.SearchClear.4dm) |
| Form.SearchButton | 🔘 button | ✅ | ✅ | ❌ | - | [Form.SearchButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/Form.SearchButton.4dm) |
| List Box2 | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ToolsEntity.ToolTemperatureTargetSelection | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/List%20Box2.4dm) |
| AddTemperatureTargetButton | 🔘 button | ✅ | ✅ | ❌ | - | [AddTemperatureTargetButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/AddTemperatureTargetButton.4dm) |
| Input | 📝 input | ✅ | ✅ | ❌ | Form:C1466.ToolsEntity.ProductEntity.OurPartName+" - Tool "+Form:C1466.ToolsEntity.Tool_No | - |
| Button | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ToolTemps/ObjectMethods/Button.4dm) |

#### Page 1

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| TextBox_SelectATool | 📄 text | ✅ | ✅ | ❌ | - | - |
| TextBox_SelectAnException | 📄 text | ✅ | ✅ | ❌ | - | - |
| TextBox_TemperatureTargets | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*

---
layout : default
title : MachineMaintenance
parent : Forms
---
# MachineMaintenance [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/MachineMaintenance)

📊 **Overview:** 10 Objects | 4 Types | 2 Pages | 15 Events | 6 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 6 |
| **Generated** | 🕐 2025-11-13T16:07:03.187Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (10)

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
| MaintenanceRequirementsListBox | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.MaintenanceRequirementsCollection | [MaintenanceRequirementsListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MachineMaintenance/ObjectMethods/MaintenanceRequirementsListBox.4dm) |
| List Box1 | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.MachineMaintenanceLogSelection | - |
| List Box2 | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.MachineMaintenanceActionsSelection | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MachineMaintenance/ObjectMethods/List%20Box2.4dm) |
| List Box3 | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.MachineMaintenanceRequirementsSelection.orderBy("Machine ASC") | - |
| Button | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MachineMaintenance/ObjectMethods/Button.4dm) |
| Button1 | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MachineMaintenance/ObjectMethods/Button1.4dm) |
| Button2 | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MachineMaintenance/ObjectMethods/Button2.4dm) |
| Input | 📝 input | ✅ | ✅ | ❌ | "<span>MC "+String:C10(Form:C1466.CurrentMaintenanceRequirementsObject.Machine)+" Maintenance Log : <span style=\"font-weight:bold\">"+Form:C1466.CurrentMaintenanceRequirementsObject.Action+"</span></span>" | - |

#### Page 1

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| MaintenanceLogText | 📄 text | ✅ | ✅ | ❌ | - | - |
| MachineRequirementsText | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*

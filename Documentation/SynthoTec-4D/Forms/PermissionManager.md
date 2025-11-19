---
layout : default
title : PermissionManager
parent : Forms
---
# PermissionManager [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/PermissionManager)

📊 **Overview:** 9 Objects | 5 Types | 3 Pages | 15 Events | 6 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/method.4dm) |
| **Object Methods** | 6 |
| **Generated** | 🕐 2025-11-19T20:54:38.232Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (9)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (3)

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
| HidePanel | Select a Person | 📄 text | ✅ | ✅ | ❌ | - | - |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/ObjectMethods/List%20Box1.4dm) |
| SelectedSubject | PERMISSION_SUBECT | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | Permissions_SetType | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/ObjectMethods/List%20Box.4dm) |
| Text | ASSIGN PERMISSIONS BY | 📄 text | ✅ | ✅ | ❌ | - | - |
| SubjectFilter | - | 🔲 subform | ✅ | ✅ | ❌ | Permissions_Subject_Filter | [SubjectFilter.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/ObjectMethods/SubjectFilter.4dm) |
| ObjectFilter | - | 🔲 subform | ✅ | ✅ | ❌ | Permissions_Object_Filter | [ObjectFilter.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/ObjectMethods/ObjectFilter.4dm) |
| Button2 | Add New Permission | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/PermissionManager/ObjectMethods/Button2.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Permissions](../Tables/Permissions.md) - Data source for PermissionManager form
- [Staff](../Tables/Staff.md) - Data source for PermissionManager form
- [StaffPermissions](../Tables/StaffPermissions.md) - Data source for PermissionManager form

---

*Generated from form.4DForm*

---
layout : default
title : CompanyNotices
parent : Forms
---
# CompanyNotices [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CompanyNotices)

📊 **Overview:** 26 Objects | 7 Types | 4 Pages | 16 Events | 16 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: variable |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/method.4dm) |
| **Object Methods** | 16 |
| **Generated** | 🕐 2025-11-14T16:53:02.356Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (26)

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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text1 | Notice Board Image | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | Notice Board Text | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button2 | Update Notice Board | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Button2.4dm) |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | CompanyNotices_Archived | [Popup Dropdown List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Popup%20Dropdown%20List1.4dm) |
| Button | New Notice | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Button.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | [CompanyNotices:61]Title:3 | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Variable.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/List%20Box.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | CompanyNotices_CategoryArray | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| TimePicker1 | - | 🔲 subform | ✅ | ✅ | ❌ | vTime | [TimePicker1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/TimePicker1.4dm) |
| DateEntry | - | 🔲 subform | ✅ | ✅ | ❌ | vDateStart | [DateEntry.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/DateEntry.4dm) |
| DateEntry1 | - | 🔲 subform | ✅ | ✅ | ❌ | vDateStop | [DateEntry1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/DateEntry1.4dm) |
| Field | - | 📝 input | ✅ | ✅ | ❌ | [CompanyNotices:61]Image:7 | [Field.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Field.4dm) |
| Button3 | Insert | 🔘 button | ✅ | ✅ | ❌ | bInsert | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Button3.4dm) |
| Field1 | - | 📝 input | ✅ | ✅ | ❌ | [CompanyNotices:61]Description:4 | [Field1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Field1.4dm) |
| Button5 | Delete Notice | 🔘 button | ✅ | ✅ | ❌ | - | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Button5.4dm) |
| Button4 | Discard Changes | 🔘 button | ✅ | ✅ | ❌ | - | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Button4.4dm) |
| Button1 | Save Notice | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/Button1.4dm) |
| Text | Title | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | Notice Category | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | Duration To Show For | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text5 | Start Date (Blank = Immediate) | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text6 | Final Date (Blank = Never) | 📄 text | ✅ | ✅ | ❌ | - | - |
| bArchive | ARCHIVE THIS COMPANY NOTICE | 🔘 button | ✅ | ✅ | ❌ | - | [bArchive.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CompanyNotices/ObjectMethods/bArchive.4dm) |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | LockedBy | - |

---

*Generated from form.4DForm*

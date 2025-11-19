---
layout : default
title : StaffMessaging
parent : Forms
---
# StaffMessaging [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/StaffMessaging)

📊 **Overview:** 12 Objects | 4 Types | 2 Pages | 15 Events | 5 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffMessaging/method.4dm) |
| **Object Methods** | 5 |
| **Generated** | 🕐 2025-11-14T16:53:02.591Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (12)

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
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffMessaging/ObjectMethods/List%20Box.4dm) |
| Text | From Address (Only Applies To Emails) | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input | - | 📝 input | ✅ | ✅ | ❌ | from_Address | - |
| Text1 | Subject (Only Applies To Emails) | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input1 | - | 📝 input | ✅ | ✅ | ❌ | email_Subject | - |
| Text2 | Message Body | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input2 | - | 📝 input | ✅ | ✅ | ❌ | email_Body | [Input2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffMessaging/ObjectMethods/Input2.4dm) |
| Button1 | Toggle All (SMS) | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffMessaging/ObjectMethods/Button1.4dm) |
| Button2 | Toggle All (Email) | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffMessaging/ObjectMethods/Button2.4dm) |
| Input3 | - | 📝 input | ✅ | ✅ | ❌ | StaffMessaging_SMSLimit | - |
| Input4 | - | 📝 input | ✅ | ✅ | ❌ | StaffMessaging_SMSCredits | - |
| Button3 | Send Messages | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffMessaging/ObjectMethods/Button3.4dm) |

---

*Generated from form.4DForm*

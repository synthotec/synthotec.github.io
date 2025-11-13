---
layout : default
title : StaffLogin
parent : Forms
---
# StaffLogin [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/StaffLogin)

📊 **Overview:** 27 Objects | 4 Types | 6 Pages | 16 Events | 11 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 6 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 11 |
| **Generated** | 🕐 2025-11-13T21:45:03.290Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (27)

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
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | vBanner | - |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text | Scan you keyfob, or enter your mobile number/email address to sign in | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vLoginInfo | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Variable.4dm) |
| Button3 | Sign In | 🔘 button | ✅ | ✅ | ❌ | - | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button3.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text1 | For notification & security purposes we require either an email address or mobile number | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vLoginEmail | - |
| Button1 | Verify | 🔘 button | ✅ | ✅ | ❌ | VerifyEmailButton | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button1.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vLoginMobile | - |
| Button | Verify | 🔘 button | ✅ | ✅ | ❌ | VerifyMobileButton | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button.4dm) |
| Button2 | Register | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button2.4dm) |
| Text2 | Email Address | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | Mobile Number | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | By choosing to continue, you give us permission to store and to use the information that you have supplied for the purposes of notifications and security checks relating to the data you enter into 4D. | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text5 | Please enter a password below, this password will be used to sign in to secure 4D areas | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vPassword1 | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | vPassword2 | - |
| Button4 | Change Password | 🔘 button | ✅ | ✅ | ❌ | - | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button4.4dm) |
| Text6 | Enter Password | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text7 | Re-Enter Password | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 4

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text8 | Enter your password to sign in or you can choose to reset your password if you have forgotten it | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | vLoginPassword | [Variable5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Variable5.4dm) |
| Button5 | Sign In | 🔘 button | ✅ | ✅ | ❌ | - | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button5.4dm) |
| Button6 | Reset Password | 🔘 button | ✅ | ✅ | ❌ | - | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button6.4dm) |

#### Page 5

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Variable7 | - | 📝 input | ✅ | ✅ | ❌ | vVerifyCode | [Variable7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Variable7.4dm) |
| Button7 | Verify Identity | 🔘 button | ✅ | ✅ | ❌ | - | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/StaffLogin/ObjectMethods/Button7.4dm) |
| Variable8 | - | 📝 input | ✅ | ✅ | ❌ | "We have sent a code to "+vContact+", enter it to verify your identity" | - |

---

*Generated from form.4DForm*

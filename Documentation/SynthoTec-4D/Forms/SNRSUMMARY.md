---
layout : default
title : SNRSUMMARY
parent : Forms
---
# SNRSUMMARY [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/SNRSUMMARY)

📊 **Overview:** 24 Objects | 5 Types | 5 Pages | 16 Events | 15 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 5 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/method.4dm) |
| **Object Methods** | 15 |
| **Generated** | 🕐 2025-11-14T16:53:02.581Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (24)

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
| Radio Button | NSK Reports | 🔘 radio | ✅ | ✅ | ❌ | rd1 | [Radio Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Radio%20Button.4dm) |
| Radio Button1 | SNR 380H | 🔘 radio | ✅ | ✅ | ❌ | rd2 | [Radio Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Radio%20Button1.4dm) |
| Radio Button2 | SKF Outbound Report | 🔘 radio | ✅ | ✅ | ❌ | rd3 | [Radio Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Radio%20Button2.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| NSKLIST | - | 📋 listbox | ✅ | ✅ | ❌ | List Box2 | [NSKLIST.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/NSKLIST.4dm) |
| Button1 | Choose NSK Report | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button1.4dm) |
| Text | Open NSK's report in Excel.

Go to file and select Save As, save the file inside
W:\Finance\REPORTS\NSK\
Select the file type as CSV (MS-DOS) *.csv

Then click Choose NSK Report | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vNSKTitle | - |
| Button3 | Print Report | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button3.4dm) |
| Button4 | SYN Stock Report | 🔘 button | ✅ | ✅ | ❌ | Button4 | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button4.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Button | Choose SNR Report | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button.4dm) |
| SNRLIST | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | [SNRLIST.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/SNRLIST.4dm) |
| Text1 | Save SNR's 380H Report in the folder
W:\Finance\REPORTS\SNR\

Then click Choose SNR Report

After you can select a location to view the products | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button2 | Print Report | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button2.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vSNRTitle | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| NSKLIST2 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box2 | - |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vNSKSYNTitle | - |
| Button5 | Print Report | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button5.4dm) |
| Button6 | EXPORT CSV | 🔘 button | ✅ | ✅ | ❌ | Button6 | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button6.4dm) |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | CanSendTxt | - |

#### Page 4

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| SKFLIST | - | 📋 listbox | ✅ | ✅ | ❌ | List Box2 | [SKFLIST.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/SKFLIST.4dm) |
| Button7 | Import Clipboard Data | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button7.4dm) |
| Text2 | Open the SKF Outbound Report in Excel.

Left Click the table containing the order information.
Press CTRL+A to select all text.
Press CTRL+C to copy the text.

Then click Import Clipboard Data | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | "SKF Outbound Report" | - |
| Button8 | Print Report | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/SNRSUMMARY/ObjectMethods/Button8.4dm) |

---

*Generated from form.4DForm*

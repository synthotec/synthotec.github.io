---
layout : default
title : Manufacture
parent : Forms
---
# Manufacture [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/Manufacture)

📊 **Overview:** 39 Objects | 9 Types | 3 Pages | 4 Events | 22 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | - |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/method.4dm) |
| **Object Methods** | 22 |
| **Generated** | 🕐 2025-11-13T23:49:49.434Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (4)
- [🧩 Form Objects](#-form-objects) (39)

---

## 🎯 Form Events

This form handles **4** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ❌ |
| `onValidate` | ❌ | `onClick` | ❌ |
| `onDoubleClick` | ❌ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ✅ |
| `onBeginDragOver` | ❌ | `onDragOver` | ❌ |
| `onDrop` | ❌ | `onAfterKeystroke` | ❌ |
| `onMenuSelect` | ❌ | `onPluginArea` | ❌ |
| `onAfterEdit` | ❌ | `onTimer` | ✅ |
| `onBoundVariableChange` | ❌ | `onPageChange` | ✅ |
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
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | "TOOL CHANGES" | - |
| 0000000039 | START / FINISH | 🔘 button | ✅ | ❌ | ❌ | BstartFin | [0000000039.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/0000000039.4dm) |
| REFFRESH | REFRESH | 🔘 button | ✅ | ✅ | ❌ | REFFRESH | [REFFRESH.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/REFFRESH.4dm) |
| Button9 | TOOL MANAGER | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button9.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button9.4dm) |
| Button322 | CREATE W/OS | 🔘 button | ✅ | ✅ | ❌ | Button122 | [Button322.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button322.4dm) |
| PriorityList | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vworksOrderNo | [Variable1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Variable1.4dm) |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | JobSearchX | [Variable6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Variable6.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/List%20Box1.4dm) |
| List Box4 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box | [List Box4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/List%20Box4.4dm) |
| Text7 | WORK ORDERS | 📄 text | ✅ | ✅ | ❌ | - | - |
| LogConditioningRecord2 | OPTIONS | 🔘 button | ✅ | ✅ | ❌ | LogConditioningRecord | [LogConditioningRecord2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/LogConditioningRecord2.4dm) |
| Button | 📑 Shift Summaries | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Check Box | Show Jobs Completed >1 Week Ago | ☑️ checkbox | ✅ | ✅ | ❌ | vShowComp | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Check%20Box.4dm) |
| Check Box2 | Show Pending Jobs | ☑️ checkbox | ✅ | ✅ | ❌ | vShowPend | [Check Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Check%20Box2.4dm) |
| Check Box3 | Show Recently Completed Jobs | ☑️ checkbox | ✅ | ✅ | ❌ | vShowNew | [Check Box3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Check%20Box3.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | JobDesc+" - "+vCreated | - |
| Text2 | Comments | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field1 | - | 📝 input | ✅ | ✅ | ❌ | [WorkRequests:65]CorrectiveAction:8 | - |
| Text5 | Corrective Action | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text6 | Estimated Cost £ | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field3 | - | 📝 input | ✅ | ✅ | ❌ | [WorkRequests:65]Cost:10 | - |
| Button7 | MODIFY | 🔘 button | ✅ | ✅ | ❌ | MODbtn | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button7.4dm) |
| Text3 | Completion Date | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field4 | - | 📝 input | ✅ | ✅ | ❌ | [WorkRequests:65]CompletedDate:12 | - |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | WorkCat | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| Field5 | Completed | ☑️ checkbox | ✅ | ✅ | ❌ | [WorkRequests:65]Completed:11 | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vCounter | - |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | ReqsBox | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/List%20Box2.4dm) |
| Text1 | WORK REQUESTS | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field | - | 📝 input | ✅ | ✅ | ❌ | vCommentR | - |
| Button4 | Add a Comment | 🔘 button | ✅ | ✅ | ❌ | Button4 | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button4.4dm) |
| Button5 | Submit Comment | 🔘 button | ✅ | ✅ | ❌ | btnCom | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button5.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | JobSearch | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Variable.4dm) |
| Button6 | NEW REQUEST | 🔘 button | ✅ | ✅ | ❌ | Button6 | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Button6.4dm) |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | JobSearchX | [Variable4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Manufacture/ObjectMethods/Variable4.4dm) |

---

*Generated from form.4DForm*

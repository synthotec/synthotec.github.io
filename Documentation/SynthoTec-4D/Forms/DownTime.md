---
layout : default
title : DownTime
parent : Forms
---
# DownTime [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/DownTime)

📊 **Overview:** 22 Objects | 5 Types | 2 Pages | 16 Events | 22 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/method.4dm) |
| **Object Methods** | 22 |
| **Generated** | 🕐 2025-11-14T16:53:02.397Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (22)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (8)

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
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox1 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/List%20Box1.4dm) |
| ButtonPop | - | 📥 dropdown | ✅ | ✅ | ❌ | vCats | [ButtonPop.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/ButtonPop.4dm) |
| Button | EDIT | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Button.4dm) |
| Button3 | ADD NEW DOWNREASON | 🔘 button | ✅ | ✅ | ❌ | Button3 | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Button3.4dm) |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | vMachines | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/List%20Box2.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | WeekCom | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| 3D Button | MON | 🔘 button | ✅ | ✅ | ❌ | bMON | [3D Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button.4dm) |
| 3D Button1 | TUE | 🔘 button | ✅ | ✅ | ❌ | bTUE | [3D Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button1.4dm) |
| 3D Button2 | WED | 🔘 button | ✅ | ✅ | ❌ | bWED | [3D Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button2.4dm) |
| 3D Button3 | THUR | 🔘 button | ✅ | ✅ | ❌ | bTHUR | [3D Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button3.4dm) |
| 3D Button4 | FRI | 🔘 button | ✅ | ✅ | ❌ | bFRI | [3D Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button4.4dm) |
| 3D Button5 | SAT | 🔘 button | ✅ | ✅ | ❌ | bSAT | [3D Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button5.4dm) |
| 3D Button6 | SUN | 🔘 button | ✅ | ✅ | ❌ | bSUN | [3D Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/3D%20Button6.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vDates | - |
| Button4 | UPDATE LAST 8 DAYS | 🔘 button | ✅ | ✅ | ❌ | Button4 | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Button4.4dm) |
| bUnidentified | SHOW ALL UNIDENTIFIED FOR WEEK | 🔘 button | ✅ | ✅ | ❌ | Button5 | [bUnidentified.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/bUnidentified.4dm) |
| bPrev | PREV | 🔘 button | ✅ | ✅ | ❌ | Button7 | [bPrev.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/bPrev.4dm) |
| bNext | NEXT | 🔘 button | ✅ | ✅ | ❌ | Button7 | [bNext.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/bNext.4dm) |
| Button9 | REFRESH | 🔘 button | ✅ | ✅ | ❌ | Button | [Button9.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Button9.4dm) |
| Button10 | UPDATE SELECTED DATE | 🔘 button | ✅ | ✅ | ❌ | Button4 | [Button10.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Button10.4dm) |
| Check Box | Show Archived Down Reasons | ☑️ checkbox | ✅ | ✅ | ❌ | ShowArchivedDownReasons | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/DownTime/ObjectMethods/Check%20Box.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - Data source for DownTime form
- [DownReasons](../Tables/DownReasons.md) - Data source for DownTime form
- [RealTimeMachines](../Tables/RealTimeMachines.md) - Data source for DownTime form
- [PlanningWheel](../Tables/PlanningWheel.md) - Data source for DownTime form
- [Works_Order](../Tables/Works_Order.md) - Data source for DownTime form
- [RTSUM](../Tables/RTSUM.md) - Data source for DownTime form
- [FieldHistory](../Tables/FieldHistory.md) - Data source for DownTime form
- [WorksOrder](../Tables/WorksOrder.md) - Data source for DownTime form

---

*Generated from form.4DForm*

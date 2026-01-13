---
layout : default
title : DownTimeForm
parent : Classes
---
# DownTimeForm [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/DownTimeForm.4dm)

📊 **Overview:** 23 Properties | 1 Constructor | 20 Functions

## 📝 Description

Form element references

🕐 *Last updated: 2026-01-13T16:04:11.411Z*

---

## 📑 Table of Contents

- [📋 Properties (23)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [updateDayButtonStyles](#updatedaybuttonstyles)
    - [calculateWeekCommencing](#calculateweekcommencing) (1 param) → `$WeekStart : Date`
    - [getDateForDay](#getdateforday) (1 param) → `$Date : Date`
    - [loadMachines](#loadmachines)
    - [loadWeekDates](#loadweekdates)
    - [loadCategories](#loadcategories)
    - [getCurrentDayNumber](#getcurrentdaynumber) → `$DayNumber : Integer`
    - [requery](#requery) (1 param)
    - [requeryReasons](#requeryreasons)
    - [setDate](#setdate) (1 param)
    - [setDayOfWeek](#setdayofweek) (1 param)
    - [setWeekCommencing](#setweekcommencing) (1 param)
    - [nextWeek](#nextweek)
    - [previousWeek](#previousweek)
    - [showUnidentifiedForWeek](#showunidentifiedforweek)
    - [setCategory](#setcategory) (1 param)
    - [toggleShowArchived](#toggleshowarchived)
    - [assignReasonToSelected](#assignreasontoselected) (2 params) → `$Success : Boolean`
    - [getMachineNumber](#getmachinenumber) (1 param) → `$MachineNumber : Integer`
    - [updateWeekDropdown](#updateweekdropdown)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `MondayButton` | `cs.FormObject` | - | Monday day button |
| `TuesdayButton` | `cs.FormObject` | - | Tuesday day button |
| `WednesdayButton` | `cs.FormObject` | - | Wednesday day button |
| `ThursdayButton` | `cs.FormObject` | - | Thursday day button |
| `FridayButton` | `cs.FormObject` | - | Friday day button |
| `SaturdayButton` | `cs.FormObject` | - | Saturday day button |
| `SundayButton` | `cs.FormObject` | - | Sunday day button |
| `SelectedDate` | `Date` | - | Currently selected date for filtering |
| `SelectedWeekCommencing` | `Date` | - | Monday of the selected week |
| `SelectedMachine` | `Object` | - | Selected machine object {Machine: Integer} |
| `SelectedCategory` | `Text` | - | Selected downtime reason category |
| `ShowArchivedReasons` | `Boolean` | - | Whether to show archived reasons |
| `CanAssignDowntime` | `Boolean` | - | Permission to assign downtime reasons |
| `RealTimeSelection` | `cs.RealTimeSelection` | - | Filtered downtime records |
| `DownReasonsSelection` | `cs.DownReasonsSelection` | - | Filtered downtime reasons |
| `SelectedRealTimeEntity` | `cs.RealTimeEntity` | - | Currently selected downtime record |
| `SelectedRealTimeEntities` | `cs.RealTimeSelection` | - | Selected downtime records |
| `SelectedReasonEntity` | `cs.DownReasonsEntity` | - | Currently selected reason |
| `CategoryCollection` | `Collection` | - | List of all categories |
| `WeekCommencingCollection` | `Collection` | - | List of week commencing dates |
| `MachineCollection` | `Collection` | - | List of machine numbers |
| `WeekDropdownObject` | `Object` | - | Week dropdown data object |
| `CategoryDropdownObject` | `Object` | - | Category dropdown data object |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Initialize form element references

---

## Functions {#functions}

### Regular Functions

#### updateDayButtonStyles {#updatedaybuttonstyles}


```4d
Function updateDayButtonStyles
```

Update day button font styles based on selected date

---

#### calculateWeekCommencing {#calculateweekcommencing}


```4d
Function calculateWeekCommencing($Date : Date) -> $WeekStart : Date
```

Calculate the Monday of the current week for a given date

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |

**Returns:** `Date`

---

#### getDateForDay {#getdateforday}


```4d
Function getDateForDay($DayNumber : Integer) -> $Date : Date
```

Calculate the date for a specific day of the week (1=Sunday, 2=Monday, etc.)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DayNumber` | `Integer` | - | - |

**Returns:** `Date`

---

#### loadMachines {#loadmachines}


```4d
Function loadMachines
```

Load all machines that have RealTime records

---

#### loadWeekDates {#loadweekdates}


```4d
Function loadWeekDates
```

Load all weeks from 2016 to current date

---

#### loadCategories {#loadcategories}


```4d
Function loadCategories
```

Load all downtime reason categories

---

#### getCurrentDayNumber {#getcurrentdaynumber}


```4d
Function getCurrentDayNumber -> $DayNumber : Integer
```

Get the current day number (for button styling)

**Returns:** `Integer`

---

#### requery {#requery}


```4d
Function requery($ShowWeekUnidentified : Boolean)
```

Main query method - queries RealTime records based on filters

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ShowWeekUnidentified` | `Boolean` | - | - |

---

#### requeryReasons {#requeryreasons}


```4d
Function requeryReasons
```

Query down reasons based on selected category and archive filter

---

#### setDate {#setdate}


```4d
Function setDate($Date : Date)
```

Set the selected date and requery

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |

---

#### setDayOfWeek {#setdayofweek}


```4d
Function setDayOfWeek($DayNumber : Integer)
```

Set the selected day by day number (1=Sunday, 2=Monday, etc.)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DayNumber` | `Integer` | - | - |

---

#### setWeekCommencing {#setweekcommencing}


```4d
Function setWeekCommencing($WeekStart : Date)
```

Set the selected week commencing date

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$WeekStart` | `Date` | - | - |

---

#### nextWeek {#nextweek}


```4d
Function nextWeek
```

Go to next week

---

#### previousWeek {#previousweek}


```4d
Function previousWeek
```

Go to previous week

---

#### showUnidentifiedForWeek {#showunidentifiedforweek}


```4d
Function showUnidentifiedForWeek
```

Show all unidentified for the week

---

#### setCategory {#setcategory}


```4d
Function setCategory($Category : Text)
```

Set the selected category

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Category` | `Text` | - | - |

---

#### toggleShowArchived {#toggleshowarchived}


```4d
Function toggleShowArchived
```

Toggle show archived reasons

---

#### assignReasonToSelected {#assignreasontoselected}


```4d
Function assignReasonToSelected($RealTimeSelection : cs.RealTimeSelection; $DownReasonID : Integer) -> $Success : Boolean
```

Assign a down reason to selected RealTime records

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeSelection` | `cs.RealTimeSelection` | - | - |
| `$DownReasonID` | `Integer` | - | - |

**Returns:** `Boolean`

---

#### getMachineNumber {#getmachinenumber}


```4d
Function getMachineNumber($RealTimeEntity : cs.RealTimeEntity) -> $MachineNumber : Integer
```

Get the machine number for a RealTime entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeEntity` | `cs.RealTimeEntity` | - | - |

**Returns:** `Integer`

---

#### updateWeekDropdown {#updateweekdropdown}


```4d
Function updateWeekDropdown
```

Update week dropdown object to reflect current selection

---

---

*Generated from DownTimeForm.4dm*

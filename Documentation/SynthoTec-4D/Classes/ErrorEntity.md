---
layout : default
title : ErrorEntity
parent : Classes
---
# ErrorEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ErrorEntity.4dm)

📊 **Overview:** 1 Functions | 6 Getters

## 📝 Description

Entity representing a logged application error, with colour-coded listbox metadata, GitHub issue linking (showing open/closed state), and the ability to send formatted error reports via email or Slack.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.583Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [createGitHubIssue](#creategithubissue)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [FirstOccurrence](#firstoccurrence) 🔍 → `Text`
    - [GitHubIssueLabel](#githubissuelabel) 🔍 → `Text`
    - [GitHubIssueText](#githubissuetext) 🔍 → `Text`
    - [GitHubIssueTitle](#githubissuetitle) 🔍 → `Text`
    - [LastOccurrence](#lastoccurrence) 🔍 → `Text`
    - [ListboxMeta->$ListboxMeta](#listboxmeta->$listboxmeta) 🔍 → `cs.UI.ListBoxMeta`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### createGitHubIssue {#creategithubissue}


```4d
Function createGitHubIssue
```

Creates a new GitHub issue for this error with stack trace, debug info, and call chain details

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### FirstOccurrence {#firstoccurrence}
 `[🔍 get only]`

```4d
Function get FirstOccurrence -> Text
```

Returns formatted date-time string (ISO format) of first error occurrence from error detail selection

**Returns:** `Text`

---

#### GitHubIssueLabel {#githubissuelabel}
 `[🔍 get only]`

```4d
Function get GitHubIssueLabel -> Text
```

Returns the GitHub label string for this error (format: 4DErrorID:ID)

**Returns:** `Text`

---

#### GitHubIssueText {#githubissuetext}
 `[🔍 get only]`

```4d
Function get GitHubIssueText -> Text
```

Returns formatted GitHub issue number text or empty string if no issue linked

**Returns:** `Text`

---

#### GitHubIssueTitle {#githubissuetitle}
 `[🔍 get only]`

```4d
Function get GitHubIssueTitle -> Text
```

Returns the GitHub issue title for this error (format: 4D Error [Code X] Method (Line Y))

**Returns:** `Text`

---

#### LastOccurrence {#lastoccurrence}
 `[🔍 get only]`

```4d
Function get LastOccurrence -> Text
```

Returns formatted date-time string (ISO format) of last error occurrence from error detail selection

**Returns:** `Text`

---

#### ListboxMeta->$ListboxMeta {#listboxmeta->$listboxmeta}
 `[🔍 get only]`

```4d
Function get ListboxMeta->$ListboxMeta -> cs.UI.ListBoxMeta
```

Returns listbox display metadata with colored backgrounds (green/red for suppress, gray/green/amber for GitHub issue)

**Returns:** `cs.UI.ListBoxMeta`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Error](../Tables/Error.md) - ORDA Entity class for Error table

### � Related Classes

- [Error](Error.md) - ORDA DataClass class for Error table

### � Forms

- [Errors](../Forms/Errors.md) - Data source for Errors form

---

*Generated from ErrorEntity.4dm*

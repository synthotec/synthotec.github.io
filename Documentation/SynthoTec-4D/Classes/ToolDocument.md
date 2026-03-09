---
layout : default
title : ToolDocument
parent : Classes
---
# ToolDocument [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolDocument.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for tool document records, providing a UI-based file upload workflow that prompts for a document name and file selection, then saves the document as a BLOB linked to the specified tool.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.732Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [newUsingEntry](#newusingentry) (1 param) → `$ToolDocumentEntity : cs.ToolDocumentEntity` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### newUsingEntry {#newusingentry}
 `[🖥️ local]`

```4d
Function newUsingEntry($ToolsEntity : cs.ToolsEntity) -> $ToolDocumentEntity : cs.ToolDocumentEntity
```

Creates a new tool document by prompting user for document name and file, returning the saved entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `cs.ToolDocumentEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolDocument](../Tables/ToolDocument.md) - ORDA DataClass class for ToolDocument table

### � Forms

- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [ToolDocuments](../Forms/ToolDocuments.md) - Data source for ToolDocuments form

---

*Generated from ToolDocument.4dm*

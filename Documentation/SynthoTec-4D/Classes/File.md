---
layout : default
title : File
parent : Classes
---
# File [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/File.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for file storage records, providing a UI-based upload function that prompts the user to select a file and stores its binary content and metadata as a FileEntity in the database.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.692Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [upload](#upload) → `$FileEntity : cs.FileEntity` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### upload {#upload}
 `[🖥️ local]`

```4d
Function upload -> $FileEntity : cs.FileEntity
```

Prompts user to select a file and uploads it to database as new FileEntity with name, blob, and timestamp

**Returns:** `cs.FileEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [File](../Tables/File.md) - ORDA DataClass class for File table

### � Related Classes

- [FileEntity](FileEntity.md) - ORDA Entity class for File table

### � Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from File.4dm*

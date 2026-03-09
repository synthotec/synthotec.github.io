---
layout : default
title : SqlAccessToken
parent : Classes
---
# SqlAccessToken [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/SqlAccessToken.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for SQL/ODBC access token records, enabling staff to generate hashed-password credentials for connecting to the 4D database via external SQL tools (e.g., Excel Power Query, ODBC drivers).

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.620Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [create](#create) → `$SqlAccessTokenEntity : cs.SqlAccessTokenEntity` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### create {#create}
 `[🖥️ local]`

```4d
Function create -> $SqlAccessTokenEntity : cs.SqlAccessTokenEntity
```

Creates a new SQL access token for current user, generates password, and displays credentials in a dialog

**Returns:** `cs.SqlAccessTokenEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [SqlAccessToken](../Tables/SqlAccessToken.md) - ORDA DataClass class for SqlAccessToken table

---

*Generated from SqlAccessToken.4dm*

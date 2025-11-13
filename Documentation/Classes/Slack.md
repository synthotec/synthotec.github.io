---
layout : default
title : Slack
parent : Classes
---
# Slack

📊 **Overview:** 1 Properties | 1 Constructor | 7 Functions

🕐 *Last updated: 2025-11-13T02:47:33.329Z*

---

## 📑 Table of Contents

### 📋 Properties (1)

- [ChannelID](#channelid) : `Text`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Functions (7):**

- [newHttpRequest](#newhttprequest) (2 params) → `4D.HTTPRequest`
- [createChannel](#createchannel) (1 param) → `Text`
- [setChannelID](#setchannelid) (1 param) → `Boolean`
- [convertBlocks](#convertblocks) (2 params) → `Collection`
- [createMessage](#createmessage) (2 params) → `Text`
- [updateMessage](#updatemessage) (3 params) → `Boolean`
- [deleteMessage](#deletemessage) (1 param) → `Boolean`

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `ChannelID` | `Text` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($ChannelName : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ChannelName` | `Text` | - | - |

---

### ⚙️ Regular Functions

#### newHttpRequest {#newhttprequest}


```4d
Function newHttpRequest($Url : Text; $Options : Object) -> 4D.HTTPRequest
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Url` | `Text` | - | - |
| `$Options` | `Object` | - | - |

**Returns:** `4D.HTTPRequest`

---

#### createChannel {#createchannel}


```4d
Function createChannel($ChannelName : Text) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ChannelName` | `Text` | - | - |

**Returns:** `Text`

---

#### setChannelID {#setchannelid}


```4d
Function setChannelID($ChannelName : Text) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ChannelName` | `Text` | - | - |

**Returns:** `Boolean`

---

#### convertBlocks {#convertblocks}


```4d
Function convertBlocks($HeaderText : Text; $Blocks : Collection) -> Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HeaderText` | `Text` | - | - |
| `$Blocks` | `Collection` | - | - |

**Returns:** `Collection`

---

#### createMessage {#createmessage}


```4d
Function createMessage($HeaderText : Text; $Blocks : Collection) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HeaderText` | `Text` | - | - |
| `$Blocks` | `Collection` | - | - |

**Returns:** `Text`

---

#### updateMessage {#updatemessage}


```4d
Function updateMessage($MessageTimeStamp : Text; $text : Text; $Blocks : Collection) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MessageTimeStamp` | `Text` | - | - |
| `$text` | `Text` | - | - |
| `$Blocks` | `Collection` | - | - |

**Returns:** `Boolean`

---

#### deleteMessage {#deletemessage}


```4d
Function deleteMessage($MessageTimeStamp : Text) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MessageTimeStamp` | `Text` | - | - |

**Returns:** `Boolean`

---

---

*Generated from Slack.4dm*

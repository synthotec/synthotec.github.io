---
layout : default
title : Slack
parent : Classes
---
# Slack [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Slack.4dm)

📊 **Overview:** 1 Properties | 1 Constructor | 7 Functions

## 📝 Description

Creates Slack integration for the specified channel, creating it if it doesn't exist

🕐 *Last updated: 2026-01-13T16:04:13.415Z*

---

## 📑 Table of Contents

- [📋 Properties (1)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [newHttpRequest](#newhttprequest) (2 params) → `4D.HTTPRequest`
    - [createChannel](#createchannel) (1 param) → `Text`
    - [setChannelID](#setchannelid) (1 param) → `Boolean`
    - [convertBlocks](#convertblocks) (2 params) → `$BlocksCollection : Collection`
    - [createMessage](#createmessage) (2 params) → `$MessageTimeStamp : Text`
    - [updateMessage](#updatemessage) (3 params) → `Boolean`
    - [deleteMessage](#deletemessage) (1 param) → `Boolean`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `ChannelID` | `Text` | - | Slack channel ID for posting messages |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($ChannelName : Text)
```

Creates Slack integration for the specified channel, creating it if it doesn't exist

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ChannelName` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### newHttpRequest {#newhttprequest}


```4d
Function newHttpRequest($Url : Text; $Options : Object) -> 4D.HTTPRequest
```

Creates HTTP request with Slack authorization header

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

Creates a new Slack channel and returns its channel ID

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

Finds and sets the channel ID for the specified channel name, returns false if not found

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ChannelName` | `Text` | - | - |

**Returns:** `Boolean`

---

#### convertBlocks {#convertblocks}


```4d
Function convertBlocks($HeaderText : Text; $Blocks : Collection) -> $BlocksCollection : Collection
```

Converts text and collections into Slack block format for rich message formatting

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HeaderText` | `Text` | - | - |
| `$Blocks` | `Collection` | - | - |

**Returns:** `Collection`

---

#### createMessage {#createmessage}


```4d
Function createMessage($HeaderText : Text; $Blocks : Collection) -> $MessageTimeStamp : Text
```

Posts a new message to the Slack channel, returns message timestamp for future updates

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

Updates an existing Slack message by timestamp, returns success status

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

Deletes a Slack message by timestamp, returns success status

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MessageTimeStamp` | `Text` | - | - |

**Returns:** `Boolean`

---

---

*Generated from Slack.4dm*

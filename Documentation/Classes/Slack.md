# Slack

## Table of Contents

### Properties

- [ChannelID](#channelid)

### Functions

- [newHttpRequest()](#newhttprequest)
- [createChannel()](#createchannel)
- [setChannelID()](#setchannelid)
- [convertBlocks()](#convertblocks)
- [createMessage()](#createmessage)
- [updateMessage()](#updatemessage)
- [deleteMessage()](#deletemessage)

---

## Properties

### ChannelID {#channelid}

**Type:** `Text`

---

## Functions

### newHttpRequest {#newhttprequest}


```4d
Function newHttpRequest($Url : Text; $Options : Object) -> 4D.HTTPRequest
```

**Returns:** `4D.HTTPRequest`

---

### createChannel {#createchannel}


```4d
Function createChannel($ChannelName : Text) -> Text
```

**Returns:** `Text`

---

### setChannelID {#setchannelid}


```4d
Function setChannelID($ChannelName : Text) -> Boolean
```

**Returns:** `Boolean`

---

### convertBlocks {#convertblocks}


```4d
Function convertBlocks($HeaderText : Text; $Blocks : Collection) -> Collection
```

**Returns:** `Collection`

---

### createMessage {#createmessage}


```4d
Function createMessage($HeaderText : Text; $Blocks : Collection) -> Text
```

**Returns:** `Text`

---

### updateMessage {#updatemessage}


```4d
Function updateMessage($MessageTimeStamp : Text; $text : Text; $Blocks : Collection) -> Boolean
```

**Returns:** `Boolean`

---

### deleteMessage {#deletemessage}


```4d
Function deleteMessage($MessageTimeStamp : Text) -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from Slack.4dm*
*Last updated: 2025-11-12T17:04:22.452Z*

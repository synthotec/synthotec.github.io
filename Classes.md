---
layout: default
title: Classes
has_children: true
parent: SynthoTec 4D
---
# Classes

## Roadmap

### Code Samples
Add code samples to cover basic usage of all classes and code samples for specific functions where required.

Example for email class:
```4D
var $Email:=cs.Email.new("This is a subject"; "This is the body of the email")
$Email.attachFile($File)
$Email.addTo("jprince@synthotec.com")
var $Success:=$Email.send() //Returns True if successful
```
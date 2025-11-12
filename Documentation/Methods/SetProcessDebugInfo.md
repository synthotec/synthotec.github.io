<!-- Add a collection of values to be sent as a JSON string in any error emails for that process
Pass no parameters to clear the current debug info -->
## Description

## Example

```4d
SetProcessDebugInfo(New collection("Value 1"; 123; Current date))
FunctionThatWillCauseAnError()
SetProcessDebugInfo()
```

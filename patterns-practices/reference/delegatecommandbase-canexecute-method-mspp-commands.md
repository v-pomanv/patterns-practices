---
TOCTitle: CanExecute Method
Title: 'DelegateCommandBase.CanExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.CanExecute(System.Object)'
ms:mtpsurl: 'delegatecommandbase-canexecute-method-mspp-commands.md'
---

# DelegateCommandBase.CanExecute Method

Determines if the command can execute with the provided parameter by invoking the [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bb549151) supplied during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


### Parameters

parameter  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
The parameter to use when determining if this command can execute.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
Returns trueTruetruetrue (True in Visual Basic) if the command can execute. falseFalsefalsefalse (False in Visual Basic) otherwise.

## See Also


[DelegateCommandBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommandbase)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
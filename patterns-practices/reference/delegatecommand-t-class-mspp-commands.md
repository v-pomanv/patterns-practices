---
TOCTitle: 'DelegateCommand(T) Class'
Title: 'DelegateCommand(T) Class (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'T:Microsoft.Practices.Prism.Commands.DelegateCommand\`1'
ms:mtpsurl: 'delegatecommand-t-class-mspp-commands.md'
---

# DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Class

An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates can be attached for [Execute(T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.execute(%600)) and [CanExecute(T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.canexecute(%600)).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

## Type Parameters


T  
Parameter type.

## Remarks

 The constructor deliberately prevents the use of value types. Because ICommand takes an object, having a value type for T would cause unexpected behavior when CanExecute(null) is called during XAML initialization for command bindings. Using default(T) was considered and rejected as a solution because the implementor would not be able to distinguish between a valid and defaulted values.

Instead, callers should support a value type by using a nullable value type and checking the HasValue property before using the Value property.
## Examples

public MyClass() { this.submitCommand = new DelegateCommand&lt;int?&gt;(this.Submit, this.CanSubmit); } private bool CanSubmit(int? customerId) { return (customerId.HasValue && customers.Contains(customerId.Value)); }

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Commands.DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase)
    Microsoft.Practices.Prism.Commands.DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)

## See Also


[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
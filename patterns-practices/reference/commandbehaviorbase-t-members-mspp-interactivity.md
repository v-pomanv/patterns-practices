---
TOCTitle: 'CommandBehaviorBase(T) Members'
Title: 'CommandBehaviorBase(T) Members (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Interactivity.CommandBehaviorBase\`1'
ms:mtpsurl: 'commandbehaviorbase-t-members-mspp-interactivity.md'
---

# CommandBehaviorBase&lt;T&gt; Members

The [CommandBehaviorBase&lt;T&gt;](https://msdn.microsoft.com/en-us/library/dn736144(v=pandp.50)) type exposes the following members.

## Constructors

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td>CommandBehaviorBase&lt;T&gt;</td>
<td><div class="summary">
Constructor specifying the target object.
</div></td>
</tr>
</tbody>
</table>

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736267(v=pandp.50)">ExecuteCommand</a></td>
<td><div class="summary">
Executes the command, if it's set, providing the <a href="https://msdn.microsoft.com/en-us/library/dn683970(v=pandp.50)">CommandParameter</a>
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736286(v=pandp.50)">UpdateEnabledState</a></td>
<td><div class="summary">
Updates the target object's IsEnabled property based on the commands ability to execute.
</div></td>
</tr>
</tbody>
</table>

## Properties

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public property](/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736180(v=pandp.50)">Command</a></td>
<td><div class="summary">
Corresponding command to be execute and monitored for <a href="http://msdn.microsoft.com/en-us/library/ms523106">CanExecuteChanged</a>
</div></td>
</tr>
<tr class="even">
<td>![Public property](/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683970(v=pandp.50)">CommandParameter</a></td>
<td><div class="summary">
The parameter to supply the command during execution
</div></td>
</tr>
<tr class="odd">
<td>![Protected property](/images/protproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736268(v=pandp.50)">TargetObject</a></td>
<td><div class="summary">
Object to which this behavior is attached.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CommandBehaviorBase&lt;T&gt; Class](https://msdn.microsoft.com/en-us/library/dn736144(v=pandp.50))

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))
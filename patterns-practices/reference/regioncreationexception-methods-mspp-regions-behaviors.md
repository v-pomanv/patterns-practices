---
TOCTitle: RegionCreationException Methods
Title: 'RegionCreationException Methods (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.Behaviors.RegionCreationException'
ms:mtpsurl: 'regioncreationexception-methods-mspp-regions-behaviors.md'
---


# RegionCreationException Methods

The [RegionCreationException](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors) type exposes the following members.

## Methods

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetBaseException](http://msdn.microsoft.com/en-us/library/49kcee3b)</td>
<td><div class="summary">
When overridden in a derived class, returns the [Exception](/http://msdn2.microsoft.com/en-us/library/c18k6c59) that is the root cause of one or more subsequent exceptions.
</div>
(Inherited from [Exception](/http://msdn2.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetObjectData](http://msdn.microsoft.com/en-us/library/fwb1489e)</td>
<td><div class="summary">
When overridden in a derived class, sets the [SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e) with information about the exception.
</div>
(Inherited from [Exception](/http://msdn2.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/44zb316t)</td>
<td><div class="summary">
Gets the runtime type of the current instance.
</div>
(Inherited from [Exception](/http://msdn2.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/es4y6f7e)</td>
<td><div class="summary">
Creates and returns a string representation of the current exception.
</div>
(Inherited from [Exception](/http://msdn2.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
</tbody>
</table>

## Extension Methods


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[GetRootException](/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp)</td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div>
(Defined by [ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp).)</td>
</tr>
</tbody>
</table>

## See Also

[RegionCreationException Class](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
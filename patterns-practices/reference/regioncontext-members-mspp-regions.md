---
TOCTitle: RegionContext Members
Title: 'RegionContext Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionContext'
ms:mtpsurl: 'regioncontext-members-mspp-regions.md'
---

# RegionContext Members

The [RegionContext](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regioncontext) type exposes the following members.

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
<td>![Public method](/images/public-method.gif)![Static member](/images/static.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regioncontext.getobservablecontext(system.windows.dependencyobject)">GetObservableContext</a></td>
<td><div class="summary">
Returns an <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.observableobject%601">ObservableObject&lt;(Of &lt;(T&gt;)&gt;)</a> wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.views">Views</a> collection by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.bindregioncontexttodependencyobjectbehavior">BindRegionContextToDependencyObjectBehavior</a> Behavior. The RegionContext will also be set to the control that hosts the Region, by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior">SyncRegionContextWithHostBehavior</a> Behavior. If the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.observableobject%601">ObservableObject&lt;(Of &lt;(T&gt;)&gt;)</a> wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.
</div></td>
</tr>
</tbody>
</table>

## See Also


[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult))'
Title: 'RegionNavigationService.RequestNavigate Method (Uri, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationService.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'regionnavigationservice-requestnavigate-method-mspp-regions.md'
---

# RegionNavigationService.RequestNavigate Method (Uri, Action&lt;NavigationResult&gt;)

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void RequestNavigate(
	Uri target,
	Action<NavigationResult> navigationCallback
)
```

### Parameters

*target*  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)  
The target.

*navigationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)&gt;  
A callback to execute when the navigation request is completed.

### Implements

[INavigateAsync.RequestNavigate(Uri, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-mspp-regions)

# RegionNavigationService.RequestNavigate Method (Uri, Action(Of NavigationResult))

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub RequestNavigate ( 
	target As Uri,
	navigationCallback As Action(Of NavigationResult)
)
```

### Parameters

*target*  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)  
The target.

*navigationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions))  
A callback to execute when the navigation request is completed.

### Implements

[INavigateAsync.RequestNavigate(Uri, Action(Of NavigationResult))](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-mspp-regions)

## See Also

[RegionNavigationService Class](/patterns-practices/reference/regionnavigationservice-class-mspp-regions)  
[RegionNavigationService Members](/patterns-practices/reference/regionnavigationservice-members-mspp-regions)  
[RequestNavigate Overload](/patterns-practices/reference/regionnavigationservice-requestnavigate-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  
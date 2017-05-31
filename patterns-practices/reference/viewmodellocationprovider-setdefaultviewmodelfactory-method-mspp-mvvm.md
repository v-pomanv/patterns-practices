---
TOCTitle: SetDefaultViewModelFactory Method
Title: 'ViewModelLocationProvider.SetDefaultViewModelFactory Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider.SetDefaultViewModelFactory(System.Func{System.Type,System.Object})'
ms:mtpsurl: 'viewmodellocationprovider-setdefaultviewmodelfactory-method-mspp-mvvm.md'
---

# ViewModelLocationProvider.SetDefaultViewModelFactory Method

Sets the default view model factory.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static void SetDefaultViewModelFactory(
	Func<Type, Object> viewModelFactory
)
```


*viewModelFactory*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[Type](http://msdn.microsoft.com/en-us/library/42892f65), [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

The view model factory.

```VB
'Declaration
Public Shared Sub SetDefaultViewModelFactory ( 
	viewModelFactory As Func(Of Type, Object)
)
```


*viewModelFactory*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of([Type](http://msdn.microsoft.com/en-us/library/42892f65), [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

The view model factory.

## See Also


[ViewModelLocationProvider Members](/patterns-practices/reference/viewmodellocationprovider-members-mspp-mvvm)

[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
---
TOCTitle: 'BackgroundEventSubscription(TPayload) Constructor'
Title: 'BackgroundEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference)'
ms:mtpsurl: 'backgroundeventsubscription-tpayload-constructor-mspp-pubsubevents.md'
---

# BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Constructor

Creates a new instance of [BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](/patterns-practices/reference/mspp-mvvm-namespace.backgroundeventsubscription%601).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


### Parameters

actionReference  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](/patterns-practices/reference/mspp-mvvm-namespace.idelegatereference)
A reference to a delegate of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8).

filterReference  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](/patterns-practices/reference/mspp-mvvm-namespace.idelegatereference)
A reference to a delegate of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz).

## Exceptions


| Exception                                                                             | Condition                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | When actionReference or are nullNothingnullptra null reference (Nothing in Visual Basic).                                                                                                                                                                                      |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | When the target of actionReference is not of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of filterReference is not of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz). |

## See Also


[BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
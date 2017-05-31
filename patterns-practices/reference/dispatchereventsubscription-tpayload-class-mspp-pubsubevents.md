---
TOCTitle: 'DispatcherEventSubscription(TPayload) Class'
Title: 'DispatcherEventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-class-mspp-pubsubevents.md'
---

# DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class

Extends [EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601) to invoke the [Action](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601.action) delegate in a specific [SynchronizationContext](http://msdn.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

## Type Parameters


TPayload  
The type to use for the generic [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.PubSubEvents.EventSubscription](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601)&lt;(Of &lt;(TPayload&gt;)&gt;)
    Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)

## See Also


[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
---
TOCTitle: InternalPublish Method
Title: 'EventBase.InternalPublish Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.InternalPublish(System.Object[])'
ms:mtpsurl: 'eventbase-internalpublish-method-mspp-pubsubevents.md'
---

# EventBase.InternalPublish Method

Calls all the execution strategies exposed by the list of [IEventSubscription](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


### Parameters

arguments  
Type: array&lt;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;
The arguments that will be passed to the listeners.

## Remarks

Before executing the strategies, this class will prune all the subscribers from the list that return a nullNothingnullptra null reference (Nothing in Visual Basic)[Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) when calling the [GetExecutionStrategy()()()](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription.getexecutionstrategy) method.

## See Also


[EventBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
---
TOCTitle: InvokeAction Method
Title: 'DispatcherEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-invokeaction-method-mspp-pubsubevents.md'
---

# DispatcherEventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

### Syntax
```C#
public override void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```

### Parameters

_action_
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)&gt;
The action to execute.

_argument_  
Type: [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)
The payload to pass action while invoking it.


Invokes the specified [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

### Syntax
```VB
'Declaration
Public Overrides Sub InvokeAction ( 
	action As Action(Of TPayload),
	argument As TPayload
)
)
```

### Parameters

_action_
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents))
The action to execute.

_argument_  
Type: [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)

DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;).InvokeAction Method

Invokes the specified [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public override void InvokeAction( Action&lt;TPayload&gt; action, TPayload argument )Public Overrides Sub InvokeAction ( action As Action(Of TPayload), argument As TPayload )

### Parameters

action  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](/patterns-practices/reference/mspp-mvvm-namespace.dispatchereventsubscription%601)&gt;)&gt;)
The action to execute.

argument  
Type: [TPayload](/patterns-practices/reference/mspp-mvvm-namespace.dispatchereventsubscription%601)

The payload to pass action while invoking it.


[DispatcherEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](/patterns-practices/reference/mspp-mvvm-namespace.dispatchereventsubscription%601)

DispatcherEventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
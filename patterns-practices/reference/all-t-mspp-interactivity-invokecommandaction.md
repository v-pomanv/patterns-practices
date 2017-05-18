---
TOCTitle: InvokeCommandAction Members
Title: 'InvokeCommandAction Members (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Interactivity.InvokeCommandAction'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn741417(v=PandP.50)'
---

Prism Class Library

InvokeCommandAction Members
===========================

Include Protected Members
Include Inherited Members

The [InvokeCommandAction](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.invokecommandaction) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[InvokeCommandAction](https://msdn.microsoft.com/m:microsoft.practices.prism.interactivity.invokecommandaction.)
Initializes a new instance of the [InvokeCommandAction](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.invokecommandaction) class

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[ApplyAnimationClock(DependencyProperty, AnimationClock)](http://msdn2.microsoft.com/en-us/library/ms590752)
Applies an [AnimationClock](http://msdn2.microsoft.com/en-us/library/ms618394) to the specified [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318). If the property is already animated, the [SnapshotAndReplace](http://msdn2.microsoft.com/en-us/library/ms596029) handoff behavior is used.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)](http://msdn2.microsoft.com/en-us/library/ms590755)
Applies an [AnimationClock](http://msdn2.microsoft.com/en-us/library/ms618394) to the specified [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318). If the property is already animated, the specified [HandoffBehavior](http://msdn2.microsoft.com/en-us/library/ms596029) is used.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
Attach
(Inherited from TriggerAction.)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[BeginAnimation(DependencyProperty, AnimationTimeline)](http://msdn2.microsoft.com/en-us/library/ms590761)
Applies an animation to the specified [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318). The animation is started when the next frame is rendered. If the specified property is already animated, the [SnapshotAndReplace](http://msdn2.microsoft.com/en-us/library/ms596029) handoff behavior is used.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)](http://msdn2.microsoft.com/en-us/library/ms590757)
Applies an animation to the specified [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318). The animation is started when the next frame is rendered. If the specified property is already animated, the specified [HandoffBehavior](http://msdn2.microsoft.com/en-us/library/ms596029) is used.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[CheckAccess](http://msdn2.microsoft.com/en-us/library/ms591167)
Determines whether the calling thread has access to this [DispatcherObject](http://msdn2.microsoft.com/en-us/library/ms615925).

(Inherited from [DispatcherObject](http://msdn2.microsoft.com/en-us/library/ms615925).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[ClearValue(DependencyProperty)](http://msdn2.microsoft.com/en-us/library/ms597464)
Clears the local value of a property. The property to be cleared is specified by a [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318) identifier.

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[ClearValue(DependencyPropertyKey)](http://msdn2.microsoft.com/en-us/library/ms597465)
Clears the local value of a read-only property. The property to be cleared is specified by a [DependencyPropertyKey](http://msdn2.microsoft.com/en-us/library/ms602348).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[Clone](http://msdn2.microsoft.com/en-us/library/ms590765)
Creates a modifiable clone of this [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388), making deep copies of this object's values. When copying this object's dependency properties, this method copies resource references and data bindings (but they might no longer resolve) but not animations or their current values.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[CloneCore](http://msdn2.microsoft.com/en-us/library/ms557724)
Makes the instance a clone (deep copy) of the specified [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) using base (non-animated) property values.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[CloneCurrentValue](http://msdn2.microsoft.com/en-us/library/ms557727)
Creates a modifiable clone (deep copy) of the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) using its current values.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[CloneCurrentValueCore](http://msdn2.microsoft.com/en-us/library/ms557729)
Makes the instance a modifiable clone (deep copy) of the specified [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) using current property values.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[CoerceValue](http://msdn2.microsoft.com/en-us/library/ms597466)
Coerces the value of the specified dependency property. This is accomplished by invoking any [CoerceValueCallback](http://msdn2.microsoft.com/en-us/library/ms589135) function specified in property metadata for the dependency property as it exists on the calling [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[CreateInstance](http://msdn2.microsoft.com/en-us/library/ms557732)
Initializes a new instance of the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) class.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
CreateInstanceCore
(Inherited from TriggerAction.)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
Detach
(Inherited from TriggerAction.)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/aa345743)
Determines whether a provided [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309) is equivalent to the current [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[Freeze](http://msdn2.microsoft.com/en-us/library/ms557735)
Makes the current object unmodifiable and sets its [IsFrozen](http://msdn2.microsoft.com/en-us/library/ms600924) property to true.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[FreezeCore](http://msdn2.microsoft.com/en-us/library/ms590769)
Makes this [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388) object unmodifiable or determines whether it can be made unmodifiable.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetAnimationBaseValue](http://msdn2.microsoft.com/en-us/library/ms590770)
Returns the non-animated value of the specified [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318).

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetAsFrozen](http://msdn2.microsoft.com/en-us/library/ms557740)
Creates a frozen copy of the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734), using base (non-animated) property values. Because the copy is frozen, any frozen sub-objects are copied by reference.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[GetAsFrozenCore](http://msdn2.microsoft.com/en-us/library/ms557742)
Makes the instance a frozen clone of the specified [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) using base (non-animated) property values.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetCurrentValueAsFrozen](http://msdn2.microsoft.com/en-us/library/ms557743)
Creates a frozen copy of the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) using current property values. Because the copy is frozen, any frozen sub-objects are copied by reference.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[GetCurrentValueAsFrozenCore](http://msdn2.microsoft.com/en-us/library/ms557745)
Makes the current instance a frozen clone of the specified [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734). If the object has animated dependency properties, their current animated values are copied.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/aa345744)
Gets a hash code for this [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetLocalValueEnumerator](http://msdn2.microsoft.com/en-us/library/ms597467)
Creates a specialized enumerator for determining which dependency properties have locally set values on this [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[GetValue](http://msdn2.microsoft.com/en-us/library/ms597469)
Returns the current effective value of a dependency property on this instance of a [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[InvalidateProperty](http://msdn2.microsoft.com/en-us/library/ms597470)
Re-evaluates the effective value for the specified dependency property

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[Invoke](https://msdn.microsoft.com/m:microsoft.practices.prism.interactivity.invokecommandaction.invoke(system.object))
Executes the command

(Overrides TriggerActionInvoke(Object).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[InvokeAction](https://msdn.microsoft.com/m:microsoft.practices.prism.interactivity.invokecommandaction.invokeaction(system.object))
Public wrapper of the Invoke method.

![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[OnAttached](https://msdn.microsoft.com/m:microsoft.practices.prism.interactivity.invokecommandaction.onattached)
This method is called after the behavior is attached. It updates the command behavior's Command and CommandParameter properties if necessary.

(Overrides TriggerActionOnAttached()()().)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[OnChanged](http://msdn2.microsoft.com/en-us/library/ms557749)
Called when the current [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) object is modified.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[OnDetaching](https://msdn.microsoft.com/m:microsoft.practices.prism.interactivity.invokecommandaction.ondetaching)
Sets the Command and CommandParameter properties to null.

(Overrides TriggerActionOnDetaching()()().)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[OnFreezablePropertyChanged(DependencyObject, DependencyObject)](http://msdn2.microsoft.com/en-us/library/aa345824)
Ensures that appropriate context pointers are established for a [DependencyObjectType](http://msdn2.microsoft.com/en-us/library/ms589310) data member that has just been set.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[OnFreezablePropertyChanged(DependencyObject, DependencyObject, DependencyProperty)](http://msdn2.microsoft.com/en-us/library/aa345825)
This member supports the Windows Presentation Foundation (WPF) infrastructure and is not intended to be used directly from your code.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[OnPropertyChanged](http://msdn2.microsoft.com/en-us/library/ms557754)
Overrides the [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309) implementation of [OnPropertyChanged(DependencyPropertyChangedEventArgs)](http://msdn2.microsoft.com/en-us/library/ms597471) to also invoke any [Changed](http://msdn2.microsoft.com/en-us/library/ms596566) handlers in response to a changing dependency property of type [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[ReadLocalValue](http://msdn2.microsoft.com/en-us/library/ms597472)
Returns the local value of a dependency property, if it exists.

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[ReadPreamble](http://msdn2.microsoft.com/en-us/library/ms557756)
Ensures that the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) is being accessed from a valid thread. Inheritors of [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) must call this method at the beginning of any API that reads data members that are not dependency properties.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[SetCurrentValue](http://msdn2.microsoft.com/en-us/library/dd549644)
Sets the value of a dependency property without changing its value source.

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[SetValue(DependencyProperty, Object)](http://msdn2.microsoft.com/en-us/library/ms597473)
Sets the local value of a dependency property, specified by its dependency property identifier.

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[SetValue(DependencyPropertyKey, Object)](http://msdn2.microsoft.com/en-us/library/ms597474)
Sets the local value of a read-only dependency property, specified by the [DependencyPropertyKey](http://msdn2.microsoft.com/en-us/library/ms602348) identifier of the dependency property.

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[ShouldSerializeProperty](http://msdn2.microsoft.com/en-us/library/ms597475)
Returns a value that indicates whether serialization processes should serialize the value for the provided dependency property.

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubmethod(en-us,PandP.50).gif "Public method")
[VerifyAccess](http://msdn2.microsoft.com/en-us/library/ms591169)
Enforces that the calling thread has access to this [DispatcherObject](http://msdn2.microsoft.com/en-us/library/ms615925).

(Inherited from [DispatcherObject](http://msdn2.microsoft.com/en-us/library/ms615925).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[WritePostscript](http://msdn2.microsoft.com/en-us/library/ms557762)
Raises the [Changed](http://msdn2.microsoft.com/en-us/library/ms596566) event for the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) and invokes its [OnChanged()()()](http://msdn2.microsoft.com/en-us/library/ms557749) method. Classes that derive from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) should call this method at the end of any API that modifies class members that are not stored as dependency properties.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.protmethod(en-us,PandP.50).gif "Protected method")
[WritePreamble](http://msdn2.microsoft.com/en-us/library/ms557763)
Verifies that the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) is not frozen and that it is being accessed from a valid threading context. [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) inheritors should call this method at the beginning of any API that writes to data members that are not dependency properties.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)

Fields
------

<span id="fieldTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn741417.pubfield(en-us,PandP.50).gif "Public field")![](https://msdn.microsoft.com/en-us/Dn741417.static(en-us,PandP.50).gif "Static member")
[CommandParameterProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.interactivity.invokecommandaction.commandparameterproperty)
Dependency property identifying the command parameter to supply on command execution.

![](https://msdn.microsoft.com/en-us/Dn741417.pubfield(en-us,PandP.50).gif "Public field")![](https://msdn.microsoft.com/en-us/Dn741417.static(en-us,PandP.50).gif "Static member")
[CommandProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.interactivity.invokecommandaction.commandproperty)
Dependency property identifying the command to execute when invoked.

![](https://msdn.microsoft.com/en-us/Dn741417.pubfield(en-us,PandP.50).gif "Public field")![](https://msdn.microsoft.com/en-us/Dn741417.static(en-us,PandP.50).gif "Static member")
[TriggerParameterPathProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.interactivity.invokecommandaction.triggerparameterpathproperty)
Dependency property identifying the TriggerParameterPath to be parsed to identify the child property of the trigger parameter to be used as the command parameter.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn741417.protproperty(en-us,PandP.50).gif "Protected property")
AssociatedObject
(Inherited from TriggerAction&lt;(Of &lt;([UIElement](http://msdn2.microsoft.com/en-us/library/ms590078)&gt;)&gt;).)
![](https://msdn.microsoft.com/en-us/Dn741417.protproperty(en-us,PandP.50).gif "Protected property")
AssociatedObjectTypeConstraint
(Inherited from TriggerAction&lt;(Of &lt;([UIElement](http://msdn2.microsoft.com/en-us/library/ms590078)&gt;)&gt;).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[CanFreeze](http://msdn2.microsoft.com/en-us/library/ms600923)
Gets a value that indicates whether the object can be made unmodifiable.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[Command](https://msdn.microsoft.com/p:microsoft.practices.prism.interactivity.invokecommandaction.command)
Gets or sets the command to execute when invoked.

![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[CommandParameter](https://msdn.microsoft.com/p:microsoft.practices.prism.interactivity.invokecommandaction.commandparameter)
Gets or sets the command parameter to supply on command execution.

![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[DependencyObjectType](http://msdn2.microsoft.com/en-us/library/ms600674)
Gets the [DependencyObjectType](http://msdn2.microsoft.com/en-us/library/ms589310) that wraps the CLR type of this instance. 

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[Dispatcher](http://msdn2.microsoft.com/en-us/library/ms605656)
Gets the [Dispatcher](http://msdn2.microsoft.com/en-us/library/ms615907) this [DispatcherObject](http://msdn2.microsoft.com/en-us/library/ms615925) is associated with.

(Inherited from [DispatcherObject](http://msdn2.microsoft.com/en-us/library/ms615925).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[HasAnimatedProperties](http://msdn2.microsoft.com/en-us/library/ms616442)
Gets a value that indicates whether one or more [AnimationClock](http://msdn2.microsoft.com/en-us/library/ms618394) objects is associated with any of this object's dependency properties.

(Inherited from [Animatable](http://msdn2.microsoft.com/en-us/library/ms618388).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
IsEnabled
(Inherited from TriggerAction.)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[IsFrozen](http://msdn2.microsoft.com/en-us/library/ms600924)
Gets a value that indicates whether the object is currently modifiable.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[IsSealed](http://msdn2.microsoft.com/en-us/library/ms600677)
Gets a value that indicates whether this instance is currently sealed (read-only).

(Inherited from [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).)
![](https://msdn.microsoft.com/en-us/Dn741417.pubproperty(en-us,PandP.50).gif "Public property")
[TriggerParameterPath](https://msdn.microsoft.com/p:microsoft.practices.prism.interactivity.invokecommandaction.triggerparameterpath)
Gets or sets the TriggerParameterPath value.

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn741417.pubevent(en-us,PandP.50).gif "Public event")
[Changed](http://msdn2.microsoft.com/en-us/library/ms596566)
Occurs when the [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734) or an object it contains is modified.

(Inherited from [Freezable](http://msdn2.microsoft.com/en-us/library/ms602734).)

See Also
--------

<span id="seeAlsoToggle"></span>
[InvokeCommandAction Class](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.invokecommandaction)

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.interactivity)
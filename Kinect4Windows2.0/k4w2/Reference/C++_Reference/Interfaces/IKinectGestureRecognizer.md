IKinectGestureRecognizer Interface  
==================================  

Provides gesture and manipulation recognition, and settings. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>interface IKinectGestureRecognizer : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectGestureRecognizer** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/CompleteGesture_Method.md">CompleteGesture</a></td>
<td align="left">Causes the gesture recognizer to finalize an interaction.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get_AutoProcessInertia.md">get_AutoProcessInertia</a></td>
<td align="left">Gets a value that indicates whether manipulations during inertia are generated automatically. If false, the app is expected to call ProcessInertia periodically.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get_BoundingRect_Method.md">get_BoundingRect</a></td>
<td align="left">Gets the bounds of a tappable gesture recognizer.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get_GestureSettings_Method.md">get_GestureSettings</a></td>
<td align="left">Sets a value that indicates the gesture and manipulation settings supported by an application.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get.md">get_InertiaTranslationDeceleration</a></td>
<td align="left">Gets or sets a value that indicates the rate of deceleration from the start of inertia to the end of inertia (when the translation manipulation is complete).</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get.md">get_InertiaTranslationDisplacement</a></td>
<td align="left">Gets or sets a value that indicates the relative change in the screen location of an object from the start of inertia to the end of inertia (when the translation manipulation is complete).</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets a value that indicates whether an interaction is being processed.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/get_IsInertial_Method.md">get_IsInertial</a></td>
<td align="left">Gets a value that indicates whether a manipulation is still being processed during inertia (no input points are active).</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/ProcessDownEvent_Method.md">ProcessDownEvent</a></td>
<td align="left">Processes pointer input and raises the <a href="">IKinectGestureRecognizer</a> events appropriate to a pointer down action for the gestures and manipulations specified by the object's gesture settings.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/ProcessInertia_Method.md">ProcessInertia</a></td>
<td align="left">Performs inertia calculations and raises the various inertia events.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/ProcessMoveEvents_Method.md">ProcessMoveEvents</a></td>
<td align="left">Processes pointer input and raises the <a href="">IKinectGestureRecognizer</a> events appropriate to a pointer move action for the gestures and manipulations specified by the object's gesture settings.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/ProcessUpEvent_Method.md">ProcessUpEvent</a></td>
<td align="left">Processes pointer input and raises the <a href="">IKinectGestureRecognizer</a> events appropriate to a pointer up action for the gestures and manipulations specified by the object's gesture settings.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/put_AutoProcessInertia.md">put_AutoProcessInertia</a></td>
<td align="left">Gets or sets a value that indicates whether manipulations during inertia are generated automatically. If false, the app is expected to call ProcessInertia periodically.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/put_BoundingRect_Method.md">put_BoundingRect</a></td>
<td align="left">Sets the bounds of a tappable gesture recognizer.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/put_GestureSettings_Method.md">put_GestureSettings</a></td>
<td align="left">Sets a value that indicates the gesture and manipulation settings supported by an application.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/put.md">put_InertiaTranslationDeceleration</a></td>
<td align="left">Sets a value that indicates the rate of deceleration from the start of inertia to the end of inertia (when the translation manipulation is complete).</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/put.md">put_InertiaTranslationDisplacement</a></td>
<td align="left">Sets a value that indicates the relative change in the screen location of an object from the start of inertia to the end of inertia (when the translation manipulation is complete).</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterManipulationComple.md">RegisterManipulationCompletedHandler</a></td>
<td align="left">Registers the handler for the selection tapped event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterManipulationInerti.md">RegisterManipulationInertiaStartingHandler</a></td>
<td align="left">Registers the handler for the manipulation inertia starting event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterManipulationStarte.md">RegisterManipulationStartedHandler</a></td>
<td align="left">Registers the handler for the manipulation stated event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterManipulationUpdate.md">RegisterManipulationUpdatedHandler</a></td>
<td align="left">Registers the handler for the manipulation updated event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterSelectionHoldingHa.md">RegisterSelectionHoldingHandler</a></td>
<td align="left">Registers the handler for the selection holding event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterSelectionPressingC.md">RegisterSelectionPressingCompletedHandler</a></td>
<td align="left">Registers the handler for the selection pressing completed event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterSelectionPressingS.md">RegisterSelectionPressingStartedHandler</a></td>
<td align="left">Registers the handler for the selection pressing started event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterSelectionPressingU.md">RegisterSelectionPressingUpdatedHandler</a></td>
<td align="left">Registers the handler for the pressing updated event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/RegisterSelectionTappedHan.md">RegisterSelectionTappedHandler</a></td>
<td align="left">Registers the handler for the selection tapped event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterManipulationComp.md">UnregisterManipulationCompletedHandler</a></td>
<td align="left">Unregisters the handler for the manipulation completed event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterManipulationIner.md">UnregisterManipulationInertiaStartingHandler</a></td>
<td align="left">Unregisters the handler for the manipulation intertia starting event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterManipulationStar.md">UnregisterManipulationStartedHandler</a></td>
<td align="left">Unregisters the handler for the manipulation started event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterManipulationUpda.md">UnregisterManipulationUpdatedHandler</a></td>
<td align="left">Unregisters the handler for the manipulation updated event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterSelectionHolding.md">UnregisterSelectionHoldingHandler</a></td>
<td align="left">Unregisters the handler for the selection holding event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterSelectionPressin.md">UnregisterSelectionPressingCompletedHandler</a></td>
<td align="left">Unregisters the handler for the pressing completed event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterSelectionPressin.md">UnregisterSelectionPressingStartedHandler</a></td>
<td align="left">Unregisters the handler for the pressing started event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterSelectionPressin.md">UnregisterSelectionPressingUpdatedHandler</a></td>
<td align="left">Unregisters the handler for the pressing updated event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizer/Methods/UnregisterSelectionTappedH.md">UnregisterSelectionTappedHandler</a></td>
<td align="left">Unregisters the handler for the selection tapped event.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IKinectGestureRecognizer Interface
RLTitle : IKinectGestureRecognizer Interface
KeywordK : IKinectGestureRecognizer interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectGestureRecognizer
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer
KeywordA : T:Microsoft.Kinect.kinect.IKinectGestureRecognizer
AssetID : T:Microsoft.Kinect.kinect.IKinectGestureRecognizer
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->

FaceFrameSource.PropertyChanged Event  
=====================================  

Occurs when a property of the [FaceFrameSource](../../FaceFrameSource_Class.md) changes. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
event <a href="../../../Data/PropertyChangedEventHandler.md">PropertyChangedEventHandler</a>^ PropertyChanged {  
         EventRegistrationToken add (<a href="../../../Data/PropertyChangedEventHandler.md">PropertyChangedEventHandler</a>^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public event <a href="../../../Data/PropertyChangedEventHandler.md">PropertyChangedEventHandler</a> PropertyChanged</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>function onPropertyChanged(eventArgs) { /* Your code */ }  

// addEventListener syntax  
faceFrameSource.addEventListener(&quot;propertychanged&quot;, onPropertyChanged);  
faceFrameSource.removeEventListener(&quot;propertychanged&quot;, onPropertyChanged);  

- or -  

faceFrameSource.onpropertychanged = onPropertyChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EU"></span>

See also  
========  

<span id="ID4EW"></span>
#### Reference  

[FaceFrameSource Class](../../FaceFrameSource_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PropertyChanged Event
RLTitle : FaceFrameSource.PropertyChanged Event
KeywordK : PropertyChanged event
KeywordK : FaceFrameSource.PropertyChanged event
KeywordF : Microsoft.Kinect.Face.FaceFrameSource.PropertyChanged
KeywordF : FaceFrameSource.PropertyChanged
KeywordF : PropertyChanged
KeywordF : Microsoft.Kinect.Face.FaceFrameSource.PropertyChanged
KeywordA : E:Microsoft.Kinect.Face.FaceFrameSource.PropertyChanged
AssetID : E:Microsoft.Kinect.Face.FaceFrameSource.PropertyChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameSource.PropertyChanged
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->

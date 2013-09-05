AngularFaces
============

AngularFaces is a JSF library making it easy to integrate AngularJS code. Currently, it offers
<ul>
<li>&lt;a:body&gt;. You need this component to activate AngularJS in a JSF page.</li>
<li>&lt;a:inputText&gt;. This is an angularized and enhanced version of the standard PrimeFaces inputText component. It also draws a label and a &lt;h:message&gt; tag automatically.</li>
<li>&lt;a:selectBooleanCheckbox&gt;. This is an angularized and enhancde version of the standard PrimeFaces checkbox component. It also draws a label and a &lt;h:message&gt; tag automatically.</li>
<li>&lt;a:selectOneMenu&gt;. This is an angularized and enhanced version of the standard PrimeFaces drop-down menu component. It also draws a label and a &lt;h:message&gt; tag automatically.</li>
<li>&lt;a:commandButton&gt;. This derivative of a PrimeFaces command button re-activates the AngularJS framework after an AJAX request. It's also disabled if one of the form's AngularJS validations is violated.
It can call an AngularJS model function prior to the request, and you can provide a Javascript function preventing the server request conditionally.</li>
<li>&lt;a:angularButton&gt;. This button has nothing to do with JSF. Instead, it calls an AngularJS controller function.</li>
<li>&lt;a:dataTable&gt; This is the component I'm currently working on. At present, it's able to display simple data tables with AngularJS support. The table may contain editable fields.</li>
<li>&lt;a:slider&gt; The AngularFaces Slider component is a PrimeFaces Slider updating the Angular model when the slider is moved. It also reads the @Min and @Max annotations of the associated input field to get default values of the sliders range. Other than its PrimeFaces counterpart, a:slider can be combined with comboboxes provided they have numeric values.<li>
</ul> 

To learn more about AngularFaces, have a look at http://www.beyondjava.net/blog/angularfaces-jsf-beyond-ajax/.

There's also a tiny tutorial on http://www.beyondjava.net/blog/started-angularfaces/.

Legal disclaimer:
This is a very early version. Nonetheless it may already be useful. Use at own risk.
<h1>Rough ideas for new functionality in HTML6</h1>

<h2>Why?</h2>

<p>There are a number of UI interactions that have become "standard" and it's time that HTML supported more. For example HTML5 brought us the new <code>date</code> input field that utilises a browser based date picker, a function that was previously only achievable using javascript. There's no reason why this canot be extended even further.</p>

<h3>Advantages</h3>
<ul>
<li>less reliance on Javascript for basic/common UI functions</li>
<li>less page weight (faster browsing on slow connections)</li>
<li>faster development for both web and HTML5 apps</li>
<li>enables authors to use more (improved?) UI enhancements without developer intervention</li>
</ul>

<h2>Simple show/hide/toggle</h2>
<p>Possibly using an attribute in a tag to trigger an action on another tag with matching ID</p>
<h3>Example</h3>
<pre>
<code>
&lt;h3 toggle="tog1"&gt;+ Parent&lt;/h3&gt;
&lt;p id="tog1" state="toggle">Toggled content...&lt;/p&gt;
</code>
</pre>
<dl>
<dt>New element attribute <code>toggle=""</code> for the parent element</dt>
<dd>The attribute value should match the ID of the element that's toggable</dd>
<dd>When the parent element is clicked, receives focus or active state it triggers the toggle to the matched ID value</dd>
</dl>
<dl>
<dt>New attribute <code>state=""</code> (There's probably a better name!)</dt>
<dd>The attribute would be the type of action that can be actioned <em>to</em> this tag, possible other uses?</dd>
<dd>By default any element with an attribute of <code>state="toggle"</code> is initially hidden (could be ovewritten using CSS e.g. with <code>:first-child</code></dd>
</dl>
<h2>Accordions</h2>
<p>Expand/collapse one element in a series of elements, maybe using attributes and ID's</p>
<h3>Example</h3>
<p>In progress.</p>


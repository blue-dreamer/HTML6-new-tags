<h1>Rough ideas for new functionality in HTML6</h1>
<h2>Simple show/hide/toggle</h2>
<p>Possibly using an attribute in a tag to trigger an action on another tag with matching ID</p>
<h3>Example</h3>
<pre>
<code>
&lt;h3 toggle="tog1"&gt;+ Heading&lt;/h3&gt;
&lt;p id="tog1" state="toggle>Toggled content...&lt;/p&gt;
</code>
</pre>
<dl>
<dt>New element attribute <code>toggle=""</code></dt>
<dd>The attribute value should match the ID of the element that's toggable</dd>
<dd>When the element is clicked or receives a focus or active state it triggers the toggle to the matched value</dd>
</dl>
<dl>
<dt>New attribute <code>state=""</code> )There's probably a better name!)</dt>
<dd>The attribute would be the type of action that can be actioned <em>to</em> this tag</dd>
<dd>By default any element with an attribute of <code>type="toggle"</code> is initially hidden</dd>
</dl>
<h2>Accordions</h2>
<p>Expand/collapse one element in a series of elements, maybe using attributes and ID's</p>
<h3>Example</h3>
<p>In progress.</p>


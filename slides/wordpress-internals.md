### WordPress Internals

<div class="fragment-replacement">
    <div class="fragment fade-out" data-fragment-index="4">
        <pre class="hljs lang-none fragment" data-fragment-index="0"><code class="fragment" data-fragment-index="0">$ wp cache set &lt;key&gt; &lt;value&gt;</code><code class="fragment" data-fragment-index="1">$ wp cache get &lt;key&gt;</code><code class="fragment" data-fragment-index="2">$ wp cache delete &lt;key&gt;</code><code class="fragment" data-fragment-index="3">$ wp cache flush</code></pre>
    </div>
    <pre class="hljs lang-none fragment fade-in" data-fragment-index="4"><code>$ wp transient set &lt;key&gt; &lt;value&gt;</code><code>$ wp transient get &lt;key&gt;</code><code>$ wp transient delete &lt;key&gt;</code><code>$ wp transient delete --all</code></pre>
</div>

Note:

* Lets you peek into WordPress internals, like the object cache + transients
    - Set, get, and delete cached values
    - Perform the same operations for transients
* Also contains a whole series of functionality for the WP_Cron system

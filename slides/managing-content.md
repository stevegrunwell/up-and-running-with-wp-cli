### Managing content

<pre class="fragment fragment-replacement hljs" data-fragment-index="0"><div class="fragment fade-out" data-fragment-index="3"><code class="hljs lang-sh fragment" data-fragment-index="0"># Create a new post
$ wp post create ...</code><code class="lang-sh fragment" data-fragment-index="1"># Update a post
$ wp post update &lt;id&gt; ...</code><code class="lang-sh fragment" data-fragment-index="2"># Generate some test content
$ wp post generate --count=10 ...</code></div><div class="fragment fade-in" data-fragment-index="3"><code class="lang-sh"># Create a new term
$ wp term create ...</code><code class="lang-sh"># Update a term
$ wp term update &lt;taxonomy&gt; &lt;term&gt;</code><code class="lang-sh"># Generate some terms
$ wp term generate &lt;taxonomy&gt; --count=10</code></div></pre>

Note:

* Create and edit content from the command line
* Generate test data, useful for theme devs
* Similar interface for taxonomy terms

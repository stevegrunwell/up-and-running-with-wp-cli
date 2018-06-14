### Managing Plugins & Themes

<pre class="fragment-replacement"><code class="hljs lang-bash fragment fade-out" data-fragment-index="0">$ wp plugin install wordpress-seo</code><span class="fragment fade-out" data-fragment-index="3"><code class="hljs lang-bash fragment fade-in" data-fragment-index="0">$ wp plugin install wordpress-seo --activate</code></span><code class="hljs lang-bash fragment fade-in" data-fragment-index="3">$ wp theme install twentyseventeen --activate</code></pre>

<pre class="fragment-replacement fragment" data-fragment-index="1"><code class="hljs lang-bash fragment fade-out" data-fragment-index="2">$ wp plugin activate wordpress-seo</code><span class="fragment fade-out" data-fragment-index="3"><code class="hljs lang-bash fragment fade-in" data-fragment-index="2">$ wp plugin deactivate wordpress-seo</code></span><code class="hljs lang-bash fragment fade-in" data-fragment-index="3">$ wp theme deactivate twentyseventeen</code></pre>

Note:

1. Install new plugins, even activating them automatically
2. Otherwise, we can explicitly activate at any time. Or deactivate.
3. When working with themes, the commands are almost exactly the same
    - Can also install from URLs or zip files

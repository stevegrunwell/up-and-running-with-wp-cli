### A Simple Command

```php
/**
 * Makes things louder.
 *
 * ## OPTIONS
 *
 * <message>
 * : The message to amplify.
 */
WP_CLI::add_command( 'amplify', function ( $args ) {
    WP_CLI::log( strtoupper( $args[0] ) . '!!!' );
} );
```

<pre class="hljs lang-sh fragment"><code class="lang-sh">$ wp amplify "hulk smash"</code><code class="fragment">> HULK SMASH!!!</code></pre>

Note:

* Very simple example, where we take a single argument and make it uppercase with exclamation marks
* Command registered as a closure, but can be any callable

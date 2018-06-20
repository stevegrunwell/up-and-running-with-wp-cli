###  Database

```sh
# Export a database dump
$ wp db export backup.sql
```
<!-- .element: class="fragment" -->

```sh
# Import a SQL file
$ wp db import backup.sql
```
<!-- .element: class="fragment" -->

```sh
# Serialization-safe search + replace!
$ wp search-replace example.test example.com
```
<!-- .element: class="fragment" -->

Note:

* WP-CLI can also handle a lot of common database operations
    - Export, import, running queries
* Includes a search & replace solution that intelligently handles serialized data!
* Can also run arbitrary queries or open an interactive session
    - Uses credentials from wp-config.php unless specified otherwise

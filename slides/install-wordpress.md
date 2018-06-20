### Installing WordPress

```sh
# Download WordPress core
$ wp core download
```
<!-- .element: class="fragment" -->

```sh
# Install WordPress
$ wp core install --url=example.com --title="My Site" \
--admin_user="steve" --admin_password="password123" \
--admin_email="steve@example.com"
```
<!-- .element: class="fragment" -->

```sh
# Upgrading WordPress
$ wp core update
```
<!-- .element: class="fragment" -->

Note:

* WP-CLI is great for managing WordPress core itself
* Download, install, and update WP
* Can also do multisite conversions, verify checksums, and more.

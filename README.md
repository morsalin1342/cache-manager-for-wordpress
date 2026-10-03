# Cache Manager for WordPress

**Status: planning.** There is no code yet. The plugin is planned in a private repository and will be built after the product it serves is ready to go live.

One WordPress plugin to keep a server-side page cache in step with the site's content: purge on content changes, purge by hand, and manage the cache from WP Admin, WP-CLI and `wp-config.php` constants. One core plus a driver for each cache: Caddy with Souin and nginx FastCGI cache are planned, with Cloudflare and Redis Object Cache integration.

It is built for the two SitesPanel products, where it is optional: installed when someone needs control from inside WordPress. The repository is public under the GPL for anyone who wants to read or use it, but outside users get no support and no features of their own.

## Related Images & Tools

<!-- BEGIN GENERATED: related (from images.yaml in the org .github repository; do not edit by hand) -->
This plugin will manage your server-side page cache, with Caddy and Souin as the first planned driver. Both of these images ship Souin already compiled in, so the only setup left is enabling the API in your Caddyfile.

| Repository | Images | Description |
|---|---|---|
| [caddy-docker](https://github.com/morsalin1342/caddy-docker) | `morsalin1342/caddy` · `easydigital/caddy` | Standalone Caddy — Souin with Redis, Otter and SimpleFS backends |
| [frankenphp-docker](https://github.com/morsalin1342/frankenphp-docker) | `morsalin1342/frankenphp` · `easydigital/frankenphp` | Caddy + PHP app server, same Souin stack compiled in |

Also in this family, though neither ships Souin: [php-docker](https://github.com/morsalin1342/php-docker), [nginx-docker](https://github.com/morsalin1342/nginx-docker) and [apache-docker](https://github.com/morsalin1342/apache-docker).
<!-- END GENERATED: related -->

## License

Copyright (C) 2026 MD Morsalin. Licensed under the **GNU General Public License, version 2 or (at your option) any later version**; see [license.txt](license.txt).

That is the one license for everyone. [Easy Digital International Limited](https://github.com/easydigitalinternationallimited) uses the plugin under the same terms as anybody else, and no other license is needed for that: the GPL already allows using, modifying and distributing it.

## Not affiliated

This project is not affiliated with, or endorsed by, the makers of any cache it works with.

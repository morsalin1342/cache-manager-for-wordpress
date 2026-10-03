# Security Policy

## Reporting a Vulnerability

**Please report privately**, using GitHub's private vulnerability reporting:

- [Report a vulnerability](https://github.com/morsalin1342/cache-manager-for-wordpress/security/advisories/new)

That keeps the details between us until there is a fix to ship. Please do not open a public
issue for a security problem — a public issue discloses the vulnerability to everyone,
including anyone who would use it, before there is anything to upgrade to.

Please include:
- A clear description of the vulnerability
- Steps to reproduce
- The plugin version affected

We aim to respond within 48 hours and publish a fix as soon as possible.

## Scope

This plugin is a WordPress admin interface for the Caddy Souin cache API. Security concerns may involve:
- Unauthorized cache access or manipulation
- Cross-site scripting (XSS) in the admin UI
- CSRF vulnerabilities in cache management actions
- Information disclosure through cache key exposure

All admin actions are protected by WordPress nonces and require the `manage_options` capability.

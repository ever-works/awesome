# .htaccess Snippets

- **Name:** .htaccess Snippets
- **Category:** Themed Directories
- **Brand:** rawesome
- **Website:** https://github.com/phanan/htaccess#readme
- **Description:** A curated collection of reusable `.htaccess` snippets and configurations for Apache web servers, gathered from multiple sources into a single reference.

## Features

### General
- Centralized list of practical `.htaccess` examples for Apache.
- Focused on users who cannot edit the main Apache configuration and must rely on `.htaccess`.
- Includes notes and disclaimers about performance and configuration caveats.
- Highlights breaking changes and differences introduced with Apache 2.4, especially for access control.
- Credits and references to upstream sources such as **h5bp/server-configs-apache** and other community contributions.

### Rewrite and Redirection
*(from the Table of Contents and visible sections)*
- Assumes `mod_rewrite` is installed and enabled.
- **Force `www`:** Rules to redirect non-`www` traffic to `www`.
- **Force `www` in a generic way:** Domain-agnostic snippet that forces `www` for any domain.
- **Force non-`www`:** Rules to redirect `www` traffic to the bare domain.

> Note: The GitHub page content shown is truncated, so additional snippet categories (e.g., security, caching, compression, custom error pages, etc.) likely exist in the full README, but are not visible in the provided extract.

## Technical Notes & Disclaimers
- `.htaccess` files are slower and more complex than editing the main Apache config; they should be used when you do not have access to the main configuration.
- Some snippets may require adaptation to your server environment or Apache version.
- Usage is at your own risk; users are advised to consult:
  - Apache `.htaccess` how-to: https://httpd.apache.org/docs/current/howto/htaccess.html
  - Apache 2.4 upgrading guide: https://httpd.apache.org/docs/2.4/upgrading.html

## Pricing
- Not applicable. This is an open-source GitHub repository of configuration snippets (no paid plans indicated).
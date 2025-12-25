# Critical-Path CSS Tools

A curated directory of tools and resources for generating and managing critical-path (above-the-fold) CSS to improve page rendering performance.

- **Website**: https://github.com/addyosmani/critical-path-css-tools#readme
- **Category**: Themed directories
- **Tags**: awesome-lists, css, performance

---

## Overview

Critical-Path CSS Tools is a curated list of open-source tools that help you:
- Generate above-the-fold (critical-path) CSS
- Inline critical CSS into HTML
- Load remaining styles asynchronously
- Integrate critical CSS workflows into build tools and servers

The goal is to prioritize above-the-fold content so browsers can render the initial view as quickly as possible.

---

## Features

### Concept & Best Practices
- Encourages inlining critical (above-the-fold) CSS directly into the HTML `<head>` to avoid extra round trips.
- Recommends loading non-critical stylesheets later (e.g., in the footer), ideally asynchronously.
- Focuses on improving perceived performance and faster first paint.

### Node Modules
- **Penthouse**
  - Generates critical-path CSS for a page.
- **Critical**
  - Generates and inlines critical-path CSS.
  - Built on top of Penthouse, Oust, and inline-styles.
- **CriticalCSS** (Filament Group)
  - Finds and outputs critical CSS for a page.

### Server-Side Modules
- **mod_pagespeed** (Apache)
  - Apache module for automatic PageSpeed optimization, including critical-path CSS related improvements.
- **ngx_pagespeed** (Nginx)
  - Nginx module for automatic PageSpeed optimization with similar capabilities.

### Grunt Tasks (Build Tool Integration)
- **grunt-penthouse**
  - Grunt task wrapper for Penthouse to generate critical CSS in Grunt workflows.
- **grunt-critical-css**
  - Grunt task for generating critical CSS using Filament Group’s CriticalCSS.
- **grunt-critical**
  - Grunt task for the Critical module to generate and inline critical-path CSS.

### CasperJS
- **critical-css-casperjs**
  - CasperJS script to extract critical CSS information from web pages.

### PhantomJS
- **dr-css-inliner**
  - PhantomJS script that inlines above-the-fold CSS directly into a page.

### Inline Sources (Styles & Scripts)
- **inline-styles**
  - Replaces `<link>` tags with inline `<style>` tags.
  - Inlines CSS `url()` assets as data URIs.
- **gulp-inline-source**
  - Gulp plugin that:
    - Replaces `<link>` tags with inline `<style>` tags.
    - Replaces `<script src="">` tags with inline script content.
- **inline-critical**
  - Inlines critical-path CSS into HTML.
  - Loads existing external stylesheets using `loadCSS` for non-blocking behavior.
- **isomorphic-style-loader** (for Webpack / React)
  - Allows extraction of critical CSS for specific pages/screens in React apps.
  - Supports inlining critical CSS into HTML during server-side rendering (SSR).
  - Used in projects like React Starter Kit.

### Async CSS Loading (Concept)
- Promotes asynchronously loading the rest of the site-wide CSS after critical CSS is inlined, to avoid render-blocking.

---

## Pricing

- This is an open-source curated list. Individual tools listed are generally open-source; no centralized pricing is defined in this directory.
# DevArt News for Joomla

Professional news widgets package for Joomla 6, designed for editorial,
magazine, news, and high-performance content websites.

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.3%2B-green)
![Release](https://img.shields.io/badge/Version-1.1.1-orange)
![License](https://img.shields.io/badge/License-GPLv3-red)

---

## Overview

DevArt News is a modern Joomla 6 native news widgets package built for editorial
websites, magazines, newspapers, news portals, and high-traffic content
environments.

It provides lightweight, cache-friendly article rendering with multiple frontend
templates, advanced filtering, publication metadata support, smart image
handling, and production-safe performance.

Designed specifically for Joomla 6 with modern architecture, strict typing, and
zero legacy baggage. Built for very large article databases, high concurrency,
and Cloudflare full-page cache deployments.

---

## Features

### Multiple Frontend Templates

Included templates:

- News Cards
- Overlay Cards
- Compact List

Use cases:

- homepage news blocks
- breaking news sections
- latest news widgets
- sidebar news modules
- related article blocks
- category mini sections
- editorial landing pages
- mobile-friendly compact lists

---

### Article Sources

Flexible content sources:

- Latest / all articles
- Category filtered articles
- Selected articles

Filtering options:

- category filtering
- featured filtering
- author filtering
- tags
- date filters
- ordering controls
- exclude current article
- article limits

---

### Publication Metadata

Display important article information including:

- publication date / time
- author
- category
- read more links

Ideal for news portals, magazines, newspapers, and editorial websites.

---

### Smart Image Handling

Automatic image discovery:

- Auto mode
- Intro image
- Full article image
- First image inside article content

Features:

- thumbnail cache generation (`resize` / `crop`)
- safe image fallback logic
- concurrent-safe thumbnail writes
- optimized frontend rendering

---

### Frontend Rendering

Built for production.

Features:

- responsive layouts
- mobile-friendly rendering
- lightweight CSS
- minimal JavaScript
- cache-friendly output
- Cloudflare-friendly architecture
- Joomla Page Cache compatibility
- production-safe rendering
- LCP-friendly first-image priority on single-column layouts

---

### Admin Features

- Dashboard hub (New Widget / Widget List / Options / cache maintenance)
- Widget manager with create / edit / duplicate
- Import / Export widgets
- Header / Footer and Content Simple / Advanced grouping
- Template Theme / Layout / Cards grouping
- Per-template News Cards and Overlay Cards controls
- Selected article picker with search and pagination
- ACL permissions support
- 15 administrator language packs

---

## Included Extensions

This package installs:

- `com_devartnews`
- `mod_devartnews`

---

## Requirements

- Joomla 6.x
- PHP 8.3+

---

## Installation

1. Download the latest release ZIP (`pkg_devartnews_v1.1.1.zip`)
2. Open:

```text
System → Extensions → Install
```

3. Upload the package ZIP
4. Open:

```text
Components → DevArt News
```

5. Create widgets
6. Publish module instances

---

## Joomla Native Updates

Supports Joomla native updates via GitHub.

Update location:

```text
System → Extensions → Update
```

Update server:

```text
https://raw.githubusercontent.com/devartgr/joomla-devart-news/main/update.xml
```

Install or update using the full package ZIP only.

---

## Performance

Designed for production and high-traffic use.

Features:

- article query caching
- thumbnail caching with locked generation
- module `safeuri` cache mode
- lightweight rendering
- minimal frontend overhead
- Joomla Page Cache compatibility
- Cloudflare full-page-cache friendly output
- CDN-friendly architecture

Suitable for:

- editorial websites
- newspapers
- magazines
- news portals
- content-heavy Joomla installations

---

## Security Highlights

- Joomla ACL support
- CSRF-safe administrator actions
- Joomla query builder protection
- XSS-safe rendering (including escaped article links)
- strict input validation
- safe image handling
- namespaced architecture

---

## Compatibility

Supported:

- Joomla 6.x
- PHP 8.3+
- Joomla native update system
- modern Joomla MVC architecture

Not supported:

- Joomla 3
- Joomla 4
- Joomla 5
- PHP 8.2 and earlier

---

## Current Version

**1.1.1**

---

## Changelog Highlights (1.1.1)

### Added

- Joomla-style widgets trash UX (Trashed filter, Untrash, Delete from Trash)
- AdminController plural language strings for all 15 administrator locales

### Improved

- Joomla 7 forward-compat (`getModel()`, Document toolbar buttons)
- Non-SEF article links: `Route::_(..., false)` before `htmlspecialchars`
- Installer language cleanup and article JSON cache flush on update
- In-request `getArticles` cache for multi-module pages
- Author JOIN only when `show_author` is enabled

### Fixed

- Raw language keys after list delete/publish actions
- Leftover unprefixed module language files shadowing labels

See `CHANGELOG.md` and `changelog.xml` for the full public history.

---

## Production Recommendations

Recommended defaults:

Frontend:

- query caching enabled
- thumbnail caching enabled
- lightweight templates
- Compact List for sidebar usage

Infrastructure:

- Cloudflare CDN / full-page cache
- PHP OPcache
- optimized image delivery
- production cache configuration

---

## Known Notes

- Always test template integration with your Joomla template and cache stack
  before production rollout.
- Purge CDN / reverse-proxy cache after updating frontend-facing packages.
- Optional DBA indexing for `#__content.hits` may help sites that heavily use
  Hits ordering on very large article tables.

---

## Author

Kostas Stathopoulos  
DevArt

https://devart.gr

GitHub Repository:

https://github.com/devartgr/joomla-devart-news

---

## Disclaimer / Limitation of Liability

This software is provided "as is", without warranty of any kind.

DevArt shall not be liable for data loss, downtime, rendering issues, cache
conflicts, production failures, or issues resulting from use or misuse.

Always test in staging before production deployment.

Maintain proper backups.

---

## License

GNU General Public License v3 or later

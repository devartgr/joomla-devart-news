# DevArt News for Joomla

Professional news widgets package for Joomla 6, designed for editorial, magazine, news, and high-performance content websites.

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.2%2B-green)
![Release](https://img.shields.io/badge/Version-1.0.1-orange)
![License](https://img.shields.io/badge/License-GPLv3-red)

---

## Overview

DevArt News is a modern Joomla 6 native news widgets package built for editorial websites, magazines, portals, and high-traffic content environments.

It provides lightweight, cache-friendly article rendering with multiple frontend templates, advanced filtering, smart image handling, and production-safe performance.

Designed specifically for Joomla 6 with modern architecture, strict typing, and zero legacy baggage.

---

## Features

### Multiple Frontend Templates

Included templates:

- News Cards
- Overlay Cards
- Compact List

Use cases:

- homepage news blocks
- latest news sections
- sidebar widgets
- related article blocks
- category mini sections
- editorial landing pages
- mobile-friendly compact lists

---

### Article Sources

Flexible content sources:

- Latest Articles
- Category Filtered Articles
- Selected Articles
- Related Articles
- Current Article Context

Filtering options:

- category filtering
- featured filtering
- author filtering
- tags
- ordering controls
- exclude current article
- article limits

---

### Smart Image Handling

Automatic image discovery:

- Auto mode
- Intro image
- Full article image
- First image inside article content

Features:

- thumbnail cache generation
- safe image fallback logic
- optimized frontend rendering
- compact thumbnail support

---

### Frontend Rendering

Built for production.

Features:

- responsive layouts
- mobile-friendly rendering
- masonry support (where applicable)
- lightweight CSS
- no heavy frontend frameworks
- minimal JavaScript
- cache-friendly output

---

### Admin Features

- Widget manager
- Create / Edit widgets
- Duplicate widgets
- Import / Export widgets
- Template settings
- Global typography controls
- Dashboard production cards
- ACL permissions support
- Selected article picker with search and pagination

---

### Compact List Template

Purpose-built lightweight template for:

- sidebar latest news
- sports blocks
- related stories
- article footer blocks
- category compact lists
- mobile compact display

Features:

- left thumbnail layout
- compact responsive rendering
- optional category badge
- optional metadata
- optional author/date
- intro line controls
- optional read more

---

## Included Extensions

This package installs:

- com_devartnews
- mod_devartnews

---

## Requirements

- Joomla 6.x
- PHP 8.2+

---

## Installation

1. Download latest release
2. Open:

`System → Extensions → Install`

3. Upload package ZIP
4. Open:

`Components → DevArt News`

5. Create widgets
6. Publish module instances

---

## Joomla Native Updates

Supports Joomla native updates via GitHub.

Update location:

`System → Extensions → Update`

Update server:

`https://raw.githubusercontent.com/devartgr/joomla-devart-news/main/update.xml`

---

## Performance

Designed for production and high-traffic use.

Features:

- article query caching
- thumbnail caching
- lightweight rendering
- minimal frontend overhead
- Joomla Page Cache compatibility
- Cloudflare-friendly output
- CDN-friendly architecture
- safe repeated rendering
- widget-level cache isolation

Suitable for:

- editorial sites
- news portals
- magazine websites
- content-heavy Joomla installations

---

## Security Highlights

- Joomla ACL support
- CSRF-safe admin actions
- Joomla query builder protection
- XSS-safe rendering
- strict input validation
- safe image handling
- namespaced architecture
- JED-ready packaging

---

## Compatibility

Supported:

- Joomla 6.x
- PHP 8.2+
- Joomla native update system
- modern Joomla MVC architecture

Not supported:

- Joomla 3
- Joomla 4
- Joomla 5
- legacy PHP versions

---

## Current Version

1.0.1

---

## Changelog 1.0.1

### Fixed

- Fixed article selector visibility in widget Data settings
- Fixed Selected Articles picker incorrectly appearing for non-selected article source modes
- Fixed administrator widget configuration workflow inconsistency in source-specific field visibility

### Improved

- Improved administrator widget Data tab source-dependent field behavior
- Improved configuration workflow consistency for widget article source selection

---

## First Public Release Highlights

### Included

- News Cards template
- Overlay Cards template
- Compact List template
- article query caching
- thumbnail caching
- widget duplication
- import / export
- global typography controls
- ACL permissions
- responsive frontend rendering
- dashboard admin interface
- mobile optimized layouts

---

## Production Recommendations

Recommended defaults:

Frontend:

- query caching enabled
- thumbnail caching enabled
- lightweight templates
- Compact List for sidebar usage

Infrastructure:

- Joomla Page Cache
- Cloudflare CDN
- proper PHP OPcache
- production image optimization

---

## Known Notes

- Always test template integration with your Joomla template and cache stack before production rollout

---

## Author

Kostas Stathopoulos  
DevArt  
https://devart.gr/

GitHub Repository:

https://github.com/devartgr/joomla-devart-news

---

## Disclaimer / Limitation of Liability

This software is provided "as is", without warranty of any kind.

DevArt shall not be liable for data loss, downtime, rendering issues, cache conflicts, production failures, or issues resulting from use or misuse.

Always test in staging before production deployment.

Maintain proper backups.

---

## License

GNU General Public License v3 or later

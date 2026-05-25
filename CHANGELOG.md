# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Recently Viewed Items tracking using localStorage
- New CONTRIBUTION_IDEAS.md with 10 feature ideas for contributors
- CODE_OF_CONDUCT.md for community guidelines
- .gitignore for version control
- CHANGELOG.md for tracking releases

### Changed

### Fixed

### Deprecated

### Removed

### Security

---

## [1.0.0] - 2026-05-25

### Added
- Initial release of ChaatBazaar
- Responsive menu display with filtering
- Shopping cart system with localStorage persistence
- Location-based delivery radius check (5 km)
- Advanced filtering by price, spice level, rating, and dietary preferences
- Search functionality with fuzzy matching
- Specials section on homepage
- Order tracking dashboard
- Accessibility features (ARIA labels, keyboard navigation)
- Contact form and newsletter subscription
- Testimonials section
- Responsive design for all devices
- Live Server compatibility

### Fixed
- Image loading optimization with lazy loading
- Cart count synchronization issues
- Filter persistence across page navigation

### Features
- [x] Menu categorization (Snacks, Chaat, Beverages)
- [x] Cart management with add/remove functionality
- [x] Geolocation for delivery validation
- [x] Dark/themed UI with Orange color scheme
- [x] Mobile-first responsive design
- [x] Accessibility compliance

---

## Guidelines for Updates

When submitting a PR:

1. Update CHANGELOG.md with your changes under the `[Unreleased]` section
2. Use these categories: Added, Changed, Fixed, Deprecated, Removed, Security
3. Keep entries brief and user-focused
4. Link to related PRs/Issues if applicable

Example:
```
### Added
- New wishlist feature for saving favorite items (#42)
- Dark mode toggle with localStorage persistence (#38)

### Fixed
- Cart not updating on item removal (#35)
```

---

## Release Process

Releases follow semantic versioning:
- **MAJOR**: Breaking changes
- **MINOR**: New features (backwards compatible)
- **PATCH**: Bug fixes

When ready for a new release:
1. Update version numbers
2. Move items from `[Unreleased]` to new version section
3. Tag the commit with version number
4. Create release notes on GitHub

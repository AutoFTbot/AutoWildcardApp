# Changelog

All notable changes to AutoWildcard will be documented in this file.

## [Unreleased]

## [0.0.4] - 2026-02-05

### Added
- **Email Routing Feature**: Setup email forwarding with Cloudflare
  - Enable Email Routing for domains
  - Catch-all email forwarding (*@domain.com)
  - Forward all emails to single destination address
  - Automatic MX and SPF records configuration
  - Email validation and verification flow
  - Accessible via menu in main screen
- **Manage Email Routing Feature**: View and manage configured email routings
  - List all domains with email routing enabled
  - Display destination email for each domain
  - Show routing status (enabled/disabled)
  - Disable email routing with confirmation dialog
  - Pull-to-refresh for updated list
  - Card-based UI with clear information display
  - Accessible via menu in main screen

### Changed
- Improved all alert dialogs with better UI/UX
  - Custom layouts with consistent typography
  - Color-coded titles (green for success, red for error)
  - Better padding and spacing
  - Visual indicators (✓ and ✗) for feedback
- Updated AdMob configuration

## [0.0.3] - 2026-02-01

### Added
- **Add Domain Feature**: New capability to add domains directly to Cloudflare
  - Add new domains to Cloudflare account via API
  - Automatic DNS quick scan for existing records
  - Display nameservers for domain activation
  - Domain validation and error handling
  - Support for bulk domain addition (max 25 per 10 minutes)
  - Multi-domain input with dynamic fields
  - Copy individual or all nameservers
  - Accessible via menu in main screen
- **VPS Rebuild Feature**: New tool to reinstall VPS operating system via SSH
  - Support for multiple Linux distributions (Ubuntu, Debian, CentOS, Alpine, etc.)
  - Secure SSH connection with password authentication
  - Real-time console output with terminal-style UI
  - Auto-retry mechanism for connection failures
  - Support for modern SSH key exchange algorithms (ED25519)
- Help link on login page for easy access to documentation
- Custom menu icon for better UI consistency

### Changed
- Menu items moved to overflow menu (three dots) for cleaner interface
- Improved console output UI with dark theme and live indicator
- Enhanced error handling with detailed troubleshooting tips

### Fixed
- Network configuration compatibility issues
- SSH authentication with modern servers

## [0.0.2] - 2026-01-31

### Added
- Initial release
- Cloudflare wildcard DNS automation
- Firebase Cloud Messaging integration
- AdMob integration
- Material Design 3 UI
- Secure credential storage
- Multi-domain support

### Features
- Automatic wildcard DNS record creation
- Custom subdomain support
- Real-time progress tracking
- Help and About sections

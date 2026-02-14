# Changelog

All notable changes to the Kiwi Digital website.

## [2026-02-15] - Global Expansion & Product Showcase Update

### Added
- **Product Screenshots**: Captured high-quality screenshots of Clockie and SafePing
  - Clockie: Hero, features, and dashboard views (desktop 1280x800)
  - SafePing: Hero, features, and mobile views
  - Stored in `public/projects/` directory
  
- **Enhanced Project Cards**: Completely redesigned Projects section
  - Featured projects (Clockie & SafePing) displayed in large, image-backed cards
  - Project screenshots as card backgrounds with gradient overlays
  - Added pricing information for Clockie
  - Improved layout: 2-column featured projects + 4-column compact grid for others
  - Better descriptions highlighting product value propositions
  - Status badges, tech stack tags, and live site links

- **Privacy Policy Page**: (`/privacy`)
  - Comprehensive privacy policy compliant with NZ Privacy Act 2020
  - Coverage: data collection, cookies, third-party services, data storage & security
  - User rights, international data transfers, and contact information
  - Professional legal page styling consistent with site design

- **Terms of Service Page**: (`/terms`)
  - Complete terms for software development consultancy services
  - Coverage: services, IP ownership, warranties, liability, dispute resolution
  - NZ law jurisdiction, payment terms, and termination clauses
  - Clear legal language with structured sections

- **Footer Links**: Added Privacy Policy and Terms of Service to footer navigation

### Changed
- **Global Positioning**: Updated all copy to reflect international reach
  - Hero badge: "Global AI Development · HQ Hawke's Bay, NZ" (was "AI-Native Studio · Hawke's Bay, NZ")
  - Hero subtitle: "businesses operate globally" (was "New Zealand businesses operate")
  - About section: "businesses globally" + "Headquartered in Havelock North, NZ" + "Our global teams"
  - Footer: "businesses globally" + "Headquartered in Hawke's Bay, New Zealand"
  - Layout meta description: Updated to reflect global reach
  - FAQ: Changed "Do you only work with NZ businesses?" to "Do you work with international clients?"
  - WhyAI stats: "of SMBs have no clear digital strategy" (was "of NZ businesses")
  - Testimonial: "next generation of businesses" (was "next generation of NZ businesses")

- **Projects Section**: Updated copy to say "businesses globally" instead of "NZ businesses"

- **Product Information**:
  - Clockie: Updated description, added pricing, changed status to "Live" with link to clockie.nz
  - SafePing: Updated description, changed status to "Live" with link to safeping.app
  - Both products now feature real screenshots and comprehensive tech stack information

### Technical
- Installed Playwright for automated screenshot capture
- Created automated screenshot script (used and removed)
- Docker image rebuilt: `kiwi-digital-website:latest`
- Container restarted and running on port 8080
- All changes committed and ready for push

### Summary
This update transforms the Kiwi Digital website from a NZ-focused to a globally-positioned software development company, while maintaining strong NZ heritage and identity. Featured products (Clockie and SafePing) now have professional showcase cards with real product screenshots. Added essential legal pages (Privacy and Terms) for business credibility and compliance.

The site now clearly communicates:
- Global capability with NZ headquarters
- Real, live products with proven track records
- Professional legal framework for client engagement
- Strong visual identity with actual product imagery

# Tibetan Bowls Solfeggio Studio Landing Page - Technical Reference

## Project Overview
- **Project Name**: Tibetan Bowls Solfeggio Studio Landing Page
- **Purpose**: Marketing website for the Tibetan Bowls Solfeggio Studio Android app
- **Technology Stack**: HTML5, CSS3, JavaScript (Vanilla)
- **Local Path**: `C:\Users\jon\frequency-studio-landing`
- **GitHub Repository**: https://github.com/jonpreizler/frequency-studio-landing

## Business Requirements
- Present the Tibetan Bowls Solfeggio Studio value proposition and solfeggio toolkit.
- Deliver quick access to FAQ, feedback, and privacy policy resources.
- Support Google Play distribution with official branding and CTA.
- Collect user feedback through a Formspree-powered contact form.
- Provide transparent privacy and data usage documentation.
- Maintain comprehensive SEO signals: sitemap, robots.txt, canonical tags, structured data.
- Force HTTPS usage and eliminate duplicate indexing.

## File Structure
```
frequency-studio-landing/
├── index.html              # Main landing page
├── faq.html               # FAQ and complete guide
├── privacy-policy.html     # Privacy policy page
├── feedback-form.html      # User feedback and support page
├── styles.css             # Global stylesheet
├── sitemap.xml            # XML sitemap for Google Search Console
├── robots.txt             # Search engine crawler directives
├── CNAME                  # Custom domain configuration
├── README.md              # Project documentation
├── TECHNICAL_REFERENCE.md # This document
└── images/
    ├── phone.png          # App screenshot
    ├── phone.webp         # Optimized app screenshot (WebP)
    ├── rotating_earth.gif # Animated Earth overlay
    ├── woman meditating_2.jpg # Meditation hero image
    ├── woman-meditating_2.webp # Optimized meditation hero image (WebP)
    ├── copyright_logo.jpg # Copyright logo
    ├── GetItOnGooglePlay_Badge_Web_color.png # Official Google Play badge
    └── get-it-on-google-play.webp # Optimized Google Play badge (WebP)
```

## Change Log

### Version 2.1 - Branding Alignment & Analytics Update (Current)
**Date**: November 2025  
**Changes**:  
- ✅ Updated privacy policy page title, hero heading, and legal copy to use the full `Tibetan Bowls Solfeggio Studio` brand name  
- ✅ Ensured Google Analytics tag fires once on the privacy policy page with explicit `page_title`/`page_path` configuration  
- ✅ Synced stylesheet header comment to the `Tibetan Bowls Solfeggio Studio` branding

**Technical Implementation**:  
- HTML: Refreshed privacy policy metadata and content to reflect the new branding  
- JavaScript: Confirmed GA configuration object includes page-specific details and prevents duplicate inits  
- CSS: Updated global comment header to match brand rename

### Version 2.0 - Complete Design Overhaul & New Features
**Date**: January 2025
**Changes**:
- ✅ Created comprehensive FAQ page (faq.html) with complete user guide
- ✅ Created support page (feedback-form.html) for user feedback collection
- ✅ Implemented global CSS stylesheet (styles.css) for consistent theming
- ✅ Updated all pages to use consistent dark neon theme with gold accents
- ✅ Added meditation hero image with 3D shadow effects
- ✅ Implemented official Google Play badge and branding
- ✅ Added smooth fade-out/fade-in transitions for all page navigation
- ✅ Updated contact email to chakra.khan.info@gmail.com
- ✅ Rewrote privacy policy with formal legal language
- ✅ Centered all headers and navigation elements
- ✅ Added prominent support link above the fold on main page
- ✅ Removed "Sacred Frequencies" section from main page
- ✅ Updated tagline to "solfeggio frequency mixer"
- ✅ Added binaural effect usage instructions
- ✅ Created XML sitemap (sitemap.xml) for Google Search Console indexing
- ✅ Created robots.txt for search engine crawler directives
- ✅ Updated site name to "Tibetan Bowls Solfeggio Studio"
- ✅ Added SoftwareApplication schema and WebP image delivery

**Technical Implementation**:
- CSS: Global stylesheet with consistent color scheme (#DAA520 gold, #9370DB purple)
- JavaScript: Fade transition system for smooth page navigation
- HTML: Consistent structure across all pages with centered content
- Images: Added meditation image with layered shadow effects
- Branding: Official Google Play badge implementation

### Version 1.2 - Navigation & UI Improvements
**Date**: January 2025
**Changes**:
- ✅ Replaced CSS-generated phone mockup with actual app screenshot
- ✅ Added privacy policy link to landing page footer
- ✅ Added "← Back to Home" button to privacy policy page
- ✅ Improved phone border styling (transparent background)
- ✅ Enhanced navigation between pages with standard links

**Technical Implementation**:
- HTML: Added `<img src="images/phone.png">` for app screenshot
- CSS: Updated `.phone-mockup` styling for better integration
- Navigation: Standard HTML links between pages


### Version 1.0 - Initial Release
**Date**: January 2025
**Changes**:
- ✅ Created main landing page (index.html)
- ✅ Created privacy policy page (Privacy-Policy.html)
- ✅ Implemented dark neon theme for landing page
- ✅ Implemented purple/blue gradient theme for privacy policy
- ✅ Added responsive design for mobile devices
- ✅ Added floating particle animations
- ✅ Added feature cards and frequency showcase
- ✅ Added call-to-action buttons

**Technical Implementation**:
- CSS: Gradient backgrounds, animations, responsive grid
- JavaScript: Floating particles, scroll effects, intersection observer
- Design: Modern glassmorphism effects, smooth animations

## Technical Specifications

### Landing Page (index.html)
- **Theme**: Dark neon with gold (#DAA520) and purple (#9370DB) accents
- **Background**: Radial gradient with cosmic aesthetics
- **Hero Image**: Meditation image with 3D shadow effects (layered box-shadow)
- **Media Delivery**: `<picture>` tags serve WebP imagery with lazy loading and PNG/JPG fallbacks
- **Animations**: Floating particles, gradient text shifts, fade transitions
- **Responsive**: Mobile-first design with CSS Grid and Flexbox
- **Performance**: Optimized animations with CSS transforms
- **Navigation**: Smooth fade-out/fade-in transitions between pages

### FAQ Page (faq.html)
- **Theme**: Consistent with main site (dark neon with gold accents)
- **Content**: Comprehensive user guide and troubleshooting
- **Navigation**: Centered back button with fade transitions and contextual internal links
- **Structure**: Organized sections with centered headers

### Privacy Policy Page (Privacy-Policy.html)
- **Theme**: Consistent dark neon theme (updated from purple/blue gradient)
- **Content**: Formal legal language written by attorney perspective
- **Design**: Glassmorphism with backdrop blur effects
- **Typography**: Clean, readable fonts with proper hierarchy
- **Accessibility**: High contrast ratios and semantic HTML

### Support Page (feedback.html)
- **Theme**: Consistent with site theme
- **Purpose**: User feedback collection and contact
- **Features**: Feedback forms, contact information, support links


## CSS Architecture

### Global Stylesheet (styles.css)
- **Color Scheme**: Gold (#DAA520) for headers, Purple (#9370DB) for accents
- **Typography**: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif with font-weight: 300
- **Animations**: Gradient shifts, floating effects, fade transitions
- **Layout**: CSS Grid and Flexbox for responsive design

### Key Classes
- `.hero` - Main hero section with background effects
- `.feature-card` - Individual feature cards with hover effects
- `.phone-screenshot` - Actual app image styling
- `.back-button` - Navigation button styling
- `.section h2` - Centered section headers with gold color
- `.footer` - Consistent footer styling across all pages

### Animation System
- **Floating Particles**: CSS keyframes with JavaScript generation
- **Gradient Shifts**: Background position animations
- **Hover Effects**: Transform and shadow transitions
- **Fade Transitions**: Page navigation with opacity animations
- **3D Effects**: Layered box-shadows for meditation image

## JavaScript Features

### Global Navigation System
- `fadeOutAndNavigate()` - Smooth page transitions with fade effects
- `DOMContentLoaded` - Page load fade-in animations
- Consistent across all pages (index.html, faq.html, Privacy-Policy.html, feedback.html)

### Landing Page Scripts
- `createFloatingDot()` - Generates animated particles
- `IntersectionObserver` - Scroll-triggered animations
- Download button click handlers

### Page-Specific Scripts
- FAQ page: Navigation and content organization
- Privacy Policy: Legal content structure
- Support page: Feedback collection and contact forms

## Browser Compatibility
- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **CSS Features**: CSS Grid, Flexbox, backdrop-filter, CSS animations
- **JavaScript**: ES6+ features, Intersection Observer API
- **Mobile**: Responsive design for all screen sizes

## Performance Considerations
- **Images**: Optimized PNG format for app screenshot
- **CSS**: Efficient animations using transforms and opacity
- **JavaScript**: Event delegation and efficient DOM manipulation
- **Loading**: Minimal external dependencies

## SEO & Search Engine Optimization

### Sitemap (sitemap.xml)
- **Purpose**: XML sitemap for Google Search Console indexing
- **Location**: Root directory (`/sitemap.xml`)
- **Content**: Lists all pages with priorities and change frequencies
- **Pages Included**:
  - Homepage (priority 1.0, weekly updates)
  - FAQ page (priority 0.8, monthly updates)
  - Feedback form (priority 0.7, monthly updates)
  - Privacy Policy (priority 0.5, yearly updates)
- **Submission**: Submitted to Google Search Console
- **Reference**: Linked in `index.html` `<head>` section

### Robots.txt
- **Purpose**: Search engine crawler directives
- **Location**: Root directory (`/robots.txt`)
- **Configuration**: Allows all crawlers, points to sitemap
- **Content**: 
  ```
  User-agent: *
  Allow: /
  Sitemap: https://chakra-khan.org/sitemap.xml
  ```

### Google Search Console Integration
- **Sitemap URL**: `https://chakra-khan.org/sitemap.xml`
- **Status**: Successfully submitted and validated
- **Custom Domain**: `chakra-khan.org` configured via CNAME file
- **Structured Data**:
  - `WebSite` + `Organization` JSON-LD on homepage
  - `SoftwareApplication` JSON-LD on homepage
  - `FAQPage` schema on FAQ page
  - `Article` schema on privacy policy page
  - `ContactPage` schema on feedback form
  - Social sharing metadata (Open Graph + Twitter cards) on all pages

### Canonical URLs & HTTPS
- **Canonical Tags**: Each page declares its canonical HTTPS URL.
- **HTTP Redirect**: Lightweight script forces all URLs to HTTPS to avoid duplicate indexing.
- **Custom Domain**: Managed through `CNAME` and GitHub Pages with enforced HTTPS.

## Future Enhancements
- [x] Add Google Analytics integration
- [x] Implement Google Play Store link with official badge
- [x] Add more app screenshots
- [x] Create additional pages (FAQ, About, Support)
- [x] Add contact form
- [x] Implement SEO optimizations
- [x] Create XML sitemap for Google Search Console
- [x] Create robots.txt for search engine directives
- [x] Add canonical URLs and HTTPS redirection
- [ ] Add Android tablet detection for portrait mode
- [ ] Implement user feedback collection system
- [ ] Add more meditation images
- [ ] Create video demonstrations

## Maintenance Notes
- **Image updates**: Replace `phone.png` and `woman meditating_2.jpg` when content changes
- **Color scheme**: Maintain consistency across all pages using global stylesheet
- **Responsive testing**: Test on various devices and screen sizes
- **Navigation**: Fade transitions work reliably across all browsers
- **Content updates**: Update FAQ and support pages as app features evolve
- **Legal compliance**: Review privacy policy annually for legal accuracy
- **SEO**: Update `sitemap.xml` when adding new pages or changing page priorities
- **Sitemap dates**: Update `<lastmod>` dates in sitemap.xml when pages are modified
- **Search Console**: Monitor Google Search Console for indexing status and errors
- **Core Web Vitals**: Run Google Lighthouse audits (mobile + desktop) after major UI/image changes
- **Structured Data Checks**: Validate JSON-LD (Organization, WebSite, SoftwareApplication, FAQPage, Article, ContactPage) via Google’s Rich Results Test when schema updates occur

## Contact Information
- **Developer**: Chakra Khan
- **Email**: chakra.khan.info@gmail.com
- **Project**: Tibetan Bowls Solfeggio Studio Landing Page

---
*Last Updated: January 2025*
*Version: 2.0*

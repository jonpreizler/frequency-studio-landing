# Frequency Studio Landing Page - Technical Reference

## Project Overview
- **Project Name**: Frequency Studio Landing Page
- **Purpose**: Marketing website for Frequency Studio Android app
- **Technology Stack**: HTML5, CSS3, JavaScript (Vanilla)
- **Local Path**: `C:\Users\jon\frequency-studio-landing`
- **GitHub Repository**: https://github.com/jonpreizler/frequency-studio-landing

## File Structure
```
frequency-studio-landing/
├── index.html              # Main landing page
├── faq.html               # FAQ and complete guide
├── Privacy-Policy.html     # Privacy policy page
├── feedback.html           # User feedback and support page
├── styles.css             # Global stylesheet
├── README.md              # Project documentation
├── TECHNICAL_REFERENCE.md # This document
└── images/
    ├── phone.png          # App screenshot
    ├── rotating_earth.gif # Animated Earth overlay
    ├── woman meditating_2.jpg # Meditation hero image
    └── GetItOnGooglePlay_Badge_Web_color.png # Official Google Play badge
```

## Change Log

### Version 2.0 - Complete Design Overhaul & New Features (Current)
**Date**: January 2025
**Changes**:
- ✅ Created comprehensive FAQ page (faq.html) with complete user guide
- ✅ Created support page (feedback.html) for user feedback collection
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
- **Animations**: Floating particles, gradient text shifts, fade transitions
- **Responsive**: Mobile-first design with CSS Grid and Flexbox
- **Performance**: Optimized animations with CSS transforms
- **Navigation**: Smooth fade-out/fade-in transitions between pages

### FAQ Page (faq.html)
- **Theme**: Consistent with main site (dark neon with gold accents)
- **Content**: Comprehensive user guide and troubleshooting
- **Navigation**: Centered back button with fade transitions
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

## Future Enhancements
- [x] Add Google Analytics integration
- [x] Implement Google Play Store link with official badge
- [x] Add more app screenshots
- [x] Create additional pages (FAQ, About, Support)
- [x] Add contact form
- [x] Implement SEO optimizations
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

## Contact Information
- **Developer**: Chakra Khan
- **Email**: chakra.khan.info@gmail.com
- **Project**: Frequency Studio Landing Page

---
*Last Updated: January 2025*
*Version: 2.0*

# Product Requirements Document (PRD): Peacey Family Website

## 1. Document Information
- **Project Name**: Peacey Family Website
- **Version**: 2.0 (Updated with Confirmed Requirements)
- **Date**: January 22, 2026
- **Author**: Claude (AI Assistant)
- **Stakeholders**: Peacey Family Members
- **Status**: Finalized – Ready for Development

## 2. Overview
### 2.1 Project Summary
The Peacey Family Website is a simple, static website hosted on GitHub Pages that serves as a central hub for the family's upcoming trip to South Africa (July 2026). The site will:
- Provide a welcoming landing page introducing the Peacey family.
- Host a trip itinerary page showing day-by-day activities (without specific dates for privacy).
- Display photos from a linked Google Photos album.
- Serve as both a pre-trip planning tool and post-trip memory repository.

The site will be **publicly accessible** (no authentication) via GitHub Pages but will exclude sensitive information (exact dates, confirmation numbers, personal contact details). Content will be static HTML/CSS/JavaScript with no backend or database, ensuring zero maintenance costs and maximum simplicity.

**Key Privacy Approach**: The site uses relative day numbering (Day 1, Day 2, etc.) instead of exact dates to maintain privacy while publicly accessible.

### 2.2 Objectives
- Create a single, easy-to-access online space for family members to view trip plans and memories.
- Display trip itinerary in a clear, day-by-day format with activities and locations.
- Integrate Google Photos album for easy photo viewing without GitHub storage.
- Keep the site simple, mobile-friendly, and fast-loading.
- Enable post-trip updates to add exact dates and additional content after returning.
- Maintain family member privacy by excluding sensitive booking and personal information.

## 3. Target Audience
- **Primary**: Peacey family members (all ages, varying tech proficiency).
- **Secondary**: Close friends or extended family invited to view trip updates.
- **Primary Devices**: Mix of mobile and desktop (requires responsive design optimized for both).
- **User Needs**:
  - Easy navigation on mobile and desktop.
  - Quick access to trip photos and itinerary.
  - Clear day-by-day trip schedule.
  - Pleasant, family-oriented design inspired by South African Springbok colors (green and gold).

## 4. Scope
### 4.1 In Scope (Phase 1 - Initial Launch)
- **Four core pages**:
  1. Home / Landing Page with family introduction
  2. South Africa Trip Hub Page (overview with links to sub-pages)
  3. Itinerary Page (day-by-day schedule using relative day numbering)
  4. Photo Gallery Page (grid layout with lightbox, linked to Google Photos)
- Responsive design optimized for mobile and desktop.
- Grid-based photo gallery with lightbox enlargement.
- Integration with external Google Photos album for photo display.
- Hosting on GitHub Pages (free, public URL: `kendrewp.github.io/PeaceyFamily`).
- Springbok-inspired color scheme (green #1B3838, gold #FFB302).

### 4.2 Deferred (Future Phases)
- Practical Information Page (flights, accommodations, visas)
- About the Family Page
- Contact/Resources Page
- Packing List / Tips Page
- Embedded maps (Google Maps integration)
- Custom domain configuration

### 4.3 Out of Scope (Permanently)
- User accounts/login (GitHub Pages limitation; site will be publicly accessible).
- Real-time/automatic updates (static site; updates require manual HTML edits).
- Backend/database (purely static HTML/CSS/JavaScript).
- Direct photo uploads to the site (photos managed via Google Photos).
- Form submissions or comment systems.

## 5. Site Structure & Pages
### 5.1 Navigation Structure
- Simple top navigation bar (consistent across all pages):
  - **Home**
  - **Trip Hub**
  - **Itinerary**
  - **Photos**
- Mobile-responsive hamburger menu for small screens.

### 5.2 Page Specifications

#### 5.2.1 Home / Landing Page (`index.html`)
- **Hero section**: 
  - Family name: "Peacey Family"
  - Welcoming message (placeholder text initially)
  - Hero image placeholder (will be replaced with family photo later - 1200x600px recommended)
- **Introduction**: Brief welcome text with excitement about the South Africa trip
- **Call-to-action**: Large button/link to "South Africa Trip 2026"
- **Footer**: Simple footer with "Made with ❤️ for the Peacey Family"

#### 5.2.2 South Africa Trip Hub Page (`trip.html`)
- **Trip overview**: 
  - General timeframe: "July 2026" (no specific dates for privacy)
  - Brief description of the adventure
- **Navigation cards** linking to:
  - Itinerary/Agenda
  - Photo Gallery
- **Visual design**: Cards with Springbok-themed colors and icons

#### 5.2.3 Itinerary / Agenda Page (`itinerary.html`)
- **Format**: Day-by-day timeline or accordion layout
- **Date display**: Relative day numbering (Day 1, Day 2, etc.) - NO specific dates shown
- **Content structure**: 
  - Day number
  - Activities/events for that day
  - Locations mentioned (general: "Cape Town", "Kruger National Park")
  - Days without finalized plans marked as "To Be Planned"
- **Trip duration**: 24 days total (Day 1 through Day 24)
- **Confirmed activities** (from spreadsheet):
  - Day 1: Depart Denver/DC
  - Day 2: Arrive Cape Town (evening)
  - Days 3-16: To Be Planned (Cape Town area)
  - Day 17: Cradle of Humankind (UNESCO World Heritage Site)
  - Day 18: Arrive Kruger National Park - Berg-en-Dal Rest Camp
  - Days 19-21: Sunrise game drives
  - Day 22: Depart Kruger National Park - Drive to Pretoria, spend one night, see PBHS
  - Day 23: Depart Johannesburg (evening)
  - Day 24: Arrive Denver/DC
- **Post-trip update**: After trip completion, exact dates and additional details will be added

#### 5.2.4 Photo Gallery Page (`photos.html`)
- **Layout**: Grid layout with responsive columns (3-4 columns desktop, 2 columns tablet, 1 column mobile)
- **Interaction**: Click to enlarge with lightbox overlay
- **Photo source**: Embedded/linked from Google Photos album
  - Album URL: https://photos.app.goo.gl/xYL5FiS8oZS4CCeC8
  - Album name: "South Africa"
  - Currently empty; will be populated with pre-trip and post-trip photos
- **Sections** (to be implemented):
  - Pre-trip excitement
  - Trip memories (post-trip)
- **Photo management**: Managed externally via Google Photos by site owner

## 6. Functional Requirements
- **Responsive Layout**: Mobile-first design that works seamlessly on mobile, tablet, and desktop.
- **Photo Gallery**: Grid-based gallery with lightbox popup for enlarged views.
- **Google Photos Integration**: Embed or link photos from external Google Photos album.
- **Day-by-Day Itinerary**: Display 24-day trip schedule with relative day numbering.
- **Smooth Navigation**: Simple navigation between pages with consistent header/footer.
- **Fast Loading**: Optimized for quick load times (minimal dependencies, compressed images if any stored in repo).
- **Accessibility**: Basic accessibility features (alt text for images, good color contrast, semantic HTML).

## 7. Non-Functional Requirements
- **Performance**: Page load < 3 seconds on standard broadband connection.
- **Security**: HTTPS enforced by GitHub Pages (automatic).
- **Privacy**: No sensitive information displayed (no exact dates, confirmation numbers, personal contact details, addresses).
- **Hosting**: GitHub Pages (free tier) - Repository: https://github.com/kendrewp/PeaceyFamily
- **Maintenance**: Site maintained by owner; updates managed via GitHub (HTML edits required for itinerary changes).
- **Browser Support**: Modern browsers (Chrome, Safari, Firefox, Edge) - last 2 versions.
- **Update Process**: Manual updates via notification to developer or direct HTML edits via GitHub web interface.

## 8. Design & Content Guidelines

### 8.1 Visual Design
- **Theme**: Adventurous, family-friendly, South African-inspired
- **Color Palette** (South African Springbok team colors):
  - **Primary Green**: #1B3838 (Medium Jungle Green)
  - **Primary Gold**: #FFB302 (UCLA Gold)
  - **Background**: #FFFFFF (White) or #F5F5F5 (Light gray)
  - **Text**: #333333 (Dark gray) for body text
  - **Accents**: Use green for headers, gold for call-to-action buttons and highlights
- **Typography**: 
  - Clean, readable Google Fonts (to be selected during development, e.g., Roboto, Open Sans, Lato)
  - Hierarchical sizing for headers (H1, H2, H3)
  - Minimum 16px for body text (mobile readability)
- **Images**: 
  - Hero image: Placeholder initially (family photo to be added later, 1200x600px recommended)
  - Gallery images: Sourced from Google Photos album
- **Layout**: 
  - Maximum content width: 1200px (centered)
  - Adequate whitespace for readability
  - Card-based design for trip hub sections

### 8.2 Content Guidelines
- **Tone**: Casual, excited, inclusive, family-oriented
- **Privacy Rules** (MUST follow):
  - ❌ **Exclude**: Exact dates, home addresses, flight confirmation numbers, phone numbers, email addresses, passport/visa details, credit card/booking reference numbers
  - ✅ **Include**: General locations (e.g., "Cape Town", "Kruger National Park"), hotel names (without full addresses), activity names and general times, relative day numbers (Day 1, Day 2, etc.)
- **Content Sources**:
  - **Itinerary**: OneDrive spreadsheet - https://1drv.ms/x/c/2047e2368cb0b4d9/IQDOm2GBK0WKT6SmP510p-5UAbPFcXJWr2QSEYe0SoDn0kA?e=YpY6SP
    - Column B: Dates
    - Column C: Activities
    - Column D: Additional details (accommodations, locations, sub-activities)
  - **Photos**: Google Photos album - https://photos.app.goo.gl/xYL5FiS8oZS4CCeC8
  - **Text**: Placeholder content initially; to be refined by family post-launch

## 9. Technical Approach

### 9.1 Technology Stack
- **HTML5**: Semantic markup for content structure
- **CSS3**: Modern styling with Flexbox/Grid for responsive layouts
- **Vanilla JavaScript**: Minimal JavaScript for interactivity (no frameworks)
- **Optional Libraries**: Lightweight lightbox library for photo gallery (CDN-hosted, e.g., GLightbox or SimpleLightbox)

### 9.2 Repository & Deployment
- **Repository**: https://github.com/kendrewp/PeaceyFamily
- **Version Control**: Git via GitHub
- **Deployment**: Automatic via GitHub Pages
- **Site URL**: https://kendrewp.github.io/PeaceyFamily/ (custom domain to be added later)

### 9.3 File Structure
```
/
├── index.html              # Home page
├── trip.html               # Trip hub page
├── itinerary.html          # Itinerary page
├── photos.html             # Photo gallery page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # Main JavaScript file
├── images/
│   └── (hero image placeholder, icons, etc.)
└── README.md               # Repository documentation
```

### 9.4 External Integrations
- **Google Photos**: Album embedded/linked for photo display (no photos stored in repo)
- **OneDrive**: Itinerary source spreadsheet (manual updates to HTML required when spreadsheet changes)

## 10. Risks & Mitigation Strategies

### 10.1 Privacy & Security Risks
- **Risk**: Site is publicly accessible without authentication
- **Mitigation**: 
  - Use relative day numbering instead of exact dates
  - Exclude all sensitive information (see Section 8.2 Privacy Rules)
  - Repository is public but URL will not be widely shared

### 10.2 Content Update Risks
- **Risk**: Static site requires manual HTML updates for itinerary changes
- **Mitigation**: 
  - Owner will notify developer for updates (Option A confirmed)
  - Clear documentation in README for simple edits via GitHub web interface
  - Itinerary is still in planning stages; structure built to accommodate changes

### 10.3 Photo Storage Risks
- **Risk**: Google Photos album link could break or require permissions
- **Mitigation**: 
  - Album is set to "Anyone with link can view"
  - Owner manages album directly
  - Fallback: Can migrate to GitHub-hosted images if needed

### 10.4 Assumptions
- ✅ Owner will manage and update Google Photos album
- ✅ Owner will notify developer when itinerary spreadsheet changes require website updates
- ✅ Family members have the website URL and can access it on mobile/desktop
- ✅ Post-trip updates (exact dates, additional photos) will be added after July 2026

## 11. Implementation Plan

### 11.1 Development Phases
**Phase 1 (Initial Launch - Pre-Trip):**
- Build 4 core pages: Home, Trip Hub, Itinerary, Photos
- Implement responsive design with Springbok color scheme
- Integrate Google Photos album
- Deploy to GitHub Pages
- Test on mobile and desktop browsers

**Phase 2 (Post-Trip Updates):**
- Add exact dates to itinerary (after trip completion)
- Update photo gallery with trip photos
- Add post-trip reflections/content
- Potentially add deferred pages (Practical Info, About Family, etc.)

### 11.2 Update Process
1. **Itinerary Updates**: Owner notifies developer → Developer updates HTML → Changes pushed to GitHub → Site auto-deploys
2. **Photo Updates**: Owner adds photos to Google Photos album → Photos automatically appear on site (if embedded) or link remains current
3. **Text Updates**: Developer makes changes or owner edits via GitHub web interface (with guidance documentation)

## 12. Confirmed Decisions Summary

All requirements have been confirmed through stakeholder Q&A (see `Docs/questions.md`). Key decisions:

| Decision Point | Confirmed Choice |
|----------------|------------------|
| **Pages (Phase 1)** | Home, Trip Hub, Itinerary, Photo Gallery |
| **Pages (Deferred)** | Practical Info, About Family, Contact, Packing List |
| **Date Display** | Relative day numbering (Day 1, Day 2, etc.) |
| **Photo Hosting** | Google Photos (external link/embed) |
| **Photo Management** | Owner manages via Google Photos album |
| **Color Scheme** | Springbok green (#1B3838) and gold (#FFB302) |
| **Authentication** | None (public site with privacy via content exclusions) |
| **Gallery Style** | Grid with lightbox |
| **Maps** | Not initially; add later if needed |
| **Primary Devices** | Mobile and desktop (responsive design) |
| **Site Maintenance** | Owner (with developer support for HTML updates) |
| **Update Method** | Manual notification → developer updates HTML |
| **Repository** | https://github.com/kendrewp/PeaceyFamily |
| **Trip Duration** | 24 days (July 2026) |
| **Blank Days Display** | Show all days; mark unplanned days as "To Be Planned" |
| **Post-Trip Plan** | Add exact dates and content after trip completion |

## 13. Ready for Development

All requirements are finalized. Development can proceed with the confirmed specifications above. Refer to `Docs/questions.md` for detailed stakeholder Q&A documentation.
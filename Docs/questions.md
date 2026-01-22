# Project Clarification Questions
**Date**: January 22, 2026  
**Purpose**: Gather factual information needed to build the Peacey Family Website

Please answer the questions below with specific, factual information. Recommendations are provided where applicable to help guide your decisions.

---

## 1. Trip Details & Content

### 1.1 Trip Dates
**Question**: What are the exact trip dates for South Africa 2026?  
**Format**: Please provide start and end dates (e.g., "March 15 - March 30, 2026")  
**Answer**: 
Wednesday	7/8/26	Leave Denver/DC
Thursday	7/9/26	Arrive Cape Town - 5:10 PM
Friday	7/10/26	
Saturday	7/11/26	
Sunday	7/12/26	
Monday	7/13/26	
Tuesday	7/14/26	
Wednesday	7/15/26	
Thursday	7/16/26	
Friday	7/17/26	
Saturday	7/18/26	
Sunday	7/19/26	
Monday	7/20/26	
Tuesday	7/21/26	
Wednesday	7/22/26	
Thursday	7/23/26	
Friday	7/24/26	
Saturday	7/25/26	Arrive Kruger National Park
Sunday	7/26/26	Sunrise game drive
Monday	7/27/26	Sunrise game drive
Tuesday	7/28/26	Sunrise game drive
Wednesday	7/29/26	Leave Kruger National Park
Thursday	7/30/26	Leave JHB - 7:00 PM
Friday	7/31/26	Arrive Denver - 3:40 PM , DC - 1:35 PM

---

### 1.2 Existing Photos
**Question**: Do you have existing photos to include now, or will this be populated later?  
**If you have photos now**: Where are they currently stored? (e.g., local folder, Google Photos, iCloud)  
**Recommendation**: For GitHub Pages, photos should be committed to the repository in an `images/` or `assets/` folder. Typical formats: JPG (compressed for web, ~100-300KB per image).  
**Answer**: 
No existing photo's
Is it possible for GitHub Pages to access a database - with no additional costs?
---

### 1.3 Itinerary/Agenda Content
**Question**: Do you have the itinerary/agenda content ready? (flights, accommodations, activities, etc.)  
**If yes**: In what format? (e.g., Google Doc, spreadsheet, notes)  
**Recommendation**: A day-by-day format works best for website display. Example:
- **Day 1 (March 15)**: Flight departure, arrival in Cape Town, hotel check-in
- **Day 2 (March 16)**: Table Mountain, V&A Waterfront

**Answer**: 
The itinery can be found in this spreadsheet

~/OneDrive/South Africa 2026/South Africa 2026.xlsx
---

### 1.4 Home Page Content
**Question**: Do you have any specific content/text ready for the home page introduction?  
**Recommendation**: If not ready, I'll use placeholder text like "Welcome to the Peacey Family hub! Follow along as we adventure through South Africa in 2026." You can replace it later.  
**Answer**: 
Use a place holder
---

## 2. Site Structure Decisions

### 2.1 Page Inclusion Confirmation
**Question**: The PRD lists several "optional" or "to be confirmed" pages. Which do you definitively want included in the initial version?

Please mark each page as **Include** or **Defer**:
- [ ] Home / Landing Page (index.html) — **Required/Core**
- [ ] South Africa Trip Hub Page — **Required/Core**
- [ ] Itinerary / Agenda Page — **Required/Core**
- [ ] Photo Gallery Page — **Required/Core**
- [ ] Practical Information Page (flights, accommodations, visas)
- [ ] About the Family Page
- [ ] Contact/Resources Page
- [ ] Packing List / Tips Page

**Recommendation**: Start with the core 4 pages (Home, Trip Hub, Itinerary, Gallery) and add others as content becomes available.  
**Answer**: 

---

### 2.2 Photo Contribution Method
**Question**: The PRD mentions family members contributing photos but no direct uploads. How exactly do you want family members to contribute photos after the initial site is built?

**Options**:
- **Option A**: Family sends photos to you via email/messaging, and you add them via GitHub
- **Option B**: Family members with GitHub accounts make pull requests
- **Option C**: Link to external album (Google Photos, Dropbox) that family updates
- **Option D**: No contributions needed; you'll handle all updates

**Recommendation**: Option A (you manage updates) is simplest for non-technical family members.  
**Answer**: 

---

## 3. Technical Specifications

### 3.1 Repository Setup
**Question**: Does the GitHub repository already exist?  
**If yes**: What is the exact GitHub URL? (e.g., `https://github.com/username/PeaceyFamily`)  
**If no**: What should the repository name be?  
**Current local path**: `/Users/kendrewpeacey/Projects/PeaceyFamily`  
**Answer**: 
yes: https://github.com/kendrewp/PeaceyFamily
---

### 3.2 GitHub Pages URL
**Question**: What URL format do you want?  
**Options**:
- **Default**: `https://[username].github.io/PeaceyFamily/`
- **Custom domain**: Your own domain (e.g., `peacey.family`) — requires DNS setup

**Recommendation**: Start with default; custom domains can be added later easily.  
**Answer**: 
We will add the custom domain later
---

### 3.3 Primary Devices/Browsers
**Question**: What devices do most family members use to browse? (e.g., "mostly iPhones", "mix of mobile and desktop", "primarily tablets")  
**Recommendation**: I'll build mobile-first responsive design regardless, but knowing primary devices helps prioritize testing.  
**Answer**: 
Mobile and desktop
---

## 4. Privacy & Access

### 4.1 Sensitive Information
**Question**: Are there specific types of information you want to exclude from the public site?

**Recommendation**: Avoid including:
- Exact home addresses
- Flight confirmation numbers
- Phone numbers or email addresses
- Passport/visa details
- Credit card or booking reference numbers

Safe to include:
- General locations (e.g., "Cape Town", "Kruger National Park")
- Hotel names (but maybe not full addresses)
- Activity names and times
- General packing lists

**Your guidance**: 
Exclude:

- Exact home addresses
- Flight confirmation numbers
- Phone numbers or email addresses
- Passport/visa details
- Credit card or booking reference numbers

---

### 4.2 Site Maintenance
**Question**: Who will update the site after initial launch? Is this you, or should it be designed for other family members with basic Git knowledge?  
**If others**: Do they have GitHub accounts and basic familiarity with commits/pull requests?  
**Recommendation**: I can provide a simple guide (`HOW_TO_UPDATE.md`) for updating content via GitHub's web interface (no command line needed).  
**Answer**: 
Me
---

## 5. Design Preferences

### 5.1 Color Scheme
**Question**: The PRD suggests "Soft blues/greens" with "Orange/yellow accents." Do you have:
- Specific hex color codes? (e.g., `#3498db`, `#f39c12`)
- Reference websites with colors you like?

**Recommendation**: If no preferences, I'll select a palette like:
- Primary: `#4A90A4` (soft teal blue)
- Secondary: `#7CB342` (soft green)
- Accent: `#FF9800` (warm orange)
- Background: `#F5F5F5` (light gray)
- Text: `#333333` (dark gray)

**Answer**: 
Green and gold - the same as the South African Springbok team - use @web to determine the exact colors
---

### 5.2 Family Photo/Logo
**Question**: Do you have a family photo or logo to use for the hero section on the home page?  
**If yes**: What format/where is it located?  
**Recommendation**: If not available now, I'll create a placeholder space that makes it easy to drop in later. Ideal size: ~1200x600px for hero images.  
**Answer**: 
No available yet
---

## 6. Interactive Features

### 6.1 Photo Gallery Style
**Question**: For the photo gallery, what style do you prefer?

**Options**:
- **Grid with lightbox**: Photos in rows/columns, click to enlarge in popup (recommended for simplicity)
- **Carousel/slider**: Swipe through photos one at a time
- **Masonry layout**: Pinterest-style varying heights

**Recommendation**: Grid with lightbox is most versatile and family-friendly.  
**Answer**: 
Grid with lightbox is most versatile and family-friendly.
---

### 6.2 Map Integration
**Question**: Do you have specific locations/addresses to embed in maps for the Practical Information page?  
**If yes**: Please list (e.g., "Cape Town International Airport", "Kruger National Park entrance")  
**Recommendation**: Google Maps embeds are easy to add later. Can start without maps if addresses aren't finalized.  
**Answer**: 
Start without maps
---

## 7. Timeline & Priority

### 7.1 Target Launch Date
**Question**: What's your target launch date for the website?  
**Purpose**: Is this pre-trip (to help with planning) or post-trip (to share memories)?  
**Answer**: 
Currently pre trip
---

### 7.2 Development Priority
**Question**: Which pages should I complete first?

**Recommendation**: Suggested phases:
- **Phase 1** (MVP): Home + Trip Hub + Itinerary (with placeholder content)
- **Phase 2**: Photo Gallery + Practical Info
- **Phase 3**: Additional pages (About, Contact, etc.)

**Your priority order**: 
- **Phase 1** (MVP): Home + Trip Hub + Itinerary (with placeholder content)
- **Phase 2**: Photo Gallery + Practical Info
- **Phase 3**: Additional pages (About, Contact, etc.)
---

## 8. Additional Questions/Notes

**Question**: Is there anything else important I should know that wasn't covered in the PRD or questions above?

**Answer**: 
As this page is public I would like to implement a user name and password to access it.
---

## 9. Follow-Up Clarifications (Based on Initial Answers)

### 9.1 Authentication/Password Protection (CRITICAL)
**Context**: You mentioned wanting username and password protection for the public site.

**FACT**: GitHub Pages (free) does **NOT support password protection or authentication**. GitHub Pages serves static HTML files publicly without any server-side logic to handle logins.

**Your options are:**
- **Option A**: Keep the site on GitHub Pages but make the repository **private** (site still publicly accessible once someone has the URL, but not discoverable via search engines). This is minimal protection.
- **Option B**: Use a **paid third-party service** that supports static site authentication (e.g., Netlify with password protection, Vercel with authentication add-ons). These have free tiers with auth features.
- **Option C**: Use a **client-side password system** (JavaScript-based "fake" password that's not secure but deters casual visitors). This is NOT real security - anyone technical can bypass it.
- **Option D**: Accept that the site is fully public (with obscure URL) and avoid posting sensitive information.

**Question**: Which option do you prefer, understanding the limitations of free GitHub Pages?

**Answer**:
Option D, but exclude exact dates. We will add the post trip.
---

### 9.2 Database for Photos
**Context**: You asked: "Is it possible for GitHub Pages to access a database - with no additional costs?"

**FACT**: GitHub Pages cannot access a traditional database. It serves only static files (HTML, CSS, JavaScript, images).

**Your options for photos are:**
- **Option A**: Commit photos directly to the GitHub repository (stored as files, not in a database). Family sees photos rendered on the site. Simple but increases repo size.
- **Option B**: Host photos on external free service (Google Photos, Imgur, Dropbox) and embed/link them in the website. Photos live elsewhere; website just displays them.
- **Option C**: Use a free "backend as a service" like Firebase Storage (free tier) with JavaScript to fetch/display photos dynamically. More complex setup.

**Question**: What problem are you trying to solve with a database? Are you concerned about:
- Storage space in the GitHub repo?
- Ability for family to upload photos directly without GitHub?
- Something else?

**Answer**:
Option B: what information will you need?
---

### 9.3 Which Pages to Include (Unanswered from Section 2.1)
**Context**: You didn't mark which pages you want in the initial version beyond the recommended Phase 1.

**Please confirm** which pages to include in the **initial build**:

- [x] Home / Landing Page — **Must include**
- [x] South Africa Trip Hub Page — **Must include**
- [x] Itinerary / Agenda Page — **Must include**
- [x] Photo Gallery Page — **Must include**
- [ ] Practical Information Page (flights, accommodations, visas) — **Include or defer?**
- [ ] About the Family Page — **Include or defer?**
- [ ] Contact/Resources Page — **Include or defer?**
- [ ] Packing List / Tips Page — **Include or defer?**

**Answer**: (Mark with 'Include' or 'Defer' for each unchecked item)
Defer these pages
- [ ] Practical Information Page (flights, accommodations, visas) — **Include or defer?**
- [ ] About the Family Page — **Include or defer?**
- [ ] Contact/Resources Page — **Include or defer?**
- [ ] Packing List / Tips Page — **Include or defer?**

---

### 9.4 Photo Contribution Method (Unanswered from Section 2.2)
**Context**: Need to understand how family members will contribute photos after the initial site is built.

**Options**:
- **Option A**: Family sends photos to you via email/messaging, and you add them via GitHub
- **Option B**: Link to external album (Google Photos) that family updates directly
- **Option C**: No contributions needed; you'll handle all updates

**Question**: Which option do you prefer?

**Answer**:
Option B
---

### 9.5 Itinerary Spreadsheet Access
**Context**: You mentioned the itinerary is in `~/OneDrive/South Africa 2026/South Africa 2026.xlsx`

**Question**: Can you either:
- **Option A**: Share the spreadsheet content with me (copy/paste the relevant columns)
- **Option B**: Provide read access if it's in OneDrive/Google Sheets
- **Option C**: Let me build the itinerary page with placeholder structure that you'll populate with the spreadsheet data later

**Which approach works best?**

**Answer**:
The spreadsheet is in OneDrive, how do I share it? How will you monitor it for updates?
---

### 9.6 Trip Itinerary Blank Days
**Context**: Based on your dates (July 8-31, 2026), the itinerary shows:
- **Cape Town portion**: July 9-25 (17 days with many blank days between July 10-24)
- **Kruger National Park**: July 25-29 (4 days with activities specified)

**Question**: For the blank days (July 10-24), are these:
- Days where plans are not yet finalized?
- Free days for exploration?
- Should I display them as "Free Day / Relaxation" or leave them blank until you provide details?

**Answer**:
This trip is only in the planning stages, so not yet finalized.
---

### 9.7 Springbok Colors Confirmation
**Research Result**: The official South African Springboks rugby team colors are:
- **Green**: #1B3838 (Medium Jungle Green)
- **Gold**: #FFB302 (UCLA Gold)

**Question**: Please confirm these are the colors you want for the website design.

**Answer**:
These are good
---

## 10. Additional Clarifications Needed (Based on Section 9 Answers)

### 10.1 Itinerary Date Display (IMPORTANT)
**Context**: You answered "Option D, but exclude exact dates" for authentication, and mentioned "We will add the post trip."

**FACT**: There's a potential conflict here. You provided specific dates (July 8-31, 2026) in Section 1.1, but now want to "exclude exact dates."

**Clarification needed**: How should the itinerary page display date information?

**Options**:
- **Option A**: Show relative days only (e.g., "Day 1: Depart Denver/DC", "Day 2: Arrive Cape Town") without specific dates
- **Option B**: Show general timeframe only (e.g., "July 2026", "Late July 2026") without specific dates
- **Option C**: Show month and day-of-week only (e.g., "Wednesday - Depart", "Thursday - Arrive Cape Town") without dates
- **Option D**: Build itinerary structure with NO dates initially, and you'll add exact dates after the trip is completed

**Question**: Which option accurately reflects what you want for the itinerary display?

**Answer**:
Option A
---

### 10.2 External Photo Service Setup
**Context**: You chose Option B (external photo service) and asked: "what information will you need?"

**For external photo hosting, I need the following information**:

1. **Which service do you prefer?**
   - Google Photos (family-friendly, easy sharing)
   - Imgur (simple, direct image links)
   - Dropbox (if you already use it)
   - OneDrive (since you're already using it for the spreadsheet)
   - Other?

2. **Who will create and manage the photo album?**
   - You will create it and share the link with me
   - You want me to provide instructions for family to create it
   - Other arrangement?

3. **When do you plan to have the photo album set up?**
   - Already exists (provide link)
   - Will create before initial site launch
   - Will create after initial site launch (I'll build placeholder gallery)

**Please answer**:
1. Preferred service: Google Photos
2. Who manages album: I do, here is the link https://photos.app.goo.gl/xYL5FiS8oZS4CCeC8
3. Timeline: Already exists https://photos.app.goo.gl/xYL5FiS8oZS4CCeC8

---

### 10.3 OneDrive Spreadsheet Sharing & Updates
**Context**: You asked "The spreadsheet is in OneDrive, how do I share it? How will you monitor it for updates?"

**FACT**: Since GitHub Pages is a static site (not dynamic), I **cannot automatically monitor** spreadsheet updates. The site must be manually updated each time the itinerary changes.

**How to share OneDrive file**:
1. Open the file in OneDrive online
2. Click "Share" button
3. Choose "Anyone with the link can view"
4. Copy the link and provide it to me

Here is the link: https://1drv.ms/x/c/2047e2368cb0b4d9/IQDOm2GBK0WKT6SmP510p-5UAbPFcXJWr2QSEYe0SoDn0kA?e=YpY6SP

**How updates will work**:
- **Initial build**: I'll read your spreadsheet content and build the itinerary page HTML
- **Future updates**: When you update the spreadsheet, you'll need to either:
  - **Option A**: Notify me and I'll manually update the website HTML with new content
  - **Option B**: I can teach you how to edit the HTML file directly via GitHub web interface
  - **Option C**: Use a more complex solution (Google Sheets API + JavaScript) to fetch live data, but this requires more setup

**Questions**:
1. Do you want to share the OneDrive spreadsheet now for me to review the structure, or wait until it's more finalized?
2. Which update approach do you prefer (Option A, B, or C)?

**Answers**:
1. Share now or wait: https://1drv.ms/x/c/2047e2368cb0b4d9/IQDOm2GBK0WKT6SmP510p-5UAbPFcXJWr2QSEYe0SoDn0kA?e=YpY6SP
2. Update approach: Option A

---

### 10.4 Itinerary Placeholder Content
**Context**: You mentioned "This trip is only in the planning stages, so not yet finalized" regarding blank days.

**Question**: Since the itinerary is still being planned, should I:
- **Option A**: Build the itinerary page with only the confirmed activities you've listed (arrival, Kruger dates, departure) and leave other days blank/omitted
- **Option B**: Display all days July 8-31 with confirmed activities shown and blank days marked as "To Be Planned" or "Free Day"
- **Option C**: Build the itinerary page structure with placeholder text (e.g., "Itinerary coming soon") that you'll update later
- **Option D**: Wait to build the itinerary page until plans are more finalized (include in Phase 2 or 3)

**Which option reflects your preference?**

**Answer**:
Option B
---

### 10.5 "Post Trip" Addition Clarification
**Context**: You mentioned "We will add the post trip" in your authentication answer.

**Question**: What does "post trip" refer to?
- **Option A**: You'll add exact dates to the itinerary AFTER the trip is completed (for memories/documentation)
- **Option B**: You'll add post-trip photos and reflections to the site after returning
- **Option C**: You'll add both exact dates and post-trip content after the trip
- **Option D**: Something else?

**Answer**:
Option C
---

## 11. Final Clarification

### 11.1 Spreadsheet Content Beyond Basic Dates
**Context**: I can access your OneDrive spreadsheet but want to confirm what information is in it beyond the dates you provided in Section 1.1.

**Question**: Does your OneDrive spreadsheet contain additional information beyond the dates and brief activities you listed (Arrive Cape Town, Kruger game drives, etc.)? For example:
- Hotel names?
- Specific activity details?
- Flight information (airlines, departure/arrival cities)?
- Booking information?
- Packing lists?
- Contact information?
- Other planning details?

If yes, please briefly describe what additional columns/information are in the spreadsheet so I know what to extract for the website.

If the spreadsheet only has the dates/activities you already provided in Section 1.1, I'll use that as the itinerary content.

**Answer**:
No not yet, Column B is the date, Column C is what is planned.
---

## Next Steps
Once you've completed this document:
1. Save your answers
2. Provide it back to me
3. I'll begin building the website structure based on your specific requirements

**Note**: All answers should be factual. If you don't have information yet (e.g., itinerary details), just note "Not ready yet" and I'll use placeholder content you can update later.

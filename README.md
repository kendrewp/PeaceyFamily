# Peacey Family Website

A static website documenting the Peacey Family's South Africa adventure in July 2026.

## 🌍 Live Site

**URL:** [https://kendrewp.github.io/PeaceyFamily/](https://kendrewp.github.io/PeaceyFamily/)

## 📋 Overview

This website serves as a digital hub for our 24-day journey through South Africa, featuring:
- **Home Page:** Welcome and introduction to our adventure
- **Trip Hub:** Overview with links to itinerary and photos
- **Itinerary:** Day-by-day schedule (using relative day numbering for privacy)
- **Photo Gallery:** Links to our Google Photos album

## 🎨 Design

The site uses the South African Springbok rugby team colors:
- **Primary Green:** #1B3838
- **Primary Gold:** #FFB302

## 🛠️ Technology Stack

- **HTML5:** Semantic markup
- **CSS3:** Custom styling with CSS Grid and Flexbox
- **Vanilla JavaScript:** Mobile navigation and lightbox functionality
- **GLightbox:** Lightweight lightbox library (CDN)
- **GitHub Pages:** Free static site hosting

## 📂 Project Structure

```
/PeaceyFamily/
├── index.html              # Home page
├── trip.html               # Trip hub page
├── itinerary.html          # 24-day itinerary
├── photos.html             # Photo gallery
├── css/
│   └── styles.css          # Global styles
├── js/
│   └── main.js             # Main JavaScript
├── images/                 # Images directory (currently empty)
├── Docs/                   # Project documentation
│   ├── Product Requirements.md
│   └── questions.md
├── .gitignore              # Git ignore rules
└── README.md               # This file
```

## 🔄 How to Update Content

### Updating the Itinerary

1. Open `itinerary.html` in a text editor or via GitHub web interface
2. Find the day entry you want to update (search for "Day X")
3. Modify the content within the `<div class="day-content">` section
4. For "To Be Planned" days, remove the `to-be-planned` class and update the content
5. Save and commit the file

**Example day entry:**
```html
<div class="day-entry highlight">
  <div class="day-number">Day 5</div>
  <div class="day-content">
    <h3>Table Mountain</h3>
    <p>Hike Table Mountain and visit the V&A Waterfront</p>
  </div>
</div>
```

### Updating Photos

Photos are managed through Google Photos:
- **Album URL:** https://photos.app.goo.gl/xYL5FiS8oZS4CCeC8
- Add photos directly to the Google Photos album
- The album link on the website will remain current

**To embed photos directly on the website (optional):**
1. Upload photos to the `images/` directory
2. Edit `photos.html`
3. Uncomment the photo grid section
4. Add photo items following the template provided

### Updating Text Content

1. Navigate to the HTML file you want to edit
2. Find the section with the text you want to change
3. Modify the content within the HTML tags
4. Save and commit the file

### Adding a New Page

1. Create a new `.html` file in the root directory
2. Copy the header and footer from any existing page
3. Add your content in the `<main>` section
4. Update navigation links in all pages to include the new page

## 🚀 Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

### To Deploy Changes:

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Update itinerary with Cape Town activities"

# Push to GitHub
git push origin main
```

The site will be live at the GitHub Pages URL within 1-2 minutes.

### Enabling GitHub Pages (if not already enabled):

1. Go to repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "main" branch and "/" (root) folder
4. Click "Save"

## 📝 Privacy & Security

- **No Exact Dates:** The itinerary uses relative day numbering (Day 1, Day 2, etc.) instead of specific dates for privacy
- **No Sensitive Info:** Excludes confirmation numbers, addresses, phone numbers, and other personal details
- **Public Site:** The site is publicly accessible; share the URL only with trusted family and friends

## 🖼️ Adding Images to the Repository (Optional)

If you prefer to host images directly in the repository instead of using Google Photos:

1. Add images to the `images/` directory
2. Optimize images for web (recommended max 1200px width, compressed JPG/PNG)
3. Update `photos.html` to reference the local images

**Note:** Large image files will increase repository size. Google Photos is recommended for large photo collections.

## 🧪 Testing

Before committing major changes:
1. Test on multiple browsers (Chrome, Safari, Firefox, Edge)
2. Test responsive design on mobile devices or browser dev tools
3. Check all navigation links work correctly
4. Verify no console errors in browser developer tools

## 📞 Support

For complex updates or technical issues, contact the developer for assistance.

## 📄 License

This is a private family project. All rights reserved.

---

**Last Updated:** January 2026  
**Created by:** Claude (AI Assistant)  
**Maintained by:** Kendrew Peacey

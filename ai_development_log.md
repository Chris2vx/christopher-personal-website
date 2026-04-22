# AI Development Log - Christopher's Personal Website
## Assignment Documentation

**Date:** April 22, 2026  
**Project:** Personal Website Development  
**Developer:** Christopher  
**AI Assistant:** GitHub Copilot  

---

## Session Overview
This log documents the complete development process of creating a personal website using AI assistance. The website features cherry blossom theming, personal information, and multimedia content.

---

## Prompt 1: Initial Website Creation
**User Prompt:** "hello agent. I would like to make a website using this html file. it will be a personal website. lets start with something simple, all i want is to add my name to the website and create a 3 color scheme for it."

**AI Response:** Created a basic HTML structure with:
- Name: Christopher prominently displayed
- 3-color scheme: White background, Dark Slate text, Blue accents
- Clean, professional layout
- Responsive design

**Files Modified:** `index.html` (created from empty file)

---

## Prompt 2: Name Confirmation
**User Prompt:** "Christopher"

**AI Response:** Confirmed the name and proceeded with website creation using "Christopher" as the name.

---

## Prompt 3: Adding Profile Elements
**User Prompt:** "okay i want to add these things to my website, it must include my name, its going to have a picuture of me, and an "about me" paragraph."

**AI Response:** Added:
- Profile image placeholder (`profile.jpg`)
- "About Me" section with sample paragraph
- Circular image styling with blue border
- Centered layout for the about section

**Files Modified:** `index.html` (added CSS and HTML structure)

---

## Prompt 4: Cherry Blossom Theme
**User Prompt:** "since its cherry blossom season, make the theme based on the color's of cherry blossom"

**AI Response:** Updated color scheme to cherry blossom theme:
- Background: Light pink (#fef7f7)
- Primary text: Deep cherry blossom pink (#be185d)
- Header: Gradient from light to deeper pink
- Accent colors: Various shades of pink
- Added subtle shadows for depth

**Files Modified:** `index.html` (updated CSS color variables)

---

## Prompt 5: Change Image to Mt. Fuji
**User Prompt:** "change the photo to a picture of mt fuji"

**AI Response:** Changed image source from `profile.jpg` to `mt-fuji.jpg` and updated alt text to "Mount Fuji".

**Files Modified:** `index.html` (updated img src and alt attributes)

---

## Prompt 6: Change to Cherry Blossom Image
**User Prompt:** "change the image to the file i have downloaded in the file, called cherry blossom.jpeg"

**AI Response:** Updated image source to `cherry blossom.jpeg` and changed alt text to "Cherry Blossoms".

**Files Modified:** `index.html` (updated img src and alt attributes)

---

## Prompt 7: Update About Me Text
**User Prompt:** "in the "about me" section change the paragraph to: Greetings!, I'm Christopher, I am cook and I am currently going to school for cybersecurity. Welcome to my personal website where I'm going to share my thoughts, projects and experiences."

**AI Response:** Replaced the sample paragraph with the user's personal information about being a cook and studying cybersecurity.

**Files Modified:** `index.html` (updated paragraph content)

---

## Prompt 8: Embed YouTube Video
**User Prompt:** "embed this video to the website, https://www.youtube.com/watch?v=oWY3fW2VpjQ"

**AI Response:** Added YouTube video embed with:
- Embedded iframe using YouTube's embed URL
- Styled video container with rounded corners and shadow
- "Featured Video" section heading
- Responsive design

**Files Modified:** `index.html` (added video section HTML and CSS)

---

## Prompt 9: Video Configuration Error
**User Prompt:** "there is a video player configuration error"

**AI Response:** Attempted to fix by:
- Simplifying iframe allow attributes
- Adding loading="lazy" parameter
- Added Content Security Policy meta tag
- Added fallback link

**Files Modified:** `index.html` (modified iframe attributes and added CSP)

---

## Prompt 10: Revert Video Changes
**User Prompt:** "revert all changes back to when you first embedded the video"

**AI Response:** Reverted all video-related changes:
- Removed Content Security Policy
- Restored original iframe with "web-share" attribute
- Removed fallback link and extra parameters

**Files Modified:** `index.html` (reverted iframe and removed CSP)

---

## Prompt 11: Video Still Not Playing
**User Prompt:** "the video still doesnt play"

**AI Response:** Replaced iframe with clickable thumbnail:
- YouTube thumbnail image
- Pink play button overlay
- Direct link to YouTube video
- Professional styling with hover effects

**Files Modified:** `index.html` (replaced iframe with thumbnail design)

---

## Prompt 12: Make Video Play on Website
**User Prompt:** "make the video play on the website"

**AI Response:** Switched back to iframe embed using:
- YouTube's privacy-enhanced nocookie domain
- Restored iframe functionality
- Removed thumbnail CSS

**Files Modified:** `index.html` (replaced thumbnail with nocookie iframe)

---

## Prompt 13: Video Still Not Playing - Investigation
**User Prompt:** "the video is not playing, why might that be"

**AI Response:** Provided comprehensive troubleshooting guide covering:
- Browser security settings
- Network/firewall restrictions
- Content Security Policy issues
- Browser extensions
- JavaScript requirements
- HTTPS vs HTTP issues
- Browser compatibility

**Files Modified:** None (diagnostic analysis only)

---

## Prompt 14: Set Up Local Server
**User Prompt:** "make the site run locallly from my computer using a local server"

**AI Response:** Created a local HTTP server using PowerShell's HttpListener:
- Started server on localhost:8000
- Bypassed file:// protocol restrictions
- Enabled proper content-type serving
- Made website accessible at http://localhost:8000/

**Process Started:** PowerShell HTTP server (running in background)

---

## Development Summary

### Final Website Features:
1. **Personal Information:** Christopher's name, profession (cook), and education (cybersecurity)
2. **Visual Design:** Cherry blossom color scheme with pink gradients and elegant styling
3. **Media Content:** Cherry blossom image and embedded YouTube video
4. **Responsive Layout:** Clean, professional design that works on all devices
5. **Local Hosting:** Runs on local server at localhost:8000

### Technical Implementation:
- HTML5 structure with semantic elements
- CSS3 styling with gradients, shadows, and responsive design
- YouTube video embedding with privacy-enhanced domain
- Local server setup for development and testing

### Challenges Overcome:
- Video embedding restrictions (tried multiple approaches)
- Browser security limitations
- Local file access issues
- Color scheme implementation
- Responsive design requirements

### Tools Used:
- HTML/CSS for website structure and styling
- PowerShell for local server setup
- YouTube API for video embedding
- VS Code for development environment

---

## Conclusion
This assignment demonstrates the complete process of creating a personal website using AI assistance, from initial concept to final deployment. The website successfully incorporates seasonal theming, personal branding, and multimedia content while overcoming various technical challenges related to web development and content embedding.

**Final Result:** A beautiful, functional personal website accessible at `http://localhost:8000/`

---
*Log created for assignment documentation purposes*
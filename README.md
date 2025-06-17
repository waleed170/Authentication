# Tokyo Ghoul Themed Website

A Tokyo Ghoul-inspired website featuring a login page, registration form, and motivational quotes section with seamless audio continuity across pages.

## Features

- **Tokyo Ghoul Themed Design**:
  - Red and black color scheme
  - Background images from Tokyo Ghoul
  - Custom favicon

- **Interactive Pages**:
  - **Login Page**: Email/password form with registration option
  - **Registration Form**: Collects name, email, age, country, and password
  - **Quotes Page**: Displays motivational quotes in red boxes

- **Seamless Audio Experience**:
  - Background audio persists across all pages
  - Remembers playback position using localStorage
  - Auto-resumes when navigating between pages

- **Responsive Design**:
  - Adapts to mobile devices (removes background images on small screens)
  - Fixed background attachment for desktop view

## Technical Details

- **HTML5** structure with semantic elements
- **CSS3** features:
  - Flexbox layout for quotes
  - Media queries for responsiveness
  - Nested CSS (Sass-like syntax)
  
- **JavaScript** functionality:
  - Audio position saving/restoring
  - Form navigation handling
  - Error handling for autoplay restrictions

## How to Use

1. Open `index.html` to access the main page
2. Navigate between:
   - Login form
   - Registration page (via Register button)
   - Quotes page (via "Famous Quotes" link)
3. Enjoy continuous background music across all pages

## Requirements

- Modern web browser with JavaScript enabled
- Audio file (`WhatsApp Audio 2024-07-28 at 00.34.17_58bc8693.mp3`) in the same directory

## Note

The audio autoplay might be restricted by some browsers - user interaction may be required to start playback initially.

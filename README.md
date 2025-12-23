# Apple Notes Blogger Theme - Enhanced Edition

A beautifully crafted Blogger theme that faithfully recreates the Apple Notes experience with modern enhancements and dark mode support.

## ✨ New Features & Enhancements

### 🎨 Dark Mode Support
- **Automatic Theme Switching:** Toggle between light and dark modes with a single click
- **Persistent Preference:** Your theme choice is saved in localStorage and persists across sessions
- **Theme-Aware Colors:** All UI elements automatically adjust for optimal contrast
- **Apple Notes Aesthetic:** Dark mode colors carefully matched to native Apple Notes dark theme
- **Smart Highlights:** Text selection and highlights use appropriate colors in both modes

### 🎯 Enhanced UI & Styling
- **Theme Variables:** Fully customizable CSS variables for Backgrounds, Accents, and Typography
- **Blogger Customization:** Change colors directly from Blogger > Customize panel without touching code
- **Visual Polish:**
    - Removed link underlines for a cleaner look
    - Authentic "Apple Notes Yellow" active states and link colors
    - Improved selection and focus states for search bars and list items
    - Pixel-perfect alignment of headers and window controls
    - Theme-aware table styles with automatic color adjustments
    - Custom highlight class for text emphasis

### 🔧 Functional Additions
- **Native Share Button:** Functional "Share" button using native OS share menu on supported devices
- **Dynamic Sidebar Footer:**
    - Replaced hardcoded buttons with dynamic Link List widget
    - Manage footer links entirely via Blogger > Layout editor
    - Inline styling with pipe separators for minimal aesthetic
- **Archive Widget Support:**
    - Fixed archive year display in middle section title
    - Archive period shown in browser page title
    - First post automatically displays when viewing archive pages

### 📱 Layout & Responsiveness
- **Admin Panel Compatibility:** Structural fixes ensure widgets stack correctly in Blogger Layout editor
- **Mobile Responsiveness:** Improved visibility of Search and Date headers across all devices
- **Cross-Platform Toggle:** Dark mode button appears on all pages (desktop and mobile)

## 🎨 Using Enhanced Features

### Text Highlighting
Instead of inline styles, use the `.highlight` class for theme-aware text highlighting:

```html
<span class="highlight">highlighted text</span>
```

### Tables
Simple table markup with automatic theme styling:

```html
<table>
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
    </tr>
  </tbody>
</table>
```

## 🚀 Installation

1. Download `applenotes-v3.xml`
2. Go to Blogger > Theme > Backup/Restore
3. Upload the XML file
4. Customize colors via Theme > Customize if desired

## 🎯 Future Roadmap

- [ ] **Search Experience:** Instant search results as you type (AJAX)
- [ ] **Reading Time Estimates:** Display estimated reading time for each post
- [ ] **Table of Contents:** Auto-generated TOC for long posts

## 📝 Changelog

### v3.0 - Dark Mode Edition
- ✅ Full dark mode implementation with toggle button
- ✅ Theme-aware CSS variables for all colors
- ✅ Fixed archive widget display and navigation
- ✅ Added text highlight and table styling classes
- ✅ Improved text contrast across all UI elements
- ✅ Dark mode toggle on all pages (desktop and mobile)

### v2.0 - Enhanced Edition
- ✅ Theme customization variables
- ✅ Native share button
- ✅ Dynamic sidebar footer
- ✅ Layout fixes for admin panel
- ✅ Mobile responsiveness improvements

## 🤝 Feedback

We would love to hear your thoughts!

- What features are missing?
- Do you encounter any layout bugs?
- How can we make the writing experience better?

## 👨‍💻 Created By

**Emin Fidan**

---


## Credits
Based on the original [Apple Notes Blogger Theme](https://github.com/muddassirhq/apple-notes-blogger-theme) by Muddassir Hussain.

*Inspired by the elegance of Apple Notes, built for the flexibility of Blogger.*

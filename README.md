# 📱 Fix Broken Mobile Layout

A responsive web design project where a desktop-only landing page was intentionally broken on mobile devices and then fully refactored using modern CSS techniques.

---

## 🚀 Live Demo

- 🔴 Broken Version: https://broken-layout.vercel.app/
- 🟢 Fixed Version: https://fix-broken-mobile-layout.vercel.app/

---

## 📂 Repository

https://github.com/AMRIsoja/fix-broken-mobile-layout

---

## 🎯 Project Goal

The goal of this project was to:

- Identify responsiveness issues in a desktop-only layout
- Diagnose layout problems using browser DevTools
- Refactor the design using Flexbox, Grid, and media queries
- Ensure full responsiveness from 320px to 1440px
- Eliminate horizontal scrolling on mobile devices

---

## 🧱 Tech Stack

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- Responsive Design Principles

---

## 🐞 Problems Found in Broken Version

The original layout had several responsiveness issues:

- Fixed container width (`1200px`)
- Images overflowing on small screens
- Navigation items not wrapping
- Hero section not adapting to mobile
- Grid layout locked to 3 columns
- Excessive spacing on small screens
- Horizontal scrolling on mobile devices
- No media queries implemented

---

## 🔧 Fixes Implemented

### 1. Responsive Container
Replaced fixed width with fluid layout:

- Used `min(100% - 2rem, 1200px)`
- Prevented overflow on small screens

---

### 2. Responsive Images
- Applied `max-width: 100%`
- Removed fixed image widths

---

### 3. Flexbox Improvements
- Added `flex-wrap` to header and hero sections
- Allowed content stacking on small screens

---

### 4. Responsive Grid System
- Converted fixed 3-column grid into:
  - `repeat(auto-fit, minmax(250px, 1fr))`

---

### 5. Typography Scaling
- Used `clamp()` for fluid typography
- Improved readability across devices

---

### 6. Media Queries
- Added breakpoints for:
  - 768px (tablet)
  - 480px (mobile)

---

### 7. Overflow Fixes
- Added `box-sizing: border-box`
- Applied `overflow-x: hidden` to prevent horizontal scroll

---

## 📱 Responsive Breakpoints

- Mobile: 320px – 480px
- Tablet: 768px
- Desktop: 1024px – 1440px

---

## 📸 Screenshots

### ❌ Before (Broken Mobile Layout)
![Broken Layout](screenshots/before-mobile/)

### ✅ After (Fixed Responsive Layout)
![Fixed Layout](screenshots/after-mobile/)

---

## 🧠 Key Learnings

- How to debug layout overflow issues
- Importance of flexible containers
- Using Flexbox and Grid together effectively
- Mobile-first responsive thinking
- Real-world CSS refactoring techniques

---

## 🏁 Project Outcome

The final result is a fully responsive landing page that:

- Works across all screen sizes
- Has no horizontal scrolling
- Adapts layout dynamically
- Provides a clean user experience on mobile, tablet, and desktop



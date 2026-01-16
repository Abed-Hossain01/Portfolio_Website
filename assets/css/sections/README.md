# Modular CSS Structure

## Overview
The CSS has been reorganized into separate modular files for better maintainability and organization. Each section of the website now has its own dedicated CSS file.

## File Structure

```
assets/css/
├── style.css (original - kept as backup)
└── sections/
    ├── base.css          - CSS variables, resets, and global styles
    ├── animations.css    - All keyframe animations
    ├── navigation.css    - Navigation bar styles
    ├── buttons.css       - Button components
    ├── home.css          - Home section styles
    ├── about.css         - About section styles
    ├── skills.css        - Skills section styles
    ├── projects.css      - Projects section styles
    ├── resume.css        - Resume section styles
    ├── contact.css       - Contact section and form styles
    └── footer.css        - Footer styles
```

## Files Description

### 1. **base.css** (Foundation)
- CSS reset and box-sizing
- CSS custom properties (variables)
  - Colors
  - Typography
  - Spacing
  - Border radius
  - Shadows
- Global body and HTML styles
- Container class
- Section title styles

### 2. **animations.css**
- fadeInLeft
- fadeInRight
- fadeInDown
- fadeInUp
- progressAnimation

### 3. **navigation.css**
- Fixed navigation bar
- Logo styles
- Navigation menu
- Hamburger menu
- Responsive navigation (mobile)

### 4. **buttons.css**
- Primary button styles
- Secondary button styles
- Large button variant
- Hover effects
- Responsive button sizing

### 5. **home.css**
- Home section layout
- Welcome heading (robotic font)
- Home content grid (2 columns)
- Profile wrapper (circular image)
- Text styles (greeting, subtitle, intro)
- Responsive home section

### 6. **about.css**
- About content grid
- Info cards
- Languages list
- Interests section
- Responsive about layout

### 7. **skills.css**
- Skills grid layout
- Skill categories
- Skill bars and progress indicators
- Responsive skills section

### 8. **projects.css**
- Projects grid
- Project cards
- Project icons
- Tech tags
- Hover effects
- Responsive projects layout

### 9. **resume.css**
- Resume section centered layout
- Resume text styles

### 10. **contact.css**
- Contact content grid (2 columns)
- Contact form wrapper
- Form groups, inputs, textarea
- Alert messages (success/error)
- Responsive contact layout

### 11. **footer.css**
- Footer background and layout
- Social links
- Responsive footer (mobile stacking)

## Loading Order

The CSS files are loaded in the following order in `includes/header.php`:

1. **base.css** - Must load first (contains CSS variables)
2. **animations.css** - Animations used across sections
3. **navigation.css** - Navigation bar
4. **buttons.css** - Button components
5. **home.css** - Home section
6. **about.css** - About section
7. **skills.css** - Skills section
8. **projects.css** - Projects section
9. **resume.css** - Resume section
10. **contact.css** - Contact section
11. **footer.css** - Footer

## Benefits of Modular CSS

✅ **Better Organization** - Each section has its own file
✅ **Easy Maintenance** - Find and edit styles quickly
✅ **Reduced Conflicts** - Less chance of style conflicts
✅ **Team Collaboration** - Multiple developers can work on different sections
✅ **Performance** - Can selectively load only needed styles (future optimization)
✅ **Reusability** - Easy to copy sections to other projects

## How to Edit Styles

### To modify a specific section:
1. Locate the section's CSS file (e.g., `sections/home.css`)
2. Make your changes
3. Save the file
4. Refresh your browser (Cmd + Shift + R for hard refresh)

### To add a new section:
1. Create a new CSS file in `assets/css/sections/`
2. Add your styles
3. Link it in `includes/header.php` (after base.css)

### To change global styles:
- Edit `sections/base.css` for:
  - Colors (CSS variables)
  - Spacing values
  - Font families
  - Border radius
  - Shadows

## Original File

The original `style.css` file has been kept as a backup. You can safely delete it once you've verified everything works correctly with the modular structure.

## Browser Compatibility

All CSS features used are widely supported:
- CSS Grid
- Flexbox
- CSS Custom Properties (Variables)
- CSS Animations
- Media Queries

Works on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

---

**Author:** Abed Hossain  
**Date:** January 2026  
**Version:** 2.0 (Modular Structure)

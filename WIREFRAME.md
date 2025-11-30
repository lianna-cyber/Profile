# Portfolio Website Wireframe

## Overview
A Victorian/Sherlockian-themed portfolio for Alexace Kyle P. Obillo, an IT aspirant and beginner front-end developer.

---

## Layout Structure

### Page Width
- **Desktop**: 1200px max-width container
- **Tablet**: Responsive (768px breakpoint)
- **Mobile**: Responsive (480px breakpoint)
- **Side Decorations**: 80px on each side (hidden on tablets/mobile)

---

## Section Breakdown

### 1. NAVIGATION BAR
```
┌─────────────────────────────────────────────────────────┐
│  🔍 Portfolio    [Home] [About] [Skills] [Projects] [Contact]  [🌙]  │
└─────────────────────────────────────────────────────────┘
```
- **Fixed/Sticky** at top
- **Logo**: 🔍 Portfolio (left)
- **Menu Items**: Horizontal navigation (center)
- **Dark Mode Toggle**: 🌙 Button (right)
- **Border**: 3px gold accent at bottom

---

### 2. SIDE DECORATIONS (Desktop Only)
```
┌──────┐                                              ┌──────┐
│ 🔍   │                                              │ 🔎   │
│ 🧩   │          MAIN CONTENT AREA                  │ ⚗️   │
│ 📜   │                                              │ 🧫   │
│ 🔬   │          (1200px max-width)                 │ 💼   │
│ 🎩   │                                              │ ⌚   │
│ 📚   │                                              │ 🗂️   │
│ 🕯️   │                                              │ 📝   │
└──────┘                                              └──────┘
```
- **Left & Right Fixed Decorations**: 80px wide each
- **Items**: 7 floating emoji icons per side
- **Animation**: Float up/down with staggered timing
- **Hover Effect**: Scale + glow
- **Border**: Golden vertical line

---

### 3. HERO SECTION
```
┌─────────────────────────────────────────────┐
│                                             │
│    Welcome, to the file of                 │
│                                             │
│    Alexace Kyle P. Obillo                  │
│                                             │
│    IT Aspirant | Developing Programming   │
│    Prowess | Code Craftsman in Training    │
│                                             │
│         [Examine My Endeavours]            │
│                                             │
└─────────────────────────────────────────────┘
```
- **Background**: Gradient (Dark Brown → Medium Brown)
- **Text Alignment**: Center
- **Padding**: 150px vertical
- **Content**: 
  - Subtitle text (h2)
  - Main heading (h1)
  - Descriptive tagline (p)
  - CTA Button

---

### 4. ABOUT SECTION
```
┌─────────────────────────────────────────────────────────┐
│                  The Case Dossier                       │
│                        ━━━━━                            │
│                                                         │
│  ┌──────────────┐      About Text Section              │
│  │   FRAME      │  • 2 paragraphs of description       │
│  │   (Photo)    │  • Personal background               │
│  │              │  • Skills & commitment               │
│  │  300x300px   │                                      │
│  │              │      ┌─────────────────────────┐     │
│  │              │      │ Credentials             │     │
│  │              │      │ Bachelor of Science in  │     │
│  └──────────────┘      │ Information Technology  │     │
│                        │ University • 2022-2026  │     │
│                        └─────────────────────────┘     │
│                        ┌─────────────────────────┐     │
│                        │ Current Investigation   │     │
│                        │ Front-End Development   │     │
│                        │ React, JavaScript, etc. │     │
│                        └─────────────────────────┘     │
└─────────────────────────────────────────────────────────┘
```
- **Background**: Light beige (alternating from hero)
- **Layout**: 2-column grid (photo left, text right)
- **Photo Frame**: 300x300px with 12px wooden border, gold inset
- **Text**: Two paragraphs + info grid (2 columns)
- **Info Items**: Cards with left border accent

---

### 5. SKILLS SECTION
```
┌─────────────────────────────────────────────────────────┐
│         Arsenal of Tools & Techniques                   │
│                        ━━━━━━━━━━━━━━━━━                │
│                                                         │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐ │
│  │ HTML & CSS   │  │ JavaScript   │  │    React     │ │
│  │    95%       │  │     88%      │  │     85%      │ │
│  │ ████████░   │  │ ████████░   │  │ ████████░   │ │
│  └──────────────┘  └──────────────┘  └──────────────┘ │
│                                                         │
│  ┌──────────────┐  ┌──────────────┐                    │
│  │ Responsive   │  │  UI/UX Design│                    │
│  │   Design     │  │  Principles  │                    │
│  │     90%      │  │     82%      │                    │
│  │ ████████░   │  │ ████████░   │                    │
│  └──────────────┘  └──────────────┘                    │
└─────────────────────────────────────────────────────────┘
```
- **Background**: White
- **Layout**: 5-column responsive grid (auto-fit)
- **Skill Items**: 
  - Header with skill name (left) + percentage (right)
  - Progress bar container with animated fill
  - Bar color: Gradient (brown → gold)
  - Shimmer animation on bar

---

### 6. PROJECTS SECTION
```
┌─────────────────────────────────────────────────────────┐
│                   Solved Cases                          │
│                        ━━━━━━━━                         │
│                                                         │
│  ┌─────────────────┐  ┌─────────────────┐              │
│  │ The Case Database │  │The London Crime │              │
│  │ [HTML][CSS][JS] │  │ Chronicle       │              │
│  │ Description...  │  │ [HTML][CSS][RD] │              │
│  │ [Live] [Repo]   │  │ Description...  │              │
│  └─────────────────┘  │ [Live] [Repo]   │              │
│                       └─────────────────┘              │
│  ┌─────────────────┐  ┌─────────────────┐              │
│  │The Elementary   │  │221B Baker Street│              │
│  │ Quiz Game       │  │ Profile         │              │
│  │ [JS][DOM][HTML] │  │ [HTML][CSS][JS] │              │
│  │ Description...  │  │ Description...  │              │
│  │ [Live] [Repo]   │  │ [Live] [Repo]   │              │
│  └─────────────────┘  └─────────────────┘              │
└─────────────────────────────────────────────────────────┘
```
- **Background**: Light beige
- **Layout**: 4-column responsive grid (auto-fit, min 300px)
- **Project Cards**:
  - Header with title + tech tags
  - Description paragraph
  - Links section (Live Demo, GitHub Repo)
  - Top border: gold accent
  - Left border: brown accent
  - Hover: Lift up effect

---

### 7. CONTACT SECTION
```
┌─────────────────────────────────────────────────────────┐
│                Send a Telegram to 221B                  │
│                        ━━━━━━━━━━━━━━━                  │
│   Have a case that requires investigation? Send word!  │
│                                                         │
│  ┌──────────────────────┐  ┌──────────────────────┐   │
│  │  Contact Form        │  │  Contact Info        │   │
│  │                      │  │                      │   │
│  │  [Name Input  ]      │  │  Telegram            │   │
│  │  [Email Input ]      │  │  john@example.com    │   │
│  │  [Message Box ...]   │  │                      │   │
│  │                      │  │  Telephone           │   │
│  │  [File a Case Button]│  │  +1 (555) 123-4567   │   │
│  │                      │  │                      │   │
│  │                      │  │  Residence           │   │
│  │                      │  │  Baker Street, London│   │
│  │                      │  │                      │   │
│  │                      │  │  Social Links        │   │
│  │                      │  │  [GitHub][LinkedIn]  │   │
│  │                      │  │  [Twitter]           │   │
│  └──────────────────────┘  └──────────────────────┘   │
└─────────────────────────────────────────────────────────┘
```
- **Background**: White
- **Layout**: 2-column grid (form left, info right)
- **Form**:
  - Text input (name)
  - Email input (telegram address)
  - Textarea (5 rows)
  - Submit button
- **Contact Info**:
  - 4 sections with headings
  - Email links, text, social links
  - Buttons on hover effect

---

### 8. FOOTER
```
┌─────────────────────────────────────────────────────────┐
│ © 2025 The Case Dossier of Alexace Kyle P. Obillo     │
│ All mysteries preserved and rights reserved.           │
└─────────────────────────────────────────────────────────┘
```
- **Background**: Dark brown (primary color)
- **Text**: Light cream color
- **Border**: Gold accent at top
- **Padding**: 2rem vertical

---

## Color Palette

### Light Mode
- **Primary**: #2c1810 (Dark Brown)
- **Secondary**: #8b4513 (Saddle Brown)
- **Accent**: #d4af37 (Gold)
- **Background**: #fefbf8 (Off-white)
- **Light BG**: #ede7dd (Beige)
- **Text Dark**: #2c1810
- **Text Light**: #666

### Dark Mode
- **Primary**: #d4af37 (Gold)
- **Secondary**: #8b4513 (Brown)
- **Background**: #1a1410 (Very Dark Brown)
- **Light BG**: #2d2420 (Dark Brown)
- **Text**: #e8dcc8 (Cream)
- **Text Light**: #b8a892 (Tan)

---

## Typography

- **Font Family**: Georgia, Garamond, serif
- **Headings (h1, h2)**: Georgia, 2.5rem-3.5rem
- **Subheadings (h3)**: 1.1rem-1.3rem
- **Body Text**: 1rem
- **Letter Spacing**: 1-2px on headings for Victorian feel

---

## Animations & Interactions

1. **Navigation Links**: Underline animation on hover
2. **Skill Bars**: Fill animation (0-100%) on scroll into view
3. **Side Decorations**: Floating up/down continuously, glow on hover
4. **Project Cards**: Lift up on hover with shadow increase
5. **Buttons**: Subtle scale/color changes on hover
6. **Dark Mode Toggle**: Scale animation with color transition
7. **Form Inputs**: Border color change on focus with shadow

---

## Responsive Breakpoints

### Desktop (1200px+)
- Full layout with side decorations
- 2-3 column grids
- All animations active

### Tablet (768px - 1023px)
- Side decorations reduced or hidden
- 2-column grids for projects/skills
- Adjusted padding/margins

### Mobile (Below 768px)
- Side decorations completely hidden
- Single column layouts
- Hamburger menu consideration (not implemented yet)
- Simplified animations for performance

---

## Key Features Summary

✓ Sherlockian Victorian theme throughout
✓ Dark mode toggle with localStorage persistence
✓ Animated skill progress bars
✓ Responsive design (mobile-first approach)
✓ Smooth scrolling navigation
✓ Interactive elements with hover effects
✓ Professional yet whimsical presentation
✓ Beginner-appropriate project descriptions
✓ Contact form with validation
✓ Social links section

---

## Files Structure

```
MY PROFILE/
├── index.html      (Main HTML structure)
├── styles.css      (All styling - light & dark modes)
├── script.js       (Interactivity & animations)
└── WIREFRAME.md    (This file)
```

---

*Wireframe created for Alexace Kyle P. Obillo's Portfolio Website - November 30, 2025*

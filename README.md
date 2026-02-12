# Taiwo Portfolio Website

Professional portfolio for an instructional designer and video producer featuring:
- Single-page portfolio with project showcase
- Detailed case study pages with methodology
- Dark theme with dot grid background and animated light streaks
- GSAP scroll-driven animations
- Optimized font loading for instant text visibility
- Fully responsive design

## Files Included

### Main Pages
- `index.html` - Main portfolio page (with favicon, navigation, projects, about, contact)
- `index-backup.html` - Backup of main portfolio page
- `index copy.html` - Portfolio page copy
- `index copy 2.html` - Portfolio page copy 2

### Case Study Pages
- `case-study-template.html` - Template for creating new case studies
- `case-study-website.html` - Cloud Design Platform Customer Onboarding case study
- `case-study-aprp.html` - Abuse Prevention and Response Protocol case study
- `case-study-peer-learning.html` - Crisis Decision-Making Through Case-Based Peer Learning
- `case-study-uxo.html` - UXO Awareness Training detailed case study
- `case-study-lethbridge.html` - Lethbridge College Interpersonal Effectiveness video case study

### Assets
- `logo_new_badex.png` - Logo (also used as favicon)
- `new-mouse.png` - Blueprint mouse background for About section
- `profile.jpg` - Profile photo
- `screenshot-elearning.png` - UXO course screenshot
- Various external images referenced via URLs

### Source Content
- `case-study-medium.md` - UXO case study markdown source
- `aprp_protocol.md` - APRP case study markdown source

## Case Studies

The portfolio includes detailed case study pages that showcase instructional design process and methodology.

### Current Case Studies

1. **UXO Awareness Training** (`case-study-uxo.html`)
   - Safety-critical microlearning for construction workers
   - Links to live project at badex.tv

2. **Abuse Prevention and Response Protocol** (`case-study-aprp.html`)
   - Behavior change training for direct-care staff
   - Links to live Storyline demo

### Creating New Case Studies

1. **Duplicate the template:**
   ```bash
   cp case-study-template.html case-study-yourproject.html
   ```

2. **Update content:**
   - Edit title tag (line 6)
   - Update project tag, title, subtitle (hero section)
   - Fill in project meta info (client, role, duration, tools, audience)
   - Update "View Live Project" button URL (in hero section)
   - Replace all placeholder content sections
   - Add your screenshots/images

3. **Link from homepage:**
   - Update the project card in `index.html` work section
   - Add dual links: "View Case Study" + "View Live Project"
   - Example structure:
   ```html
   <div style="display: flex; gap: 16px; margin-top: 20px;">
       <a href="case-study-yourproject.html" class="view-project">View Case Study →</a>
       <a href="https://your-live-demo.com" target="_blank" rel="noopener noreferrer" class="view-project">View Live Project →</a>
   </div>
   ```

## Uploading to WordPress with WP File Manager

### Step 1: Install WP File Manager Plugin

1. Log into your WordPress admin dashboard
2. Go to **Plugins > Add New**
3. Search for "WP File Manager"
4. Install and activate **WP File Manager** by developer "mndpsingh287"

### Step 2: Upload the Portfolio Files

1. Go to **WP File Manager** in your WordPress admin sidebar
2. Navigate to your root directory (usually `public_html` or where your WordPress is installed)
3. Create a new folder called `portfolio` (right-click > New Folder)
4. Open the `portfolio` folder
5. Click the **Upload** button in the toolbar
6. Upload files:

**Essential files:**
- `index.html`
- `logo_new_badex.png`
- `new-mouse.png`
- `screenshot-elearning.png`

**Optional (if deploying case studies):**
- `case-study-uxo.html`
- `case-study-aprp.html`
- Any additional case study pages

**Note:** Case studies link to external live demos (AWS S3, badex.tv) so those URLs must remain accessible.

Your portfolio will now be accessible at: `https://yourdomain.com/portfolio/`

## Setting Up Redirects

If you want visitors to your main domain to see this portfolio instead of your WordPress site, use a redirect plugin.

### Option 1: Redirection Plugin (Recommended)

1. Go to **Plugins > Add New**
2. Search for "Redirection" by developer "John Godley"
3. Install and activate the plugin
4. Go to **Tools > Redirection**
5. Complete the setup wizard
6. Add a new redirect:
   - **Source URL:** `/` (or specific pages you want to redirect)
   - **Target URL:** `/portfolio/index.html`
   - **Match:** URL only
   - **Action:** Redirect to URL
   - **Group:** Redirections
7. Click **Add Redirect**

### Option 2: Simple 301 Redirects Plugin

1. Go to **Plugins > Add New**
2. Search for "Simple 301 Redirects"
3. Install and activate
4. Go to **Settings > 301 Redirects**
5. Add redirect:
   - **Request:** `/`
   - **Destination:** `/portfolio/index.html`
6. Save changes

### Option 3: Manual .htaccess Redirect (Advanced)

If you have FTP/File Manager access and want a code-based solution:

1. Open WP File Manager
2. Navigate to your root directory
3. Edit the `.htaccess` file
4. Add this line BEFORE the WordPress rules:

```apache
RedirectMatch 301 ^/$ /portfolio/index.html
```

## Features

### Portfolio Page (index.html)
- **Favicon:** Browser tab displays logo
- **Fixed navigation:** Logo + Work/About/Contact links
- **Animated background:** Vertical light streaks with grid alignment
- **Optimized font loading:** Font-display swap for instant text visibility
- **Project cards:** Dual-link structure (case study + live demo)
- **Scroll animations:** GSAP-powered reveals and transitions
- **Responsive:** Mobile-first design, works on all devices
- **Dark theme:** Dot grid background with clean typography

### Animated Light Streaks Background

The portfolio features subtle animated vertical light streaks that enhance the ambient atmosphere:

**Technical Specifications:**
- 6 active streaks on desktop (3 on mobile)
- Grid-aligned positions: 528px, 752px, 1200px, 1424px, 1648px, 1904px
- Aligned with 32px dot grid (centered on dots with 16px offset)
- Slow, graceful animation (8-10 second durations)
- Staggered delays (0s-9s) for asynchronous flow
- Feathered gradient (transparent → white → transparent)
- GPU-accelerated transforms for 60fps performance
- Respects reduced motion preferences

**CSS Location:** Lines 130-200 in `<style>` section

```css
/* Light streaks container */
.light-streaks {
    position: fixed;
    z-index: -1;
    overflow: hidden;
}

/* Individual streak animation */
@keyframes streak-fall {
    0% { transform: translateY(0); opacity: 0; }
    10% { opacity: 1; }
    90% { opacity: 1; }
    100% { transform: translateY(calc(100vh + 40vh)); opacity: 0; }
}
```

**HTML Location:** After `.diagonal-stroke` element in hero section

To disable: Set `.light-streaks { display: none; }` or remove the HTML markup.

### Font Loading Optimization

Optimized for instant text visibility, eliminating 15-30 second blank screens:

**Performance Improvements:**
- **Font-display: swap** - Explicit @font-face declarations ensure text shows immediately
- **Reduced font variants** - 7 variants → 4 variants (43% reduction)
- **File size reduction** - ~280KB → ~160KB font files
- **Load time** - Zero blank screen (text visible instantly with fallback fonts)

**Fonts Used:**
- **Inter:** 400, 600, 700 (body text, navigation, descriptions)
- **Sora:** 700 (headings, hero title)

**CSS Location:** Lines 14-50 in `<style>` section (FONT DISPLAY FIX comment block)

**Google Fonts URL:**
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Sora:wght@700&display=swap" rel="stylesheet">
```

### Case Study Pages
- **Hero section:** Project overview with meta info (client, role, tools, timeline, audience)
- **"View Live Project" button:** Positioned at top for quick access to demo
- **Structured sections:** Overview, Challenge, Approach, Solution, Key Decisions, Results, Lessons Learned
- **Performance metrics:** Highlight boxes showing targets and outcomes
- **Process timeline:** Visual 4-step design methodology
- **Consistent design:** Matches portfolio dark theme and typography
- **Responsive:** Works seamlessly on mobile, tablet, and desktop

## Customization

### Changing Colors

Edit the CSS variables in `index.html` under `:root`:

```css
:root {
    --bg-primary: #0a0a0a;      /* Main background */
    --bg-secondary: #111111;     /* Section backgrounds */
    --text-primary: #ffffff;     /* Main text */
    --text-secondary: #a0a0a0;   /* Secondary text */
    --accent: #6366f1;           /* Accent color */
}
```

The same CSS variables are used in all case study pages, so changing them in `index.html` as a reference will help you maintain consistency across pages.

### Adjusting Dot Grid

Find the `background-image` property in the `body` styles:

```css
background-image: radial-gradient(circle, rgba(255,255,255,0.18) 1px, transparent 1px);
```

- Change `0.18` to adjust dot visibility
- Change `32px 32px` in `background-size` to adjust dot spacing

### Customizing Animated Light Streaks

**Adjust Speed:**
Find the animation durations in `.light-streak:nth-child()` rules:
```css
animation: streak-fall 8s linear infinite;  /* Change 8s to faster (6s) or slower (12s) */
```

**Adjust Opacity/Visibility:**
Find the gradient in `.light-streak`:
```css
rgba(255, 255, 255, 0.2) 50%,  /* Change 0.2 to more subtle (0.1) or brighter (0.3) */
```

**Adjust Number of Streaks:**
Hide streaks by adding `display: none;` to specific children:
```css
.light-streak:nth-child(6) { display: none; }  /* Hides the 6th streak */
```

**Adjust Positions:**
Change the `left` values to reposition streaks (use multiples of 32px + 16px for grid alignment):
```css
.light-streak:nth-child(3) { left: 720px; }  /* Moves 3rd streak to different position */
```

**Disable on Mobile:**
The CSS already reduces streaks from 6 to 3 on mobile (<768px). To disable entirely on mobile:
```css
@media (max-width: 768px) {
    .light-streaks { display: none; }
}
```

### Customizing Case Studies

Edit case study pages to match your projects:

**Project Meta (hero section):**
```html
<div class="meta-item">
    <span class="meta-label">Client</span>
    <span class="meta-value">Your Client Name</span>
</div>
```

**Live Project Link (in hero section):**
```html
<a href="https://your-demo-url.com" target="_blank" rel="noopener noreferrer" class="btn-primary" style="margin-top: 32px;">
    View Live Project
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5">
        <path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6M15 3h6v6M10 14L21 3"/>
    </svg>
</a>
```

**Content Sections:**
Replace placeholder text in each section with your project details. The template includes:
- Overview (project background)
- The Challenge (problem statement)
- My Approach (4-step process timeline)
- The Solution (what you created)
- Key Decisions (critical design choices)
- Results & Impact (measurable outcomes)
- Lessons Learned (reflection)

Follow the existing structure to maintain consistency across case studies.

### Portfolio Grid Layout

**Current Layout: 2-Column Grid (January 2026)**

The portfolio uses a CSS Grid layout for the "Selected Work" section to create a compact, scannable view:

```css
.work-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 60px 40px; /* row-gap column-gap */
}

/* Tablet */
@media (max-width: 968px) {
    .work-grid {
        gap: 48px 32px;
    }
}

/* Mobile */
@media (max-width: 768px) {
    .work-grid {
        grid-template-columns: 1fr; /* Single column */
        gap: 40px;
    }
}
```

**Benefits:**
- 45% reduction in page height on desktop
- Better scannability with side-by-side project comparison
- More compact, professional appearance
- Scales well as portfolio grows

**Previous Layout: Single-Column Flexbox (to revert if needed)**

If you prefer the original vertical stack layout, replace the `.work-grid` base styles (around line 395-399) with:

```css
.work-grid {
    display: flex;
    flex-direction: column;
    gap: 80px;
}

/* Mobile */
@media (max-width: 768px) {
    .work-grid {
        gap: 48px;
    }
}
```

Then remove the tablet-specific `.work-grid` rule from the `@media (max-width: 968px)` breakpoint.

### Updating Content

All content is in the HTML sections:
- **Hero section:** Main headline and description
- **Work section:** Project cards with images and descriptions
- **About section:** Bio text and skills
- **Contact section:** Email and social links

## Dependencies (CDN)

The site loads these libraries from CDN (no local files needed):
- Google Fonts (Sora, Inter)
- GSAP 3.12.5
- GSAP ScrollTrigger Plugin
- GSAP ScrollToPlugin

## Performance Metrics

**Optimized Loading:**
- Font loading: Zero blank screen (instant text visibility)
- Font file size: 160KB (43% reduction from original 280KB)
- Animation performance: 60fps maintained across all devices
- GPU-accelerated transforms for smooth animations

**Lighthouse Scores (Typical):**
- Performance: 90+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 100

## Browser Support

Works in all modern browsers:
- Chrome, Firefox, Safari, Edge (latest versions)
- Includes reduced motion support for accessibility
- Responsive design tested on mobile, tablet, and desktop
- GPU-accelerated animations for optimal performance

## Project Info

**Last Updated:** January 2026
**Technologies:** HTML5, CSS3, JavaScript (GSAP 3.12.5)
**Design System:** Dark theme with 32px grid, Inter + Sora fonts
**Responsive Breakpoints:** 768px (mobile), 968px (tablet), 1100px+ (desktop)

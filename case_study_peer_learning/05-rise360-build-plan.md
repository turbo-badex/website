# Rise 360 Build Plan
## UXO Awareness Training: "Stop Work. Secure the Area. Report."

**Client:** Defence Construction Canada (DCC), Environmental Services
**Project:** UXO Awareness for Construction Teams
**Build Tool:** Articulate Rise 360
**Developer:** [Your Name / Development Team]
**Date:** [Current Date]
**Version:** 1.0

---

## Table of Contents
1. [Build Overview](#1-build-overview)
2. [Pre-Build Preparation](#2-pre-build-preparation)
3. [Media Asset Requirements](#3-media-asset-requirements)
4. [Module-by-Module Build Guide](#4-module-by-module-build-guide)
5. [Quality Assurance Checklist](#5-quality-assurance-checklist)
6. [Testing Protocol](#6-testing-protocol)
7. [SCORM Export & Delivery](#7-scorm-export--delivery)
8. [Build Timeline & Effort Estimate](#8-build-timeline--effort-estimate)

---

## 1. Build Overview

### 1.1 Project Summary

**What we're building:**
A 20-minute, mobile-responsive Rise 360 training module with 5 modules, 31 screens, interactive scenarios, and a 10-question assessment.

**Key features:**
- ✅ 31 screens across 5 modules
- ✅ Branching scenarios with consequences (3 scenarios)
- ✅ Formative knowledge checks (5 embedded checks)
- ✅ Summative assessment (10 questions, 80% pass, critical items)
- ✅ Downloadable job aid (PDF + PNG)
- ✅ Certificate of completion
- ✅ Mobile-responsive, WCAG 2.1 AA accessible

**Storyboard source:** Document 04-deliverable-specifications.md (Section 2: Complete Module Storyboard)

---

### 1.2 Rise 360 Project Structure

**Project name:** UXO_Awareness_v1.0

**Module structure:**
```
UXO Awareness Training
├── Module 1: Why UXO Awareness Matters (6 screens)
├── Module 2: Recognize Suspicious Objects (6 screens)
├── Module 3: The Protocol - Stop, Secure, Report (10 screens)
├── Module 4: Scenario Practice (5 screens)
└── Module 5: Assessment & Resources (4 screens)
```

**Rise 360 blocks used:**
- Title cards (module intros)
- Text blocks (content, instructions)
- Scenario blocks (branching scenarios)
- Flashcard blocks (recognition red flags)
- Accordion blocks (DO/DON'T lists)
- Tabs blocks (role-specific content)
- Process blocks (protocol flowchart)
- Video blocks (optional protocol demo)
- Sorting/matching interactions
- Quiz block (10 questions, settings configured)
- Download blocks (job aid)
- Statement blocks (commitment, certificate)

---

### 1.3 Build Workflow

**Phase 1: Pre-Build (Week 1)**
- [ ] Set up Rise 360 project
- [ ] Configure theme (colors, fonts)
- [ ] Gather/create media assets
- [ ] Review storyboard with SME

**Phase 2: Module Build (Weeks 2-4)**
- [ ] Build Module 1 (screens 1.1-1.6)
- [ ] Build Module 2 (screens 2.1-2.6)
- [ ] Build Module 3 (screens 3.1-3.10)
- [ ] Build Module 4 (scenarios 4.1-4.5)
- [ ] Build Module 5 (assessment 5.1-5.4)

**Phase 3: Media Integration (Week 5)**
- [ ] Insert images (illustrations, icons, diagrams)
- [ ] Insert video (protocol demo)
- [ ] Add audio/narration (if included)
- [ ] Embed job aid download links

**Phase 4: Quality Assurance (Week 6)**
- [ ] Content review (typos, accuracy)
- [ ] Functionality testing (interactions, branching)
- [ ] Accessibility audit (alt text, color contrast, keyboard nav)
- [ ] Mobile testing (phone, tablet)
- [ ] Browser testing (Chrome, Firefox, Safari, Edge)

**Phase 5: Review & Revisions (Week 7)**
- [ ] SME review
- [ ] Stakeholder review
- [ ] Implement feedback
- [ ] Final proofread

**Phase 6: Export & Delivery (Week 8)**
- [ ] Export SCORM package
- [ ] Test SCORM in LMS
- [ ] Package deliverables
- [ ] Deliver to client

**Total timeline:** 8 weeks (with buffer for reviews and revisions)

---

## 2. Pre-Build Preparation

### 2.1 Rise 360 Setup

**Step 1: Create New Course**
1. Log in to Rise 360 (https://articulate.com/360/rise)
2. Click "New Course"
3. Title: "UXO Awareness Training: Stop Work. Secure. Report."
4. Description: "Safety-critical training for construction teams on DND sites"

**Step 2: Configure Theme**

**Colors:**
- **Primary:** Blue `#1976D2` (DCC branding, professional)
- **Accent 1:** Red `#D32F2F` (STOP, critical warnings)
- **Accent 2:** Orange `#F57C00` (SECURE, caution)
- **Accent 3:** Green `#388E3C` (WAIT, correct actions)

**How to set:**
- Rise → Settings → Theme
- Background: White
- Primary color: #1976D2
- Accent colors: #D32F2F, #F57C00, #388E3C
- Heading font: Default (Lato or Open Sans)
- Body font: Default

**Step 3: Configure Navigation**
- Rise → Settings → Navigation
- Navigation style: Top bar (default)
- Progress: Show module completion indicators
- Continue button: Auto-advance enabled (learner-paced)

**Step 4: Configure Completion**
- Rise → Settings → Completion
- Mark complete when: Learner views all lessons + passes quiz
- Quiz passing score: 80%
- Allow retakes: Unlimited

**Step 5: Configure Accessibility**
- Rise → Settings → Accessibility
- Enable keyboard navigation: ON (default)
- Alt text required: ON (validator will check)
- Color contrast: AUTO (Rise validates WCAG AA)

---

### 2.2 Storyboard Review

**Before building, review the storyboard with stakeholders:**

**Participants:**
- Instructional designer (you)
- SME (UXO safety expert)
- DCC sponsor
- Development team (if applicable)

**Review checklist:**
- [ ] Content accuracy (SME validates technical content)
- [ ] Protocol sequence correct (STOP → SECURE → REPORT → WAIT)
- [ ] Scenarios realistic (match field conditions)
- [ ] Assessment questions valid (measure objectives)
- [ ] Tone appropriate (serious, not fear-based)
- [ ] Scope appropriate (no ordnance identification details)

**Output:**
- Approved storyboard (Document 04 with sign-off)
- Change log (any revisions from review)

---

### 2.3 Media Asset Inventory

**What media assets are needed?**

**Images:**
- Construction site scenes (excavation, demolition, trenching)
- Suspicious object illustrations (cylindrical, cone-shaped, with fins)
- Normal construction finds (rebar, pipes, rocks)
- UXO expert with equipment
- Protocol flowchart diagrams
- Icons (🛑 ⚠️ 📞 ⏸️ 👷 👔 🏢 ❌ ✅)
- Top-down exclusion zone diagram (25m radius)
- Reporting chain flowchart

**Video (optional):**
- Protocol demonstration (90 seconds)
  - Worker encounters object
  - STOP, SECURE, REPORT, WAIT sequence
  - Animated or live-action with actors

**Audio (optional):**
- Narration for protocol video
- Module intro voiceovers (if desired)

**Documents:**
- Job aid PDF (printable version)
- Job aid PNG (mobile version)
- Certificate template (Rise auto-generates, customize if needed)

**Source:**
- **Stock libraries:** Envato Elements, Adobe Stock, Shutterstock (construction scenes)
- **Custom illustrations:** Hire illustrator or use Canva/Figma (UXO objects, diagrams)
- **Icons:** Material Design Icons, Font Awesome, Noun Project
- **Video:** Hire production company or use animation tool (Vyond, Powtoon)
- **Job aid:** Graphic designer using Adobe InDesign/Illustrator or Canva

**Action items:**
- [ ] Source/create all media assets (see Section 3)
- [ ] Organize in shared folder (Google Drive, Dropbox, SharePoint)
- [ ] Naming convention: `UXO_[AssetType]_[Description].ext`
  - Example: `UXO_Image_ExcavatorScene.png`
  - Example: `UXO_Video_ProtocolDemo.mp4`

---

### 2.4 Content Preparation

**Gather all text content:**

**Source:** Document 04-deliverable-specifications.md (Section 2: Module Storyboard)

**Method:**
1. Copy all screen content (headlines, body text, button labels) into a Word document or spreadsheet
2. Organize by screen number (1.1, 1.2, etc.)
3. Include:
   - Headlines
   - Body text
   - Accordion/tab labels and content
   - Button text
   - Feedback text (correct/incorrect)
   - Alt text for images

**Why:** Easier to copy/paste into Rise during build (vs. switching between documents)

**Action:**
- [ ] Create content document: `UXO_Content_Master.docx`
- [ ] Proofread all content (typos, grammar)
- [ ] Run readability check (target: Grade 8)

---

## 3. Media Asset Requirements

### 3.1 Image Assets

**Total images needed:** ~25-30 images

#### **Category 1: Construction Scenes (6 images)**

**Image 1: Construction Site (Generic)**
- **Usage:** Screen 1.1 (Title screen), Screen 1.2 (Scenario intro)
- **Description:** Professional construction site, excavation in progress, DND property feel (not specific site)
- **Style:** Realistic illustration or photo
- **Size:** 1200×800 px minimum (landscape)
- **Alt text:** "Construction site with excavation equipment on DND property"

**Image 2: Excavator Digging**
- **Usage:** Screen 4.2 (Scenario 1 - Excavation)
- **Description:** Excavator digging trench, bucket in soil
- **Style:** Illustration
- **Size:** 1200×800 px
- **Alt text:** "Excavator digging foundation trench"

**Image 3: Hand Digging Post Holes**
- **Usage:** Screen 4.3 (Scenario 2 - Hand digging)
- **Description:** Worker with shovel digging post hole
- **Style:** Illustration
- **Size:** 1200×800 px
- **Alt text:** "Construction worker hand-digging post hole with shovel"

**Image 4: Building Demolition**
- **Usage:** Screen 4.4 (Scenario 3 - Demolition)
- **Description:** Demolition site, old building interior
- **Style:** Illustration
- **Size:** 1200×800 px
- **Alt text:** "Building demolition site with exposed wall cavities"

**Image 5: Evacuation Scene**
- **Usage:** Screen 1.3 (Real consequences)
- **Description:** Construction workers at safe distance, emergency responders, cordoned area
- **Style:** Illustration (not graphic, professional tone)
- **Size:** 1200×800 px
- **Alt text:** "Construction site evacuation with workers at safe distance and emergency responders"

**Image 6: UXO Expert at Work**
- **Usage:** Screen 3.6 (WAIT for clearance)
- **Description:** UXO disposal expert with detection equipment, examining from distance
- **Style:** Illustration
- **Size:** 1200×800 px
- **Alt text:** "UXO disposal expert examining suspicious object from safe distance with detection equipment"

---

#### **Category 2: Suspicious Objects (Illustrations) (6 images)**

**IMPORTANT:** Do NOT use photos of real UXO. Use simplified illustrations.

**Image 7: Cylindrical Object with Fins**
- **Usage:** Screen 2.4 (Recognition practice - Image 2)
- **Description:** Rusty cylindrical object, visible fins, partially exposed in soil
- **Style:** Simplified illustration (icon-like)
- **Size:** 600×600 px (square)
- **Alt text:** "Illustration of cylindrical metal object with fins, partially buried"

**Image 8: Cone-Shaped Object**
- **Usage:** Screen 2.4 (Recognition practice - Image 6), Screen 4.3 (Scenario 2)
- **Description:** Cone-shaped metal object, corroded
- **Style:** Simplified illustration
- **Size:** 600×600 px
- **Alt text:** "Illustration of cone-shaped corroded metal object"

**Image 9: Corroded Metal with Markings**
- **Usage:** Screen 2.4 (Recognition practice - Image 4)
- **Description:** Metal object with visible military-style markings, corroded
- **Style:** Simplified illustration (markings not specific to real ordnance)
- **Size:** 600×600 px
- **Alt text:** "Illustration of corroded metal object with military-style markings"

**Image 10: Generic Suspicious Object**
- **Usage:** Screen 1.2 (reveal), Screen 1.4 (UXO definition)
- **Description:** Ambiguous metallic object, unfamiliar shape
- **Style:** Simplified illustration
- **Size:** 600×600 px
- **Alt text:** "Illustration of suspicious unfamiliar metal object"

**Image 11: Multiple UXO Types (Icon Set)**
- **Usage:** Screen 1.4 (Accordion - What does UXO look like?)
- **Description:** 3-4 simplified icons showing variety (cylindrical, cone, sphere)
- **Style:** Icon set, consistent style
- **Size:** 800×400 px (horizontal layout)
- **Alt text:** "Illustrations of various unexploded ordnance shapes: cylindrical, cone-shaped, and spherical"

**Image 12: Object Partially Exposed in Soil**
- **Usage:** Screen 1.2 (scenario reveal), Scenario 1
- **Description:** Close-up of suspicious object partially visible in excavated soil
- **Style:** Illustration
- **Size:** 800×600 px
- **Alt text:** "Suspicious metal object partially exposed in excavated soil"

---

#### **Category 3: Normal Construction Finds (5 images)**

**Image 13: Rusty Pipe**
- **Usage:** Screen 2.4 (Recognition practice - Image 1)
- **Description:** Old rusty pipe, clearly identifiable
- **Style:** Photo or illustration
- **Size:** 600×600 px
- **Alt text:** "Old rusty pipe, typical construction debris"

**Image 14: Rebar Bundle**
- **Usage:** Screen 2.4 (Recognition practice - Image 5)
- **Description:** Bundle of steel rebar (reinforcement bars)
- **Style:** Photo or illustration
- **Size:** 600×600 px
- **Alt text:** "Bundle of steel reinforcement bars (rebar)"

**Image 15: Large Rock**
- **Usage:** Screen 2.4 (Recognition practice - Image 3)
- **Description:** Large rock/boulder
- **Style:** Photo
- **Size:** 600×600 px
- **Alt text:** "Large natural rock"

**Image 16: Normal Construction Materials Composite**
- **Usage:** Screen 2.3 (Normal vs Suspicious - Tab 1)
- **Description:** Collage showing rebar, pipes, concrete, rocks
- **Style:** Photo composite or illustration
- **Size:** 1000×600 px
- **Alt text:** "Typical construction materials: rebar, pipes, concrete, and natural materials"

**Image 17: Suspicious Objects Composite**
- **Usage:** Screen 2.3 (Normal vs Suspicious - Tab 2)
- **Description:** Collage of illustrated suspicious objects (from Images 7-9)
- **Style:** Illustration composite
- **Size:** 1000×600 px
- **Alt text:** "Examples of suspicious objects requiring stop-work protocol"

---

#### **Category 4: Diagrams & Flowcharts (5 images)**

**Image 18: Protocol Flowchart (4 Steps)**
- **Usage:** Screen 1.5 (Protocol preview), Screen 3.2 (Protocol overview), Screen 3.10 (Summary)
- **Description:** Visual flowchart: STOP → SECURE → REPORT → WAIT with icons and color coding
- **Style:** Professional diagram (PowerPoint, Lucidchart, or Canva)
- **Colors:** Red (#D32F2F), Orange (#F57C00), Blue (#1976D2), Green (#388E3C)
- **Size:** 1200×800 px
- **Alt text:** "UXO stop-work protocol flowchart: Stop work immediately, secure 25-meter area, report through chain, wait for expert clearance"

**Image 19: Exclusion Zone Diagram (Top-Down View)**
- **Usage:** Screen 3.4 (Step 2: SECURE)
- **Description:** Top-down view showing object (center), 25m radius circle, markers/cones, workers outside zone
- **Style:** Technical diagram (simple, clear)
- **Size:** 800×800 px (square)
- **Alt text:** "Top-down diagram of 25-meter exclusion zone around suspicious object with safety markers"

**Image 20: Reporting Chain Flowchart**
- **Usage:** Screen 3.5 (Step 3: REPORT), job aid back side
- **Description:** Chain diagram: Worker → Supervisor → Site Authority → DCC PM → UXO Expert
- **Style:** Flowchart with role icons
- **Size:** 1200×400 px (horizontal)
- **Alt text:** "Reporting chain: Worker notifies supervisor, supervisor notifies site authority, site authority notifies DCC project manager, DCC PM requests UXO expert"

**Image 21: Protocol Steps Icons (Set of 4)**
- **Usage:** Throughout Module 3, protocol screens
- **Description:** Individual icons for each step (STOP, SECURE, REPORT, WAIT)
- **Style:** Consistent icon set, 4 separate files + 1 composite
- **Size:** 200×200 px each (icons), 800×200 px (composite horizontal)
- **Alt text (individual):**
  - "Stop sign icon representing immediate work stoppage"
  - "Warning triangle icon representing area security"
  - "Phone icon representing reporting through chain"
  - "Pause icon representing waiting for expert clearance"

**Image 22: Role Icons (3 icons)**
- **Usage:** Screen 3.5 (Tabs: Worker, Supervisor, Site Authority)
- **Description:** Icons for worker (hard hat), supervisor (clipboard), site authority (building/briefcase)
- **Style:** Consistent with protocol icons
- **Size:** 150×150 px each
- **Alt text:**
  - "Construction worker icon"
  - "Supervisor icon"
  - "Site authority icon"

---

#### **Category 5: Visual Assets (3 items)**

**Image 23: DCC Logo**
- **Usage:** Header/footer, certificate, title screen
- **Description:** Defence Construction Canada official logo
- **Source:** Provided by client (request high-res version)
- **Format:** PNG with transparent background
- **Size:** 300×100 px minimum
- **Alt text:** "Defence Construction Canada logo"

**Image 24: Success/Checkmark Graphic**
- **Usage:** Scenario success screens, correct feedback
- **Description:** Green checkmark or success badge
- **Style:** Icon or graphic
- **Size:** 200×200 px
- **Alt text:** "Success checkmark indicating correct action"

**Image 25: Warning/X Graphic**
- **Usage:** Scenario wrong choice feedback
- **Description:** Red X or warning icon
- **Style:** Icon or graphic
- **Size:** 200×200 px
- **Alt text:** "Warning icon indicating incorrect action"

---

### 3.2 Video Asset (Optional)

**Video 1: Protocol Demonstration (90 seconds)**

**Usage:** Screen 3.9 (Protocol video - full sequence)

**Content outline:**
1. **Scene 1 (0:00-0:20):** Worker operating excavator, bucket strikes object, worker stops and looks
2. **Scene 2 (0:20-0:35):** STOP WORK - Worker shuts off excavator, alerts crew, all move away
3. **Scene 3 (0:35-0:50):** SECURE - Worker establishes 25m zone with cones/tape, prevents access
4. **Scene 4 (0:50-1:05):** REPORT - Worker calls supervisor (phone), supervisor calls site authority, DCC PM notified
5. **Scene 5 (1:05-1:25):** WAIT - UXO expert arrives, assesses with equipment, provides clearance
6. **Scene 6 (1:25-1:30):** RESUME - Site authority gives all-clear, work resumes safely

**Production options:**

**Option A: Animated Video (Recommended)**
- **Tool:** Vyond, Powtoon, or custom animation (Adobe After Effects)
- **Pros:** Full control, no actors needed, easy to revise, cost-effective
- **Cons:** Requires animation skills or budget for animator
- **Cost:** $500-1500 (freelance animator) or $300/year (Vyond subscription)

**Option B: Live-Action with Actors**
- **Crew:** Videographer, actors (construction workers), location (construction site)
- **Pros:** Realistic, engaging
- **Cons:** Higher cost, weather-dependent, harder to revise
- **Cost:** $2000-5000 (professional production) or $500-1000 (low-budget with local crew)

**Option C: Screen Recording with Slides + Voiceover**
- **Tool:** PowerPoint slides with illustrations + screen recording
- **Pros:** Very low cost, fast to produce
- **Cons:** Less engaging, more static
- **Cost:** $0 (DIY) or $200-500 (freelance)

**Recommendation:** Option A (Animated video) - best balance of quality, cost, and revisability

**Video specifications:**
- **Resolution:** 1920×1080 (1080p HD)
- **Format:** MP4 (H.264 codec)
- **Aspect ratio:** 16:9 (landscape) OR 1:1 (square for mobile optimization)
- **File size:** <20 MB (for Rise embedding)
- **Audio:** Narration + subtle background music (not distracting)
- **Captions:** SRT file for Rise (auto-sync) or burned-in captions

**Narration script:** (See Document 04, Screen 3.9 for full script)

**Captions:** Full transcript provided as SRT file

**Delivery:**
- [ ] MP4 file: `UXO_Video_ProtocolDemo_v1.mp4`
- [ ] SRT captions: `UXO_Video_ProtocolDemo_v1.srt`
- [ ] Source files (for future edits): `UXO_Video_Source.zip`

---

### 3.3 Audio Assets (Optional)

**Audio 1: Module Introduction Voiceovers (Optional)**

**Usage:** Modules 1-5 intro screens (narration over text)

**Content:** First paragraph of each module intro

**Example (Module 1):**
"Welcome to UXO Awareness Training. In the next 20 minutes, you'll learn to recognize suspicious objects on DND construction sites and execute the stop-work protocol that protects lives. Let's get started."

**Production:**
- **Voice talent:** Professional voiceover artist (male or female, authoritative but warm tone)
- **Recording:** Studio recording (clean, no background noise)
- **Format:** MP3, 128 kbps
- **Length:** ~10-15 seconds per module intro (5 files total)

**Cost:** $100-300 (freelance voice talent via Voices.com, Fiverr, or local talent)

**Decision:** Optional (Rise works perfectly fine without narration; text alone is effective)

---

### 3.4 Document Assets

**Document 1: Job Aid PDF (Printable)**

**Usage:** Screen 5.3 (Job aid download)

**Source:** Document 03-job-aid-design.md (complete specifications)

**Action:** Design job aid using:
- Adobe InDesign or Illustrator (professional)
- Microsoft PowerPoint (accessible)
- Canva (user-friendly)

**Specifications:**
- **Size:** 8.5×11" (Letter)
- **Pages:** 2 (front and back)
- **Resolution:** 300 DPI
- **Format:** PDF (fillable contact fields)
- **File size:** <2 MB
- **Accessibility:** Tagged PDF, OCR text layer

**Deliverable:**
- [ ] `UXO_JobAid_v1.0_Printable.pdf`

**Embed in Rise:**
- Rise → Screen 5.3 → Add Block → Button/Download Block
- Upload PDF
- Button text: "Download Job Aid (PDF)"

---

**Document 2: Job Aid PNG (Mobile)**

**Usage:** Screen 5.3 (mobile viewing option)

**Source:** Same design as PDF, exported as image

**Specifications:**
- **Size:** 2550×3300 px (8.5×11" @ 300 DPI)
- **Format:** PNG
- **File size:** <1 MB (optimized for mobile)
- **Files:** 2 PNGs (front and back as separate images)

**Deliverables:**
- [ ] `UXO_JobAid_Front_v1.0.png`
- [ ] `UXO_JobAid_Back_v1.0.png`

**Embed in Rise:**
- Rise → Screen 5.3 → Add Block → Image Block (expandable)
- Upload both PNGs
- Label: "Front Side" and "Back Side"

---

**Document 3: Certificate Template (Auto-Generated)**

**Usage:** Screen 5.4 (completion certificate)

**Source:** Rise 360 auto-generates certificates

**Customization (optional):**
- Rise → Settings → Certificate
- Add DCC logo
- Customize text: "has successfully completed UXO Awareness Training"
- Signature: DCC Environmental Services Director (digital signature image)
- Valid until: {completion date + 12 months}

**Action:**
- [ ] Upload DCC logo to Rise certificate settings
- [ ] Customize certificate text
- [ ] Add signature image (if available)

**Note:** Rise auto-fills learner name, completion date, and generates PDF for download

---

### 3.5 Icon Assets

**Icon Set: Protocol & UI Icons**

**Icons needed:**
- 🛑 Stop sign (STOP WORK)
- ⚠️ Warning triangle (SECURE)
- 📞 Phone (REPORT)
- ⏸️ Pause (WAIT)
- 👷 Hard hat / worker
- 👔 Person with clipboard / supervisor
- 🏢 Building / site authority
- ❌ Red X (prohibited actions)
- ✅ Green checkmark (correct actions)
- 📋 Clipboard (documentation)
- 🏗️ Construction (site/general)

**Source:**
- **Material Design Icons:** https://fonts.google.com/icons (free, high quality)
- **Font Awesome:** https://fontawesome.com (free & pro versions)
- **Noun Project:** https://thenounproject.com (free with attribution or $3/icon)

**Specifications:**
- **Format:** PNG with transparent background OR SVG
- **Size:** 200×200 px (PNG) or vector (SVG)
- **Style:** Consistent (all from same icon set)
- **Color:** Black/dark gray (can be recolored in Rise)

**Action:**
- [ ] Download icon set (12 icons)
- [ ] Save in folder: `UXO_Icons/`
- [ ] Naming: `Icon_[Name].png` (e.g., `Icon_Stop.png`)

---

### 3.6 Media Asset Checklist

**Before starting build, ensure you have:**

- [ ] **Images (25-30):** All sourced/created, organized, named consistently
- [ ] **Video (1, optional):** Protocol demo (90 sec), MP4 format, captions included
- [ ] **Audio (5, optional):** Module intro narrations, MP3 format
- [ ] **Job Aid PDF:** Designed, fillable, <2 MB
- [ ] **Job Aid PNGs:** Front and back, optimized for mobile
- [ ] **Icons (12):** Protocol and UI icons, consistent style
- [ ] **DCC Logo:** High-res PNG with transparent background
- [ ] **Alt text document:** All images have descriptive alt text written

**Organization:**
```
UXO_Media_Assets/
├── Images/
│   ├── Scenes/
│   ├── SuspiciousObjects/
│   ├── NormalFinds/
│   ├── Diagrams/
│   └── Visual/
├── Video/
│   └── UXO_Video_ProtocolDemo_v1.mp4
│   └── UXO_Video_ProtocolDemo_v1.srt
├── Audio/ (optional)
├── Documents/
│   ├── UXO_JobAid_v1.0_Printable.pdf
│   ├── UXO_JobAid_Front_v1.0.png
│   └── UXO_JobAid_Back_v1.0.png
├── Icons/
└── Alt_Text_Master.xlsx (spreadsheet with all alt text)
```

---

## 4. Module-by-Module Build Guide

### MODULE 1: Why UXO Awareness Matters (6 screens)

**Build time:** 2-3 hours

---

#### Screen 1.1 - Title Screen

**Rise Block:** Title Card (Lesson Intro)

**Build steps:**
1. Add new lesson: "Module 1: Why UXO Awareness Matters"
2. Add Title Card block
3. **Headline:** "Stop Work. Secure the Area. Report."
4. **Subhead:** "UXO Awareness for Construction Teams"
5. **Background image:** Upload Image 1 (Construction site scene)
   - Position: Center
   - Opacity: 70% (so text is readable)
6. **Button:** "START TRAINING" (default Rise continue button)

**QA checklist:**
- [ ] Title text is clear and readable over background image
- [ ] Background image loads quickly
- [ ] Button is visible and clickable
- [ ] Mobile view: Text doesn't overlap, image scales properly

**Alt text:**
- Background image: "Construction site with excavation equipment on DND property"

---

#### Screen 1.2 - Scenario Introduction

**Rise Block:** Scenario Block (interactive reveal)

**Build steps:**
1. Add Scenario block
2. **Headline:** "Hidden Dangers on DND Sites"
3. **Body text:** (Copy from storyboard Document 04, Screen 1.2)
   ```
   Construction sites on Department of National Defence (DND) properties can hold hidden dangers from historical military activities. Training exercises, weapons testing, and ammunition storage have left behind unexploded ordnance (UXO) in the ground.
   ```
4. **Initial image:** Upload Image 1 (Construction site, no object visible)
5. **Add reveal interaction:**
   - Rise Scenario block → Add choice/reveal
   - Button text: "What could be hidden?"
   - **Reveal image:** Upload Image 12 (Object partially exposed in soil)
   - **Reveal text:** "Suspicious objects like this can be buried beneath the surface."

6. **Continue button:** "Continue"

**QA checklist:**
- [ ] Initial image displays correctly
- [ ] Reveal button is clear and clickable
- [ ] Reveal image replaces initial image (or overlays correctly)
- [ ] Reveal text appears
- [ ] Mobile: Images scale, reveal works on touch

**Alt text:**
- Initial image: "Construction excavation site"
- Reveal image: "Suspicious metal object partially exposed in excavated soil"

---

#### Screen 1.3 - Real Consequences

**Rise Block:** Text block with image

**Build steps:**
1. Add Text block
2. **Headline:** "Protocol Saves Lives"
3. **Body text:** (Copy from storyboard - 2019 incident story)
4. Add Image block (below or beside text)
   - Upload Image 5 (Evacuation scene)
   - Position: Full width
5. Add Callout block (Rise "Important" or "Note" style)
   - **Text:** "Following the protocol protects you, your crew, and the public."
   - **Style:** Blue background (primary color)

**QA checklist:**
- [ ] Story is compelling but not fear-based
- [ ] Image supports the message (safe evacuation, not graphic)
- [ ] Callout box is visually distinct
- [ ] Mobile: Text readable, image scales

**Alt text:**
- Image: "Construction site evacuation with workers at safe distance and emergency responders"

---

#### Screen 1.4 - What is UXO?

**Rise Block:** Accordion block

**Build steps:**
1. Add Accordion block
2. **Headline:** "What is UXO?"
3. **Definition (above accordion):** (Copy from storyboard)
   ```
   UXO = Unexploded Ordnance. Military munitions (shells, grenades, mortars, training rounds) that were fired, dropped, or placed but did not detonate as intended.
   ```

4. **Accordion Item 1:**
   - **Label:** "What does UXO look like?"
   - **Content:** (Copy from storyboard)
   - **Image:** Upload Image 11 (Multiple UXO types icon set)
   - **Alt text:** "Illustrations of various unexploded ordnance shapes: cylindrical, cone-shaped, and spherical"

5. **Accordion Item 2:**
   - **Label:** "Where is UXO found?"
   - **Content:** (Bulleted list from storyboard)
   - **Icon:** Map/location icon (optional)

6. **Accordion Item 3:**
   - **Label:** "Why didn't it explode originally?"
   - **Content:** (List from storyboard)

7. **Accordion Item 4:**
   - **Label:** "Your role"
   - **Content:** "You don't need to identify ordnance types..."
   - **Style:** Bold or highlighted (Rise accent color)

**QA checklist:**
- [ ] All 4 accordion items collapse/expand correctly
- [ ] Content is concise (not overwhelming when all expanded)
- [ ] Images load within accordion panels
- [ ] Mobile: Accordion works on touch, content readable

**Alt text:**
- Image 11: (as above)
- Icons: Descriptive (e.g., "Map icon representing UXO locations")

---

#### Screen 1.5 - The Protocol Preview

**Rise Block:** Process block

**Build steps:**
1. Add Process block (Rise → Interactive Blocks → Process)
2. **Headline:** "The 4-Step Protocol"
3. **Intro text:** (Copy from storyboard)
4. **Process steps:**

   **Step 1:**
   - **Icon:** Upload Icon_Stop.png (🛑)
   - **Title:** "STOP WORK"
   - **Content:** "Immediately halt all activities, move away from object, alert your crew"
   - **Color:** Red (#D32F2F)

   **Step 2:**
   - **Icon:** Upload Icon_Secure.png (⚠️)
   - **Title:** "SECURE THE AREA"
   - **Content:** "Establish 25-meter exclusion zone, mark the area, prevent all access"
   - **Color:** Orange (#F57C00)

   **Step 3:**
   - **Icon:** Upload Icon_Report.png (📞)
   - **Title:** "REPORT"
   - **Content:** "Notify supervisor (workers), escalate through chain, document details"
   - **Color:** Blue (#1976D2)

   **Step 4:**
   - **Icon:** Upload Icon_Wait.png (⏸️)
   - **Title:** "WAIT FOR CLEARANCE"
   - **Content:** "Only UXO expert can assess, only site authority can provide all-clear, resume work only after clearance"
   - **Color:** Green (#388E3C)

5. **Interactive:** Rise Process block allows click-to-expand (default behavior)

6. **Continue button:** "Let's learn each step in detail"

**QA checklist:**
- [ ] Process block displays 4 steps in sequence
- [ ] Icons are clear and consistent
- [ ] Colors match specified palette (red, orange, blue, green)
- [ ] Click-to-expand works (if Rise supports)
- [ ] Mobile: Process block stacks vertically, readable

**Alt text:**
- Icon_Stop: "Stop sign icon representing immediate work stoppage"
- Icon_Secure: "Warning triangle icon representing area security"
- Icon_Report: "Phone icon representing reporting through chain"
- Icon_Wait: "Pause icon representing waiting for expert clearance"

---

#### Screen 1.6 - Your Commitment

**Rise Block:** Statement block (or Text block with interactive element)

**Build steps:**
1. Add Text block
2. **Headline:** "Your Commitment to Safety"
3. **Body text:** (Copy from storyboard)
4. **Interactive element:**
   - Rise doesn't have native text input for name entry
   - **Workaround:** Use Knowledge Check (short answer question)
   - Question: "Type your name to commit to this training:"
   - Feedback: "Thank you, [Name]. Let's begin."
   - **Alternative:** Skip text input, use Statement block with acknowledgment

5. **Commitment statement:**
   ```
   I, [NAME], commit to learning and applying the UXO stop-work protocol on every DND site I work on.
   ```

6. **Image:** Upload Image (professional construction team, safety focus)

7. **Button:** "I'm Ready to Learn"

8. **Transition message (bottom of screen):**
   "Module 1 Complete. Next: Learn to recognize suspicious objects."

**QA checklist:**
- [ ] Statement is clear and professional (not gamified)
- [ ] Interactive element (if included) works
- [ ] Button is prominent
- [ ] Transition message visible
- [ ] Mobile: Layout works, button tappable

**Alt text:**
- Image: "Professional construction team focused on safety"

---

**Module 1 Build Complete Checklist:**
- [ ] All 6 screens built
- [ ] Content proofread (no typos)
- [ ] Images uploaded with alt text
- [ ] Interactive elements tested (reveals, accordions, process)
- [ ] Mobile preview checked
- [ ] Continue buttons functional
- [ ] Progress indicator shows "Module 1 of 5"

---

### MODULE 2: Recognize Suspicious Objects (6 screens)

**Build time:** 2-3 hours

---

#### Screen 2.1 - Module Introduction

**Rise Block:** Divider + Text

**Build steps:**
1. Add Divider block (visual break between modules)
   - Style: Thick line or graphic divider
2. Add Text block
3. **Headline:** "Module 2: Recognize Suspicious Objects"
4. **Learning objective:**
   ```
   You'll learn to spot red flags that require stop-work protocol—with 90% accuracy by the end of this module.
   ```
5. **Icon/graphic:** Upload detective/magnifying glass icon
6. **Button:** "Start Module 2"

**QA checklist:**
- [ ] Divider clearly separates from Module 1
- [ ] Objective is clear and motivating
- [ ] Icon supports content
- [ ] Mobile: Divider and text scale properly

**Alt text:**
- Icon: "Detective magnifying glass icon representing object recognition"

---

#### Screen 2.2 - Red Flags Flashcards

**Rise Block:** Flashcard Stack

**Build steps:**
1. Add Flashcard block (Rise → Interactive Blocks → Flashcard Stack)
2. **Headline:** "Red Flags: When to Stop Work"
3. **Instruction:** "Click each card to learn what to look for."

4. **Flashcard 1:**
   - **Front:** "Unusual Metal Objects in Soil"
   - **Back:** (Content from storyboard)
   - **Icon:** Metal cylinder icon

5. **Flashcard 2:**
   - **Front:** "Military-Looking Items"
   - **Back:** (Content from storyboard)
   - **Icon:** Object with fins illustration

6. **Flashcard 3:**
   - **Front:** "Ground Disturbances"
   - **Back:** (Content from storyboard)
   - **Icon:** Disturbed soil graphic

7. **Flashcard 4:**
   - **Front:** "Unfamiliar = Suspicious"
   - **Back:** (Content from storyboard)
   - **Icon:** Question mark + stop sign

8. **Flashcard 5:**
   - **Front:** "Context Matters"
   - **Back:** (Content from storyboard)
   - **Icon:** Map/location pin

9. **Flashcard 6:**
   - **Front:** "Size Doesn't Equal Safety"
   - **Back:** (Content from storyboard)
   - **Icon:** Small vs large objects comparison

**QA checklist:**
- [ ] All 6 flashcards flip correctly (click to reveal back)
- [ ] Front text is concise (fits on card)
- [ ] Back content is readable (not too much text)
- [ ] Icons/images load on cards
- [ ] Mobile: Flashcards work on touch, text readable

**Alt text:**
- Each icon: Descriptive (e.g., "Metal cylinder icon")

---

#### Screen 2.3 - Normal vs Suspicious Comparison

**Rise Block:** Tabs Block

**Build steps:**
1. Add Tabs block (Rise → Interactive Blocks → Tabs)
2. **Headline:** "Normal Construction Finds vs Suspicious Objects"

3. **Tab 1: Normal Construction Finds**
   - **Label:** "Normal Construction Finds"
   - **Content:**
     - Upload Image 16 (Normal materials composite)
     - **Description:** "Typical construction materials you may encounter. Identifiable, expected."
     - **List:** Rebar, PVC/metal pipes, concrete chunks, rocks, railroad spikes

4. **Tab 2: Suspicious Objects**
   - **Label:** "Suspicious Objects"
   - **Content:**
     - Upload Image 17 (Suspicious objects composite)
     - **Description:** "Military-looking, unfamiliar, or unexplained metal objects. These require STOP WORK."
     - **List:** Cylindrical with corrosion, cone-shaped with fins, unusual markings, unexplained metallic items

5. **Callout box (below tabs):**
   - **Style:** Important/Warning
   - **Text:** "WHEN IN DOUBT, TREAT AS SUSPICIOUS. Better to stop work and be wrong than to ignore a real threat."

6. **Button:** "Practice Recognition"

**QA checklist:**
- [ ] Tabs switch correctly
- [ ] Images load in each tab
- [ ] Content is balanced (similar length in both tabs)
- [ ] Callout box is prominent
- [ ] Mobile: Tabs work on touch, images scale

**Alt text:**
- Image 16: "Typical construction materials: rebar, pipes, concrete, and natural materials"
- Image 17: "Examples of suspicious objects requiring stop-work protocol"

---

#### Screen 2.4 - Recognition Practice (Image Sort)

**Rise Block:** Sorting Interaction (or Knowledge Check with images)

**Build steps:**

**Option A: Use Knowledge Check (Multiple Choice with Images)**
1. Add Knowledge Check block
2. **Question:** "Which of these require stop-work protocol?"
3. **Format:** Multiple images, click to select (or multiple separate questions)

**Image 1: Rusty pipe (normal)**
- Upload Image 13
- **Feedback if selected as suspicious:** "This looks like an old pipe—normal construction debris. But good instinct to be cautious!"
- **Feedback if selected as normal:** "Correct! This is typical construction material."

**Image 2: Cylindrical object with fins (SUSPICIOUS)**
- Upload Image 7
- **Feedback if selected as normal:** "❌ No—this has fins and an unusual shape. STOP WORK immediately."
- **Feedback if selected as suspicious:** "✅ Correct! Fins and unusual shape = suspicious. Stop work."

**Image 3: Large rock (normal)**
- Upload Image 15
- **Feedback:** "Correct, it's a rock. Natural material."

**Image 4: Corroded metal with markings (SUSPICIOUS)**
- Upload Image 9
- **Feedback:** "✅ Right! Military-looking markings = suspicious."

**Image 5: Rebar bundle (normal)**
- Upload Image 14
- **Feedback:** "Correct! Rebar is common on construction sites."

**Image 6: Cone-shaped metal object (SUSPICIOUS)**
- Upload Image 8
- **Feedback:** "✅ Yes! Cone shape, metallic = suspicious."

4. **Summary (after all selections):**
   "When unsure: STOP WORK. You identified [X/6] correctly. Remember: better safe than sorry."

**Option B: Use Sorting Interaction (if Rise supports)**
- Rise → Interactive Blocks → Sorting/Matching
- Create two categories: "Normal" and "Suspicious"
- Drag images to correct category
- Immediate feedback on correct/incorrect sorting

**QA checklist:**
- [ ] All 6 images load
- [ ] Selection/sorting mechanism works
- [ ] Feedback is immediate and clear
- [ ] Learner can retry if incorrect
- [ ] Mobile: Images tappable, sorting works on touch

**Alt text:**
- Image 13: "Old rusty pipe, typical construction debris"
- Image 7: "Illustration of cylindrical metal object with fins, partially buried"
- Image 15: "Large natural rock"
- Image 9: "Illustration of corroded metal object with military-style markings"
- Image 14: "Bundle of steel reinforcement bars (rebar)"
- Image 8: "Illustration of cone-shaped corroded metal object"

---

#### Screen 2.5 - Scenario Knowledge Check

**Rise Block:** Knowledge Check (Multiple Choice with Branching Feedback)

**Build steps:**
1. Add Knowledge Check block
2. **Scenario:**
   ```
   You're digging post holes and hit a metal object. It's rusty, about 30cm long, with an unusual shape. What do you do?
   ```

3. **Options:**
   - A) Keep digging carefully to see what it is
   - B) Stop work immediately ✓ CORRECT
   - C) Take a photo to show your supervisor
   - D) Cover it back up and work elsewhere

4. **Feedback:**

   **If B (Correct):**
   ```
   ✅ Exactly right! STOP WORK is always the first action. No matter what, stop immediately.
   ```

   **If A (Wrong):**
   ```
   ❌ Never continue digging. The object could detonate. Your first action is STOP WORK.

   [Show brief consequence graphic: Explosion risk icon]

   Try again.
   ```

   **If C (Wrong):**
   ```
   ❌ Photos can wait. Approaching the object for a photo puts you at risk. STOP WORK first, then document from a safe distance.

   [Show graphic: Worker too close, danger icon]

   Try again.
   ```

   **If D (Wrong):**
   ```
   ❌ Covering it doesn't eliminate the danger. The next worker could trigger it. STOP WORK and report.

   [Show graphic: Future worker endangered]

   Try again.
   ```

5. **Attempts:** Unlimited (Rise setting: Allow retries)

6. **Branching:**
   - Rise Knowledge Check allows custom feedback per answer
   - Add consequence graphics (optional: small warning icons or illustrations)

**QA checklist:**
- [ ] Scenario is realistic and clear
- [ ] All 4 answer options display
- [ ] Feedback is specific to each wrong answer (consequence-based)
- [ ] Learner can retry until correct
- [ ] Consequence graphics (if included) support feedback
- [ ] Mobile: Scenario readable, buttons tappable

**Alt text:**
- Consequence graphics: "Warning icon showing explosion risk" / "Icon showing worker in danger zone"

---

#### Screen 2.6 - Module 2 Summary

**Rise Block:** Summary Card (Text block)

**Build steps:**
1. Add Text block
2. **Headline:** "Module 2 Complete: Recognition Checklist"
3. **Summary:**
   ```
   You've learned to recognize suspicious objects. Remember these red flags:

   ✓ Unusual metal objects in soil
   ✓ Military-looking items (fins, fuses, markings)
   ✓ Unexplained ground disturbances
   ✓ When in doubt, STOP WORK
   ```

4. **Key principle (callout box):**
   ```
   You don't need to identify the object—just recognize suspicious and follow protocol.
   ```

5. **Progress indicator:**
   - Rise auto-shows progress in navigation
   - Add text: "2 of 5 modules complete"

6. **Button:** "Continue to Protocol Training"

**QA checklist:**
- [ ] Summary is concise (key takeaways only)
- [ ] Checkmarks display correctly (use emoji ✓ or icon)
- [ ] Progress indicator visible
- [ ] Button advances to Module 3
- [ ] Mobile: Text readable, layout clear

---

**Module 2 Build Complete Checklist:**
- [ ] All 6 screens built
- [ ] Flashcards flip correctly
- [ ] Tabs switch properly
- [ ] Image recognition practice functional
- [ ] Knowledge check has branching feedback
- [ ] Summary reinforces key points
- [ ] Mobile preview checked
- [ ] Progress shows "2 of 5"

---

### MODULE 3: The Protocol - Stop, Secure, Report (10 screens)

**Build time:** 4-5 hours (longest module, includes video)

---

#### Screen 3.1 - Module Introduction

**Rise Block:** Divider + Text

**Build steps:**
1. Add Divider block
2. Add Text block
3. **Headline:** "Module 3: The Protocol"
4. **Learning objective:**
   ```
   You'll learn the exact 4-step protocol to follow when you encounter a suspicious object—and practice executing it with 100% accuracy.
   ```
5. **Visual:** Upload Image 18 (Protocol flowchart - 4 steps)
6. **Button:** "Start Module 3"

**QA checklist:**
- [ ] Divider separates modules
- [ ] Objective is clear
- [ ] Flowchart image loads and is readable
- [ ] Mobile: Image scales, text readable

**Alt text:**
- Image 18: "UXO stop-work protocol flowchart: Stop work immediately, secure 25-meter area, report through chain, wait for expert clearance"

---

#### Screen 3.2 - Protocol Overview

**Rise Block:** Process Block

**Build steps:**
1. Add Process block
2. **Headline:** "The 4-Step UXO Stop-Work Protocol"
3. **Intro text:** "When you encounter a suspicious object, follow these steps IN ORDER:"

4. **Process steps:** (Same as Screen 1.5, but add click-to-preview)

   **Step 1: STOP WORK**
   - Icon, title, brief content
   - **Preview:** "Immediately halt all work and move away"

   **Step 2: SECURE THE AREA**
   - Icon, title, brief content
   - **Preview:** "Establish 25-meter exclusion zone"

   **Step 3: REPORT**
   - Icon, title, brief content
   - **Preview:** "Notify supervisor and escalate through chain"

   **Step 4: WAIT FOR CLEARANCE**
   - Icon, title, brief content
   - **Preview:** "Only UXO expert can provide all-clear"

5. **Button:** "Learn Step 1"

**QA checklist:**
- [ ] Process block displays all 4 steps
- [ ] Click-to-expand shows preview (if Rise supports)
- [ ] Colors match palette
- [ ] Mobile: Process stacks vertically, readable

---

#### Screen 3.3 - Step 1: STOP WORK

**Rise Block:** Accordion + Video (optional)

**Build steps:**
1. Add Text block
2. **Headline:** "🛑 STEP 1: STOP WORK Immediately"
3. **Key message:**
   ```
   The moment you recognize a suspicious object, your FIRST action is to STOP ALL WORK. No exceptions.
   ```

4. Add Accordion block

   **Accordion 1: "What 'Stop Work' Means"**
   - Content: (Copy from storyboard - halt equipment, alert crew, move away, time: 30 seconds)

   **Accordion 2: "DO Actions"**
   - Content: Bulleted list (✅ Stop immediately, turn off equipment, alert crew, move to safe distance, account for crew)

   **Accordion 3: "DON'T Actions"**
   - Content: Bulleted list (❌ Do not touch/move, take photos close, continue work, approach, pour liquids)

5. **Optional Video block:**
   - Add Video block (below accordion)
   - Upload Video 1 (30-45 sec animation - STOP WORK sequence)
   - **Captions:** Upload SRT file or enable auto-captions
   - **Narration:** (Script from storyboard)

6. **Callout box:**
   ```
   Your safety comes first. STOP WORK means STOP—immediately.
   ```

7. **Button:** "Continue to Step 2"

**QA checklist:**
- [ ] Accordion items expand/collapse
- [ ] DO/DON'T lists are clear with checkmarks/X marks
- [ ] Video (if included) plays correctly
- [ ] Captions display (test with sound off)
- [ ] Callout box is prominent
- [ ] Mobile: Accordion works, video responsive

**Alt text:**
- Video: "Animation demonstrating immediate stop-work procedure when suspicious object encountered"

---

#### Screen 3.4 - Step 2: SECURE THE AREA

**Rise Block:** Accordion + Diagram

**Build steps:**
1. Add Text block
2. **Headline:** "⚠️ STEP 2: SECURE the Area"
3. **Key message:**
   ```
   After stopping work, establish a safety perimeter to protect everyone.
   ```

4. Add Accordion block

   **Accordion 1: "Establish 25-Meter Exclusion Zone"**
   - Content: Minimum 25m, why, measurement method

   **Accordion 2: "Mark the Area"**
   - Content: Use cones, tape, barriers, natural markers

   **Accordion 3: "Prevent All Access"**
   - Content: Stop crew, prevent public, post monitor, account for personnel

   **Accordion 4: "DON'T Actions"**
   - Content: Do not return to area, no quick trips, no entry until clearance

5. **Diagram:**
   - Add Image block (below or beside accordion)
   - Upload Image 19 (Top-down exclusion zone diagram)
   - **Caption:** "25-meter exclusion zone around suspicious object"

6. **Callout box:**
   ```
   25 meters minimum. When in doubt, go farther.
   ```

7. **Button:** "Continue to Step 3"

**QA checklist:**
- [ ] Accordion items work
- [ ] Diagram is clear and labeled
- [ ] 25m distance is emphasized (bold, highlighted)
- [ ] Callout reinforces key point
- [ ] Mobile: Diagram scales, readable

**Alt text:**
- Image 19: "Top-down diagram of 25-meter exclusion zone around suspicious object with safety markers"

---

#### Screen 3.5 - Step 3: REPORT (Role-Specific Tabs)

**Rise Block:** Tabs Block

**Build steps:**
1. Add Text block
2. **Headline:** "📞 STEP 3: REPORT Immediately"
3. **Intro text:**
   ```
   Reporting follows a chain of command. Your role determines who you contact first.
   ```

4. Add Tabs block

   **Tab 1: 👷 WORKERS**
   - **Icon:** Upload Icon (hard hat / worker)
   - **Content:**
     - Your responsibility
     - Who to contact: Direct supervisor
     - When: Immediately after securing area
     - What to report: Location, description, time, personnel affected
     - Stay available
   - **Example script:** (Copy from storyboard)

   **Tab 2: 👔 SUPERVISORS**
   - **Icon:** Upload Icon (clipboard / supervisor)
   - **Content:**
     - Your responsibility
     - Who to contact: Site authority / safety officer
     - When: Immediately after worker reports
     - Actions: Verify security, confirm safety, contact authority, document
     - What to report: All worker info + confirmation

   **Tab 3: 🏢 SITE AUTHORITY / DCC STAFF**
   - **Icon:** Upload Icon (building / briefcase)
   - **Content:**
     - Your responsibility
     - Who to contact: DCC Project Manager
     - When: Immediately after supervisor reports
     - Actions: Contact DCC PM, request expert, coordinate safety, prepare for expert
     - Escalation: DCC PM contacts UXO expert

5. **Visual (below tabs):**
   - Upload Image 20 (Reporting chain flowchart)
   - **Caption:** "Worker → Supervisor → Site Authority → DCC PM → UXO Expert"

6. **Callout box:**
   ```
   🚨 IMMEDIATE DANGER (fire, explosion, injury): Call 911 first, then follow reporting chain.
   ```

7. **Button:** "Continue to Step 4"

**QA checklist:**
- [ ] All 3 tabs switch correctly
- [ ] Icons display in tab labels
- [ ] Content is role-specific and clear
- [ ] Reporting chain flowchart is visible and clear
- [ ] Emergency callout is prominent (red background)
- [ ] Mobile: Tabs work, content readable

**Alt text:**
- Icon (worker): "Construction worker icon"
- Icon (supervisor): "Supervisor icon"
- Icon (site authority): "Site authority icon"
- Image 20: "Reporting chain: Worker notifies supervisor, supervisor notifies site authority, site authority notifies DCC project manager, DCC PM requests UXO expert"

---

#### Screen 3.6 - Step 4: WAIT FOR CLEARANCE

**Rise Block:** Text + Visual

**Build steps:**
1. Add Text block
2. **Headline:** "⏸️ STEP 4: WAIT for Expert Clearance"
3. **Key message:**
   ```
   Only a qualified UXO expert can assess the object. Only site authority can issue all-clear to resume work.
   ```

4. **Body text:**
   - What happens: Expert arrives, assessment, determination, all-clear
   - DO actions: Wait for clearance, remain available, follow expert directions
   - DON'T actions: No resuming before clearance, no returning to check, no moving object, no pressure

5. **Timeline expectations:**
   ```
   Expert arrival: 2-24 hours (depending on location and availability)
   Assessment: 30 minutes to several hours
   Your patience = everyone's safety
   ```

6. **Image:**
   - Upload Image 6 (UXO expert at work)
   - **Caption:** "UXO expert assessing object from safe distance"

7. **Callout box:**
   ```
   Work resumes ONLY after expert clearance and site authority all-clear. No shortcuts.
   ```

8. **Button:** "Practice the Protocol"

**QA checklist:**
- [ ] Message is clear: Wait is mandatory
- [ ] Timeline expectations set (reduces frustration)
- [ ] Image shows expert with equipment (builds confidence)
- [ ] Callout emphasizes no shortcuts
- [ ] Mobile: Text readable, image scales

**Alt text:**
- Image 6: "UXO disposal expert examining suspicious object from safe distance with detection equipment"

---

#### Screen 3.7 - Protocol Sequencing Practice

**Rise Block:** Sorting/Sequencing Interaction

**Build steps:**

**Option A: Use Knowledge Check (Drag-to-Order Question)**
1. Add Knowledge Check block
2. **Question type:** Sequence/Ordering
3. **Headline:** "Practice: Put the Steps in Order"
4. **Instruction:** "Drag the actions into the correct sequence for the UXO stop-work protocol."

5. **Items to sequence (presented in random order):**
   1. Notify your supervisor
   2. Stop work immediately
   3. Establish 25-meter exclusion zone
   4. Wait for UXO expert clearance
   5. Move away from the object

6. **Correct order:**
   1. Stop work immediately
   2. Move away from the object
   3. Establish 25-meter exclusion zone
   4. Notify your supervisor
   5. Wait for UXO expert clearance

7. **Feedback:**
   - **Correct:** "✅ Perfect! You've got the sequence. Stop → Secure → Report → Wait."
   - **Incorrect:** "Not quite. Remember: STOP first, SECURE the area, REPORT through chain, WAIT for clearance. Try again."

8. **Attempts:** Unlimited

**Option B: Use Sorting Interaction (if Rise supports drag-drop)**
- Rise → Interactive Blocks → Sorting
- Learner drags items into correct order
- Immediate feedback on submit

**QA checklist:**
- [ ] Items display in randomized order initially
- [ ] Drag-and-drop works (desktop)
- [ ] Touch-and-hold works (mobile)
- [ ] Feedback is immediate after submission
- [ ] Learner can retry if incorrect
- [ ] Mobile: Dragging/sequencing works smoothly

---

#### Screen 3.8 - Reporting Chain Practice

**Rise Block:** Knowledge Check (Multiple Choice)

**Build steps:**
1. Add Knowledge Check block
2. **Scenario:**
   ```
   You're a construction worker. You've stopped work and secured the area after finding a suspicious object. Who do you contact FIRST?
   ```

3. **Options:**
   - A) DCC Project Manager
   - B) Your direct supervisor ✓ CORRECT
   - C) 911 Emergency Services
   - D) UXO disposal company

4. **Feedback:**

   **If B (Correct):**
   ```
   ✅ Correct! As a worker, your first contact is your supervisor. They'll escalate through the chain (Supervisor → Site Authority → DCC PM → UXO Expert).
   ```

   **If A (Wrong):**
   ```
   ❌ Not directly. Workers report to supervisors, who escalate to site authority, who then contact the DCC PM. Follow the chain.
   ```

   **If C (Wrong):**
   ```
   ❌ Call 911 only if there's immediate danger (fire, explosion, injury). For suspicious objects without immediate danger, follow the reporting chain.
   ```

   **If D (Wrong):**
   ```
   ❌ You don't contact the UXO company directly. Report to your supervisor, who escalates. The DCC PM will arrange expert response.
   ```

5. **Attempts:** Unlimited (must answer correctly to continue)

**QA checklist:**
- [ ] Scenario is clear (worker perspective)
- [ ] All 4 options display
- [ ] Feedback is specific and educational
- [ ] Learner can retry
- [ ] Mobile: Scenario readable, options tappable

---

#### Screen 3.9 - Protocol Video (Full Sequence)

**Rise Block:** Video Block

**Build steps:**
1. Add Video block
2. **Headline:** "Watch the Full Protocol in Action"
3. **Intro text:**
   ```
   This 90-second video shows all 4 steps in action, from discovery to safe work resumption.
   ```

4. **Upload Video:**
   - File: `UXO_Video_ProtocolDemo_v1.mp4`
   - Upload to Rise (or embed from Vimeo/YouTube if hosted externally)

5. **Captions:**
   - Upload SRT file: `UXO_Video_ProtocolDemo_v1.srt`
   - Rise auto-syncs captions
   - Enable captions by default (accessibility)

6. **Video player settings:**
   - Autoplay: OFF (user controls start)
   - Controls: Visible (play, pause, volume, captions, fullscreen)
   - Replay: Allow

7. **Optional: Video transcript download**
   - Add Download block below video
   - Upload PDF: `UXO_Video_Transcript.pdf`
   - Button: "Download Video Transcript (PDF)"

8. **Button:** "Continue"

**QA checklist:**
- [ ] Video uploads successfully and loads
- [ ] Video plays without buffering (test on 3G/4G)
- [ ] Captions display correctly (test with sound off)
- [ ] Video controls work (pause, replay, fullscreen)
- [ ] Mobile: Video responsive, plays on iOS/Android
- [ ] File size <20 MB (for fast loading)

**Alt text:**
- Video: "Animated demonstration of complete UXO stop-work protocol from object discovery through expert clearance and work resumption"

---

#### Screen 3.10 - Module 3 Summary

**Rise Block:** Summary Card + Quiz Preview

**Build steps:**
1. Add Text block
2. **Headline:** "Module 3 Complete: Protocol Recap"
3. **Summary:**
   ```
   You've learned the 4-step UXO stop-work protocol:

   1. 🛑 STOP WORK Immediately
      Halt equipment, alert crew, move away

   2. ⚠️ SECURE the Area
      25-meter exclusion zone, mark perimeter, prevent access

   3. 📞 REPORT Through Chain
      Workers → Supervisor → Site Authority → DCC PM → Expert

   4. ⏸️ WAIT for Clearance
      UXO expert assesses, site authority issues all-clear
   ```

4. **Key principle (callout):**
   ```
   When in doubt, follow the protocol. Your safety and your crew's safety depend on it.
   ```

5. **Progress indicator:**
   "3 of 5 modules complete"

6. **Next step:**
   ```
   Ready to practice? The next module puts you in realistic scenarios to test your decision-making.
   ```

7. **Button:** "Practice Scenarios"

**QA checklist:**
- [ ] Summary is comprehensive but concise
- [ ] 4 steps listed with icons and brief descriptions
- [ ] Callout reinforces importance
- [ ] Progress indicator shows 3/5
- [ ] Transition to Module 4 is clear
- [ ] Mobile: Summary readable, layout clear

---

**Module 3 Build Complete Checklist:**
- [ ] All 10 screens built
- [ ] Accordion blocks expand/collapse
- [ ] Tabs switch correctly (role-specific content)
- [ ] Diagrams (exclusion zone, reporting chain) are clear
- [ ] Video plays with captions
- [ ] Sequencing practice functional
- [ ] Knowledge checks have feedback
- [ ] Summary reinforces all 4 steps
- [ ] Mobile preview checked
- [ ] Progress shows "3 of 5"

---

### MODULE 4: Scenario Practice (5 screens)

**Build time:** 3-4 hours (branching scenarios require careful setup)

---

#### Screen 4.1 - Module Introduction

**Rise Block:** Text + Visual

**Build steps:**
1. Add Divider block
2. Add Text block
3. **Headline:** "Module 4: Practice Scenarios"
4. **Learning objective:**
   ```
   You'll face realistic situations and make decisions. See the consequences of your choices in a safe environment—before you're on a real site.
   ```

5. **Visual:** Upload construction scene (generic - excavation, demolition, trenching composite)

6. **Tone message:**
   ```
   Practice makes prepared. Let's go.
   ```

7. **Button:** "Start Scenario 1"

**QA checklist:**
- [ ] Objective sets expectation (consequence-based learning)
- [ ] Visual supports message
- [ ] Tone is serious but encouraging
- [ ] Mobile: Text readable, image scales

---

#### Screen 4.2 - Scenario 1: Excavation (Branching)

**Rise Block:** Scenario Block (Branching)

**Build steps:**

Rise Scenario block supports branching. Follow this structure:

1. **Add Scenario block**

2. **Setup (Initial Screen):**
   - **Headline:** "Scenario 1: Foundation Excavation"
   - **Context:**
     ```
     You're operating an excavator, digging foundation trenches for a new building on a DND site. Your bucket strikes something solid. You stop and look—there's a rusty, cylindrical metal object partially exposed in the soil. It's about 30cm long with an unusual shape.
     ```
   - **Visual:** Upload Image 2 (Excavator digging) + Image 12 (Object partially exposed)

3. **Decision Point 1:**
   - **Question:** "What do you do FIRST?"
   - **Options:**
     - A) Continue digging carefully to expose it fully
     - B) Stop the excavator immediately and alert your crew ✓ CORRECT
     - C) Get out and take a photo for your supervisor
     - D) Cover it back up and continue working elsewhere

---

**Branching Path A (Wrong):**
- **Consequence screen:**
  - **Visual:** Animation or graphic showing explosion risk (symbolic, not graphic)
  - **Text:**
    ```
    ❌ NEVER continue digging. The object could detonate from vibration or impact. You've put yourself and your crew in extreme danger.

    INCIDENT REPORT: Detonation during excavation. Multiple injuries. Site shutdown.
    ```
  - **Remediation:**
    ```
    The FIRST action is always STOP WORK. Immediately.
    ```
  - **Button:** "Try Again" (loops back to Decision Point 1)

---

**Branching Path B (Correct):**
- **Feedback screen:**
  - **Text:**
    ```
    ✅ Correct! You stopped immediately and alerted your crew. Everyone is safe and moving away.
    ```
  - **Continue to Decision Point 2**

**Decision Point 2:**
- **Question:** "After stopping work, what do you do?"
- **Options:**
  - A) Take photos of the object for documentation
  - B) Call your supervisor right away
  - C) Establish a 25-meter exclusion zone ✓ CORRECT
  - D) Inspect the object more closely to describe it

- **Correct path (C):**
  ```
  ✅ Right! Secure the area first. You establish a 25-meter exclusion zone using cones and tape. Area secured, crew safe.
  ```
  - **Continue to Decision Point 3**

**Decision Point 3:**
- **Question:** "Area secured. Now you need to report. As a worker, who do you contact first?"
- **Options:**
  - A) Your supervisor ✓ CORRECT
  - B) DCC Project Manager
  - C) 911 Emergency
  - D) UXO disposal company

- **Correct path (A):**
  ```
  ✅ Perfect! You call your supervisor with the details: location, description, time. Your supervisor escalates to site authority, who contacts the DCC PM. An expert is dispatched.
  ```
  - **Continue to Final Outcome**

**Final Outcome (Success Path):**
- **Visual:** Green checkmark, success graphic
- **Text:**
  ```
  Excellent work! You followed the protocol perfectly:
  ✅ Stopped work immediately
  ✅ Secured 25-meter area
  ✅ Reported to supervisor
  ✅ Crew safe, expert en route

  The UXO expert assesses the object, confirms it's safe, and work resumes without incident.
  ```
- **Button:** "Next Scenario"

---

**Branching Path C (Wrong - Decision 1):**
- **Consequence screen:**
  - **Text:**
    ```
    ❌ Photos can wait. By getting out and approaching the object, you're putting yourself at risk.

    STOP WORK means stop—don't approach.
    ```
  - **Visual:** Worker too close, danger icon
  - **Button:** "Try Again"

---

**Branching Path D (Wrong - Decision 1):**
- **Consequence screen:**
  - **Text:**
    ```
    ❌ Covering it doesn't eliminate the danger. The next shift could trigger it.

    You must STOP WORK and report immediately.
    ```
  - **Visual:** Future worker endangered
  - **Button:** "Try Again"

---

**Rise Scenario Block Setup:**

1. **Add Scenario block**
2. **Initial scene:** Context + image
3. **Add Decision (branching):**
   - Rise → Scenario → Add Decision Point
   - Enter question and options (A, B, C, D)
4. **For each option:**
   - Rise → Add Branch
   - **If correct:** Show feedback → Continue to next decision
   - **If wrong:** Show consequence → Button "Try Again" loops back
5. **Chain decisions:** Decision 1 → Decision 2 → Decision 3 → Final Outcome
6. **Configure retries:** Unlimited attempts, must reach correct outcome

**QA checklist:**
- [ ] Scenario context is clear and realistic
- [ ] All 4 options display for each decision
- [ ] Branching works (wrong answers loop back, correct advances)
- [ ] Consequence graphics/text display for wrong answers
- [ ] Success outcome shows all correct actions
- [ ] Mobile: Scenario readable, branching works on touch

**Alt text:**
- Images: "Excavator digging foundation trench" / "Suspicious object partially exposed"
- Consequence graphics: "Explosion risk warning icon" / "Worker in danger zone illustration"

---

#### Screen 4.3 - Scenario 2: Hand Digging (Branching)

**Rise Block:** Scenario Block (Branching)

**Build steps:**

Follow same structure as Scenario 1 (setup, decisions, branching)

**Setup:**
- **Headline:** "Scenario 2: Fence Post Installation"
- **Context:** (Copy from storyboard - hand-digging post holes, cone-shaped object with fins found)
- **Visual:** Upload Image 3 (Hand digging) + Image 8 (Cone-shaped object)

**Decision structure:**
- Decision 1: What do you do? (Pull it out / Stop and step back ✓ / Pour water / Cover and dig elsewhere)
- Decision 2: What's next? (Mark 25m zone ✓ / Take photo / Call supervisor / Ask coworker)
- Decision 3: Who to report to? (Supervisor ✓ / DCC PM / Expert / Security)

**Outcome:**
```
Excellent! You recognized a suspicious object (cone + fins), stopped work, secured the area, and reported. Expert confirms it's a training round. Site cleared safely.
```

**QA checklist:**
- [ ] Scenario is distinct from Scenario 1 (hand digging vs excavator)
- [ ] Decision sequence reinforces protocol
- [ ] Branching works
- [ ] Success outcome displayed
- [ ] Mobile: Scenario functional

---

#### Screen 4.4 - Scenario 3: Supervisor Role (Branching)

**Rise Block:** Scenario Block (Branching)

**Build steps:**

**Setup:**
- **Headline:** "Scenario 3: Demolition Site (Supervisor Perspective)"
- **Context:** (Copy from storyboard - supervisor receives radio call from worker about object in wall cavity)
- **Visual:** Upload Image 4 (Demolition scene)

**Decision 1:** "What do you do FIRST as the supervisor?"
- Options: Inspect yourself / Verify work stopped and area secured ✓ / Call DCC PM / Tell worker to take photo

**Decision 2:** "Safety confirmed. What's your next responsibility?"
- Options: Document incident / Contact site authority ✓ / Assess danger / Resume other work

**Decision 3 (Multiple Select):** "What are your ongoing responsibilities? (Select all that apply)"
- ☑ Ensure no one enters exclusion zone (CORRECT)
- ☑ Keep crew informed of timeline (CORRECT)
- ☐ Inspect object closely (WRONG)
- ☑ Coordinate with site authority (CORRECT)
- ☐ Pressure expert to hurry (WRONG)

**Feedback:**
```
✅ Correct selections! Your role: safety, communication, coordination—NOT object assessment or timeline pressure.
```

**Outcome:**
```
Great work! As supervisor, you verified safety, escalated properly, documented the incident, and coordinated response. Expert cleared the site. Your leadership kept everyone safe.
```

**QA checklist:**
- [ ] Scenario shows supervisor perspective (role shift)
- [ ] Decisions reflect supervisor responsibilities
- [ ] Multiple-select question works (Decision 3)
- [ ] Feedback explains supervisor role clearly
- [ ] Mobile: Multiple-select functional

---

#### Screen 4.5 - Scenario Summary

**Rise Block:** Text + Results Summary

**Build steps:**
1. Add Text block
2. **Headline:** "Scenario Practice Complete"
3. **Results summary:**
   ```
   You've successfully completed all 3 scenarios:

   ✅ Scenario 1 (Excavation): Passed
   ✅ Scenario 2 (Hand Digging): Passed
   ✅ Scenario 3 (Supervisor): Passed
   ```

4. **Key takeaways:**
   ```
   You've practiced the protocol in realistic scenarios. You've seen the consequences of wrong decisions and the success of following protocol. You're ready for the final assessment.
   ```

5. **Confidence check:**
   - Add Knowledge Check (single question, optional)
   - **Question:** "How confident are you in applying the protocol on a real site?"
   - **Options (rating scale):**
     - ⭐⭐⭐⭐⭐ Very confident
     - ⭐⭐⭐⭐ Confident
     - ⭐⭐⭐ Somewhat confident
     - ⭐⭐ Not very confident
     - ⭐ Not confident
   - **Purpose:** Self-assessment data (not graded)

6. **If ≤3 stars selected:**
   - **Feedback:** "We recommend reviewing Module 3 (Protocol) before the assessment. You can also revisit scenarios."
   - **Link:** "Review Module 3"

7. **Progress indicator:** "4 of 5 modules complete"

8. **Button:** "Take Final Assessment"

**QA checklist:**
- [ ] Results summary shows all 3 scenarios passed
- [ ] Confidence check (if included) displays rating scale
- [ ] Feedback for low confidence offers review option
- [ ] Progress indicator shows 4/5
- [ ] Button advances to Module 5
- [ ] Mobile: Summary readable, confidence rating tappable

---

**Module 4 Build Complete Checklist:**
- [ ] All 5 screens built
- [ ] Scenario 1 (Excavation) branching works, all paths tested
- [ ] Scenario 2 (Hand Digging) branching works
- [ ] Scenario 3 (Supervisor) branching works, multiple-select functional
- [ ] Consequence screens display for wrong choices
- [ ] Success outcomes show for correct paths
- [ ] Scenario summary displayed
- [ ] Confidence check (optional) functional
- [ ] Mobile: All scenarios work on touch devices
- [ ] Progress shows "4 of 5"

---

### MODULE 5: Assessment & Resources (4 screens)

**Build time:** 2-3 hours

---

#### Screen 5.1 - Assessment Introduction

**Rise Block:** Quiz Intro (Text)

**Build steps:**
1. Add Text block (before Quiz block)
2. **Headline:** "Final Assessment: Prove Your Readiness"
3. **Instructions:**
   ```
   Questions: 10 multiple choice / multiple select
   Passing score: 80% (8/10 correct)
   Critical items: Must score 100% on safety-critical questions (4 questions)
   Attempts: Unlimited (review and retake until you pass)
   Feedback: Immediate after each question
   ```

4. **What's tested:**
   ```
   ✓ Recognition of suspicious objects
   ✓ Stop-work procedures
   ✓ Area security (25m exclusion)
   ✓ Reporting chain
   ✓ Role-specific responsibilities
   ✓ Prohibited actions
   ```

5. **Message:**
   ```
   This isn't about memorization—it's about proving you can protect yourself and your crew. Take your time.
   ```

6. **Button:** "Start Assessment"

**QA checklist:**
- [ ] Instructions are clear (passing score, attempts, critical items)
- [ ] "What's tested" sets expectations
- [ ] Tone is supportive, not intimidating
- [ ] Button starts quiz
- [ ] Mobile: Text readable

---

#### Screen 5.2 - Assessment Questions (Quiz Block)

**Rise Block:** Quiz

**Build steps:**

1. **Add Quiz block** (Rise → Assessment → Quiz)

2. **Quiz Settings:**
   - Rise → Quiz Settings
   - **Passing score:** 80%
   - **Attempts:** Unlimited
   - **Randomize questions:** Yes (randomize from 12-question bank)
   - **Randomize answers:** Yes
   - **Show feedback:** After each question (immediate)
   - **Results screen:** Show score, correct/incorrect breakdown
   - **Certificate:** Auto-issue on pass

3. **Question Bank:**

   **Import questions from Section 3 (Question Bank):**

   Use 10 of the 12 questions (see Document 04, Section 3 for full question bank)

   **Critical Items (must include these 4):**
   - Q1 (corrected): "What is your FIRST action when you encounter a suspicious object?" (Stop work immediately)
   - Q2: "What is the minimum safe distance for the exclusion zone?" (25 meters)
   - Q3: "As a construction worker, who do you report to first?" (Your supervisor)
   - Q5 (Multiple Select): "Which actions should NEVER be taken? (Select all)" (Touch/move, pour water, photograph close)

   **Additional Questions (choose 6 from remaining 8):**
   - Q4: "Which object characteristic is LEAST indicative of UXO?" (Square and wooden)
   - Q6: "You're unsure if an object is suspicious. What should you do?" (Treat as suspicious, stop work)
   - Q7: "After securing 25m exclusion zone, you should:" (Prevent all access)
   - Q8: "Which action violates stop-work protocol?" (Photographing up close)
   - Q9: "On DND site, when should you be aware of potential UXO?" (During any ground disturbance)
   - Q10: "What information should you provide when reporting?" (Location, description, time)
   - Q11: "Who is authorized to provide all-clear?" (UXO expert and site authority)
   - Q12: "A coworker wants to move suspicious object. What should you do?" (Stop them, reinforce protocol)

4. **Question Format in Rise:**

   **Example - Question 1 (Critical):**
   - **Type:** Multiple Choice
   - **Question:** "What is your FIRST action when you encounter a suspicious object?"
   - **Options:**
     - A) Take a photo
     - B) Stop work immediately ✓ CORRECT
     - C) Call your supervisor
     - D) Cover it with soil
   - **Feedback (Correct):** "✅ Correct! STOP WORK is always the first action."
   - **Feedback (Incorrect):** "❌ Not quite. The FIRST action is to STOP WORK immediately. Review Module 3, Screen 3.3."
   - **Mark as critical:** Tag question (for scoring logic)

   **Example - Question 5 (Critical, Multiple Select):**
   - **Type:** Multiple Select
   - **Question:** "Which actions should NEVER be taken with a suspicious object? (Select all)"
   - **Options:**
     - ☑ Touch or move the object (CORRECT)
     - ☐ Stop work (INCORRECT - this is correct action)
     - ☑ Pour water on it (CORRECT)
     - ☑ Photograph it up close (CORRECT)
     - ☐ Maintain 25m distance (INCORRECT - this is correct action)
   - **Feedback (All correct):** "✅ Correct! Never touch, move, apply liquids, or approach closely."
   - **Feedback (Partial/Incorrect):** "❌ Review which actions are prohibited. See Module 3, Screen 3.3."

5. **Scoring Logic:**
   - **Rise auto-scores** based on correct answers
   - **Critical item requirement:** If any critical item is wrong, show remediation message on results screen
   - **Custom results message:**
     - If score ≥80% AND all critical items correct: "PASS"
     - If score ≥80% BUT critical item(s) wrong: "You must score 100% on critical safety items. Review and retake."
     - If score <80%: "Review the content and retake the quiz."

6. **Question Entry:**
   - Rise → Quiz → Add Question
   - Enter each question (10 total)
   - Set correct answers
   - Add feedback for each option
   - Tag critical items (Questions 1, 2, 3, 5)

**QA checklist:**
- [ ] All 10 questions entered correctly
- [ ] Correct answers marked
- [ ] Feedback written for all options (correct + incorrect)
- [ ] Critical items tagged (4 questions)
- [ ] Randomization enabled
- [ ] Passing score set to 80%
- [ ] Unlimited attempts allowed
- [ ] Mobile: Questions readable, radio buttons/checkboxes tappable

---

#### Screen 5.3 - Job Aid Download

**Rise Block:** Text + Download Block

**Build steps:**

1. Add Text block
2. **Headline:** "Your Performance Support Tool: Job Aid"
3. **Body text:**
   ```
   You've completed the training. Now download this 1-page job aid for field reference. Keep it with you on every DND construction site.
   ```

4. **Job aid preview:**
   - Add Image block
   - Upload thumbnail preview of job aid (PDF first page screenshot)
   - **Caption:** "Quick reference for the 4-step protocol: Stop, Secure, Report, Wait. Includes red flags, prohibited actions, reporting chain, and emergency contacts."

5. **Download option 1: PDF**
   - Add Download block (Rise → Content → Download)
   - Upload file: `UXO_JobAid_v1.0_Printable.pdf`
   - **Button text:** "Download Job Aid (PDF)"
   - **Description:** "Printable, fillable contact fields"

6. **Download option 2: PNG (Mobile)**
   - Add Download block
   - Upload files: `UXO_JobAid_Front_v1.0.png` and `UXO_JobAid_Back_v1.0.png`
   - **Button text:** "View on Mobile (PNG)"
   - **Description:** "Mobile/tablet optimized images"

7. **Instructions:**
   ```
   Print and laminate for durability, or save to your mobile device. This job aid is your go-to resource in the field.
   ```

8. **Additional options:**
   - Add Button block (optional)
   - **Link:** "Email this job aid to yourself" (mailto link or form)

9. **Callout box:**
   ```
   Keep this accessible—it could save lives.
   ```

10. **Button:** "Continue"

**QA checklist:**
- [ ] Job aid preview image displays
- [ ] PDF download link works (test download)
- [ ] PNG download links work (test download)
- [ ] Downloaded files open correctly (PDF reader, image viewer)
- [ ] Instructions are clear
- [ ] Callout emphasizes importance
- [ ] Mobile: Downloads work on iOS/Android, files accessible

**Alt text:**
- Job aid preview: "Preview of UXO stop-work protocol job aid showing 4-step flowchart"

---

#### Screen 5.4 - Safety Commitment & Completion

**Rise Block:** Statement + Certificate

**Build steps:**

1. Add Text block
2. **Headline:** "Your Safety Commitment"
3. **Commitment statement:**
   ```
   Before you complete, acknowledge your commitment to safety:
   ```

4. **Interactive checkbox:**
   - Rise doesn't have native checkbox
   - **Workaround:** Use Knowledge Check with single question
   - **Question:** "Do you commit to applying the UXO stop-work protocol?"
   - **Options:**
     - ☑ "Yes, I understand the UXO stop-work protocol and commit to applying it on every DND site I work on. I will STOP work, SECURE the area, and REPORT any suspicious objects immediately."
   - **Feedback:** "Thank you for your commitment to safety."

5. **Legal disclaimer:**
   ```
   This training does not certify you as a UXO expert. Only qualified UXO disposal experts may handle, identify, or assess explosive ordnance. Your role is to recognize, stop work, and report.
   ```

6. **Certificate:**
   - Rise auto-generates certificate on quiz pass
   - **Display certificate preview image** (mock certificate graphic)
   - **Text:**
     ```
     Certificate of Completion
     UXO Awareness Training
     [Learner Name]
     Completed: [Date]
     Valid until: [Date + 12 months]
     Issued by: Defence Construction Canada
     ```

7. **Download certificate:**
   - Rise → Auto-download button appears after completion
   - **Button text:** "Download Certificate (PDF)"

8. **Next steps:**
   ```
   ✅ Keep your job aid accessible on site
   ✅ Review this training annually
   ✅ Ask questions anytime—safety first
   ✅ Apply the protocol every time
   ```

9. **Contact for questions:**
   ```
   Questions about UXO protocol?
   Contact DCC Environmental Services: [PHONE/EMAIL]
   ```

10. **Final message:**
    ```
    Thank you for completing this training. Your commitment to safety protects you, your crew, and the public. Stay safe.
    ```

11. **Button:** "Exit Training"

**Rise Completion Trigger:**
- Rise → Settings → Completion
- **Mark complete when:** Learner views all lessons + passes quiz + reaches this final screen
- SCORM/xAPI sends completion status to LMS

**QA checklist:**
- [ ] Commitment question/checkbox displays
- [ ] Learner must acknowledge to proceed (if using KnowledgeCheck workaround)
- [ ] Legal disclaimer is visible
- [ ] Certificate preview displays
- [ ] Certificate download button appears (after quiz pass)
- [ ] Next steps are actionable
- [ ] Contact info is accurate
- [ ] "Exit Training" button triggers SCORM completion
- [ ] Mobile: All elements display, certificate downloadable

**Alt text:**
- Certificate preview: "UXO Awareness Training certificate of completion template"

---

**Module 5 Build Complete Checklist:**
- [ ] Assessment intro sets clear expectations
- [ ] Quiz block configured (10 questions, 80% pass, unlimited attempts)
- [ ] All 10 questions entered with correct answers and feedback
- [ ] Critical items scored correctly (4 questions)
- [ ] Results screen shows pass/fail with custom messages
- [ ] Job aid downloads work (PDF + PNG)
- [ ] Safety commitment displayed
- [ ] Certificate auto-generates and downloads
- [ ] Completion triggers SCORM/xAPI
- [ ] Mobile: Quiz functional, downloads work

---

**FULL MODULE BUILD COMPLETE! 🎉**

**Final Build Checklist:**
- [ ] Module 1 (6 screens) - Complete
- [ ] Module 2 (6 screens) - Complete
- [ ] Module 3 (10 screens) - Complete
- [ ] Module 4 (5 screens) - Complete
- [ ] Module 5 (4 screens) - Complete
- [ ] Total: 31 screens built
- [ ] All interactions tested (flashcards, accordions, tabs, scenarios, quiz)
- [ ] All media embedded (images, video, job aids)
- [ ] All alt text added
- [ ] Mobile preview checked
- [ ] Ready for QA testing

---

## 5. Quality Assurance Checklist

### 5.1 Content Review

**Proofread all text:**
- [ ] No typos or grammatical errors
- [ ] Consistent terminology (e.g., "UXO" not "ERW" randomly)
- [ ] Consistent formatting (capitalization, punctuation)
- [ ] Numbers/measurements accurate (25 meters, 80% pass score)
- [ ] Contact information accurate (placeholders replaced)

**SME Review:**
- [ ] All technical content accurate (protocol steps, distances, roles)
- [ ] No sensitive information included (specific site locations, classified details)
- [ ] Scope appropriate (no ordnance identification details)
- [ ] Tone appropriate (serious but not fear-based)

**Storyboard alignment:**
- [ ] All screens match storyboard (Document 04)
- [ ] No screens skipped or missing content
- [ ] All changes from storyboard documented (with justification)

---

### 5.2 Functionality Testing

**Interactive elements:**
- [ ] Flashcards flip (Screen 2.2)
- [ ] Accordions expand/collapse (Screens 3.3, 3.4)
- [ ] Tabs switch (Screens 2.3, 3.5)
- [ ] Process blocks display correctly (Screens 1.5, 3.2)
- [ ] Scenario branching works (Module 4 - all paths tested)
- [ ] Knowledge checks provide feedback (all KCs)
- [ ] Sorting/sequencing works (Screen 3.7)
- [ ] Quiz questions display and score correctly (Module 5)

**Navigation:**
- [ ] Continue buttons advance to next screen
- [ ] Module progress indicators update
- [ ] Learner can navigate backward (Rise sidebar)
- [ ] "Try Again" buttons loop back correctly (branching scenarios)

**Downloads:**
- [ ] Job aid PDF downloads and opens
- [ ] Job aid PNGs download and display
- [ ] Certificate generates and downloads (after quiz pass)

**Video/Audio:**
- [ ] Video plays without buffering
- [ ] Video controls work (play, pause, volume, fullscreen)
- [ ] Captions display correctly (if video included)
- [ ] Audio syncs with video (if narration included)

---

### 5.3 Accessibility Audit

**WCAG 2.1 AA Compliance:**

**Perceivable:**
- [ ] All images have alt text (descriptive, not decorative)
- [ ] Color contrast ≥4.5:1 for all text (Rise auto-validates)
- [ ] Color is not the only means of conveying information (use color + icon)
- [ ] Video has captions (if video included)
- [ ] Audio has transcript (if audio included)

**Operable:**
- [ ] All interactive elements keyboard-navigable (Tab, Enter, Arrow keys)
- [ ] No keyboard traps (can navigate in and out of all elements)
- [ ] No time limits (or user can extend/disable)
- [ ] Link text is descriptive ("Download job aid" not "Click here")

**Understandable:**
- [ ] Language is plain (Grade 8 reading level)
- [ ] Navigation is consistent (Rise default)
- [ ] Error messages are clear and constructive (quiz feedback)
- [ ] Instructions appear before interactions (e.g., "Click each card to flip")

**Robust:**
- [ ] Screen reader compatible (Rise native support)
- [ ] Works across browsers (Chrome, Firefox, Safari, Edge)
- [ ] Works across devices (desktop, tablet, mobile)
- [ ] ARIA labels present (Rise handles automatically)

**Testing tools:**
- [ ] Run WAVE accessibility checker (browser extension)
- [ ] Test with screen reader (NVDA, JAWS, or VoiceOver)
- [ ] Test keyboard-only navigation (no mouse)

---

### 5.4 Mobile Testing

**Devices to test:**
- [ ] iOS (iPhone - Safari browser)
- [ ] Android (Samsung/Google Pixel - Chrome browser)
- [ ] Tablet (iPad / Android tablet)

**Test checklist:**
- [ ] All screens load correctly
- [ ] Images scale and display (no broken images)
- [ ] Text is readable (no overlapping, no tiny font)
- [ ] Interactive elements work on touch (flashcards, tabs, accordions, buttons)
- [ ] Scenario branching works on touch
- [ ] Quiz questions are tappable (radio buttons, checkboxes)
- [ ] Video plays on mobile (iOS and Android)
- [ ] Downloads work (PDF and PNG files accessible)
- [ ] Vertical orientation works (primary)
- [ ] Landscape orientation works (secondary)

**Performance:**
- [ ] Module loads quickly on 4G/LTE (<10 seconds)
- [ ] Video buffers minimally (file size optimized)
- [ ] No crashes or freezes
- [ ] SCORM tracking works on mobile

---

### 5.5 Browser Testing

**Test in these browsers (latest 2 versions):**
- [ ] Google Chrome (desktop + mobile)
- [ ] Mozilla Firefox (desktop)
- [ ] Apple Safari (desktop + iOS)
- [ ] Microsoft Edge (desktop)

**Test checklist per browser:**
- [ ] Module loads and displays correctly
- [ ] All interactive elements work
- [ ] Video/audio plays
- [ ] Downloads work
- [ ] SCORM completion tracking works
- [ ] No console errors (developer tools → Console tab)

---

### 5.6 SCORM Testing

**LMS Upload Test:**
1. Export SCORM package from Rise (see Section 7)
2. Upload to test LMS (Moodle, Canvas, or client LMS)
3. Launch module as learner

**Test completion tracking:**
- [ ] LMS marks "Not Started" initially
- [ ] LMS marks "In Progress" after starting
- [ ] LMS saves progress (close and reopen - should resume)
- [ ] LMS marks "Complete" after finishing all screens + passing quiz
- [ ] LMS records score (quiz percentage)

**Test on multiple attempts:**
- [ ] Fail quiz (<80%) - LMS marks "Failed"
- [ ] Retake quiz - LMS updates score
- [ ] Pass quiz (≥80%) - LMS marks "Complete" + "Passed"

**Test certificate:**
- [ ] Certificate downloads after passing
- [ ] Certificate includes learner name, date, validity period

**Test on different LMS (if possible):**
- [ ] SCORM 1.2 package works
- [ ] SCORM 2004 package works (if using 2004)
- [ ] xAPI package works (if using xAPI)

---

### 5.7 Final QA Sign-Off

**Before delivering to client:**

- [ ] All content proofread (no errors)
- [ ] SME approved all technical content
- [ ] All interactions tested and functional
- [ ] Accessibility audit complete (WCAG 2.1 AA compliant)
- [ ] Mobile tested on iOS + Android
- [ ] Browser tested (Chrome, Firefox, Safari, Edge)
- [ ] SCORM package tested in LMS
- [ ] Certificate generates correctly
- [ ] Job aid downloads work
- [ ] All media assets load (images, video, audio)
- [ ] No broken links or missing files
- [ ] Stakeholder final approval received

**Sign-off document:**
```
UXO Awareness Training - Rise 360 Module
Version: 1.0
QA Completed: [Date]
Tested by: [QA Tester Name]
Approved by: [Stakeholder Name]
Status: READY FOR DELIVERY
```

---

## 6. Testing Protocol

### 6.1 Test Plan

**Testing phases:**
1. **Developer testing** (during build - iterative)
2. **QA testing** (after build complete - comprehensive)
3. **SME review** (content accuracy)
4. **Stakeholder review** (alignment with goals)
5. **Pilot testing** (50 users - real-world)

---

### 6.2 Developer Testing (During Build)

**Test as you build:**
- After each screen: Preview in Rise, check functionality
- After each module: Preview full module, test navigation
- After adding media: Check image display, video playback
- After interactions: Test flashcards, tabs, accordions, scenarios

**Tools:**
- Rise 360 Preview mode (desktop + mobile preview)
- Browser developer tools (inspect elements, check console for errors)

---

### 6.3 QA Testing (After Build)

**QA tester:** Dedicated QA person (not the builder - fresh eyes)

**Test environment:**
- Desktop (Windows + Mac)
- Mobile (iOS + Android)
- Tablet (iPad or Android)
- Browsers (Chrome, Firefox, Safari, Edge)

**Test cases:**

**TC1: Content Accuracy**
- Read all text, check for typos
- Verify numbers/facts (25m, 80%, 12 months)
- Check storyboard alignment

**TC2: Interactive Elements**
- Test all flashcards, accordions, tabs, process blocks
- Test scenario branching (all paths)
- Test quiz (correct answers, feedback, scoring)

**TC3: Navigation**
- Navigate forward through all 31 screens
- Navigate backward (Rise sidebar)
- Test "Try Again" loops (scenarios)
- Test module transitions

**TC4: Media**
- Verify all images load
- Test video playback + captions
- Test job aid downloads (PDF + PNG)
- Test certificate download

**TC5: Accessibility**
- Run WAVE checker (all screens)
- Test keyboard navigation (Tab through all elements)
- Test screen reader (NVDA or JAWS - sample screens)
- Verify alt text present (all images)

**TC6: Mobile**
- Test on iOS (iPhone, iPad)
- Test on Android (phone, tablet)
- Test touch interactions (flashcards, tabs, scenario branching)
- Test downloads on mobile

**TC7: SCORM**
- Export SCORM, upload to LMS
- Test completion tracking
- Test scoring
- Test resume functionality

**Bug tracking:**
- Use spreadsheet or tool (Jira, Trello, Google Sheets)
- Log: Screen #, Issue description, Severity (Critical/High/Medium/Low), Status

---

### 6.4 SME Review

**Subject Matter Expert:** UXO safety specialist, DCC Environmental Services

**Review focus:**
- Content accuracy (protocol steps, distances, terminology)
- Scenario realism (do scenarios match field conditions?)
- Tone appropriateness (serious, not fear-based)
- Scope appropriateness (no ordnance identification details)

**Review method:**
- Provide SME with Rise preview link or SCORM package in LMS
- Ask SME to review all 5 modules
- Provide feedback form (Google Form or Word doc)

**SME feedback form questions:**
1. Is the protocol sequence correct? (STOP → SECURE → REPORT → WAIT)
2. Are distances/measurements accurate? (25m exclusion zone)
3. Are role responsibilities accurate? (worker, supervisor, site authority)
4. Are scenarios realistic for DND construction sites?
5. Is any critical information missing?
6. Is any information incorrect or misleading?
7. Is the tone appropriate for safety-critical training?
8. Is the scope appropriate (no sensitive/classified details)?
9. Any other feedback or concerns?

**Incorporate feedback:**
- Fix critical issues (inaccuracies, missing info)
- Consider medium issues (wording, clarity)
- Discuss low-priority suggestions (nice-to-have improvements)

---

### 6.5 Stakeholder Review

**Stakeholders:** DCC sponsor, project manager, instructional design lead

**Review focus:**
- Alignment with project goals
- Learner experience (engaging, clear, professional)
- Completion feasibility (can learners complete in 20 min?)
- Assessment rigor (does quiz prove competency?)

**Review method:**
- Provide stakeholders with Rise preview link
- Schedule review meeting (30-60 min walkthrough)
- Demonstrate key features (scenarios, quiz, job aid)

**Stakeholder approval:**
- Get written sign-off (email confirmation or approval form)
- Document any requested changes
- Implement approved changes before final delivery

---

### 6.6 Pilot Testing (Optional but Recommended)

**Pilot group:** 50 representative users
- 30 construction workers
- 10 supervisors
- 10 project managers

**Pilot duration:** 2 weeks

**Data to collect:**
- Completion rate (% who finish)
- Assessment scores (average, pass rate, most-missed questions)
- Time-on-task (average completion time)
- User feedback (survey - 5 questions)

**Pilot survey questions:**
1. The training was clear and easy to understand. (1-5 scale)
2. The scenarios were realistic and relevant to my work. (1-5 scale)
3. I feel confident applying the UXO protocol on site. (1-5 scale)
4. The training length was appropriate. (Too short / Just right / Too long)
5. What would you change or improve? (Open text)

**Analyze pilot data:**
- If completion rate <90%: Investigate barriers
- If average score <85%: Review most-missed questions, clarify content
- If time >25 min: Consider shortening or chunking differently
- If satisfaction <4.0: Review feedback, identify pain points

**Iterate based on pilot:**
- Fix critical issues (confusing content, broken interactions)
- Revise quiz questions (if consistently missed)
- Adjust scenarios (if unrealistic feedback)
- Update to v1.1 before full rollout

---

## 7. SCORM Export & Delivery

### 7.1 Export from Rise 360

**Steps:**

1. **Open project in Rise 360**
   - Navigate to your course: "UXO Awareness Training"

2. **Click "Export"** (top right)
   - Rise → Export button

3. **Choose format:**
   - **SCORM 1.2** (most compatible with older LMS)
   - **SCORM 2004 3rd Edition** (newer, better tracking)
   - **xAPI/Tin Can** (if client has LRS)
   - **PDF** (for review only, not for LMS)

   **Recommendation:** Export both SCORM 1.2 and SCORM 2004 (provide both to client for flexibility)

4. **Configure export settings:**
   - **Title:** "UXO Awareness Training"
   - **Description:** "Safety-critical training for construction teams on DND sites"
   - **Completion tracking:** Track by views + quiz (must view all lessons and pass quiz)
   - **Quiz tracking:** Track score + pass/fail
   - **LMS behavior:** Resume from last location

5. **Click "Export"**
   - Rise generates SCORM package (takes 1-3 minutes)
   - Download ZIP file: `UXO_Awareness_SCORM.zip`

6. **Repeat for other formats** (if needed)
   - Export SCORM 2004: `UXO_Awareness_SCORM2004.zip`
   - Export xAPI: `UXO_Awareness_xAPI.zip`

---

### 7.2 SCORM Package Contents

**Inside the ZIP file:**
- `imsmanifest.xml` (SCORM manifest - LMS reads this)
- `scormdriver/` (SCORM tracking scripts)
- `lib/` (Rise 360 runtime libraries)
- `index_lms.html` (launch file)
- Media files (images, video, audio)

**File size:** Typically 30-60 MB (depending on video/media)

**DO NOT unzip or modify files** - LMS uploads the ZIP as-is

---

### 7.3 Test SCORM Package in LMS

**Before delivering to client, test in LMS:**

**Option A: Use SCORM Cloud (free testing)**
1. Go to https://cloud.scorm.com
2. Create free account
3. Upload SCORM ZIP
4. Launch and test as learner
5. Verify completion tracking, scoring

**Option B: Use client's LMS (if available)**
1. Request test LMS access from client
2. Upload SCORM ZIP to test course
3. Launch and test
4. Verify completion, scoring, resume

**Test checklist:**
- [ ] Module launches correctly
- [ ] All screens display
- [ ] Interactions work
- [ ] Quiz scores correctly
- [ ] Completion status updates (In Progress → Complete)
- [ ] Score is recorded in LMS
- [ ] Learner can resume from last location

---

### 7.4 Delivery Package

**What to deliver to client:**

**Primary deliverables:**
1. **SCORM packages:**
   - `UXO_Awareness_SCORM_v1.0.zip` (SCORM 1.2)
   - `UXO_Awareness_SCORM2004_v1.0.zip` (SCORM 2004)
   - `UXO_Awareness_xAPI_v1.0.zip` (xAPI - if requested)

2. **Job aid files:**
   - `UXO_JobAid_v1.0_Printable.pdf`
   - `UXO_JobAid_Front_v1.0.png`
   - `UXO_JobAid_Back_v1.0.png`

3. **Implementation package:**
   - `UXO_Implementation_Guide_v1.0.pdf` (from Document 04)

4. **Question bank:**
   - `UXO_Question_Bank_v1.0.docx`

**Supporting deliverables:**
5. **Source files:**
   - `UXO_Awareness_Source_v1.0.zip` (Rise 360 project export - for future edits)

6. **Media assets:**
   - `UXO_Media_Assets_v1.0.zip` (all images, video, audio files)

7. **Documentation:**
   - `UXO_Build_Documentation_v1.0.pdf` (this build plan + storyboard)
   - `UXO_QA_Report_v1.0.pdf` (QA test results, sign-off)

**Delivery method:**
- Upload to secure file transfer (SFTP, SharePoint, Dropbox, Google Drive)
- Create README.txt file with:
  - File manifest (list of all files)
  - Instructions for LMS upload
  - Contact info for support

**README.txt example:**
```
UXO Awareness Training - Delivery Package
Version: 1.0
Date: [Delivery Date]
Client: Defence Construction Canada (DCC)

FILES INCLUDED:
1. UXO_Awareness_SCORM_v1.0.zip (SCORM 1.2 package for LMS)
2. UXO_Awareness_SCORM2004_v1.0.zip (SCORM 2004 package)
3. UXO_JobAid_v1.0_Printable.pdf (Job aid - printable)
4. UXO_JobAid_Front_v1.0.png (Job aid - mobile front)
5. UXO_JobAid_Back_v1.0.png (Job aid - mobile back)
6. UXO_Implementation_Guide_v1.0.pdf (LMS setup + rollout plan)
7. UXO_Question_Bank_v1.0.docx (12-item assessment bank)
8. UXO_Awareness_Source_v1.0.zip (Rise 360 source - for edits)
9. UXO_Media_Assets_v1.0.zip (Images, video, audio files)
10. UXO_Build_Documentation_v1.0.pdf (Build plan + storyboard)
11. UXO_QA_Report_v1.0.pdf (QA test results)

INSTRUCTIONS:
1. Upload SCORM package (file 1 or 2) to your LMS
2. Configure LMS settings per Implementation Guide (file 6)
3. Distribute job aid (files 3-5) to learners
4. Follow rollout plan in Implementation Guide

SUPPORT:
For technical support or questions, contact:
[Your Name]
[Email]
[Phone]

For content questions, contact:
[SME Name]
[Email]
```

---

## 8. Build Timeline & Effort Estimate

### 8.1 Timeline Overview

**Total build time:** 8 weeks (with contingency for reviews)

| Week | Phase | Tasks | Hours |
|------|-------|-------|-------|
| 1 | Pre-Build | Setup, asset gathering, storyboard review | 20 |
| 2 | Module 1 + 2 | Build Modules 1-2 (12 screens) | 30 |
| 3 | Module 3 (Part 1) | Build Module 3, Screens 1-5 | 20 |
| 4 | Module 3 (Part 2) + Module 4 | Build Module 3 (Screens 6-10) + Module 4 (scenarios) | 30 |
| 5 | Module 5 + Media | Build Module 5 (quiz) + integrate video/media | 25 |
| 6 | QA Testing | Comprehensive QA, accessibility audit, SCORM testing | 20 |
| 7 | Reviews | SME review, stakeholder review, implement feedback | 15 |
| 8 | Final QA + Delivery | Final testing, SCORM export, packaging, delivery | 10 |
| **Total** | | | **170 hours** |

**Note:** This is developer time (hands-on build). Additional time needed for:
- Media creation (video, job aid design): +20-40 hours
- Project management: +10-15 hours
- Client meetings/reviews: +5-10 hours

**Total project time:** ~205-235 hours

---

### 8.2 Detailed Effort Breakdown

#### Week 1: Pre-Build Preparation (20 hours)

- [ ] Rise 360 setup (project, theme, settings): 2 hours
- [ ] Storyboard review meeting with SME/stakeholders: 2 hours
- [ ] Media asset gathering/sourcing: 8 hours
  - Source stock images: 3 hours
  - Commission/create illustrations: 3 hours (or external vendor)
  - Source icons: 1 hour
  - Organize files, write alt text: 1 hour
- [ ] Content preparation (copy text from storyboard, proofread): 3 hours
- [ ] Job aid design (external or internal): 5 hours (may be parallel with build)

#### Week 2: Build Modules 1-2 (30 hours)

- [ ] Module 1 (6 screens): 12 hours
  - Title card, scenario intro, consequences, UXO definition, protocol preview, commitment: ~2 hours per screen
- [ ] Module 2 (6 screens): 12 hours
  - Intro, flashcards, tabs, recognition practice, knowledge check, summary: ~2 hours per screen
- [ ] First QA pass (developer testing): 3 hours
- [ ] Revisions: 3 hours

#### Week 3: Module 3 Part 1 (20 hours)

- [ ] Module 3, Screens 1-5: 15 hours
  - Intro, protocol overview, Step 1 (STOP), Step 2 (SECURE), Step 3 (REPORT): ~3 hours per screen (more complex with accordions, tabs, diagrams)
- [ ] Developer testing: 3 hours
- [ ] Revisions: 2 hours

#### Week 4: Module 3 Part 2 + Module 4 (30 hours)

- [ ] Module 3, Screens 6-10: 12 hours
  - Step 4 (WAIT), sequencing practice, reporting chain KC, video integration, summary: ~2-3 hours per screen
- [ ] Module 4 (5 screens - branching scenarios): 15 hours
  - Intro: 1 hour
  - Scenario 1 (Excavation): 5 hours (branching logic setup)
  - Scenario 2 (Hand Digging): 4 hours
  - Scenario 3 (Supervisor): 4 hours
  - Scenario summary: 1 hour
- [ ] Developer testing: 3 hours

#### Week 5: Module 5 + Media Integration (25 hours)

- [ ] Module 5 (4 screens): 15 hours
  - Assessment intro: 1 hour
  - Quiz setup (10 questions, feedback, scoring logic): 8 hours
  - Job aid download screen: 2 hours
  - Commitment + certificate: 4 hours
- [ ] Video integration (if video ready): 3 hours
  - Upload, caption sync, test playback
- [ ] Final media checks (all images, downloads): 2 hours
- [ ] Developer testing: 3 hours
- [ ] Revisions: 2 hours

#### Week 6: QA Testing (20 hours)

- [ ] Content review (proofread all 31 screens): 4 hours
- [ ] Functionality testing (all interactions, navigation): 6 hours
- [ ] Accessibility audit (WCAG, WAVE checker, screen reader): 4 hours
- [ ] Mobile testing (iOS, Android, tablet): 3 hours
- [ ] Browser testing (Chrome, Firefox, Safari, Edge): 2 hours
- [ ] SCORM export + LMS testing: 1 hour

#### Week 7: Reviews & Revisions (15 hours)

- [ ] SME review meeting: 2 hours
- [ ] Implement SME feedback: 5 hours
- [ ] Stakeholder review meeting: 2 hours
- [ ] Implement stakeholder feedback: 4 hours
- [ ] Final proofread: 2 hours

#### Week 8: Final QA & Delivery (10 hours)

- [ ] Final QA pass (all screens, all devices): 3 hours
- [ ] SCORM export (SCORM 1.2 + 2004 + xAPI): 1 hour
- [ ] Test SCORM in LMS (final check): 2 hours
- [ ] Package deliverables (organize files, create README): 2 hours
- [ ] Upload to delivery platform: 1 hour
- [ ] Delivery meeting with client: 1 hour

---

### 8.3 Accelerated Timeline (6 weeks)

**If timeline is tight:**

- **Week 1:** Pre-build (compress to 15 hours)
- **Week 2:** Modules 1-2 (build faster, minimal revisions)
- **Week 3:** Module 3 complete (work longer days)
- **Week 4:** Modules 4-5 (scenarios + quiz in one week)
- **Week 5:** QA + Reviews (combined, parallel feedback)
- **Week 6:** Final QA + Delivery

**Risk:** Less time for iteration, higher risk of issues in pilot

---

### 8.4 Resources Needed

**People:**
- **Instructional designer / Rise 360 developer:** 1 FTE (full-time equivalent) for 8 weeks
- **QA tester:** 0.5 FTE (part-time) for Week 6
- **SME (UXO safety expert):** 5-10 hours (reviews, feedback)
- **Graphic designer (job aid):** 5-10 hours (may be parallel)
- **Video producer (optional):** 10-20 hours (if creating protocol demo video)
- **Project manager:** 0.25 FTE (coordination, meetings)

**Tools:**
- **Articulate Rise 360:** Subscription ($1,399/year per seat or $125/month)
- **Stock images:** Envato Elements ($16.50/month) or Adobe Stock ($30-100 one-time)
- **Video editing (if DIY):** Adobe Premiere, Final Cut, or free (DaVinci Resolve)
- **Graphic design (job aid):** Adobe InDesign/Illustrator, Canva Pro, or PowerPoint

**Budget estimate:**
- Developer time (170 hours @ $75-150/hr): $12,750 - $25,500
- Media assets (stock images, icons): $100 - $500
- Video production (optional): $500 - $5,000 (depending on approach)
- Job aid design: $300 - $1,000
- Rise 360 subscription: $125/month (2 months = $250)
- **Total:** $13,900 - $32,250 (wide range depending on hourly rate and video option)

---

## Summary

This Rise 360 Build Plan provides:

✅ **Complete build workflow** - Pre-build → Module build → QA → Delivery
✅ **Screen-by-screen build guide** - Step-by-step instructions for all 31 screens
✅ **Media asset specifications** - Detailed requirements for 25+ images, video, job aid
✅ **QA checklist** - Content, functionality, accessibility, mobile, SCORM testing
✅ **Testing protocol** - Developer, QA, SME, stakeholder, pilot testing
✅ **SCORM export guide** - Export, test, package, deliver
✅ **Timeline & effort estimate** - 8-week timeline, 170-hour build estimate

**Next steps:**
1. ✅ Review this build plan
2. ✅ Gather/create media assets (Section 3)
3. ✅ Set up Rise 360 project (Section 2.1)
4. ✅ Begin Module 1 build (Section 4)
5. ✅ Follow QA protocol (Section 5)
6. ✅ Export SCORM and deliver (Section 7)

**Your UXO Awareness Training module will be built to professional standards, accessible, engaging, and ready to save lives on DND construction sites!**

---

**End of Rise 360 Build Plan**

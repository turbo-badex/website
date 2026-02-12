# Learning Experience Design
## UXO Awareness Training: "Stop Work. Secure the Area. Report."

**Client:** Defence Construction Canada (DCC), Environmental Services
**Project:** UXO Awareness for Construction Teams
**Focus:** Engagement, Completion, Multimedia Learning
**Designer:** [Your Name]
**Date:** [Current Date]
**Version:** 1.0

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Completion Optimization Strategy](#completion-optimization-strategy)
3. [Engagement Design](#engagement-design)
4. [Multimedia Learning Design](#multimedia-learning-design)
5. [Microlearning Design](#microlearning-design)
6. [Scenario Design](#scenario-design)
7. [Visual Design System](#visual-design-system)
8. [Accessibility Design](#accessibility-design)

---

## Executive Summary

This learning experience design document outlines strategies to ensure high completion rates and effective learning for **mandatory safety training**. The challenge: engage construction workers in compliance training while respecting their time and delivering life-saving protocol knowledge.

### Design Challenge

| Challenge | Solution |
|-----------|----------|
| **Mandatory training** (low intrinsic motivation) | Hook with real consequences, emphasize life-saving value |
| **Mobile-first audience** (field distractions) | Clear visuals, minimal text, high-impact messaging |
| **Time-limited** (15-20 min max) | Microlearning structure (5 modules, 3-7 min each) |
| **Compliance mindset** ("just pass and move on") | Scenario-based consequences (show why protocol matters) |
| **Wide experience range** (novice to expert) | Accessible to beginners, not boring to experts |

### Key Experience Design Decisions

| Aspect | Decision | Rationale |
|--------|----------|-----------|
| **First 60 Seconds** | Hook with real incident + clear promise ("20 min, could save your life") | Critical window to capture attention |
| **Progress Visualization** | Module badges, "3 of 5 complete" tracker | Reduce uncertainty, celebrate milestones |
| **Friction Reduction** | Auto-save, mobile-optimized, offline-capable | Respect worker context (field, limited time) |
| **Engagement** | Branching scenarios with consequences | Active learning, show "why it matters" |
| **Gamification** | Subtle (progress tracking, badges) NOT points/leaderboards | Appropriate for safety (avoid trivialization) |

### Success Metrics

- **Completion Rate:** ≥90% (mandatory, well-designed)
- **Time-on-Task:** 15-20 minutes average (within design spec)
- **Drop-Off Analysis:** <5% abandonment per module
- **Confidence Increase:** +1.5 points (pre/post survey: "I feel confident applying the protocol")

---

## Completion Optimization Strategy

### Challenge: Mandatory Safety Training

**Low Intrinsic Motivation Factors:**
- Compliance-driven (required for site access, not personal interest)
- "Just want to work" attitude (training seen as obstacle)
- Skepticism ("I've worked construction for 20 years, I know what I'm doing")
- Mobile distractions (notifications, calls, field environment)

**Extrinsic Motivators We Can Leverage:**
- Job requirement (no training = no site access)
- Safety culture (protect yourself and crew)
- Completion certificate (proof of compliance)
- Manager oversight (accountability)

### Completion Tactics

#### 1. First 60 Seconds: Critical Hook

**Goal:** Capture attention, set expectations, create urgency

**Screen 1.1-1.2 Design:**

**Opening Line (Screen 1.2):**
> "Construction sites on DND properties can hold hidden dangers from historical military activities."

[Click to reveal: Suspicious object appears in ground]

**Hook (Screen 1.3):**
> "In 2019, a worker at a former military base touched a suspicious object. The site was evacuated. Bomb disposal experts confirmed it was live ordnance. **The worker was lucky—he followed protocol and stopped work immediately.**"

**Promise (Screen 1.3):**
> "20 minutes. Could save your life. Let's go."

**Progress Preview (Screen 1.1):**
> "5 short modules, ~4 min each"

**Why This Works:**
- **Real Consequence:** Not hypothetical ("could happen") but actual ("did happen")
- **Positive Outcome:** Worker who followed protocol stayed safe (not fear-based)
- **Clear Promise:** Specific time commitment + value proposition
- **Low Commitment:** 20 minutes feels manageable (not "this will take all day")
- **Quick Win:** First knowledge check at Screen 2.4 (within 5 minutes)

**Measurement:** <5% drop-off after Module 1

---

#### 2. Progress Visualization

**Goal:** Reduce uncertainty, celebrate progress, maintain momentum

**Progress Indicators:**

| Location | Indicator | Purpose |
|----------|-----------|---------|
| **Module Menu** (Left sidebar) | Checkmarks for completed modules | See overall progress at a glance |
| **Within Module** | "Screen 3 of 10" or progress bar | Know how far through current module |
| **Module Intro** | "Module 2 of 5" + time estimate "~3 min" | Set expectations, manage time |
| **Module Completion** | ✅ Badge graphic + "Module 2 Complete!" | Celebrate milestone, micro-reward |
| **Between Modules** | "Great progress! 3 of 5 modules complete" | Positive reinforcement, keep going |

**Celebratory Micro-Animations:**
- Module complete: Checkmark animation + brief success sound (optional)
- Final assessment passed: Certificate reveal animation + congratulations message
- Job aid download: Download icon animation + "Keep this with you on site" reminder

**Why This Works:**
- **Reduces Anxiety:** Learners know exactly how far they are, how much remains
- **Celebrates Progress:** Each module completion feels like an achievement
- **Maintains Momentum:** "3 of 5 done—almost there!" motivates continuation
- **Progress Salience:** Visible progress creates commitment to finish

**Measurement:** Track average modules completed per session (target: ≥3)

---

#### 3. Friction Reduction

**Goal:** Make it easy to start, continue, and complete training

**Friction Points & Solutions:**

| Friction Point | Solution |
|----------------|----------|
| **"I don't have time now"** | Auto-save progress, resume later exactly where you left off |
| **"Mobile site doesn't load"** | Rise 360 responsive design, optimized for 4G, works on all devices |
| **"I'm in the field with no WiFi"** | SCORM download = offline-capable, complete without internet |
| **"I already know this"** | Skip navigation (if previously passed), fast-forward to assessment (v2 feature) |
| **"I got stuck on that question"** | Unlimited assessment attempts, review content between attempts |
| **"My browser crashed"** | Auto-save + LMS suspend data = no lost progress |

**Mobile Optimization:**
- **Vertical Scroll:** Rise default (thumb-friendly)
- **Large Tap Targets:** Buttons ≥44px (easy to tap with gloves or in field)
- **Minimal Data:** Compressed images, optimized video (works on 4G)
- **Offline Mode:** Download SCORM package in advance, complete without connectivity
- **Battery-Friendly:** No auto-playing videos, no animations that drain battery

**Learner-Paced:**
- **Continue Buttons:** Learner clicks to advance (no auto-advance timers)
- **Pause Anytime:** Close browser, resume later (LMS suspend data saves state)
- **No Time Limits:** Self-paced assessment (safety learning, not speed test)
- **Review Allowed:** Go back to previous screens if needed (menu access)

**Why This Works:**
- **Respects Context:** Construction workers have unpredictable schedules (breaks, calls, emergencies)
- **Reduces Abandonment:** "I'll finish this later" actually happens (not lost progress)
- **Removes Excuses:** "No WiFi", "No time", "Got interrupted" → all addressed
- **Increases Completion:** Every barrier removed = higher completion rate

**Measurement:** Completion rate by device type (mobile vs. desktop), session distribution (1 sitting vs. multiple)

---

#### 4. Accountability Structures

**Goal:** Create external motivation and consequences for non-completion

**Accountability Mechanisms:**

| Mechanism | Implementation | Effectiveness |
|-----------|----------------|---------------|
| **Mandatory Requirement** | No training = No site access (enforced by DCC) | HIGH |
| **Manager Notification** | Supervisor receives completion notification (LMS email) | MEDIUM-HIGH |
| **Certificate Expiry** | Certificate valid 1 year (annual refresher required) | MEDIUM |
| **Peer Pressure** | (Optional) Crew completion leaderboard by site | MEDIUM |
| **Follow-Up Emails** | Reminder emails to non-completers (7 days before deadline) | MEDIUM |

**Pre-Training Accountability:**
- **Manager Communication:** Supervisor assigns training, sets deadline, explains importance
- **Site Induction:** Training requirement communicated during onboarding
- **Access Control:** LMS completion required to access site (enforced at gate or badge system)

**During Training:**
- **Progress Emails:** "You're halfway through—finish today!" (if paused mid-module)
- **Deadline Reminders:** "Training due in 3 days" (automated LMS emails)

**Post-Training:**
- **Completion Certificate:** Proof of compliance (downloadable, shareable)
- **Manager Report:** Supervisor sees crew completion status (encourages follow-up)
- **Annual Renewal:** Certificate expires, requires refresher (ongoing accountability)

**Why This Works:**
- **Clear Stakes:** "No training = Can't work" is unambiguous motivation
- **Social Accountability:** Manager oversight and peer visibility create pressure to complete
- **Long-Term:** Annual renewal prevents "one and done" mindset

**Measurement:** Completion rate by deadline, time-to-completion distribution

---

### Completion Benchmarks

| Audience | Target Completion | Rationale |
|----------|-------------------|-----------|
| **Construction Workers** | ≥90% | Mandatory, largest audience |
| **Site Supervisors** | ≥95% | Leadership role, model behavior |
| **DCC Project Staff** | ≥90% | Oversight responsibility |

**Acceptable Completion Timeline:**
- **Week 1:** 40-50% complete (early adopters)
- **Week 2:** 70-80% complete (majority)
- **Week 3:** 85-90% complete (stragglers)
- **Week 4:** ≥90% complete (deadline, escalations)

**Red Flags (Requiring Intervention):**
- Overall completion <80% by deadline → Investigate barriers, extend deadline, increase reminders
- Module 1 drop-off >10% → Opening not engaging, revise hook
- Module 3 drop-off >10% → Content too long/complex, simplify protocol section
- Assessment failure rate >20% → Content not preparing learners, revise instruction

---

## Engagement Design

### Motivation Framework

**Challenge:** Mandatory compliance training has LOW intrinsic motivation

**Intrinsic Motivators (Limited Applicability):**
- **Autonomy:** Choice of device (mobile/desktop), pace (self-paced), order (can skip around within modules)
- **Mastery:** Progressive difficulty (recognition → protocol → practice), retry until confident
- **Purpose:** "Protect yourself and your crew" (safety value, not just compliance)

**Extrinsic Motivators (Primary Drivers):**
- **Compliance:** Required for job (site access), clear consequence
- **Social:** Crew completion tracking (optional leaderboard), manager oversight
- **Recognition:** Completion certificate, "Safety Certified" badge, manager acknowledgment

**How We Address the Motivation Challenge:**
1. **Acknowledge Reality:** Open with "This is mandatory, AND it's life-saving"
2. **Minimize Time:** 20 minutes (respect their time, don't waste it)
3. **Show Relevance:** Real incidents, construction-specific scenarios
4. **Make It Engaging:** Scenarios, not lectures; consequences, not theory
5. **Provide Value:** Job aid they can actually use in the field

---

### Engagement Tactics

#### 1. Emotional Connection

**Goal:** Make it personal, not abstract

**Techniques:**

| Technique | Implementation | Screen |
|-----------|----------------|--------|
| **Real Consequences** | Anonymized 2019 incident (worker touched object, evacuation) | 1.3 |
| **"It Could Happen to You"** | Construction-specific scenarios (excavation, trenching, demolition) | 2.5, 4.2-4.4 |
| **Crew Safety Focus** | "Protect yourself and your crew" (not just individual) | Throughout |
| **Positive Framing** | Worker who followed protocol stayed safe (success story, not fear) | 1.3, 4.2 outcome |
| **Respect for Experience** | "You know construction—now add this safety layer" | 1.6 |

**Why This Works:**
- **Concrete > Abstract:** Real incident > "UXO is dangerous" (which everyone already knows)
- **Crew Responsibility:** Construction culture values team safety ("watch out for each other")
- **Positive Outcome:** Success stories motivate better than fear ("this saved a life" vs. "you could die")
- **Respect:** Acknowledges their expertise, positions training as additional tool (not remedial)

---

#### 2. Active Learning

**Goal:** No passive "next, next, next" clicking—every screen has interaction

**Interaction Types:**

| Screen Type | Interaction | Engagement Level |
|-------------|-------------|------------------|
| **Scenario Reveal** | Click to uncover hidden object | Medium-High |
| **Flashcards** | Flip cards to reveal details (6 red flags) | High |
| **Image Sorting** | Drag or click to categorize (suspicious vs. normal) | High |
| **Branching Scenario** | Make decision → See consequence | Very High |
| **Drag-and-Drop** | Order protocol steps correctly | High |
| **Multiple Choice** | Select answer, get immediate feedback | Medium |
| **Role-Specific Tabs** | Choose your role, see relevant content | Medium-High |
| **Video** | Watch protocol demonstration (optional captions) | Medium |
| **Quiz** | Test knowledge, retry if failed | High (stakes) |

**No Passive Screens:**
- ❌ NO walls of text ("Read this policy")
- ❌ NO lecture-style content dumps
- ❌ NO "Click Next to Continue" as the only interaction

**Every Screen Has:**
- ✅ Decision point OR
- ✅ Interactive element OR
- ✅ Practice opportunity OR
- ✅ Self-check question

**Why This Works:**
- **Active Encoding:** Interaction improves memory retention vs. passive reading
- **Engagement:** Hands-on tasks feel less like "training," more like doing
- **Immediate Feedback:** Know instantly if you're right/wrong (not wait until end)
- **Reduces Boredom:** Variety of interactions = less monotony

---

#### 3. Consequences Made Visible

**Goal:** Show why the protocol matters (not just "because we say so")

**Consequence Design:**

**Scenario: Excavator Operator (Module 4, Screen 4.2)**

| Choice | Immediate Consequence Shown | Learning Point |
|--------|----------------------------|----------------|
| **A: Continue digging** | ⚠️ Animation: Explosion, evacuation, medics | "This is why we STOP immediately" |
| **B: Stop immediately ✓** | ✅ "Correct! Site secured, crew safe" | Positive reinforcement |
| **C: Take photo** | ⚠️ "You're too close! Photos later" | Prioritization (safety > documentation) |
| **D: Cover and ignore** | ⚠️ "Next worker could trigger it" | Responsibility (can't ignore danger) |

**Visual Consequences:**
- **Wrong Choice:** Brief animation showing outcome (explosion, injury risk)—NOT graphic, but impactful
- **Correct Choice:** Success animation (checkmark, "site secured," thumbs up from crew)
- **Text Feedback:** Explain WHY choice is wrong ("Vibration could detonate") or right ("Correct sequence")

**Emotional Impact:**
- Serious tone (not cartoonish)
- Focus on "what could happen" (risk) vs. "what you did wrong" (blame)
- Emphasize successful outcome when protocol followed ("Everyone stayed safe")

**Why This Works:**
- **Motivation:** Seeing consequences creates urgency ("I MUST do this correctly")
- **Memory:** Emotional events are remembered better (consequence-based learning sticks)
- **Behavior Change:** Scenarios simulate real decisions, practice behavioral response
- **Transfer:** "I remember seeing what happened when I clicked wrong—I won't do that on site"

---

#### 4. Gamification (Subtle, Appropriate for Safety)

**Goal:** Increase engagement WITHOUT trivializing safety

**What We Include (Subtle Gamification):**

| Element | Implementation | Why It's Appropriate |
|---------|----------------|----------------------|
| **Progress Tracking** | Module checkmarks, "3 of 5 complete" | Completion-focused, not competitive |
| **Achievement Badges** | ✅ Module completion badges | Celebrate milestones, not points |
| **Streak Protection** | Resume later without penalty, auto-save | Removes pressure, supports flexibility |
| **Immediate Feedback** | Instant right/wrong in quizzes | Learning-focused, not score-focused |
| **Mastery-Based** | Retry until pass (unlimited attempts) | Emphasizes learning, not gatekeeping |

**What We Exclude (Inappropriate for Safety):**

| Element | Why We DON'T Use It |
|---------|---------------------|
| ❌ **Points System** | Trivializes safety ("You earned 100 points for knowing not to die!") |
| ❌ **Leaderboards** | Competition inappropriate (this isn't a game, it's life-safety) |
| ❌ **Timers / Speed Bonuses** | Rushing through safety training defeats the purpose |
| ❌ **Unlockables / Rewards** | Completion IS the reward (site access + safety knowledge) |
| ❌ **Avatars / Personas** | Unnecessary distraction from serious content |

**Design Principle:**
> "Gamification for engagement, NOT for entertainment. Safety training is serious business."

**Why This Works:**
- **Engagement:** Progress tracking and badges increase motivation (documented in learning research)
- **Respect:** Avoids trivializing serious safety content with inappropriate "game" elements
- **Focus:** Keeps attention on learning objectives, not chasing points
- **Culture-Appropriate:** Construction workers expect straightforward, no-BS training (not "edutainment")

---

### Interactivity Map

| Module | Primary Interactions | Engagement Level |
|--------|---------------------|------------------|
| **Module 1: Why This Matters** | Scenario reveal (click to uncover object), commitment statement (type name) | Medium-High |
| **Module 2: Recognition** | Flashcard stack (flip 6 cards), image sorting (6 items), scenario quiz (MC with branching) | High |
| **Module 3: Protocol** | Video (protocol demo), role tabs (Worker/Supervisor/PM), accordion (DO/DON'T lists), drag-and-drop (sequence), MC quiz | High |
| **Module 4: Practice** | Branching scenarios (3 scenarios, multiple decision points each, consequence animations) | Very High |
| **Module 5: Assessment** | 10-question quiz (immediate feedback, retry if failed), job aid download, certificate | High (stakes) |

**Engagement Variety:**
- **No 3 consecutive screens use the same interaction type** (prevents monotony)
- **High-stakes interactions cluster in Module 4** (practice) and Module 5 (assessment)
- **Lower-stakes interactions early on** (Module 1-2) to build confidence before critical content

---

### Attention Management

**Goal:** Maintain focus for 20 minutes in a distracting environment

**Techniques:**

| Technique | Implementation |
|-----------|----------------|
| **Screen Variety** | No 3 screens with identical layout (text, image, interaction pattern varies) |
| **1 Concept per Screen** | Each screen = 1 key idea (e.g., Screen 3.3 = STOP WORK only, not Stop + Secure) |
| **Visual Breaks** | Generous whitespace, max 3-4 bullets per screen, icons break up text |
| **Chunking** | 5 modules (not 1 long module), 3-7 min each = natural break points |
| **Micro-Celebrations** | Positive feedback ("Great catch!", "Exactly right!", "Perfect!") maintains energy |
| **Pacing** | Vary speed: Quick knowledge checks (1 min) → Longer scenarios (3 min) |

**Attention Span Research:**
- **Average:** 10-15 minutes for focused attention (Bradbury, 2016)
- **Mobile:** Even shorter (~8 minutes on mobile devices)
- **Our Strategy:** 20-minute training broken into 5 modules = 4-minute chunks, which is BELOW attention threshold

**Why This Works:**
- **Variety Prevents Boredom:** Different visuals, interactions keep brain engaged
- **Chunking Matches Attention Span:** 3-7 min modules = digestible, not overwhelming
- **Positive Reinforcement:** Celebratory feedback creates dopamine hits (maintains motivation)
- **Modular Structure:** Can pause between modules if interrupted (field environment)

---

## Multimedia Learning Design

### Mayer's Principles Applied to Rise 360

**Foundation:** Richard Mayer's *Multimedia Learning* (2021) provides evidence-based guidelines for instructional visuals

**Our Implementation:**

#### 1. Coherence Principle (Remove Extraneous Content)

**Rule:** Remove interesting-but-irrelevant material

**What We Exclude:**
- ❌ **Decorative Images:** Stock photos of construction workers smiling (not instructional)
- ❌ **Background Music:** Distracting, increases cognitive load
- ❌ **Unnecessary Text:** "Welcome!", "Did you know?", fun facts about DND history
- ❌ **Complex Animations:** Flashy transitions, animated backgrounds

**What We Include:**
- ✅ **Instructional Images Only:** Protocol steps, suspicious objects, exclusion zone diagram
- ✅ **Essential Text:** Instructions, key points, feedback (nothing decorative)
- ✅ **Simple Transitions:** Rise defaults (fade, slide), not distracting effects

**Why This Works:**
- **Reduces Cognitive Load:** Every element that's not instructional steals attention from learning
- **Faster Processing:** Learner focuses on essential information only
- **Mobile-Friendly:** Less data = faster loading on 4G connections

---

#### 2. Signaling Principle (Highlight Essential Content)

**Rule:** Guide attention to what matters most

**Our Signaling Techniques:**

| Technique | Implementation | Example |
|-----------|----------------|---------|
| **Color Coding** | Red = STOP, Yellow = CAUTION, Blue = INFO, Green = SAFE | Step 1 (Stop) has red background |
| **Bold Text** | Critical actions bolded ("STOP WORK immediately") | "Do NOT touch or move the object" |
| **Icons** | Consistent system (🛑 📞 ⚠️) draws eye | 🛑 appears on all STOP WORK screens |
| **Arrows** | Point to important elements in diagrams | Arrow points to 25m radius on exclusion zone diagram |
| **Callout Boxes** | Highlight critical "DO" vs. "DON'T" lists | Yellow box with ⚠️ icon for prohibited actions |

**Visual Hierarchy:**
- **Headings:** Largest, bold, colored (draws attention first)
- **Key Points:** Bolded within body text
- **Body Text:** Regular weight, black on white
- **Fine Print:** Smaller font (legal disclaimers, document control)

**Why This Works:**
- **Guides Eye Movement:** Learner looks at critical content first (color, size, icons attract attention)
- **Reduces Search Time:** Don't have to hunt for important information
- **Improves Retention:** Signaled content is remembered better than unsignaled

---

#### 3. Redundancy Principle (Avoid Redundant Text)

**Rule:** Don't add on-screen text to narrated graphics (creates split attention)

**What We Avoid:**
- ❌ **Narration + Identical On-Screen Text:** Video voice-over reading bullet points shown on screen
- ❌ **Duplicate Content:** Same information in multiple formats without added value

**What We Do:**
- ✅ **Narration + Graphics (No Duplicate Text):** Video explains protocol while showing animation (not reading text)
- ✅ **Text for Reference:** Job aid, summary screens (when narration not present)
- ✅ **Captions (Exception):** Accessibility requirement + sound-off viewing (different purpose than redundancy)

**Example: Protocol Video (Module 3, Screen 3.9)**
- **On-Screen:** Animation of worker executing protocol (visual demonstration)
- **Narration:** "The moment he recognizes a suspicious object, he stops all work immediately..." (explains actions)
- **NOT On-Screen:** Text reading "Stop work immediately, alert crew, move away" (would be redundant)

**Why This Works:**
- **Reduces Cognitive Load:** Brain can't process audio + identical text simultaneously (split attention)
- **Faster Processing:** Visuals + narration = complementary channels (not competing)

---

#### 4. Spatial Contiguity Principle (Place Words Near Graphics)

**Rule:** Integrate text and images (don't separate them)

**What We Avoid:**
- ❌ **Separated:** Diagram on left side of screen, labels in list on right side (learner must scan back and forth)
- ❌ **Refer Out:** "See Figure 3 for exclusion zone" (requires flipping screens)

**What We Do:**
- ✅ **Integrated Labels:** Text callouts directly on diagram (exclusion zone diagram has "25m minimum" label with arrow pointing to radius)
- ✅ **Hotspots:** Click elements on image to reveal details (not separate legend)
- ✅ **Same Screen:** Image and explanation together (not split across screens)

**Example: Exclusion Zone Diagram (Module 3, Screen 3.4)**
- Illustration: Top-down view of construction site with suspicious object in center
- Label: "25m minimum" with arrow pointing from text to perimeter circle
- NOT: Separate text box saying "The exclusion zone is 25 meters radius from object"

**Why This Works:**
- **Reduces Eye Movement:** Don't have to look back and forth between image and label
- **Faster Comprehension:** Integrated labels are processed faster
- **Less Working Memory Load:** Don't have to hold information while searching for matching visual

---

#### 5. Temporal Contiguity Principle (Present Words and Graphics Simultaneously)

**Rule:** Narration and visuals should happen at the same time, not sequentially

**What We Avoid:**
- ❌ **Sequential:** Show diagram → Then explain in text after
- ❌ **Delayed:** Narration before or after visual appears

**What We Do:**
- ✅ **Synchronized:** Narration explains AS animation shows action
- ✅ **Just-in-Time:** Text appears when relevant to current visual

**Example: Protocol Video (Module 3, Screen 3.9)**
- **0:00-0:10:** VISUAL: Worker hits object with excavator | NARRATION: "The bucket strikes something solid..."
- **0:10-0:20:** VISUAL: Worker stops machine, exits | NARRATION: "He stops the machine immediately..."
- **0:20-0:30:** VISUAL: Worker alerts crew | NARRATION: "He alerts his crew to move back..."

(NOT: Show all visuals first, THEN explain afterward)

**Why This Works:**
- **Immediate Connection:** Brain links words and visuals when presented together
- **Reduces Working Memory Load:** Don't have to remember earlier visual while waiting for explanation

---

#### 6. Segmenting Principle (Break Content into Learner-Paced Chunks)

**Rule:** Allow learner to control pace (don't force continuous presentation)

**Our Implementation:**
- ✅ **Continue Buttons:** Learner clicks "Continue" to advance (not auto-advance)
- ✅ **Modular Videos:** 30-sec and 90-sec videos (not 10-minute lecture)
- ✅ **Pause Points:** Natural breaks between modules (5 modules vs. 1 long module)
- ✅ **Review Option:** Can go back to previous screens via menu

**Segmentation Strategy:**
- **Concept → Practice → Concept → Practice** (not all concepts, then all practice)
- **Screen 3.3:** Teach STOP WORK → Immediate practice (Screen 3.7)
- **Screen 3.4:** Teach SECURE AREA → Immediate practice (Screen 3.7)
- (NOT: Teach all 4 steps, then practice at end)

**Why This Works:**
- **Respects Cognitive Limits:** Small chunks prevent overload
- **Learner Control:** Pause for processing, resume when ready
- **Better for Mobile:** Short segments work better on mobile (battery, connection, interruptions)

---

#### 7. Pre-Training Principle (Teach Names and Characteristics First)

**Rule:** Introduce key terms and concepts BEFORE complex content

**Our Implementation:**

**Module 1, Screen 1.4:** Define "UXO" before teaching protocol
> "UXO = Unexploded Ordnance. Military munitions that didn't detonate as intended."

**Module 1, Screen 1.5:** Explain WHERE UXO is found before teaching recognition
> "Former training ranges, historical military bases, ammunition storage areas"

**Module 2:** Teach RECOGNITION (what is suspicious) BEFORE protocol (what to do)

**Module 3:** Teach EACH STEP separately before full protocol integration

**Why This Works:**
- **Builds Schema:** Foundational knowledge makes complex content easier to process
- **Reduces Confusion:** Key terms defined upfront (not encountered mid-explanation)
- **Scaffolding:** Simple → Complex progression

---

#### 8. Modality Principle (Use Narration Rather Than On-Screen Text)

**Rule:** For graphics/animations, use spoken explanation (not text)

**Our Implementation:**

| Content Type | Modality | Rationale |
|-------------|----------|-----------|
| **Protocol Video** | Narration + animation (no on-screen text blocks) | Narration explains while visual shows |
| **Static Diagrams** | On-screen text labels (no narration) | Persistent reference, learner-paced |
| **Interactive Elements** | Text instructions + optional audio | Flexibility (sound on/off) |
| **Job Aid** | Text only (no audio) | Print/mobile reference, used offline |

**Why This Works:**
- **Dual-Channel Processing:** Auditory (narration) + Visual (graphics) use separate channels = more capacity
- **Reduces On-Screen Clutter:** Less text on screen = clearer visuals
- **Exception:** Text is appropriate for reference materials (job aid, summary screens—not explaining process)

---

#### 9. Personalization Principle (Use Conversational Style)

**Rule:** Use "you" and "I" (not "the learner" or "one")

**Formal vs. Conversational:**

| Formal (Avoid) | Conversational (Use) |
|----------------|----------------------|
| "Workers should stop work immediately" | "Stop work immediately" |
| "The learner will identify suspicious objects" | "You'll learn to spot suspicious objects" |
| "One must establish an exclusion zone" | "Establish a 25-meter exclusion zone" |
| "It is recommended that personnel..." | "Your next step is..." |

**Tone:**
- **Direct Address:** "You're excavating..." (not "The operator is excavating...")
- **Active Voice:** "Stop work immediately" (not "Work should be stopped")
- **Conversational:** "Here's what to do" (not "The following procedure shall be executed")
- **Respectful:** "You know construction—add this safety layer" (not "You don't know this")

**Why This Works:**
- **Social Presence:** Conversational style feels like person-to-person communication (not reading a manual)
- **Better Engagement:** "You" activates personal relevance (this applies to ME)
- **Improved Learning:** Conversational tone improves retention (Mayer's research)

---

#### 10. Voice Principle (Use Human Voice, Not Machine)

**Rule:** Real narration > Text-to-Speech

**Our Implementation:**
- ✅ **Professional Voice-Over:** Human narration for protocol video
- ✅ **Natural Pace:** Moderate speed, clear enunciation
- ✅ **Appropriate Accent:** Canadian English (audience match)
- ✅ **Authoritative but Not Fear-Based:** Serious, confident, supportive tone

**NOT:**
- ❌ **Text-to-Speech (TTS):** Robotic, distracting, lower credibility
- ❌ **Overly Dramatic:** Fear-based tone ("You WILL DIE if you don't follow this!")
- ❌ **Monotone:** Boring, disengaging

**Why This Works:**
- **Credibility:** Human voice conveys authority (TTS feels cheap)
- **Engagement:** Natural speech patterns maintain attention
- **Emotional Connection:** Human voice creates rapport

---

### Media Specifications

#### Images

**Format:** PNG (transparency) or JPG (photos)
**Resolution:** 1200px wide minimum (retina displays)
**Style:** Illustrated (NOT real ordnance photos)

**Content:**
1. **Construction Scenes:** Excavation, trenching, demolition (context for scenarios)
2. **Suspicious Objects:** Generic illustrated ordnance (cylindrical, cone-shaped, with fins)—NO specific military ordnance types (out of scope, safety concern)
3. **Protocol Steps:** Workers stopping, securing perimeter, reporting
4. **Diagrams:** Exclusion zone (top-down view, 25m radius), reporting chain flowchart

**Accessibility:**
- **ALT Text:** Descriptive (e.g., "Illustration of cylindrical metal object with fins partially exposed in excavated soil")
- **High Contrast:** Dark elements on light background (outdoor mobile visibility)
- **Simple Composition:** Clear subject, minimal background clutter

**Why Illustrated (Not Photos of Real UXO):**
1. **Safety:** Real ordnance photos could be misused for identification (not our goal)
2. **Simplicity:** Illustrations emphasize key features (fins, shape) without overwhelming detail
3. **Consistency:** Illustrated style matches Rise 360 modern aesthetic

---

#### Video

**Format:** MP4 (H.264 codec)
**Resolution:** 1080p (1920x1080) or 720p (1280x720)
**Duration:** 30-120 seconds per video (total 2 videos)
**Aspect Ratio:** 16:9 (standard) or 1:1 (mobile-optimized square)

**Videos:**
1. **Module 3, Screen 3.3:** STOP WORK demonstration (30 seconds)
   - Worker recognizes object → Stops equipment → Alerts crew → Moves away
2. **Module 3, Screen 3.9:** Full protocol demonstration (90 seconds)
   - Complete sequence: Recognize → Stop → Secure → Report → Wait → Expert clearance

**Style:** Animated or illustrated (NOT live-action with real ordnance)

**Narration:** Professional voice-over (Canadian accent, authoritative but supportive tone)

**Captions:** Full transcript, WCAG compliant (accessibility + sound-off viewing)

**Sound:** Narration only (NO background music—reduces cognitive load)

**Why This Works:**
- **Demonstration:** Video shows HOW to execute protocol (worked example)
- **Engagement:** Movement attracts attention (more engaging than static text)
- **Mobile-Friendly:** Short videos load on 4G, don't drain battery
- **Accessibility:** Captions allow sound-off viewing (field environment, noisy sites)

---

#### Icons

**Source:** Professional icon library (e.g., Font Awesome, Noun Project, or custom)
**Style:** Simple, bold, flat design (no 3D, gradients, or shadows)
**Size:** 60-80px (large enough for mobile tap targets)
**Color:** Consistent system throughout

**Icon System:**

| Icon | Meaning | Color | Usage |
|------|---------|-------|-------|
| 🛑 | STOP WORK | Red (#D32F2F) | All stop-work content |
| ⚠️ | SECURE AREA / CAUTION | Yellow/Orange (#F57C00) | Exclusion zone content |
| 📞 | REPORT / NOTIFY | Blue (#1976D2) | Reporting chain content |
| ⏸️ | WAIT / PAUSE | Green (#388E3C) | Wait for clearance content |
| 👷 | WORKER ROLE | Gray (#616161) | Worker-specific content |
| 👔 | SUPERVISOR ROLE | Gray (#616161) | Supervisor-specific content |
| 📋 | DOCUMENT | Gray (#616161) | Documentation steps |
| ❌ | PROHIBITED ACTION | Red (#D32F2F) | DON'T lists |
| ✅ | CORRECT ACTION | Green (#388E3C) | DO lists, correct answers |

**Accessibility:** Color + shape (not color alone)
- Example: STOP is 🛑 (red octagon) not just red text

---

## Microlearning Design

### Microlearning Principles

**Definition:** Short, focused learning units (3-7 minutes) with single learning objective

**Why Microlearning for UXO Training:**
1. **Time-Limited Audience:** Construction workers have limited training time
2. **Mobile Context:** Short modules work better on mobile devices (battery, connection, interruptions)
3. **Attention Span:** 3-7 minute chunks match natural attention limits
4. **Flexibility:** Can pause between modules without losing context

---

### Standalone Value

**Principle:** Each module should have independent learning value (not just "part 2 of 10")

**Our Module Outcomes:**

| Module | Standalone Value | Learner Can Say |
|--------|------------------|-----------------|
| **Module 1** | Why UXO awareness matters | "I understand the risk and why this matters" |
| **Module 2** | Recognize suspicious objects | "I can identify red flags that require stop-work" |
| **Module 3** | Execute the protocol | "I know the exact steps: Stop, Secure, Report, Wait" |
| **Module 4** | Practice scenarios | "I've practiced making the right decisions" |
| **Module 5** | Prove readiness | "I've passed the assessment and have my job aid" |

**Why This Works:**
- **Modular Completion:** If interrupted after Module 2, learner has still gained value (recognition skill)
- **Review:** Can revisit specific module (e.g., "I need to review the protocol" → Module 3)
- **Onboarding:** New hires can complete modules over multiple days if needed

---

### Single Concept Per Unit

**Principle:** Focus on ONE key idea per module (no scope creep)

**Our Focus:**

| Module | Single Concept | NOT Included |
|--------|---------------|--------------|
| **Module 2** | Recognition (what is suspicious) | HOW to secure area (that's Module 3) |
| **Module 3** | Protocol (Stop, Secure, Report, Wait) | WHY UXO exists (that's Module 1) |
| **Module 4** | Application (practice scenarios) | New protocol steps (already taught in Module 3) |

**Content Filtering:**
- **"Does this support THIS module's objective?"** → KEEP
- **"Is this interesting but off-topic?"** → CUT or move to appropriate module
- **"Is this 'nice to know' but not essential?"** → CUT (job aid or out of scope)

**Why This Works:**
- **Reduces Cognitive Load:** One concept = easier to process, remember
- **Clear Outcomes:** Learner knows exactly what they're learning (not overwhelmed with multiple topics)
- **Efficient:** Focused content = shorter modules = higher completion

---

### 3-7 Minute Modules

**Module Duration Breakdown:**

| Module | Time | Screens | Justification |
|--------|------|---------|---------------|
| **Module 1** | 5 min | 6 | Context + motivation (slightly longer to hook learner) |
| **Module 2** | 3 min | 6 | Recognition practice (interactive, quick) |
| **Module 3** | 7 min | 10 | Most content (4 protocol steps + video + practice) |
| **Module 4** | 3 min | 5 | Scenario practice (high engagement, moves quickly) |
| **Module 5** | 2 min | 12 | Assessment (10 questions + job aid + certificate) |
| **TOTAL** | **20 min** | **39** | Within design spec (15-20 min target) |

**Why These Durations:**
- **Module 1 (5 min):** Longer to establish importance (critical for engagement)
- **Module 2 (3 min):** Short and interactive (quick win)
- **Module 3 (7 min):** Longest module (most critical content—protocol steps)
- **Module 4 (3 min):** Practice moves quickly (branching scenarios, high engagement)
- **Module 5 (2 min):** Assessment is fast if prepared (10 questions, most already practiced)

**Pacing Strategy:**
- **Start Longer (5 min):** Establish context, build buy-in
- **Quick Win (3 min):** Module 2 reinforces "this is doable"
- **Core Content (7 min):** Module 3 is longest but essential
- **End Fast (3 + 2 min):** Modules 4-5 feel like quick finish (momentum to completion)

---

### Mobile-First Design

**Goal:** Training must work on smartphones in field conditions

**Mobile Optimization:**

| Aspect | Mobile-First Design |
|--------|---------------------|
| **Layout** | Vertical scroll (thumb-friendly), not horizontal swipe |
| **Navigation** | Large tap targets (≥44px), not tiny buttons |
| **Data Usage** | Compressed images, optimized video, works on 4G |
| **Offline Mode** | SCORM download = complete without WiFi |
| **Battery** | No auto-playing videos, minimal animations (battery-friendly) |
| **Readability** | 16px+ font size, high contrast (outdoor visibility) |
| **Interactions** | Tap/swipe (not hover), works with work gloves |

**Testing:**
- **Devices:** iPhone (Safari), Android (Chrome)
- **Conditions:** Outdoor (sunlight glare), with gloves, on 4G network
- **Battery Test:** Complete full module without charging (should use <10% battery)

**Why This Matters:**
- **Audience Context:** Many workers will complete on phone during break, on site
- **Completion Rate:** Mobile-friendly = higher completion (can do it anywhere)
- **Accessibility:** Workers without desktop access can still complete

---

### Lesson Structure (Per Module)

**Template (Applied to Each Module):**

```
1. HOOK (Why this matters) — 30 sec
   ↓
2. CONCEPT (One key idea) — 2-3 min
   ↓
3. EXAMPLE (Show it in action) — 1-2 min
   ↓
4. PRACTICE (Try it yourself) — 2-3 min
   ↓
5. SUMMARY (Remember this) — 30 sec
```

**Example: Module 2 (Recognition)**

| Step | Screen | Content |
|------|--------|---------|
| **1. HOOK** | 2.1 | "You'll spot red flags that require stop-work" |
| **2. CONCEPT** | 2.2 | Flashcards: 6 red flags (fins, markings, unusual shapes) |
| **3. EXAMPLE** | 2.3 | Normal vs. Suspicious comparison (rebar vs. ordnance) |
| **4. PRACTICE** | 2.4-2.5 | Sort 6 items (suspicious vs. normal) + scenario quiz |
| **5. SUMMARY** | 2.6 | "When in doubt, stop work" |

**Why This Structure:**
- **Hook:** Orients learner to module goal
- **Concept:** Delivers core knowledge
- **Example:** Demonstrates application (worked example)
- **Practice:** Active learning (encode knowledge)
- **Summary:** Reinforces key takeaway

---

### Sequencing for Retention

**Principle:** Spaced repetition and scaffolding improve long-term retention

**Our Sequencing Strategy:**

**1. Spiral Reinforcement:**
- **Module 2:** Learn recognition → Practice (Screen 2.4-2.5)
- **Module 4:** Practice recognition AGAIN in scenarios (identify object)
- **Module 5:** Assess recognition (Q3, Q6)

**2. Module Bridging:**
- **End of Module 2:** "Next, you'll learn the exact protocol to follow"
- **Start of Module 3:** "Last module, you learned to recognize suspicious objects. Now, what do you DO?"

**3. Job Aid Reinforcement:**
- **Module 5:** Download job aid (post-training reference)
- **Job Aid:** Repeats protocol steps visually (ongoing reinforcement)

**4. Manager Reinforcement:**
- **Toolbox Talk Script:** Supervisor reviews protocol on site (weeks/months after training)

**Why This Works:**
- **Spaced Repetition:** Repeated exposure over time (Module 2 → Module 4 → Module 5 → Job Aid → Toolbox Talk)
- **Scaffolding:** Simple (recognition) → Complex (application in scenarios) → Integration (full protocol)
- **Long-Term Retention:** Job aid + manager support extend learning beyond 20-minute module

---

## Scenario Design

### Scenario-Based Learning Rationale

**Why Scenarios (Not Lectures)?**
1. **Safety Training = Behavioral:** Goal is action (what to DO), not just knowledge (what to KNOW)
2. **Safe Failure Environment:** Practice making mistakes without real consequences
3. **Consequence Visibility:** Show WHY protocol matters (not just "because we say so")
4. **Transfer:** Realistic practice → Better real-world application

---

### Scenario Design Framework

**Components of Effective Scenarios:**

| Component | Purpose | Our Implementation |
|-----------|---------|-------------------|
| **Realistic Context** | Match actual job conditions | Excavation, hand-digging, demolition (actual construction tasks) |
| **Plausible Choices** | Multiple options (not obviously wrong) | All choices sound reasonable to novice |
| **Visible Consequences** | Show outcomes of decisions | Animation, text feedback explaining impact |
| **Immediate Feedback** | Learn from mistakes quickly | Instant branching (not wait until end) |
| **Multiple Attempts** | Safe failure, retry until correct | Unlimited attempts, no penalty |
| **Role Variation** | Different perspectives | Worker scenarios (Module 4.2-4.3) + Supervisor scenario (Module 4.4) |

---

### Scenario 1: Ground Disturbance - Excavator Operator

**Context (Module 4, Screen 4.2):**
> "You're operating an excavator, digging foundation trenches. Your bucket strikes something solid. You see a rusty cylindrical object, approximately 30cm long, partially exposed in the soil."

**Why This Context:**
- **Common Task:** Excavation is frequent on construction sites (relatable)
- **High Risk:** Heavy equipment + UXO = detonation risk (consequence-rich)
- **Worker Role:** Operator makes first decision (stop or continue)

---

**Decision Point 1: Immediate Action**

**Question:** "What do you do FIRST?"

**Options:**
- A) Continue digging carefully to expose it fully
- B) Stop the excavator immediately and alert your crew ✓
- C) Get out and take a photo for your supervisor
- D) Cover it back up and continue working elsewhere

**Branching Consequences:**

**PATH A (Wrong):**
- **Consequence Animation:** Explosion graphic (not graphic gore, but impactful—orange flash, debris, evacuation sirens)
- **Text Feedback:** "❌ NEVER continue digging. Vibration or impact could detonate the object. You've put yourself and your crew in immediate danger. The correct action is to STOP IMMEDIATELY."
- **Remediation:** "Review: STOP WORK is ALWAYS the first action. No exceptions."
- **Button:** "Try Again" → Returns to decision point

**PATH B (Correct):**
- **Visual:** Checkmark animation, worker safely exits cab, crew moves back
- **Text Feedback:** "✅ Correct! You stopped work immediately. This is the FIRST and most critical action. Now, what's your next step?"
- **Continue:** Proceeds to Decision Point 2

**PATH C (Wrong):**
- **Consequence Animation:** Worker approaches object with phone, too close (red danger zone)
- **Text Feedback:** "❌ While you're taking photos, you're too close to a potential hazard. Photos can wait—your safety can't. STOP WORK and move away FIRST, then document from a safe distance."
- **Remediation:** "Review: Stop → Secure → Report → THEN document."
- **Button:** "Try Again"

**PATH D (Wrong):**
- **Consequence Animation:** Object covered, next worker (different shift) digs nearby, object visible again
- **Text Feedback:** "❌ Ignoring the object doesn't make it safe. The next worker could trigger it. You have a responsibility to stop work and report it immediately."
- **Remediation:** "Review: When you find something suspicious, you MUST stop work and follow the protocol."
- **Button:** "Try Again"

---

**Decision Point 2: Area Security** (Only if Decision 1 correct)

**Question:** "You've stopped the excavator and alerted your crew. Now you need to secure the area. How far back should everyone stay?"

**Interactive Element:** Slider (5m → 10m → 25m → 50m → 100m)

**Feedback:**
- **<25m (e.g., 5m, 10m, 15m):** "❌ Too close! The minimum safe distance is 25 meters. Shrapnel and blast radius can extend well beyond 10 meters. Move everyone back to at least 25m."
- **25m (Correct):** "✅ Correct! 25 meters is the minimum exclusion zone for unidentified objects. Mark this perimeter with cones, tape, or barriers."
- **>25m (e.g., 50m, 100m):** "✅ That works too! 25m is the minimum, but more distance is safer. Good caution."

**Visual:** Diagram updates in real-time as slider moves (shows exclusion zone radius)

---

**Decision Point 3: Reporting**

**Question:** "Area secured. Who do you notify first?"

**Options:**
- A) 911 Emergency Services
- B) DCC Project Manager
- C) Your supervisor ✓
- D) UXO disposal company

**Feedback:**
- **C (Correct):** "✅ Correct! Workers report to their supervisor, who escalates through the chain: Supervisor → Site Authority → DCC PM → UXO Expert."
- **A:** "⚠️ Call 911 only if there's immediate danger (fire, explosion, injury). For UXO protocol, follow the reporting chain. Your supervisor will escalate if 911 is needed."
- **B/D:** "❌ Workers do not contact the PM or experts directly. Follow the chain: Your Supervisor FIRST, who will escalate."

---

**Outcome (Success Path):**

**Visual:** Animated success sequence
1. Area secured (25m marked with cones)
2. Crew safe (outside exclusion zone)
3. Supervisor on phone (reporting)
4. Expert arrives (protective gear, examines object)
5. Expert gives thumbs up (clearance)
6. Work resumes safely

**Text:**
> "✅ Excellent work! You followed the protocol perfectly. The site is secure, your crew is safe, and UXO experts are en route. Because you stopped immediately and secured the area, everyone stayed safe. Work will resume after expert clearance."

---

### Scenario 2: Unusual Metal Object - Laborer

**Context (Module 4, Screen 4.3):**
> "You're hand-digging post holes for fencing. You uncover a metal object, cone-shaped, about 20cm long, with fins. It looks old and corroded."

**Why This Context:**
- **Manual Work:** Hand tools (different from heavy equipment)
- **Shape Cues:** Cone + fins = classic ordnance red flags (tests recognition)
- **Worker Role:** Same role as Scenario 1 (reinforces worker protocol)

**Decision Structure:** Similar to Scenario 1 (What do you do FIRST? → Secure area → Reporting)

**Key Difference:** Object description emphasizes recognition red flags (fins, cone shape)

---

### Scenario 3: Demolition - Supervisor Perspective

**Context (Module 4, Screen 4.4):**
> "You're a site supervisor. A worker calls you over—they found a metal canister in a wall cavity during demolition of an old DND building. The worker has stopped work. What's YOUR role?"

**Why This Context:**
- **Supervisor Role:** Different responsibilities than worker (tests role recognition)
- **Object Already Found:** Worker did the right thing (stopped)—now supervisor must act
- **Indoor Setting:** Demolition/renovation (not just excavation)

---

**Decision: Multiple Select**

**Question:** "As the supervisor, what are your responsibilities? (Select all that apply)"

**Options:**
- ☑ Ensure the area is secured (25m exclusion zone)
- ☑ Account for all crew members (confirm everyone is safe)
- ☑ Notify site authority or safety officer
- ☐ Inspect the object closely to determine if it's dangerous
- ☐ Move the object to a safer location

**Feedback:**

**If All Correct Selected:**
> "✅ Correct! As a supervisor, your responsibilities are:
> 1. **Verify area secured** (worker should have done this, but you confirm)
> 2. **Account for crew** (ensure everyone is safe and outside exclusion zone)
> 3. **Notify site authority** (escalate through chain)
>
> You do NOT inspect or move the object—only UXO experts handle suspicious items."

**If Prohibited Actions Selected (Inspect, Move):**
> "❌ Supervisors should NEVER inspect or move suspicious objects. Your role is to:
> - Verify the area is secured
> - Ensure crew safety
> - Escalate reporting
>
> Leave object assessment to UXO experts. Attempting to move or closely inspect the object puts you and others at risk."

**Why This Scenario:**
- **Role Clarity:** Reinforces that supervisors escalate, not inspect
- **Worker-Supervisor Coordination:** Supervisor verifies worker's stop-work (not override it)
- **Prohibited Actions:** Emphasizes DON'Ts (even supervisors don't touch)

---

### Scenario 4: Ambiguous Find - "When in Doubt"

**Context (Assessment or Module 4.5):**
> "You're trenching for utilities. Your shovel hits a metal pipe. It could be old plumbing, or it could be something else. You're not sure."

**Decision:** "What do you do?"

**Correct Answer:** Treat as suspicious and stop work (when in doubt, apply protocol)

**Why This Scenario:**
- **Ambiguity:** Most real situations aren't obvious (tests "when in doubt" principle)
- **Common Object:** Metal pipe could be legitimate (tests judgment)
- **Key Lesson:** "Better safe than sorry"

---

### Scenario Design Principles Summary

| Principle | Implementation |
|-----------|----------------|
| **Realistic** | Actual construction tasks (excavation, hand-digging, demolition) |
| **Role-Specific** | Worker scenarios (do the protocol) vs. Supervisor (verify and escalate) |
| **Consequences Visible** | Wrong choice → Show outcome (explosion, crew at risk) |
| **Multiple Attempts** | Learn from mistakes, retry (no penalty) |
| **Immediate Feedback** | Instant branching (not wait until end of scenario) |
| **Variety** | Different contexts (heavy equipment, manual, indoor), different objects (cylindrical, cone-shaped, ambiguous) |

---

## Visual Design System

### Color Coding

**Purpose:** Use color to guide attention and convey meaning

**Color Palette:**

| Color | Hex Code | Meaning | Usage |
|-------|----------|---------|-------|
| 🔴 **Red** | #D32F2F | STOP, danger, critical action | STOP WORK screens, prohibited actions |
| 🟡 **Yellow/Orange** | #F57C00 | CAUTION, warning, important | SECURE AREA screens, exclusion zone |
| 🔵 **Blue** | #1976D2 | Information, reference | REPORT screens, informational content |
| 🟢 **Green** | #388E3C | SAFE, correct, proceed | CLEARANCE screens, correct answers, success feedback |
| ⚪ **White** | #FFFFFF | Background, neutral | Screen backgrounds |
| ⚫ **Black** | #000000 | Text, high contrast | Body text, headings |
| 🔘 **Gray** | #616161 | Secondary, neutral | Icons, supporting text |

**Color Application:**

**Module 3 (Protocol):**
- **Screen 3.3 (STOP WORK):** Red header background, 🛑 red icon
- **Screen 3.4 (SECURE AREA):** Yellow/orange header, ⚠️ yellow icon
- **Screen 3.5 (REPORT):** Blue header, 📞 blue icon
- **Screen 3.6 (WAIT):** Green header, ⏸️ green icon

**Assessment Feedback:**
- **Correct Answer:** Green checkmark ✅ + "Correct!"
- **Wrong Answer:** Red X ❌ + explanation

**Job Aid:**
- **Front:** Color-coded steps (red → yellow → blue → green)
- **Back:** Red for prohibited actions, green for correct actions

**Accessibility:**
- **Never use color alone:** Always pair with icon or shape (e.g., 🛑 is red AND octagon shape)
- **High Contrast:** 4.5:1 minimum (WCAG AA)—black text on white, colored headers with sufficient contrast

---

### Icon System

**Purpose:** Visual consistency, quick recognition, language-independent

**Core Icons:**

| Icon | Name | Usage |
|------|------|-------|
| 🛑 | Stop Sign | STOP WORK (all stop-related content) |
| ⚠️ | Warning | CAUTION, exclusion zone, important notices |
| 📞 | Phone | REPORT, notify, communication |
| ⏸️ | Pause | WAIT for clearance |
| 👷 | Construction Worker | Worker-specific content, role tabs |
| 👔 | Business Professional | Supervisor/manager-specific content |
| 📋 | Clipboard | Documentation, reporting details |
| ❌ | X Mark | Prohibited actions, wrong answers |
| ✅ | Checkmark | Correct actions, right answers, completion |
| 🏗️ | Construction Site | Context setting, module intros |

**Icon Usage Rules:**
1. **Consistency:** Same icon ALWAYS means same thing (🛑 = stop work everywhere)
2. **Size:** 60-80px (large enough for mobile tap, small enough to not overwhelm)
3. **Color + Icon:** Always pair (🛑 is red, 📞 is blue—reinforces meaning)
4. **Simple Style:** Flat design, no 3D effects or shadows (clean, modern)

---

### Typography

**Font:** Sans-serif (Helvetica, Arial, or Rise 360 default)

**Why Sans-Serif:**
- **Readability:** Easier to read on screens (especially mobile)
- **Modern:** Professional, clean aesthetic
- **Accessibility:** Better for dyslexic readers (no decorative serifs)

**Type Scale:**

| Element | Size | Weight | Usage |
|---------|------|--------|-------|
| **Main Heading** | 32-36px | Bold | Module titles (e.g., "Module 3: The Protocol") |
| **Section Heading** | 24-28px | Bold | Screen titles (e.g., "Step 1: STOP WORK") |
| **Subheading** | 20-22px | Bold | Subsections within screens |
| **Body Text** | 16-18px | Regular | Main content, instructions |
| **Small Text** | 12-14px | Regular | Fine print, document control |

**Text Formatting:**

| Technique | Usage | Example |
|-----------|-------|---------|
| **Bold** | Critical actions | "**STOP WORK** immediately" |
| **ALL CAPS** | Emphasis (sparingly) | "DO NOT touch the object" |
| **Sentence Case** | Headings | "Recognize Suspicious Objects" (not "RECOGNIZE SUSPICIOUS OBJECTS") |
| **Color** | Highlight warnings | Red text for prohibited actions |

**Plain Language:**
- **Active Voice:** "Stop work" (not "Work should be stopped")
- **Short Sentences:** <20 words
- **Concrete Words:** "25 meters" (not "appropriate distance")
- **Grade 8 Reading Level:** Tested with Hemingway App

---

### Layout Principles

**Whitespace:**
- **Generous Margins:** 0.5-1 inch around screen edges
- **Breathing Room:** Space between elements (not cramped)
- **Chunking:** Max 3-4 bullet points per screen (not walls of text)

**Visual Hierarchy:**
- **Headings:** Largest, bold, colored (draws eye first)
- **Body Text:** Regular weight, black on white
- **Supporting Text:** Smaller, gray (less prominent)

**Consistency:**
- **Layout Patterns:** Similar screens use similar layouts (learner knows what to expect)
- **Navigation:** Rise 360 standard (menu, back/forward buttons—don't customize)
- **Button Placement:** "Continue" button always bottom-right (consistency reduces cognitive load)

**Mobile-Responsive:**
- **Single Column:** Content stacks vertically on mobile (no multi-column layouts that break)
- **Large Tap Targets:** Buttons ≥44x44px (Apple accessibility guideline)
- **Readable Text:** 16px minimum (smaller text hard to read on mobile)

---

### Branding

**DCC Branding:**
- **Logo:** DCC logo in header or footer (per client brand guidelines)
- **Federal Identity:** Government of Canada branding (if required)
- **Color Palette:** Can align with DCC brand colors (if provided), while maintaining our functional color coding (red=stop, etc.)

**Tone:**
- **Professional:** Authoritative, serious, clear
- **Supportive:** "We're here to keep you safe" (not fear-based)
- **Respectful:** Acknowledges construction expertise, adds safety layer

---

## Accessibility Design

### WCAG 2.1 AA Compliance

**Goal:** Ensure training is usable by all learners, including those with disabilities

**Compliance Level:** WCAG 2.1 AA (industry standard, required for government projects)

---

### 1. Perceivable (Information must be presented in ways users can perceive)

#### Guideline 1.1: Text Alternatives

**Requirement:** Provide text alternatives for non-text content

**Our Implementation:**
- ✅ **ALT Text for All Images:** Every image has descriptive alt text
  - Example: `alt="Illustration of cylindrical metal object with fins partially exposed in excavated soil"`
  - NOT: `alt="image1.png"` or `alt="UXO"` (too vague)
- ✅ **Icon Labels:** Icons paired with text (🛑 + "STOP WORK")
- ✅ **Video Captions:** Full transcript for all videos (narration + sound effects described)
- ✅ **Interactive Elements:** Buttons have descriptive labels ("Download Job Aid" not "Click Here")

**Testing:** Screen reader (JAWS, NVDA) reads all content correctly

---

#### Guideline 1.3: Adaptable

**Requirement:** Content can be presented in different ways without losing information

**Our Implementation:**
- ✅ **Semantic HTML:** Rise 360 uses proper heading structure (H1, H2, H3)
- ✅ **Logical Reading Order:** Content flows top-to-bottom, left-to-right
- ✅ **No Information by Shape/Location Alone:** "Click the red button below" (not "click the button on the right")
- ✅ **Responsive Design:** Adapts to different screen sizes (mobile, tablet, desktop)

---

#### Guideline 1.4: Distinguishable

**Requirement:** Make it easy to see and hear content

**Our Implementation:**
- ✅ **Color Contrast:** 4.5:1 minimum for text (black on white = 21:1, far exceeds)
- ✅ **Color + Icon:** Never use color alone (🔴 red + 🛑 octagon shape)
- ✅ **Text Resize:** Text can be enlarged to 200% without loss of functionality (Rise handles)
- ✅ **No Images of Text:** Actual text (not text baked into images), except logos

**Contrast Testing:**
- Tool: WebAIM Contrast Checker
- All text meets WCAG AA (4.5:1) or AAA (7:1) standards

---

### 2. Operable (Interface must be operable by all users)

#### Guideline 2.1: Keyboard Accessible

**Requirement:** All functionality available via keyboard

**Our Implementation:**
- ✅ **Keyboard Navigation:** Rise 360 native support (Tab, Enter, Arrow keys)
- ✅ **Focus Indicators:** Visible outline when element is focused (Rise default)
- ✅ **No Keyboard Traps:** Can Tab through all elements, Escape closes modals
- ✅ **Skip Links:** Rise provides "Skip to main content" link

**Testing:** Complete training using keyboard only (no mouse)

---

#### Guideline 2.2: Enough Time

**Requirement:** Users have enough time to read and use content

**Our Implementation:**
- ✅ **No Time Limits:** Self-paced (no auto-advance, no timers on assessment)
- ✅ **Pause/Resume:** Can close browser and resume later (LMS suspend data)
- ✅ **No Auto-Playing Media:** Videos require user to click play

---

#### Guideline 2.4: Navigable

**Requirement:** Provide ways to help users navigate and find content

**Our Implementation:**
- ✅ **Descriptive Titles:** Each screen has clear title ("Step 1: STOP WORK")
- ✅ **Navigation Menu:** Rise sidebar shows all modules, current location
- ✅ **Descriptive Links:** "Download Job Aid PDF" (not "Click Here")
- ✅ **Consistent Navigation:** Back/Forward buttons in same location (Rise standard)

---

### 3. Understandable (Information and interface must be understandable)

#### Guideline 3.1: Readable

**Requirement:** Text content is readable and understandable

**Our Implementation:**
- ✅ **Language Attribute:** HTML `lang="en"` tag set (for screen readers)
- ✅ **Plain Language:** Grade 8 reading level (Hemingway App tested)
- ✅ **Abbreviations Explained:** First use of "UXO" is spelled out ("Unexploded Ordnance (UXO)")
- ✅ **Glossary:** Key terms defined (Module 1)

**Plain Language Examples:**
- "Stop work immediately" (not "Cease all operational activities forthwith")
- "25 meters" (not "appropriate perimeter distance")
- "Report to supervisor" (not "initiate escalation protocols")

---

#### Guideline 3.2: Predictable

**Requirement:** Pages operate in predictable ways

**Our Implementation:**
- ✅ **Consistent Navigation:** Menu always in same location (left sidebar)
- ✅ **Consistent Buttons:** "Continue" always bottom-right
- ✅ **No Unexpected Context Changes:** Clicking link doesn't automatically play video or open new window
- ✅ **Consistent Labeling:** Same icon always means same thing (🛑 = stop work)

---

#### Guideline 3.3: Input Assistance

**Requirement:** Help users avoid and correct mistakes

**Our Implementation:**
- ✅ **Error Feedback:** Clear, constructive ("❌ The correct answer is C. Review Module 3.")
- ✅ **Instructions Before Input:** Interaction instructions BEFORE interactive element
- ✅ **Retry Allowed:** Unlimited assessment attempts (can correct mistakes)
- ✅ **Success Feedback:** Positive reinforcement for correct answers ("✅ Correct!")

---

### 4. Robust (Content must be robust enough to work with assistive technologies)

#### Guideline 4.1: Compatible

**Requirement:** Maximize compatibility with current and future assistive technologies

**Our Implementation:**
- ✅ **Valid HTML:** Rise 360 generates standards-compliant HTML5
- ✅ **ARIA Labels:** Rise handles automatically (buttons, navigation, etc.)
- ✅ **Screen Reader Compatible:** Tested with JAWS (Windows), NVDA (Windows), VoiceOver (Mac/iOS)
- ✅ **Cross-Browser:** Works in Chrome, Firefox, Safari, Edge (all modern browsers)
- ✅ **Mobile Responsive:** Works on iOS and Android (native Rise support)

**Testing:**
- Screen reader: JAWS 2022+, NVDA 2022+, VoiceOver (latest)
- Browsers: Chrome, Firefox, Safari, Edge (latest 2 versions)
- Devices: Windows PC, Mac, iPhone, Android phone, iPad, Android tablet

---

### Accessibility Checklist (Pre-Launch)

**Perceivable:**
- [ ] All images have descriptive ALT text
- [ ] Videos have captions (full transcript)
- [ ] Color contrast ≥4.5:1 (text to background)
- [ ] Color + icon (not color alone)

**Operable:**
- [ ] Keyboard navigation works (Tab through all elements)
- [ ] No time limits (self-paced)
- [ ] Descriptive link text (not "Click Here")
- [ ] Consistent navigation

**Understandable:**
- [ ] Plain language (Grade 8 level)
- [ ] Abbreviations explained (UXO = Unexploded Ordnance)
- [ ] Error feedback clear and constructive
- [ ] Instructions before interactions

**Robust:**
- [ ] Screen reader compatible (tested with JAWS, NVDA, VoiceOver)
- [ ] Cross-browser (Chrome, Firefox, Safari, Edge)
- [ ] Mobile responsive (iOS, Android)

---

## Conclusion

This learning experience design ensures high completion rates and effective learning for mandatory safety training by:

1. **Optimizing Completion:** Engaging hook, progress visualization, friction reduction, accountability
2. **Designing Engagement:** Emotional connection, active learning, visible consequences, appropriate gamification
3. **Applying Multimedia Principles:** Mayer's 12 principles (coherence, signaling, modality, personalization, etc.)
4. **Implementing Microlearning:** 3-7 minute modules, single concept focus, mobile-first design
5. **Creating Scenarios:** Realistic, consequence-based, role-specific practice
6. **Establishing Visual System:** Color coding, icon system, plain language typography
7. **Ensuring Accessibility:** WCAG 2.1 AA compliance (perceivable, operable, understandable, robust)

**Expected Outcomes:**
- **Completion Rate:** ≥90% (mandatory, engaging, respectful of worker time)
- **Engagement:** High interaction throughout (no passive "next, next, next")
- **Transfer:** Realistic scenarios → Better real-world protocol application
- **Accessibility:** Usable by all learners, all devices, all contexts

---

**Document Control:**
- **Version:** 1.0
- **Date:** [Current Date]
- **Author:** [Your Name], Learning Experience Designer
- **Next Review:** [Date + 1 year]

---

**End of Learning Experience Design Document**

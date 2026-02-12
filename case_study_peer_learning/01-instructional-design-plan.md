# Instructional Design Plan
## UXO Awareness Training: "Stop Work. Secure the Area. Report."

**Client:** Defence Construction Canada (DCC), Environmental Services
**Project:** UXO Awareness for Construction Teams
**Format:** Microlearning Module (Rise 360) + Job Aid
**Duration:** 15-20 minutes
**Designer:** [Your Name]
**Date:** [Current Date]
**Version:** 1.0

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Needs Analysis](#needs-analysis)
3. [Learning Objectives](#learning-objectives)
4. [Assessment Design](#assessment-design)
5. [Instructional Strategy](#instructional-strategy)
6. [Development Specifications](#development-specifications)
7. [Evaluation Plan](#evaluation-plan)
8. [Iteration & Continuous Improvement](#iteration--continuous-improvement)

---

## Executive Summary

This instructional design plan outlines a safety-critical microlearning module to train construction personnel on DND sites to recognize and respond to potentially suspicious objects (unexploded ordnance/UXO). The training uses **scenario-driven, consequence-based learning** to ensure 100% protocol adherence: Stop Work → Secure Area → Report → Wait for Clearance.

### Key Design Decisions

| Aspect | Decision | Rationale |
|--------|----------|-----------|
| **Framework** | ADDIE + Merrill + Gagné | Systematic, evidence-based approach for safety-critical content |
| **Assessment Approach** | Assessment-first design | Ensures content directly serves measurable objectives |
| **Delivery Strategy** | Scenario-based with branching | Behavior change requires practice with consequences |
| **Cognitive Load** | Chunked 3-step protocol | Simplify complex safety procedure to "Stop, Secure, Report" |
| **Transfer Design** | Job aid + manager support | Field-usable reference at point of need |

### Success Criteria

- **Completion rate:** ≥90% (mandatory, engaging design)
- **Assessment pass rate:** ≥90% (80% threshold, 100% on critical items)
- **Confidence increase:** +1.5 points (pre/post survey)
- **Field behaviour:** 100% protocol adherence in real incidents

---

## Needs Analysis

### 1. Performance Gap Analysis

**Current State (Problem)**
- Workers delay or fail to stop work promptly when encountering suspicious objects
- Personnel approach, touch, or handle potentially dangerous items
- Inconsistent reporting procedures across crews and sites
- Documentation gaps increase risk exposure and schedule impacts
- Potential for serious injury or fatality from UXO detonation

**Desired State (Goal)**
- 100% immediate stop-work response when suspicious object encountered
- Zero incidents of personnel handling or approaching suspicious objects
- Consistent, accurate reporting through established chain of command
- Complete documentation for all UXO incidents
- Work resumes only after expert clearance

**Performance Gap**
Workers lack:
1. **Knowledge:** Clear understanding of what constitutes a suspicious object
2. **Skill:** Practiced protocol execution (stop, secure, report sequence)
3. **Judgment:** Confidence to stop work immediately ("when in doubt, stop")
4. **Awareness:** Understanding of consequences (both of protocol and violations)

### 2. Root Cause Analysis

**Is training the right solution?**

| Potential Cause | Analysis | Solution |
|----------------|----------|----------|
| **Lack of knowledge** | ✅ YES - Workers don't know what's suspicious or what to do | **TRAINING** |
| **Lack of skill** | ✅ YES - Workers haven't practiced the protocol | **TRAINING** |
| **Unclear expectations** | ✅ YES - Protocol not standardized/communicated | **TRAINING + Job Aid** |
| **Bad systems/tools** | ❌ NO - Reporting chain exists | Not a system issue |
| **Lack of motivation** | ⚠️ PARTIAL - Compliance-driven, but safety matters | Address in training design |
| **No consequences** | ❌ NO - Serious safety and liability consequences exist | Clarify in training |

**Conclusion:** Training is the appropriate solution. The performance gap is caused by knowledge and skill deficits, not system or motivation barriers.

### 3. Audience Analysis

**Primary Audience**
- **Role:** Construction contractors, subcontractors, equipment operators, laborers, forepersons, site supervisors
- **Number:** Variable (estimated 500-1000 annually)
- **Location:** DND construction sites across Canada
- **Experience:** Wide range (novice to 20+ years in construction)
- **Age range:** 18-65+
- **Education:** High school to technical certifications
- **Language:** English (bilingual EN/FR may be required)

**Secondary Audience**
- **Role:** DCC project managers, site representatives, project staff
- **Purpose:** Oversight and protocol enforcement

**Learner Characteristics**

| Characteristic | Implication for Design |
|----------------|------------------------|
| **Mobile-first users** | Must work on smartphones/tablets in field |
| **Limited time** | 15-20 minutes maximum, chunked into 3-7 min modules |
| **"Just want to work" attitude** | Make training relevant, show consequences, quick hook |
| **Hands-on learners** | Scenario-based practice, not lecture-heavy |
| **Wide experience range** | Accessible to novices, not boring to experts |
| **Mandatory training mindset** | Acknowledge compliance need, emphasize life-saving value |
| **Field distractions** | Clear visuals, minimal text, high-impact messaging |

**Learning Environment**
- **Device:** Mobile phones, tablets, desktop computers
- **Connection:** Variable (4G to WiFi); must work offline after download
- **Context:** Pre-deployment (office/home) or on-site breaks
- **Support:** Job aid for field reference post-training
- **Accessibility:** WCAG 2.1 AA compliance required

### 4. Task Analysis

**Critical Task Sequence** (when suspicious object encountered)

```
┌─────────────────────────────────────────────────┐
│ TRIGGER: Worker encounters suspicious object    │
│ (unusual metal, military-looking, unfamiliar)   │
└─────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────┐
│ TASK 1: RECOGNIZE situation requires protocol   │
│ - Visual identification (shape, material, fins) │
│ - Context awareness (DND site, ground work)     │
│ - Decision: Suspicious? → Apply protocol        │
└─────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────┐
│ TASK 2: STOP WORK immediately                   │
│ - Halt all equipment/tools (30 seconds)         │
│ - Alert all crew members verbally               │
│ - Move away from object (back to safe distance) │
│ - Do NOT touch, photograph, or investigate      │
└─────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────┐
│ TASK 3: SECURE THE AREA                         │
│ - Establish 25-meter exclusion zone             │
│ - Mark perimeter (cones, tape, barriers)        │
│ - Prevent all access (crew + public)            │
│ - Account for all personnel (ensure safe)       │
└─────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────┐
│ TASK 4: REPORT through chain of command         │
│ - Worker → Notify supervisor immediately        │
│ - Supervisor → Notify site authority            │
│ - Site authority → Contact DCC PM               │
│ - DCC PM → Request UXO expert                   │
│ - Document: Location, description, time         │
└─────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────┐
│ TASK 5: WAIT for expert clearance               │
│ - UXO expert assesses object                    │
│ - Site authority provides all-clear             │
│ - Do NOT resume work without clearance          │
│ - Follow any additional expert instructions     │
└─────────────────────────────────────────────────┘
```

**Task Complexity Analysis**

| Task | Complexity | Error Risk | Training Priority |
|------|------------|------------|-------------------|
| Recognize suspicious | Medium | Medium (false negatives) | HIGH - Practice scenarios |
| Stop work | Low | High (failure to stop) | CRITICAL - Immediate action |
| Secure area | Medium | Medium (wrong distance) | HIGH - 25m standard |
| Report chain | Low | Medium (skip steps) | HIGH - Role-specific paths |
| Wait for clearance | Low | High (premature return) | CRITICAL - Emphasize waiting |

### 5. Context Analysis

**Delivery Method:** Self-paced e-learning (Articulate Rise 360)
- **Rationale:** Scalable to large audience, mobile-responsive, SCORM-compliant
- **Platform:** LMS (client-specified)
- **Tracking:** Completion + assessment score (SCORM 1.2/2004 or xAPI)

**Timing:** Pre-deployment (before site access)
- **Mandatory:** Required for all personnel before working on DND sites
- **Frequency:** Initial training + annual refresher
- **Certificate:** Valid for 1 year

**Performance Support:** 1-page laminated job aid
- **Purpose:** Field reference during actual suspicious object encounters
- **Distribution:** Downloadable in module, printed/laminated for site offices
- **Format:** Pocket-sized or clipboard-attached

**Constraints**
- **Duration:** 15-20 minutes maximum (respect worker time)
- **Safety-critical:** Must NOT teach handling, identification, or neutralization
- **Bilingual:** English version first; French translation may be required
- **Accessibility:** WCAG 2.1 AA compliance (alt text, contrast, keyboard, captions)
- **Privacy:** No sensitive site details, no real incident identifiers
- **Approval:** SME review (UXO safety authority) + DCC safety + sponsor

---

## Learning Objectives

### Terminal Objective (ABCD Format)

**Given a ground disturbance scenario where a suspicious object is encountered (Condition), construction personnel (Audience) will execute the stop-work, secure, and report protocol (Behavior) with 100% accuracy and within protocol timeframes (Degree).**

**Bloom's Taxonomy Level:** Application (Apply procedures in realistic scenarios)

### Enabling Objectives (ABCD Format)

#### Objective 1: Recognition (Cognitive - Identify)

**Given images of ground disturbance scenarios (C), learners (A) will identify (B) situations requiring stop-work protocol with 90% accuracy (D).**

- **Bloom's Level:** Comprehension (Understand red flags)
- **Assessment:** Image sorting (6 scenarios: 3 suspicious, 3 normal)
- **Module:** Module 2 (Recognition)

#### Objective 2: Stop Work (Psychomotor - Execute)

**When encountering a suspicious object (C), workers (A) will immediately halt all work activities and alert crew members (B) within 30 seconds (D).**

- **Bloom's Level:** Application (Execute immediate response)
- **Assessment:** Scenario-based: "What is your FIRST action?"
- **Module:** Module 3 (Protocol - Step 1)

#### Objective 3: Secure Area (Psychomotor - Execute)

**Given a suspicious object situation (C), personnel (A) will establish and mark a 25-meter exclusion zone (B) preventing all access with 100% adherence (D).**

- **Bloom's Level:** Application (Execute safety perimeter)
- **Assessment:** "What is the minimum safe distance?" (25m)
- **Module:** Module 3 (Protocol - Step 2)

#### Objective 4: Reporting Sequence (Cognitive/Psychomotor - Apply)

**Following stop-work and area security (C), personnel (A) will complete the 4-step reporting chain (B) in correct sequence with 100% accuracy (D).**

- **Bloom's Level:** Application (Execute reporting protocol)
- **Assessment:** Drag-and-drop sequencing + role-specific scenarios
- **Module:** Module 3 (Protocol - Step 3)

#### Objective 5: Role Recognition (Cognitive - Classify)

**Given their role (worker/supervisor/PM) (C), learners (A) will identify their specific responsibilities in the protocol (B) with 100% accuracy (D).**

- **Bloom's Level:** Comprehension (Understand role-specific duties)
- **Assessment:** Multiple choice: "As a [role], your responsibility is..."
- **Module:** Module 3 (Role-specific tabs)

### Objective-to-Assessment Alignment Matrix

| Objective | Assessment Item | Module | Critical? |
|-----------|-----------------|--------|-----------|
| 1. Recognition | Image sorting (6 items) | Module 2 | YES |
| 2. Stop Work | "What is your FIRST action?" | Module 4 + Final | CRITICAL |
| 3. Secure Area | "Minimum exclusion zone distance?" | Module 3 + Final | CRITICAL |
| 4. Reporting Chain | Drag-and-drop sequence + scenario | Module 3 + Final | CRITICAL |
| 5. Role Recognition | Role-based scenario selection | Module 3 + Final | YES |

**Critical Items:** Must score 100% on objectives 2, 3, 4 (stop work, secure, report). These are life-safety actions.

---

## Assessment Design

### Assessment Philosophy: Assessment-First Design

**Principle:** Design assessments BEFORE developing content. Content should enable learners to pass assessments, not the reverse.

**Rationale for Safety Training:**
- Assessments prove behavioral readiness (not just knowledge)
- Critical items require 100% accuracy (no room for error in safety)
- Branching scenarios show consequences (why protocol matters)
- Multiple attempts with remediation (learn from mistakes safely)

### 1. Formative Assessments (During Learning)

**Knowledge Check 1: Recognition** (Module 2, Screen 2.4)

**Type:** Image sorting (drag-drop or click-to-categorize)

**Scenario:** "Which items require stop-work protocol?"

**Images (6 items):**
1. Rusty pipe (construction debris) → NORMAL
2. Cylindrical object with fins → SUSPICIOUS
3. Large rock → NORMAL
4. Corroded metal with military markings → SUSPICIOUS
5. Rebar (steel reinforcement) → NORMAL
6. Cone-shaped metal object → SUSPICIOUS

**Feedback:**
- Correct suspicious identification: "Yes, this is suspicious—stop work immediately."
- Incorrect (marking normal as suspicious): "Good caution! But this is typical construction material. When truly unsure, always err on the side of safety."
- Incorrect (missing suspicious): "⚠️ This object shows red flags: [fins/shape/markings]. When in doubt, treat as suspicious."

**Remediation:** If ≤4 correct, review red flags flashcards (Module 2, Screen 2.2)

**Objective Assessed:** Objective 1 (Recognition - 90% accuracy)

---

**Knowledge Check 2: Stop Work Actions** (Module 2, Screen 2.5)

**Type:** Multiple choice with consequence branching

**Scenario:** "You're digging post holes and hit a metal object. It's rusty, about 30cm long, with an unusual shape. What do you do?"

**Options:**
- A) Keep digging carefully to see what it is
- B) Stop work immediately ✓
- C) Take a photo to show your supervisor
- D) Cover it back up and work elsewhere

**Branching:**
- **Choice B (Correct):** "✅ Correct! Stop work is ALWAYS the first action. Now, what's your next step?" → Continue to Module 3
- **Choice A (Wrong):** Animation showing potential explosion → "❌ NEVER continue digging. The object could detonate from vibration or impact. Lives are at risk." → Retry
- **Choice C (Wrong):** "❌ Photos can wait—your safety can't. The first action is to STOP WORK and move to a safe distance." → Retry
- **Choice D (Wrong):** "❌ Ignoring the object doesn't make it safe. The next worker could trigger it. You must stop work and follow protocol." → Retry

**Objective Assessed:** Objective 2 (Stop Work - immediate action)

---

**Knowledge Check 3: Reporting Chain** (Module 3, Screen 3.7-3.8)

**Type 1:** Drag-and-drop sequencing

**Instructions:** "Put these protocol steps in the correct order"

**Items to sequence:**
- [ ] Contact DCC Project Manager
- [ ] Notify site supervisor
- [ ] Establish 25m exclusion zone
- [ ] Stop work immediately
- [ ] Wait for UXO expert clearance
- [ ] Move away from object

**Correct Sequence:**
1. Stop work immediately
2. Move away from object
3. Establish 25m exclusion zone
4. Notify site supervisor
5. Contact DCC Project Manager (via chain)
6. Wait for UXO expert clearance

**Feedback:**
- All correct: "✅ Perfect! You know the protocol sequence."
- 1-2 errors: "Almost there. Review these steps: [highlight incorrect]"
- 3+ errors: "Let's review the protocol flowchart." → Return to Screen 3.2

**Type 2:** Role-specific multiple choice

**Scenario:** "You're a construction worker and found a suspicious object. You've stopped work and secured the area. Who do you contact first?"

**Options:**
- A) DCC Project Manager
- B) Your supervisor ✓
- C) 911 Emergency Services
- D) UXO disposal company

**Feedback:**
- B: "✅ Correct! Your supervisor is your first point of contact. They will escalate through the chain."
- A/D: "❌ Workers do not contact PM or experts directly. Report to your supervisor, who will escalate."
- C: "⚠️ Call 911 only if there's immediate danger (fire, explosion, injury). Otherwise, follow the reporting chain."

**Objective Assessed:** Objective 4 (Reporting Chain - 100% accuracy)

### 2. Summative Assessment (Post-Module Final Assessment)

**Assessment Type:** Scenario-based performance quiz (10 questions)

**Passing Criteria:**
- **Overall Score:** 80% minimum (8/10 questions correct)
- **Critical Items:** 100% required (Questions 1, 2, 4, 5, 9)
- **Attempts:** Unlimited with remediation
- **Time Limit:** None (self-paced, safety-critical learning)

**Assessment Structure:**

#### Question 1: Immediate Action (CRITICAL)

**Scenario:** "You encounter a suspicious object while excavating. What is your FIRST action?"

**Options:**
- A) Take a photo
- B) Stop work immediately ✓
- C) Call your supervisor
- D) Cover it with soil

**Feedback:**
- B: "✅ Correct! STOP WORK is always the first action—no exceptions."
- A/C/D: "❌ The FIRST action is STOP WORK. Everything else comes after you and your crew are at a safe distance. Review Module 3."

**Objective:** Objective 2 (Stop Work)
**Critical:** YES
**Weight:** 15%

---

#### Question 2: Area Security (CRITICAL)

**Question:** "What is the minimum safe distance for the exclusion zone?"

**Options:**
- A) 5 meters
- B) 10 meters
- C) 25 meters ✓
- D) 50 meters

**Feedback:**
- C: "✅ Correct! 25 meters is the minimum safe distance for unidentified objects."
- A/B: "❌ Too close! Minimum 25 meters. Shrapnel and blast radius can extend beyond 10 meters."
- D: "⚠️ 50 meters is safer than necessary (25m minimum), but not wrong. 25m is the standard protocol."

**Objective:** Objective 3 (Secure Area)
**Critical:** YES
**Weight:** 15%

---

#### Question 3: Recognition

**Question:** "Which characteristic suggests an object is suspicious?"

**Options:**
- A) It's made of wood
- B) It has fins or markings ✓
- C) It's a familiar construction material
- D) It's very large

**Feedback:**
- B: "✅ Correct! Fins, fuses, markings are red flags for military ordnance."
- A: "❌ UXO is typically metal. Wooden objects are not ordnance."
- C: "❌ Familiar materials (rebar, pipes) are not suspicious. Unfamiliar = suspicious."
- D: "⚠️ Size doesn't determine danger. Small ordnance can be lethal."

**Objective:** Objective 1 (Recognition)
**Critical:** NO
**Weight:** 10%

---

#### Question 4: Reporting Chain (CRITICAL)

**Question:** "As a construction worker, who do you report to first?"

**Options:**
- A) DCC PM
- B) UXO expert
- C) Your supervisor ✓
- D) 911

**Feedback:**
- C: "✅ Correct! Workers report to their supervisor, who escalates through the chain."
- A/B: "❌ Workers do not contact PM or experts directly. Follow the chain: Worker → Supervisor → Site Authority → DCC PM."
- D: "⚠️ 911 is for immediate danger only. For UXO protocol, report to your supervisor first."

**Objective:** Objective 4 (Reporting Chain)
**Critical:** YES
**Weight:** 15%

---

#### Question 5: Prohibited Actions (CRITICAL - Multiple Select)

**Question:** "Which actions should NEVER be taken with a suspicious object? (Select all that apply)"

**Options:**
- ☑ Touch or move it
- ☐ Stop work (CORRECT ACTION)
- ☑ Pour water on it
- ☑ Photograph it up close
- ☐ Maintain 25m distance (CORRECT ACTION)

**Feedback:**
- All correct: "✅ Correct! Never touch, move, or closely approach a suspicious object."
- Missed prohibited actions: "❌ You missed critical prohibitions. Review Module 3, Screen 3.3: DO NOT touch, move, photograph up close, or apply liquids."
- Incorrect (marked stop work/distance as prohibited): "⚠️ Stopping work and maintaining distance are CORRECT actions, not prohibited."

**Objective:** Objective 2, 3 (Stop Work, Secure Area)
**Critical:** YES
**Weight:** 20%

---

#### Question 6: When to Apply Protocol

**Question:** "When should you apply the stop-work protocol?"

**Options:**
- A) Only if you're certain it's UXO
- B) If you recognize the ordnance type
- C) Anytime you encounter something suspicious ✓
- D) Only if it looks new

**Feedback:**
- C: "✅ Correct! When in doubt, stop work. Better safe than sorry."
- A/B: "❌ Do NOT wait for certainty or identification. If it's unfamiliar or suspicious, apply the protocol immediately."
- D: "❌ Age doesn't determine danger. Old, corroded ordnance can still detonate."

**Objective:** Objective 1 (Recognition)
**Critical:** NO
**Weight:** 5%

---

#### Question 7: Protocol Sequence

**Question:** "After stopping work, what is your next action?"

**Options:**
- A) Call supervisor
- B) Take photos
- C) Secure the area ✓
- D) Document details

**Feedback:**
- C: "✅ Correct! Sequence: Stop → Secure → Report."
- A: "⚠️ Reporting is step 3. After stopping, immediately secure the area (step 2)."
- B/D: "❌ Documentation comes later. Priority sequence: Stop → Secure → Report."

**Objective:** Objective 4 (Reporting Chain)
**Critical:** NO
**Weight:** 5%

---

#### Question 8: Role Clarity

**Question:** "As a worker, your primary responsibility is to:"

**Options:**
- A) Identify the ordnance type
- B) Assess the danger level
- C) Stop work, secure area, notify supervisor ✓
- D) Contact UXO experts directly

**Feedback:**
- C: "✅ Correct! Workers execute: Stop, Secure, Notify. Identification and expert contact are not your role."
- A/B: "❌ Workers do NOT identify or assess. Your role: Stop, Secure, Notify."
- D: "❌ Workers report to supervisors, not experts. Follow the chain of command."

**Objective:** Objective 5 (Role Recognition)
**Critical:** NO
**Weight:** 5%

---

#### Question 9: Clearance Requirement (CRITICAL)

**Question:** "When can you resume work after finding a suspicious object?"

**Options:**
- A) After securing the area
- B) After notifying supervisor
- C) After UXO expert provides clearance ✓
- D) After 24 hours

**Feedback:**
- C: "✅ Correct! ONLY a UXO expert can provide clearance. Do not resume work until site authority confirms all-clear."
- A/B: "❌ Securing and reporting are necessary, but NOT sufficient. You must wait for expert clearance."
- D: "❌ Time does not equal safety. Only expert assessment clears the site."

**Objective:** Objective 4 (Reporting Chain)
**Critical:** YES
**Weight:** 15%

---

#### Question 10: Consequence Understanding

**Question:** "Why is the stop-work protocol critical?"

**Options:**
- A) To avoid project delays
- B) To protect worker safety ✓
- C) To comply with regulations
- D) To document findings

**Feedback:**
- B: "✅ Correct! Safety is the primary reason. UXO can cause serious injury or death."
- A: "⚠️ While delays matter, safety is the PRIMARY concern. Lives over schedules."
- C: "⚠️ Compliance is important, but safety is the fundamental reason for the protocol."
- D: "❌ Documentation is a step in the protocol, not the reason for it."

**Objective:** All (Understanding importance)
**Critical:** NO
**Weight:** 5%

---

### Assessment Rubric

| Component | Points | Criteria | Critical? |
|-----------|--------|----------|-----------|
| **Immediate Stop Work** | 15 | Q1 correct | YES |
| **Area Security** | 15 | Q2 correct | YES |
| **Prohibited Actions** | 20 | Q5 all correct | YES |
| **Reporting Chain** | 20 | Q4 + Q9 correct | YES |
| **Recognition** | 15 | Q3 + Q6 correct | NO |
| **Sequence/Role** | 15 | Q7 + Q8 correct | NO |
| **Total** | 100 | | |

**Passing Criteria:**
1. **Overall:** ≥80% (8/10 questions or equivalent points)
2. **Critical Items:** 100% (Q1, Q2, Q4, Q5, Q9 must ALL be correct)
3. **Remediation:** If failed, must review specific module content before retake
4. **Attempts:** Unlimited (safety-critical learning, no penalty for multiple attempts)

**Remediation Branching:**
- **Failed Q1/Q2:** Review Module 3 (Protocol)
- **Failed Q3/Q6:** Review Module 2 (Recognition)
- **Failed Q4/Q9:** Review Module 3 (Reporting Chain)
- **Failed Q5:** Review Module 3 (Prohibited Actions)
- **Failed Q7/Q8:** Review Module 3 (Full Protocol + Roles)

---

## Instructional Strategy

### Overall Approach

**Design Philosophy:** Scenario-driven, consequence-based learning for safety-critical behavior change

**Key Principles:**
1. **Problem-Centered (Merrill):** Start with realistic UXO scenarios, not abstract concepts
2. **Consequence-Based:** Show what happens when protocol is followed vs. violated
3. **Behavior-Focused:** Training goal is action, not just awareness
4. **Role-Specific:** Workers, supervisors, and PMs have different responsibilities
5. **Performance Support:** Job aid bridges training to real-world application

### Content Sequencing Framework

**Gagné's Nine Events of Instruction** (applied to each module)

| Event | Purpose | Application in UXO Training |
|-------|---------|----------------------------|
| 1. Gain attention | Hook learner | Real incident consequence (Module 1) |
| 2. Inform objectives | Set expectations | "You'll know exactly what to do" |
| 3. Stimulate recall | Activate prior knowledge | "Ever found something unusual digging?" |
| 4. Present content | Deliver information | Protocol steps (chunked, visual) |
| 5. Provide guidance | Support understanding | Worked example: Expert executes protocol |
| 6. Elicit performance | Practice | Branching scenarios with choices |
| 7. Provide feedback | Correct errors | Immediate, consequence-based |
| 8. Assess performance | Verify learning | Post-module quiz (80% pass) |
| 9. Enhance retention | Support transfer | Job aid, manager toolbox talk |

**Merrill's First Principles** (integrated throughout)

| Principle | Implementation |
|-----------|----------------|
| **Problem-Centered** | Module 4 starts with full excavation scenario (not theory) |
| **Activation** | Connect to construction experience: "You've found unusual things before..." |
| **Demonstration** | Show expert worker executing protocol (video/animation) |
| **Application** | Practice in branching scenarios (safe failure environment) |
| **Integration** | Job aid for field use, manager reinforcement |

### Module Structure (5 Modules)

#### Module 1: Why This Matters (5 minutes)

**Objective:** Establish importance and motivation

**Gagné Events Applied:**
1. **Gain Attention:** Real incident story (worker touched object → evacuation → bomb disposal)
2. **Inform Objectives:** "You'll learn the protocol that could save your life"
3. **Stimulate Recall:** "DND sites have historical military activity"

**Content:**
- **Screen 1.1:** Title screen (high-impact visual)
- **Screen 1.2:** Scenario reveal (construction site → hidden danger)
- **Screen 1.3:** Real consequences (anonymized incident, serious tone)
- **Screen 1.4:** What is UXO? (definition, illustrated examples)
- **Screen 1.5:** Where UXO is found (accordion: training ranges, historical bases, etc.)
- **Screen 1.6:** Your role (commitment statement, learner types name)

**Instructional Techniques:**
- Emotional hook (safety, not fear)
- Storytelling (real incident, anonymized)
- Interactive reveal (click to uncover hidden object)
- Personal commitment (type your name)

---

#### Module 2: Recognize Suspicious Objects (3 minutes)

**Objective:** Learners identify suspicious situations requiring stop-work protocol

**Gagné Events Applied:**
4. **Present Content:** Red flags flashcards (fins, markings, unusual shapes)
5. **Provide Guidance:** Normal vs. suspicious comparison
6. **Elicit Performance:** Image sorting practice
7. **Provide Feedback:** Immediate, specific to each choice

**Content:**
- **Screen 2.1:** Module intro (detective icon, "spot the red flags")
- **Screen 2.2:** Red flags flashcards (6 cards, flip to reveal details)
- **Screen 2.3:** Normal vs. suspicious comparison (side-by-side images)
- **Screen 2.4:** Recognition practice (sort 6 items: 3 suspicious, 3 normal)
- **Screen 2.5:** Scenario check (multiple choice with branching)
- **Screen 2.6:** Summary (checklist: unusual metal, military-looking, when in doubt)

**Instructional Techniques:**
- Flashcards (active exploration)
- Comparison (build discrimination skill)
- Image sorting (hands-on practice)
- Consequence branching (show why recognition matters)

**Cognitive Load Management:**
- Chunk: 6 red flags (not 20)
- Visual: Illustrated (not text-heavy descriptions)
- Practice: Immediate after concept introduction
- Remove: No ordnance identification details (out of scope)

---

#### Module 3: The Protocol - Stop, Secure, Report (7 minutes)

**Objective:** Learners execute the 4-step protocol with 100% accuracy

**Gagné Events Applied:**
4. **Present Content:** Protocol flowchart (visual, chunked into 4 steps)
5. **Provide Guidance:** Video demonstration (expert executes protocol)
6. **Elicit Performance:** Drag-and-drop sequencing, role-specific practice
7. **Provide Feedback:** Immediate correctness + rationale

**Content:**
- **Screen 3.1:** Module intro (3-step icon sequence)
- **Screen 3.2:** Protocol overview (process block: Stop → Secure → Report → Wait)
- **Screen 3.3:** Step 1: STOP WORK (accordion + 30-sec video)
- **Screen 3.4:** Step 2: SECURE the area (accordion + diagram showing 25m)
- **Screen 3.5:** Step 3: REPORT (tabs: Worker / Supervisor / Site Authority)
- **Screen 3.6:** Step 4: WAIT for clearance (text + visual)
- **Screen 3.7:** Protocol practice (drag-and-drop sequence)
- **Screen 3.8:** Reporting chain practice (multiple choice)
- **Screen 3.9:** Full protocol video (90-sec narrated animation)
- **Screen 3.10:** Summary (recap with icons)

**Instructional Techniques:**
- Process flowchart (visual, sequential)
- Video demonstration (worked example)
- Role-specific tabs (personalized content)
- Drag-and-drop (kinesthetic practice)
- Accordion blocks (manage cognitive load)

**Cognitive Load Management:**
- **Signaling:** Color-code steps (Red=Stop, Yellow=Secure, Blue=Report, Green=Clear)
- **Segmenting:** Each step is a separate screen (not all at once)
- **Modality:** Video with narration (not video + on-screen text)
- **Coherence:** Remove decorative images (only instructional visuals)

**Worked Example (Video Script):**
```
NARRATION: "Watch how this worker handles a suspicious object discovery."

VISUAL: Worker operating excavator, bucket hits something solid.

NARRATION: "The moment he feels the impact, he stops the machine immediately."

VISUAL: Worker turns off excavator, exits cab.

NARRATION: "He alerts his crew: 'Everyone, stop! I hit something unusual. Move back.'"

VISUAL: Workers stop, move away together.

NARRATION: "He establishes a 25-meter exclusion zone using cones and tape."

VISUAL: Wide shot showing marked perimeter, workers outside zone.

NARRATION: "He immediately calls his supervisor to report the situation."

VISUAL: Worker on phone, providing location and description.

NARRATION: "The supervisor contacts site authority, who calls DCC PM and requests UXO experts."

VISUAL: Chain of communication shown (supervisor → site authority → DCC PM → expert).

NARRATION: "Work remains stopped until the expert arrives, assesses, and provides clearance."

VISUAL: Expert in protective gear examining object, gives thumbs up, workers resume safely.

NARRATION: "This worker followed the protocol perfectly. Everyone stayed safe."
```

---

#### Module 4: Scenario Practice (3 minutes)

**Objective:** Apply protocol in realistic scenarios with branching consequences

**Gagné Events Applied:**
6. **Elicit Performance:** Branching scenarios (decision points)
7. **Provide Feedback:** Consequence-based (show outcomes of choices)

**Content:**
- **Screen 4.1:** Module intro (scenario setup)
- **Screen 4.2:** Scenario 1 - Excavator operator (ground disturbance)
  - Decision 1: What do you do FIRST? (A: Continue digging / B: Stop immediately ✓ / C: Take photo / D: Cover it)
  - Branching: Wrong choice → Show consequence (explosion animation) → Remediation → Retry
  - Decision 2: How far back? (Slider: 5m / 10m / 25m ✓ / 50m / 100m)
  - Decision 3: Who do you call? (Supervisor ✓)
  - Outcome: Success path shows site secured, expert en route, zero injuries
- **Screen 4.3:** Scenario 2 - Laborer (hand-digging post holes, cone-shaped object)
  - Similar branching structure, different context
- **Screen 4.4:** Scenario 3 - Supervisor (crew found object, what's YOUR role?)
  - Multiple select: Ensure secured, account for crew, notify authority ✓ (NOT: inspect, move)
- **Screen 4.5:** Scenario summary (results: passed all 3 scenarios)

**Instructional Techniques:**
- **Branching Scenarios:** Realistic choices with consequences
- **Safe Failure:** Wrong choices show outcomes, then allow retry
- **Immediate Feedback:** Not just "wrong"—show WHY (explosion, injury risk)
- **Role Variation:** Worker vs. supervisor perspectives
- **Multiple Attempts:** Learn from mistakes, no penalty

**Consequence-Based Feedback Examples:**

| Choice | Consequence Shown | Lesson |
|--------|-------------------|--------|
| Continue digging | Animation: Explosion, evacuation, injury | NEVER continue work near suspicious objects |
| Take photo up close | Visual: Worker too close, object in frame | Stop FIRST, photos later from safe distance |
| Call PM directly | Visual: Confusion, delays, supervisor bypassed | Follow chain: Worker → Supervisor → Authority → PM |
| 10m distance | Visual: Shrapnel radius extends beyond 10m | 25m minimum—blast radius is larger than you think |

---

#### Module 5: Assessment & Next Steps (2 minutes)

**Objective:** Demonstrate protocol knowledge, download job aid, commit to protocol

**Gagné Events Applied:**
8. **Assess Performance:** 10-question quiz (80% pass, 100% on critical)
9. **Enhance Retention:** Job aid download, certificate, manager support

**Content:**
- **Screen 5.1:** Assessment intro (instructions: 10 questions, 80% pass, unlimited attempts)
- **Screens 5.2-5.11:** Quiz questions (see Assessment Design section)
- **Screen 5.12:** Quiz results (pass/fail, score breakdown, retry button if failed)
- **Screen 5.13:** Job aid download (PDF + PNG, "Keep this with you on site")
- **Screen 5.14:** Safety commitment (checkbox: "I commit to applying this protocol")
- **Screen 5.15:** Certificate + next steps (download certificate, review annually, stay safe)

**Instructional Techniques:**
- **Mastery-Based:** Must pass to complete (safety-critical)
- **Unlimited Attempts:** Remediation between attempts (review specific modules)
- **Job Aid:** Performance support for real-world application
- **Commitment:** Psychological contract (type acknowledgment)
- **Certificate:** Validation + accountability (valid 1 year)

---

### Transfer Design

**Goal:** Ensure protocol is applied on actual construction sites (not just passed in training)

**Transfer Strategies:**

| Strategy | Implementation | Rationale |
|----------|----------------|-----------|
| **Realistic Practice** | Scenarios match actual site conditions (excavation, trenching, demolition) | Near transfer: Practice context = performance context |
| **Job Aid** | 1-page laminated protocol card (pocket/clipboard) | Performance support at point of need |
| **Manager Briefing** | Toolbox talk script for supervisors | Reinforce protocol on-site, social accountability |
| **Application Assignment** | (Optional) Locate job aid on site, identify reporting chain | Connect training to real site |
| **Follow-Up Survey** | 30-day email: "Have you encountered suspicious objects? Did you follow protocol?" | Monitor transfer, identify barriers |
| **Incident Analysis** | Track protocol adherence in real UXO incidents | Measure behavioral outcome (Level 3 evaluation) |

**Job Aid Design** (detailed in separate document)
- **Format:** 1-page front/back, laminated
- **Front:** Visual protocol flowchart (Stop → Secure → Report → Wait)
- **Back:** Red flags list, prohibited actions, role-specific contacts
- **Distribution:** Downloadable in module, printed for site offices, posted on bulletin boards

**Manager Support Package:**
- **Toolbox Talk Script:** 5-minute protocol review for crew meetings
- **Incident Response Guide:** What to do if object found
- **Completion Tracking:** Manager notified when crew completes training

---

### Cognitive Load Management

**Working Memory Limits:** 7±2 items (Miller's Law)

**Strategies to Reduce Extraneous Load:**

| Technique | Application |
|-----------|-------------|
| **Chunk Information** | 4-step protocol (not 10 steps): Stop, Secure, Report, Wait |
| **Remove Decorative Elements** | No stock photos of construction workers (not instructional) |
| **Eliminate Redundancy** | Don't read on-screen text in narration (Mayer's principle) |
| **Consistent Icons** | 🛑 Stop, ⚠️ Secure, 📞 Report (visual consistency reduces load) |
| **Whitespace** | Generous spacing, max 3-4 bullets per screen |
| **Segment Content** | 5 short modules (3-7 min each) vs. 1 long module (20 min) |

**Strategies to Manage Intrinsic Load:**

| Technique | Application |
|-----------|-------------|
| **Simple → Complex** | Module 2: Recognition basics → Module 4: Complex scenarios |
| **Worked Examples** | Show expert executing protocol BEFORE learner practices |
| **Scaffolding** | Module 3: Guided practice → Module 4: Independent scenarios |
| **Isolate then Integrate** | Each step taught separately (3.3-3.6) → Full protocol (3.9) |

**Strategies to Increase Germane Load:**

| Technique | Application |
|-----------|-------------|
| **Varied Examples** | Different contexts: excavation, hand-digging, demolition |
| **Self-Explanation Prompts** | "Why is 25m the minimum distance?" (not just memorize) |
| **Comparison** | Normal construction finds vs. suspicious objects |
| **Application Practice** | Scenarios require applying protocol, not just recalling steps |

---

## Development Specifications

### Rise 360 Block Types

| Block Type | Use Case | Modules |
|------------|----------|---------|
| **Scenario Block** | Branching decisions with consequences | Module 4 (all scenarios) |
| **Flashcard Stack** | Red flags exploration (click to flip) | Module 2 (Screen 2.2) |
| **Process Block** | Sequential protocol steps (Stop → Secure → Report → Wait) | Module 3 (Screen 3.2) |
| **Accordion Block** | Expandable details (DO/DON'T lists, location types) | Modules 1, 3 |
| **Tabs Block** | Role-specific content (Worker / Supervisor / Site Authority) | Module 3 (Screen 3.5) |
| **Button Stack** | Image sorting (click to categorize) | Module 2 (Screen 2.4) |
| **Quiz Block** | Formative checks + final assessment | Modules 2, 3, 5 |
| **Video Block** | Protocol demonstration (worked example) | Module 3 (Screens 3.3, 3.9) |
| **Labeled Graphic** | Diagram of 25m exclusion zone | Module 3 (Screen 3.4) |
| **Continue Block** | Learner-paced progression | All modules (bottom of screens) |

### Media Specifications

**Images:**
- **Format:** PNG or JPG
- **Resolution:** 1200px wide minimum (retina-ready)
- **Style:** Illustrated (NOT photos of real UXO—too detailed, safety concern)
- **Content:**
  - Construction scenes (excavation, trenching, demolition)
  - Illustrated suspicious objects (generic cylindrical, cone-shaped, with fins—NO specific ordnance photos)
  - Protocol steps (workers stopping, securing, reporting)
  - Exclusion zone diagram (top-down view, 25m radius marked)
- **Accessibility:** ALT text for all images (descriptive, not decorative)
- **Contrast:** High contrast for outdoor mobile viewing (dark text on light background)

**Video (Optional Protocol Demonstration):**
- **Duration:** 90-120 seconds maximum
- **Format:** MP4 (H.264 codec)
- **Resolution:** 1080p (1920x1080) or 720p (1280x720)
- **Aspect Ratio:** 16:9 (standard) or 1:1 (square for mobile)
- **Style:** Animated or illustrated (NOT live-action with real ordnance)
- **Narration:** Professional voice-over (Canadian accent)
- **Captions:** Full transcript, WCAG compliant
- **Content:**
  - Worker encounters object → stops immediately → secures area → reports → waits for clearance
  - Emphasize critical actions (stop, back away, 25m zone)
- **Sound:** Narration only (no background music—reduces cognitive load)

**Audio (Narration):**
- **Format:** MP3 or M4A
- **Quality:** 128 kbps minimum
- **Tone:** Authoritative but not fear-based, conversational
- **Pace:** Moderate (not rushed, allows processing)
- **Accent:** Canadian English (audience match)
- **Must Work Sound-Off:** Content must be understandable without audio (captions + visuals)

**Icons:**
- **Style:** Simple, bold, professional (e.g., Font Awesome, Noun Project)
- **Size:** 60-80px (large enough for mobile tap targets)
- **Color:** Consistent system (Red=Stop, Yellow=Caution, Blue=Info, Green=Safe)
- **Accessibility:** Color + shape (not color alone—e.g., 🛑 is red AND octagon)

### Content Chunking Summary

| Module | Screens | Time | Key Interactions |
|--------|---------|------|------------------|
| 1. Why This Matters | 6 | 5 min | Click reveal, commitment statement |
| 2. Recognition | 6 | 3 min | Flashcards, image sort, scenario quiz |
| 3. Protocol | 10 | 7 min | Video, tabs, accordion, drag-and-drop, full protocol video |
| 4. Practice | 5 | 3 min | 3 branching scenarios with consequences |
| 5. Assessment | 12 | 2 min | 10-question quiz, job aid download, certificate |
| **TOTAL** | **39 screens** | **20 min** | High interactivity throughout |

### Accessibility Compliance (WCAG 2.1 AA)

**Perceivable:**
- ✅ **Alt Text:** All images have descriptive alt text (e.g., "Illustration of cylindrical metal object with fins partially exposed in soil")
- ✅ **Color Contrast:** 4.5:1 minimum for text (black on white or near-white)
- ✅ **Color + Icon:** Never use color alone (e.g., red text AND ❌ icon for prohibited actions)
- ✅ **Captions:** Video includes full transcript captions
- ✅ **Text Alternatives:** Interactive elements have text labels

**Operable:**
- ✅ **Keyboard Navigation:** All interactions accessible via keyboard (Rise 360 native support)
- ✅ **No Time Limits:** Learner-paced (no auto-advance, no timers)
- ✅ **Descriptive Links:** "Download job aid PDF" (not "Click here")
- ✅ **Skip Navigation:** Rise provides skip links

**Understandable:**
- ✅ **Plain Language:** Grade 8 reading level (Hemingway App tested)
- ✅ **Consistent Navigation:** Rise standard navigation (menu, back/forward)
- ✅ **Error Feedback:** Clear, constructive ("Review Module 3: Protocol steps")
- ✅ **Instructions First:** Interaction instructions BEFORE interactive element

**Robust:**
- ✅ **ARIA Labels:** Rise 360 handles automatically
- ✅ **Screen Reader Compatible:** Tested with JAWS, NVDA
- ✅ **Cross-Browser:** Works in Chrome, Firefox, Safari, Edge
- ✅ **Mobile Responsive:** Adapts to phone, tablet, desktop

### Plain Language Guidelines

**Target Reading Level:** Grade 8 (construction audience)

**Techniques:**
- **Active Voice:** "Stop work immediately" (NOT "Work should be stopped")
- **Short Sentences:** <20 words per sentence
- **Concrete Words:** "25 meters" (NOT "appropriate distance")
- **Familiar Terms:** "Suspicious object" (NOT "potential explosive remnants of war")
- **Avoid Jargon:** "Report to supervisor" (NOT "initiate chain of command protocols")
- **Simple Structure:** Subject-Verb-Object ("You stop work" not "Cessation of activities is required")

**Before/After Examples:**

| Complex (Before) | Plain Language (After) |
|------------------|------------------------|
| "Personnel must immediately cease all operational activities upon encountering a potentially hazardous item." | "Stop work immediately when you find a suspicious object." |
| "Establish a minimum exclusion perimeter of 25 meters radius." | "Keep everyone at least 25 meters away." |
| "Initiate the established chain of command communication protocol." | "Report to your supervisor." |
| "Await authorization from qualified UXO disposal specialists prior to resuming work activities." | "Wait for UXO expert clearance before resuming work." |

---

## Evaluation Plan

### Kirkpatrick's Four Levels of Evaluation

#### Level 1: Reaction (Immediate Post-Training)

**What It Measures:** Did learners find the training relevant, clear, and practical?

**Method:** End-of-module survey (2 questions)

**Questions:**
1. "This training was clear and practical." (1-5 scale: Strongly Disagree → Strongly Agree)
2. "I feel confident applying the UXO stop-work protocol on site." (1-5 scale: Not at all → Very confident)

**Target:** ≥4.0 average on both questions

**Data Source:** Rise 360 quiz/survey block (exported to LMS)

**Frequency:** Every completion

**Action:** If <4.0 average, review feedback comments and revise unclear content

---

#### Level 2: Learning (Immediate Post-Training)

**What It Measures:** Did learners achieve the learning objectives? Can they pass the assessment?

**Metrics:**
1. **Assessment Pass Rate:** % of learners who achieve ≥80% on first attempt
2. **Average Score:** Mean score across all attempts
3. **Critical Item Performance:** % who score 100% on critical items (Q1, Q2, Q4, Q5, Q9)
4. **Attempts to Pass:** How many attempts needed to reach 80%
5. **Most-Missed Questions:** Which questions have highest failure rate

**Targets:**
- **Pass Rate (first attempt):** ≥70%
- **Pass Rate (any attempt):** ≥90%
- **Average Score:** ≥85%
- **Critical Item Performance:** ≥95%
- **Attempts to Pass:** ≤2 attempts average

**Data Source:** LMS assessment reports (SCORM tracking)

**Frequency:** Weekly during rollout, monthly ongoing

**Action:**
- If questions have <70% correct rate → Review question clarity and/or content
- If critical items <95% → Add remediation, strengthen Module 3 content
- If >3 attempts average → Content may be too difficult, simplify

---

#### Level 3: Behavior (30-90 Days Post-Training)

**What It Measures:** Are learners applying the protocol on actual construction sites?

**Methods:**

**3A. Follow-Up Survey** (30 days post-training)
- Email survey to all completers
- Questions:
  1. "Have you encountered a suspicious object on site?" (Yes/No)
  2. (If Yes) "Did you follow the stop-work protocol?" (Yes/No/Partially)
  3. (If Yes) "Which steps did you take?" (Checklist: Stop, Secure, Report, Wait)
  4. "Do you have the job aid accessible on site?" (Yes/No)
  5. "Has your supervisor reinforced the protocol?" (Yes/No)

**3B. Manager Observation Checklist**
- Provide to supervisors/site managers
- Checklist completed if suspicious object found:
  - [ ] Work stopped immediately
  - [ ] Area secured (25m minimum)
  - [ ] Proper reporting chain followed
  - [ ] No prohibited actions (touching, moving, photographing)
  - [ ] Waited for expert clearance

**3C. Incident Report Analysis**
- Review all UXO incident reports
- Assess protocol adherence (did they follow trained steps?)
- Identify deviations and root causes
- Compare pre-training vs. post-training incidents

**Targets:**
- **Survey Response:** ≥30% response rate
- **Protocol Adherence (Real Incidents):** 100% (critical safety requirement)
- **Job Aid Access:** ≥80% have job aid accessible
- **Manager Reinforcement:** ≥70% received toolbox talk

**Data Source:**
- Survey: SurveyMonkey or LMS survey tool
- Incident reports: DCC safety database
- Manager checklists: Emailed to DCC Environmental Services

**Frequency:** 30 days, 90 days, 6 months post-training

**Action:**
- If <100% protocol adherence → Investigate barriers (training issue? site culture? unclear protocol?)
- If job aid not accessible → Improve distribution, remind supervisors
- If manager not reinforcing → Send toolbox talk script, emphasize leadership role

---

#### Level 4: Results (6-12 Months Post-Training)

**What It Measures:** Did the training solve the business problem? Did it improve safety outcomes?

**Metrics:**

**4A. Incident Reduction**
- **Metric:** Reduction in protocol deviations (handling objects, failing to stop work, skipping reporting)
- **Baseline:** Pre-training incident rate (if available)
- **Target:** 50% reduction in protocol violations year-over-year

**4B. Reporting Speed**
- **Metric:** Time from object discovery to UXO expert notification
- **Target:** <2 hours (faster response = safer site)

**4C. Site Delay Reduction**
- **Metric:** Reduction in project delays due to UXO incidents
- **Rationale:** Proactive protocol adherence prevents larger issues (uncontrolled evacuations, investigations)
- **Target:** 20% reduction in UXO-related delays

**4D. Zero Injuries**
- **Metric:** Zero injuries or fatalities from UXO handling
- **Target:** Maintain 100% safety record

**Data Source:**
- DCC safety records (incident reports, injury logs)
- Project management data (delay tracking)
- UXO expert reports (response times)

**Frequency:** Quarterly for first year, annually thereafter

**Action:**
- If protocol violations persist → Analyze root cause (training? enforcement? site culture?)
- If reporting delays → Review chain of command clarity, simplify reporting
- If injuries occur → Immediate investigation, emergency training refresh

---

### Evaluation Data Collection Summary

| Level | Data Source | Timeline | Responsible Party |
|-------|-------------|----------|-------------------|
| 1 - Reaction | LMS survey | Immediate (post-training) | LMS Administrator |
| 2 - Learning | LMS assessment scores | Immediate (post-training) | LMS Administrator |
| 3 - Behavior | Follow-up survey, manager checklists, incident reports | 30, 90, 180 days | DCC Environmental Services |
| 4 - Results | Safety records, project data | Quarterly, annually | DCC Safety + Project Management |

### Continuous Improvement Process

**Quarterly Review Cycle:**
1. **Collect Data:** Pull LMS reports, survey results, incident data
2. **Analyze:** Identify trends, gaps, high-failure questions
3. **Act:** Update content, revise questions, enhance job aid
4. **Communicate:** Share results with stakeholders (sponsor, SMEs, managers)

**Annual Review (Major Update):**
- **SME Review:** Verify protocol accuracy (any regulatory changes?)
- **Scenario Refresh:** Add new scenarios based on real incidents
- **Accessibility Audit:** Test with assistive technology, update for WCAG standards
- **Technology Refresh:** Update to latest Rise 360 features, optimize mobile experience

---

## Iteration & Continuous Improvement

### Pilot Phase (Weeks 1-2)

**Audience:** 50 representative users
- 30 construction workers (laborers, operators, forepersons)
- 10 site supervisors
- 10 DCC project staff

**Purpose:** Validate training effectiveness, identify issues before full rollout

**Activities:**
1. **Deploy:** Assign training to pilot group via LMS
2. **Monitor:** Track completion rate, assessment scores, time-on-task
3. **Survey:** Send post-pilot survey (usability, clarity, relevance)
4. **Review Analytics:**
   - Screen-by-screen drop-off (where do learners abandon?)
   - Most-missed assessment questions (content gaps?)
   - Time per module (too long? too short?)
   - Device types (mobile vs. desktop usage)
5. **Interview:** Optional 1:1 interviews with 5-10 pilot users (deeper insights)

**Success Criteria:**
- ✅ **Completion Rate:** ≥90%
- ✅ **Pass Rate:** ≥90% (80% threshold)
- ✅ **Satisfaction:** ≥4.0/5.0 average
- ✅ **No Critical Feedback:** No safety concerns, unclear protocol, or major usability issues

**If Success Criteria Not Met:**
- **Low Completion (<90%):** Investigate drop-off points, shorten modules, improve engagement
- **Low Pass Rate (<90%):** Review most-missed questions, clarify content, add examples
- **Low Satisfaction (<4.0):** Analyze feedback, address clarity, relevance, or technical issues

---

### Version 1.1 (Week 3)

**Purpose:** Revise based on pilot feedback

**Typical Revisions:**
- **Content Clarification:** Rewrite unclear screens, add examples
- **Assessment Adjustment:** Revise ambiguous questions, adjust difficulty
- **Media Updates:** Replace ineffective visuals, improve video quality
- **Scenario Refinement:** Make scenarios more realistic based on user input
- **Technical Fixes:** Resolve navigation issues, mobile bugs, LMS tracking

**Process:**
1. Analyze pilot data (completion, scores, feedback)
2. Prioritize revisions (critical fixes first)
3. Update Rise 360 module
4. SME review of revisions (ensure accuracy maintained)
5. Upload v1.1 to LMS
6. Document changes in version log

**Version 1.1 Target:** Address all critical issues, 80% of user feedback items

---

### Full Rollout (Week 4+)

**Audience:** All construction personnel (estimated 500-1000 users annually)

**Communication Plan:**
- **Week 4 (Launch):** Email announcement from sponsor, manager briefings, site posters
- **Weeks 5-7 (Reinforcement):** Weekly completion reminders, toolbox talks, job aid distribution
- **Week 8 (Close-out):** Thank completers, follow up with non-completers, escalate critical cases

**Timeline:** 4 weeks for completion (flexible for project schedules)

**Support:**
- **Help Desk:** Technical support for LMS access, browser issues
- **Manager Support:** Toolbox talk script, completion tracking
- **FAQ Document:** Common questions answered (updated weekly)

**Monitoring:**
- **Weekly Report:** Completion rate by role, site, region
- **Escalation:** Follow up with non-completers (safety-critical, mandatory)
- **Feedback Log:** Track user questions, issues, suggestions

---

### Ongoing Optimization (Post-Rollout)

**Monthly Review (First 6 Months):**
- **Metrics:** Completion rate, pass rate, average score, time-on-task
- **Feedback:** User comments, help desk tickets, manager reports
- **Action:** Minor content tweaks, FAQ updates, manager reinforcement

**Quarterly Review (Year 1):**
- **Deep Dive:** Analyze Level 3 data (behavior change, protocol adherence)
- **Scenario Update:** Add new scenarios based on real incidents
- **Assessment Review:** Update questions if trends emerge (e.g., Q7 consistently failed)

**Annual Major Review:**
1. **SME Review:** Verify protocol accuracy with UXO safety authority
   - Any regulatory changes?
   - Any new best practices?
   - Any site-specific learnings?

2. **Content Refresh:**
   - Update scenarios to reflect recent incidents (anonymized)
   - Refresh statistics (e.g., "In 2024, X incidents on DND sites")
   - Revise examples based on user feedback

3. **Accessibility Audit:**
   - Test with screen readers (JAWS, NVDA)
   - Verify WCAG 2.1 AA compliance (standards evolve)
   - Check mobile experience on new devices

4. **Technology Refresh:**
   - Update to latest Rise 360 features
   - Optimize for new LMS integrations
   - Improve mobile performance

5. **Stakeholder Review:**
   - Present evaluation results to sponsor
   - Gather input from DCC project managers (field perspective)
   - Collect SME feedback on training effectiveness

**Version 2.0 Trigger:** Significant protocol changes, major content overhaul, or regulatory updates

---

## Appendices

### Appendix A: Glossary

| Term | Definition |
|------|------------|
| **UXO** | Unexploded Ordnance - Military munitions that were fired/deployed but did not detonate as intended |
| **DND** | Department of National Defence (Canada) |
| **DCC** | Defence Construction Canada - Crown corporation managing DND construction projects |
| **Ground Disturbance** | Excavation, trenching, drilling, or demolition activities that disturb soil |
| **Suspicious Object** | Any unfamiliar metal object, military-looking item, or ground anomaly requiring stop-work protocol |
| **Exclusion Zone** | 25-meter perimeter around suspicious object where access is prohibited |
| **Chain of Command** | Reporting sequence: Worker → Supervisor → Site Authority → DCC PM → UXO Expert |
| **Clearance** | Authorization from UXO expert and site authority to resume work (object assessed as safe or removed) |
| **SME** | Subject Matter Expert (UXO safety authority, DND site authority) |

### Appendix B: References

**Instructional Design Frameworks:**
- Gagné, R. M., Wager, W. W., Golas, K. C., & Keller, J. M. (2005). *Principles of Instructional Design* (5th ed.). Wadsworth Publishing.
- Merrill, M. D. (2002). First principles of instruction. *Educational Technology Research and Development*, 50(3), 43-59.
- Mayer, R. E. (2021). *Multimedia Learning* (3rd ed.). Cambridge University Press.
- Kirkpatrick, D. L., & Kirkpatrick, J. D. (2006). *Evaluating Training Programs* (3rd ed.). Berrett-Koehler Publishers.

**Safety Training:**
- OSHA (2015). *Recommended Practices for Safety and Health Programs*. U.S. Department of Labor.
- CSA Group (2019). *CAN/CSA-Z1000-19: Occupational health and safety management*.

### Appendix C: Approval Log

| Reviewer | Role | Date | Status | Comments |
|----------|------|------|--------|----------|
| [Name] | DCC Sponsor | [Date] | ☐ Approved / ☐ Revisions | |
| [Name] | UXO SME | [Date] | ☐ Approved / ☐ Revisions | |
| [Name] | DCC Safety | [Date] | ☐ Approved / ☐ Revisions | |
| [Name] | Communications | [Date] | ☐ Approved / ☐ Revisions | |

---

**Document Control:**
- **Version:** 1.0
- **Date:** [Current Date]
- **Author:** [Your Name], Instructional Designer
- **Next Review:** [Date + 1 year]
- **Classification:** Internal Use / Controlled Distribution

---

**End of Instructional Design Plan**

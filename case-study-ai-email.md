# AI Email Assessment Demo

Designing an AI-powered, rubric-driven writing assessment that replaces multiple-choice evaluation with a more authentic workplace task.

Role: Lead Instructional Designer, Experience Designer, Rubric Designer, Prompt Strategist, Product Concept Owner

Duration: Rapid MVP / Proof of Concept

Tools: Next.js, TypeScript, Tailwind CSS, Supabase, OpenAI API, JSON schema validation

Audience: Hiring managers, L&D leaders, learning experience designers, collaborators evaluating AI-enabled assessment concepts

Live Demo: Add production URL here

At a Glance
## Project Summary

Situation

Many digital assessments check recall or recognition, but they do not reflect how people actually communicate at work. Writing tasks are more authentic, yet they are harder to scale because open-ended responses usually require manual review.

Task

Design a portfolio-ready MVP that shows how AI could support a scenario-based writing assessment without hiding the rubric, collapsing the experience into a model answer generator, or relying on vague, unstructured feedback.

Action

I designed and shipped a single-scenario web prototype where learners write a workplace phishing-warning email, review the same rubric the AI uses, optionally request drafting support, submit their response for rubric-based analysis, and receive structured criterion-level feedback plus a suggested rewrite.

Result

The result is a deployed proof of concept that demonstrates a credible alternative to traditional pre-programmed assessment logic: authentic learner performance, transparent scoring criteria, traceable AI outputs, and a reviewer-facing system trace that makes the concept easier to inspect and discuss.

Overview
## Project Background

This project started from an instructional design problem, not a technology-first brief. In many workplace learning contexts, assessments still over-index on multiple choice, short answer recall, or static “correct answer” logic. Those formats are efficient to administer, but they often fail to capture whether someone can actually produce a real workplace artifact under realistic constraints.

I wanted to explore a better pattern: what if the learner completed an authentic communication task, and AI was used not to replace the instructional design, but to operationalize a visible rubric, return criterion-level feedback, and make open-ended practice more scalable?

The use case I chose was intentionally narrow and credible: writing an all-staff phishing warning email. It is a realistic workplace task, easy to understand quickly, and rich enough to evaluate clarity, tone, structure, and action guidance.

The Challenge
## Authenticity, Transparency, and Support in Tension

This was not simply a UI exercise or a generic “AI feedback” demo. The core challenge was designing an assessment experience that balanced three competing needs:

1. Authenticity

The learner needed to write a realistic workplace artifact, not answer a disguised quiz. That meant the assessment had to feel like a genuine communication task with a plausible scenario and clear performance expectations.

2. Transparency

If AI was going to score the response, the scoring logic could not be mysterious. The learner needed access to the rubric before writing, and the system needed to use that same rubric as the explicit source of truth rather than hidden rules.

3. Support

AI drafting support could make the experience more useful and more impressive as a product concept, but it also risked undermining the assessment if coaching and scoring were blended together carelessly.

The design problem, then, was not “how do I add AI?” It was “how do I structure AI so it strengthens the assessment experience without distorting what the assessment is supposed to measure?”

My Approach
## Assessment-First, Product-Minded Design

I approached this as both an instructional design problem and a product concept.

### 01
### Start With the Performance Task

I defined the assessment around a concrete workplace output: an all-staff phishing warning email. From there, I articulated the learner objective, task requirements, expected strengths, and expected weaknesses before thinking about UI or prompts.

### 02
### Engineer the Rubric First

Instead of treating feedback as a loose AI text-generation problem, I used the rubric as the backbone of the system. The four criteria were:

- Understanding of Email Communication
- Appropriate Response to the Situation
- Advice on Phishing
- Presentation and Writing Style

This gave the product a stable scoring frame and made the learner-facing expectations explicit.

### 03
### Separate Coaching From Evaluation

I deliberately split the system into two workflows:

- Assist flow: supports the learner with outline, improve draft, and full draft modes
- Evaluation flow: scores the final learner response against the visible rubric

That separation matters instructionally. Coaching support can be generous and helpful without contaminating the scoring logic.

### 04
### Make the AI Traceable

On the technical side, I designed the AI layer to be inspectable rather than magical:

- server-side model calls only
- structured JSON outputs for assist and evaluation
- schema validation against defined response contracts
- retry handling for invalid model responses
- attempt persistence with prompt version, model name, and timestamp

This helped the prototype feel less like a speculative mockup and more like a serious systems concept.

The Solution
## A Working Assessment Prototype With Traceable AI Feedback

The finished MVP is a single-scenario web application designed to feel polished enough for a portfolio reviewer to experience directly.

The learner flow is intentionally simple:

1. Open the assessment and read a short workplace scenario
2. Review the visible rubric
3. Draft an all-staff phishing warning email in a clean response editor
4. Optionally use AI drafting support
5. Submit the response for analysis
6. Receive criterion-level scores, overall feedback, strengths, improvements, and a suggested rewrite

The reviewer flow is equally important. A separate System Trace view exposes saved attempts, total scores, model name, prompt version, and timestamps so the concept can be discussed as a product system rather than just a surface-level interface.

The prototype is intentionally narrow:

- one assessment scenario
- one visible rubric
- one end-to-end learner flow
- one reviewer trace view

That constraint was deliberate. Rather than simulating an entire LMS or assessment platform, I focused on making one scenario feel coherent, inspectable, and believable.

Design Decisions
## Critical Choices That Shaped the Prototype

### Visible Rubric as the Source of Truth

The learner sees the same rubric the evaluator uses. This was the most important design decision in the project. It improves transparency, gives the learner a fair frame for the task, and prevents the AI from being positioned as a mysterious scoring authority.

### Authentic Writing Task Over Multiple Choice

I chose a workplace email instead of a quiz because the portfolio point of the project is stronger when the learner produces a real artifact. The task is more representative of workplace communication, and it creates space for higher-quality feedback than a pre-authored answer key would allow.

### Separate Assist and Analyze Modes

The product distinguishes between “help me draft” and “analyze response.” That separation makes the learning experience more credible. Coaching can support the learner, while final analysis remains bounded by the rubric and the submitted text.

### Structured Outputs Over Loose AI Prose

Rather than accepting free-form model output, the system requires structured JSON, validates it against schemas, retries if needed, and computes the total score server-side from criterion scores. This decision made the prototype more reliable and easier to explain in product and technical terms.

### System Trace Instead of Hidden Plumbing

I added a reviewer-facing trace view to make the system legible. In portfolio work, this matters: it shows not just the learner UI, but the underlying logic, saved attempts, and traceability of the AI workflow.

Impact
## What This Prototype Demonstrates

Because this is an MVP and proof of concept, I frame impact in terms of concept validation rather than business KPIs.

### Instructional Value

The prototype demonstrates that AI can support a more authentic performance task without abandoning clarity or structure. Learners are asked to produce a realistic workplace artifact, guided by a visible rubric, and receive feedback that is more specific and educational than a typical auto-graded quiz response.

### Product Value

The project demonstrates a plausible product pattern for AI-enabled assessment:

- visible criteria instead of hidden scoring logic
- separate coaching and evaluation flows
- structured and traceable model outputs
- persistence that supports reviewer trust and future analytics

### Portfolio Value

For hiring managers and collaborators, the project makes several capabilities concrete:

- translating an instructional problem into a product concept
- designing a rubric suitable for AI-supported evaluation
- shaping prompts and system rules around instructional intent
- building a narrow but credible MVP instead of an over-scoped concept deck

### Technical Validation

The deployed prototype proves that the concept can operate end to end:

- learner input is captured
- AI assist and evaluation happen server-side
- model outputs are schema-validated
- attempts are stored in Supabase
- reviewer-facing trace data is available for inspection

Reflection
## What I Learned

This project reinforced that AI in learning design is most useful when it is tightly bounded by instructional intent. The value did not come from adding a chatbot or generating generic feedback. It came from defining a real performance task, writing a transparent rubric, and designing the AI layer to support that structure rather than bypass it.

It also reinforced the importance of scope discipline. Building one scenario well was a stronger portfolio move than pretending to have a full assessment platform. The narrower scope made it possible to think carefully about prompt behavior, error handling, reviewer trust, and learner experience.

The project also surfaced important limitations. This should not be positioned as a high-stakes scoring engine. Reliability, calibration, fairness review, and human moderation patterns would all matter much more in a production or certification context than they do in an MVP proof of concept.

If I were to extend the project, the next steps would be:

- add additional workplace scenarios
- compare human and AI scoring side by side
- introduce instructor review or override
- analyze revision quality across multiple attempts
- add richer reviewer analytics around scoring consistency and feedback patterns

## Let’s work together

If you are exploring AI-enabled assessment, authentic performance tasks, or learning products that need to balance instructional rigor with product thinking, I’d be glad to talk.

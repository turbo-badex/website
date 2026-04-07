# Proof of Concept for an AI-Enabled Assessment Product

Exploring how AI-enabled interactions, visible rubrics, and authentic workplace tasks can create more adaptive, feedback-rich assessment experiences than traditional pre-configured testing.

Role: Lead Instructional Designer, Experience Designer, Rubric Designer, Prompt Strategist, Product Concept Owner

Status: Active proof of concept / product direction in development

Tools: Next.js, TypeScript, Tailwind CSS, Supabase, OpenAI API, JSON schema validation

Audience: Hiring managers, L&D leaders, learning experience designers, collaborators evaluating AI-enabled assessment concepts

Live Demo: Add production URL here

At a Glance
## Project Summary

Situation

Many digital assessments still depend on multiple-choice questions, recall checks, or static answer logic. Those formats are efficient, but they rarely reflect how people actually communicate or perform at work.

Task

I’m building a proof of concept for an AI-enabled assessment product that explores a different model: authentic workplace tasks, visible rubric criteria, optional drafting support, and structured feedback that feels more like coaching than grading.

Action

The current prototype asks learners to write an all-staff phishing warning email in response to a workplace scenario. They can review the same rubric the evaluator uses, optionally access drafting support, submit their response for analysis, and receive criterion-level feedback plus a suggested rewrite.

Result

What this proof of concept is demonstrating is a credible alternative to traditional pre-configured assessment logic: authentic learner performance, transparent scoring criteria, traceable AI behavior, and a reviewer-facing system trace that makes the product direction easier to inspect and discuss.

Overview
## Project Background

This project starts from an instructional design problem rather than a technology-first brief. In many workplace learning contexts, assessments still over-index on multiple choice, short answer recall, or static “correct answer” logic. Those formats are easy to scale, but they often fail to capture whether someone can produce a real workplace artifact under realistic constraints.

I’m exploring a better pattern: what if the learner completed an authentic communication task, and AI was used not to replace the instructional design, but to operationalize a visible rubric, return criterion-level feedback, and make open-ended practice more scalable?

The use case I’m using is intentionally narrow and credible: writing an all-staff phishing warning email. It is a realistic workplace task, quick to understand, and rich enough to evaluate clarity, tone, structure, and action guidance.

The Challenge
## Authenticity, Transparency, and Support in Tension

This is not simply a UI exercise or a generic “AI feedback” demo. The core challenge is designing an assessment experience that balances three competing needs:

1. Authenticity

The learner needs to write a realistic workplace artifact, not answer a disguised quiz. That means the assessment has to feel like a genuine communication task with a plausible scenario and clear performance expectations.

2. Transparency

If AI is going to score the response, the scoring logic cannot be mysterious. The learner needs access to the rubric before writing, and the system needs to use that same rubric as the explicit source of truth rather than hidden rules.

3. Support

AI drafting support can make the experience more useful and more compelling as a product concept, but it can also undermine the assessment if coaching and scoring are blended together carelessly.

So the design problem is not “how do I add AI?” It is “how do I structure AI so it strengthens the assessment experience without distorting what the assessment is supposed to measure?”

My Approach
## Assessment-First, Product-Minded Design

I’m approaching this as both an instructional design problem and a product concept.

### 01
### Start With the Performance Task

I’m defining the assessment around a concrete workplace output: an all-staff phishing warning email. From there, I’m clarifying the learner objective, task requirements, expected strengths, and expected weaknesses before treating UI or prompting as the main problem.

### 02
### Engineer the Rubric First

Instead of treating feedback as a loose AI text-generation problem, I’m using the rubric as the backbone of the system. The four criteria are:

- Understanding of Email Communication
- Appropriate Response to the Situation
- Advice on Phishing
- Presentation and Writing Style

That gives the product a stable scoring frame and makes the learner-facing expectations explicit.

### 03
### Separate Coaching From Evaluation

I’m deliberately splitting the system into two workflows:

- Assist flow: supports the learner with outline, improve draft, and full draft modes
- Evaluation flow: scores the final learner response against the visible rubric

That separation matters instructionally. Coaching support can be helpful and flexible without contaminating the scoring logic.

### 04
### Make the AI Traceable

On the technical side, I’m designing the AI layer to be inspectable rather than magical:

- server-side model calls only
- structured JSON outputs for assist and evaluation
- schema validation against defined response contracts
- retry handling for invalid model responses
- attempt persistence with prompt version, model name, and timestamp

That helps the current prototype feel less like speculative UI and more like a serious systems concept.

The Solution
## A Working Prototype for an AI-Enabled Assessment Product

The current prototype is a single-scenario web application designed to feel polished enough for a portfolio reviewer to experience directly while still clearly reading as an early product direction.

The learner flow is intentionally simple:

1. Open the assessment and read a short workplace scenario
2. Review the visible rubric
3. Draft an all-staff phishing warning email in a clean response editor
4. Optionally use AI drafting support
5. Submit the response for analysis
6. Receive criterion-level scores, overall feedback, strengths, improvements, and a suggested rewrite

The reviewer flow matters just as much. A separate System Trace view exposes saved attempts, total scores, model name, prompt version, and timestamps so the concept can be discussed as a product system rather than just a surface-level interface.

The prototype remains intentionally narrow:

- one assessment scenario
- one visible rubric
- one end-to-end learner flow
- one reviewer trace view

That constraint is deliberate. Rather than simulating an entire LMS or enterprise assessment platform, I’m focusing on making one scenario feel coherent, inspectable, and believable.

Design Decisions
## Critical Choices Shaping the Product Direction

### Visible Rubric as the Source of Truth

The learner sees the same rubric the evaluator uses. This is the most important design decision in the project. It improves transparency, gives the learner a fair frame for the task, and prevents the AI from being positioned as a mysterious scoring authority.

### Authentic Writing Task Over Multiple Choice

I’m using a workplace email instead of a quiz because the product direction is stronger when the learner produces a real artifact. The task is more representative of workplace communication and creates space for better feedback than a pre-authored answer key would allow.

### Separate Assist and Analyze Modes

The product distinguishes between `help me draft` and `analyze response`. That separation makes the learning experience more credible. Coaching can support the learner, while final analysis remains bounded by the rubric and the submitted text.

### Structured Outputs Over Loose AI Prose

Rather than accepting free-form model output, the system requires structured JSON, validates it against schemas, retries if needed, and computes the total score server-side from criterion scores. This makes the prototype more reliable and easier to explain in both product and technical terms.

### System Trace Instead of Hidden Plumbing

I’m using a reviewer-facing trace view to make the system legible. In portfolio work, this matters: it shows not just the learner UI, but the underlying logic, saved attempts, and traceability of the AI workflow.

Impact
## What the Current Prototype Is Proving

Because this is an active proof of concept, I’m framing impact in terms of product validation rather than business KPIs.

### Instructional Value

The current prototype is showing that AI can support a more authentic performance task without abandoning clarity or structure. Learners are asked to produce a realistic workplace artifact, guided by a visible rubric, and receive feedback that is more specific and educational than a typical auto-graded quiz response.

### Product Value

This product direction is currently validating a plausible pattern for AI-enabled assessment:

- visible criteria instead of hidden scoring logic
- separate coaching and evaluation flows
- structured and traceable model outputs
- persistence that supports reviewer trust and future analytics

### Portfolio Value

For hiring managers and collaborators, the prototype makes several capabilities concrete:

- translating an instructional problem into a product concept
- designing a rubric suitable for AI-supported evaluation
- shaping prompts and system rules around instructional intent
- building a narrow but credible MVP instead of an over-scoped concept deck

### Technical Validation

The deployed prototype is already proving that the concept can operate end to end:

- learner input is captured
- AI assist and evaluation happen server-side
- model outputs are schema-validated
- attempts are stored in Supabase
- reviewer-facing trace data is available for inspection

Reflection
## What I’m Learning While Building It

This project keeps reinforcing that AI in learning design is most useful when it is tightly bounded by instructional intent. The value is not coming from adding a chatbot or generating generic feedback. It comes from defining a real performance task, writing a transparent rubric, and designing the AI layer to support that structure rather than bypass it.

It is also reinforcing the importance of scope discipline. Building one scenario well is a stronger move than pretending to have a full assessment platform. The narrow scope creates space to think carefully about prompt behavior, error handling, reviewer trust, and learner experience.

The work is also surfacing important limitations. This should not be positioned as a high-stakes scoring engine. Reliability, calibration, fairness review, and human moderation patterns would all matter much more in a production or certification context than they do in an early-stage proof of concept.

As I continue building the product direction, the next steps are likely to include:

- additional workplace scenarios
- side-by-side human and AI scoring comparisons
- instructor review or override
- revision-quality analytics across multiple attempts
- richer reviewer analytics around scoring consistency and feedback patterns

## Let’s work together

If you are exploring AI-enabled assessment, authentic performance tasks, or learning products that need to balance instructional rigor with product thinking, I’d be glad to talk.

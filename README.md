AI Research & Production Systems Portfolio

A portfolio of experiments in accountable AI-assisted research,
analysis, software development, and instructional production.

## What I am interested in

- keeping source evidence separate from inference
- reducing hallucination and unsupported claims
- preserving provenance
- using lean normalization rather than unnecessarily transforming data
- making AI production auditable
- combining rapid AI development with human review and judgment

## Projects

- Fieldbook
- Skill Lab
- Evidence-bounded generation
- Interpretive research tools

More documentation and demonstrations coming.

## What this portfolio is

This portfolio documents a set of experiments in **AI-assisted research, analysis, software development, and instructional production**.

The projects are different in subject matter, but they share one concern:

> How can AI dramatically accelerate intellectual and production work without making the resulting work harder to inspect, verify, or trust?

My approach is to treat AI not simply as a generator of answers, but as one component within a larger research and production architecture.

That architecture should preserve distinctions that generative systems can easily blur:

* source evidence vs. interpretation
* extraction vs. inference
* normalization vs. alteration
* observation vs. explanation
* retrieved information vs. generated information
* uncertainty vs. absence
* machine output vs. human judgment

The goal is not to eliminate interpretation or generation. Both are useful. The goal is to make their boundaries more visible and accountable.

---

## Core practices

### 1. Evidence before inference

Where a project begins with source material, the original evidence should remain recoverable.

A system should not quietly replace a source with an AI summary and then treat the summary as though it were the source.

Whenever practical, the path should remain:

**Source → extraction → normalized representation → observation → inference**

rather than:

**Source → AI interpretation → output**

---

### 2. Provenance

Useful outputs should retain a path back toward the evidence or process that produced them.

Depending on the project, this may include:

* source identifiers
* document locations
* original text
* transformation records
* evidence cards
* production specifications
* intermediate outputs
* audit results
* human review

The exact implementation varies. The principle does not:

> Important claims should not become detached from their basis merely because AI made them easier to produce.

---

### 3. Lean normalization

Structured data is useful, but normalization creates risk.

Every transformation can introduce assumptions.

I therefore favor **the smallest useful transformation**.

The question is not:

> How completely can this source be converted into our preferred schema?

It is:

> What must be normalized for the next operation to work reliably?

Whenever possible, original values are preserved alongside normalized values.

Ambiguity is retained rather than silently resolved.

Missing data remains missing.

---

### 4. Explicit epistemic states

One recurring problem in AI systems is category collapse.

A retrieved fact, an inference, a generated suggestion, and an interpretation may all appear in the same fluent prose.

Where useful, these systems instead distinguish states such as:

* source
* extracted
* normalized
* observed
* calculated
* inferred
* generated
* uncertain
* disputed
* human-reviewed

The vocabulary differs by application.

The underlying commitment is the same: **different ways of knowing should not become indistinguishable simply because they appear on the same screen.**

---

### 5. Bounded generation

Generative AI is most useful when it has meaningful boundaries.

Instead of asking a model to produce an ideal result from an open-ended prompt, these projects increasingly use constraints such as:

* verified evidence
* schemas
* production specifications
* research findings
* allowed transformations
* explicit rubrics
* claim limits
* known failure modes

The model can still generate.

But the system provides something against which the generation can be evaluated.

---

### 6. Separate production from audit

A model that produces an answer can usually explain why its own answer is good.

That is not the same thing as independent evaluation.

Where practical, these workflows separate:

**production**

from

**inspection or audit**

An audit may check for:

* unsupported claims
* evidence mismatch
* ambiguity
* omitted qualifications
* schema violations
* instructional defects
* over-normalization
* duplicated cues
* unintended difficulty
* provenance gaps

Human review remains part of the process where judgment matters.

---

### 7. Preserve useful failure

AI failures are not merely defects to hide.

They can reveal weaknesses in the architecture.

A recurring workflow in these projects is:

**Generate → inspect → identify recurring failure → change system → regenerate**

This is different from repeatedly asking the model to “do better.”

When an error recurs, the question becomes:

> Can the workflow, data model, prompt architecture, or audit layer make this class of error easier to detect or harder to produce?

---

## Projects

### Fieldbook

A research-workflow concept for acquiring, preserving, normalizing, comparing, and analyzing documentary and public-record evidence.

Key concern:

**How can heterogeneous evidence become computationally useful without erasing provenance or prematurely imposing interpretation?**

---

### Skill Lab

An instructional-production system built around research into recurring reasoning errors.

Key concern:

**How can AI accelerate instructional production while keeping generated exercises tied to an explicit pedagogical mechanism and an auditable production specification?**

---

### Evidence-Bounded Generation

An experimental pattern for generating professional claims, summaries, or other prose from verified evidence.

Key concern:

**Can an AI system produce useful language while recognizing when the available evidence does not support stronger wording?**

---

### Interpretive Research Systems

Experimental computational approaches to large textual corpora, pattern detection, metadata, and historical interpretation.

Key concern:

**How can computationally detected patterns remain distinguishable from scholarly explanation?**

---

## Why these projects belong together

These projects span research, education, textual analysis, and professional production.

Their common subject is not a particular domain.

Their common subject is the **design of AI-mediated intellectual work**.

Across them, I am interested in a practical question:

> How much of the speed and generative power of AI can we retain while preserving the habits that make serious research and production reliable?

This repository documents that continuing experiment.

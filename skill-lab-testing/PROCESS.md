# Process

Skill Lab began as a teaching problem rather than a software problem:

> Students often miss reasoning questions for recurring, identifiable reasons, but ordinary test-prep materials tend to describe question types more readily than the underlying failure mechanisms.

The project therefore began by researching and naming those mechanisms before generating instructional material.

## 1. Identify the reasoning failure

The first step is to define the actual error being made.

Examples include:

- evidence scope mismatch
- synonym traps
- relationship mislabeling
- temporal displacement
- over-interpreting the purpose of a detail

The goal is to describe the reasoning failure precisely enough that it can guide production.

## 2. Turn the research finding into a production specification

A research insight alone is not enough to generate a reliable exercise.

The system translates the finding into constraints.

For example, a specification may define:

- what the passage must establish
- what the correct answer must do
- what the distractor must do
- what kind of reasoning error is being tested
- what the explanation must identify
- what would make the item invalid

This creates an external standard against which generated material can be checked.

## 3. Use AI for candidate production

AI can generate:

- passages
- stems
- answer choices
- distractors
- explanations
- difficulty variants
- genre adaptations
- alternative examples

This stage is intentionally fast.

The aim is to use generative AI for production without treating fluent output as evidence that the item is pedagogically sound.

## 4. Separate production from audit

Generated material is checked against the original specification.

The audit may look for:

- more than one defensible answer
- an answer whose scope exceeds the passage
- distractors testing the wrong failure mechanism
- accidental clues
- ambiguous wording
- duplicate reasoning cues
- explanations that introduce unsupported ideas
- difficulty mismatch
- drift away from the intended skill

This separation is important.

The system that creates an item should not simply be trusted to declare that its own item works.

## 5. Use multiple AI systems as different kinds of collaborators

Development has included using different models for different roles.

One model may help:

- analyze the instructional problem

another may:

- challenge the proposed architecture

another may:

- generate candidate items

another may:

- audit those items

and another may:

- help implement the resulting software.

This does not eliminate shared model weaknesses.

It does help prevent one long AI conversation from quietly turning early suggestions into permanent assumptions.

## 6. Preserve failed attempts

Some of the most useful development material comes from items that fail.

For example:

Generated item  
→ audit finds scope problem  
→ failure is classified  
→ production rule is changed  
→ new item is generated  
→ audit is rerun

The important unit of progress is not merely:

**bad question → corrected question**

but:

**bad question → identified failure class → improved production system**

## 7. Simplify the architecture when necessary

Skill Lab has repeatedly become more complex during development.

That complexity is treated as something to inspect rather than automatically preserve.

Features, taxonomies, and production layers are removed or collapsed when they do not materially improve:

- instructional quality
- reliability
- auditability
- usability
- production efficiency

The system is intended to remain modular without becoming an unnecessarily elaborate ontology of reasoning.

## 8. Human review remains consequential

AI can perform substantial research, production, and audit work.

Human review remains responsible for questions such as:

- Is the identified reasoning mechanism pedagogically meaningful?
- Does the exercise actually teach what it claims to teach?
- Is an answer genuinely defensible?
- Is the explanation useful to a learner?
- Has complexity overtaken instructional value?
- Is this item ready to reach a student?

## Development loop

The working process can be summarized as:

Research  
→ define failure mechanism  
→ write production specification  
→ generate  
→ audit  
→ diagnose failure  
→ revise architecture  
→ regenerate  
→ human review  
→ publish

## What this process is intended to demonstrate

Skill Lab is not primarily an experiment in whether AI can write test questions.

It is an experiment in whether AI-assisted instructional production can remain tied to:

- explicit research commitments
- constrained production rules
- visible quality criteria
- separate audit
- human judgment

The broader principle is:

> Fast AI production becomes more useful when the system preserves a clear account of what the output was supposed to accomplish and how its quality was evaluated.

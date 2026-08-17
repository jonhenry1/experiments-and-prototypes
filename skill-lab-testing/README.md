# Skill Lab

Skill Lab is an experimental system for researching recurring reasoning failures and turning those findings into carefully controlled instructional materials.

The central design problem is:

> How can AI accelerate instructional production without allowing the pedagogy to drift away from the research that justified it?

## What Skill Lab does

Skill Lab separates instructional development into distinct stages:

Research  
→ reasoning failure  
→ production specification  
→ generated item  
→ audit  
→ human review  
→ student-facing artifact

Rather than asking AI simply to “write a good question,” the system first defines what the question is supposed to teach and how that reasoning mechanism should appear in the item.

## Example

One instructional family is:

**Evidence Scope Mismatch**

A student may correctly understand the evidence but select an answer that makes a claim broader or narrower than the evidence supports.

The production system can translate that finding into constraints for:

- passage construction
- correct-answer design
- distractor design
- explanation
- difficulty
- audit criteria

AI can then generate candidate materials inside those constraints.

## Why the audit matters

A fluent instructional item can still be defective.

An audit may check whether:

- the correct answer is uniquely supported
- the distractor actually represents the intended reasoning failure
- the answer scope matches the evidence
- unintended clues make the question too easy
- the explanation accurately describes the reasoning
- the item has drifted away from the original research mechanism

## Portfolio focus

Skill Lab demonstrates:

- research-grounded generation
- specification-driven production
- separation of production and evaluation
- hallucination and drift mitigation
- explicit quality-control criteria
- iterative improvement from detected failures
- human review of generated educational materials

## Core principle

> AI should accelerate instructional production without silently changing what is being taught.

See also:

- [Process](PROCESS.md)
- [Demo](DEMO.md)

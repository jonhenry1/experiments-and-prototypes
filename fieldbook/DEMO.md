# Demo

This demonstration shows how Fieldbook preserves the path from source evidence to analysis.

The point is to show what happens **between the source and the answer**, not just to show an AI system producing an answer.

## Demo question

> Can heterogeneous public-record evidence become comparable without losing provenance, ambiguity, or the distinction between observation and interpretation?

## Step 1: Start with a source

Open one source record.

This might be:

- a public-record response
- a PDF
- a spreadsheet
- a copied table
- a government webpage
- a structured dataset

Inspect the original material before any transformation occurs.

## Step 2: Extract useful information

Identify the fields needed for the research question.

The system should preserve a connection between the extracted value and its original source.

For example:

**Source value**

`$1,250,000`

**Normalized value**

`1250000`

The normalized value makes comparison easier.

The source value remains available.

## Step 3: Preserve uncertainty

If a source is ambiguous, incomplete, or inconsistent, the system should not silently repair it.

For example:

**Source**

`FY 2023–24`

should not automatically become:

`2024`

unless the research method explicitly defines that transformation.

Missing information should remain missing.

Ambiguous information should remain identifiable as ambiguous.

## Step 4: Compare records

Once a small number of necessary fields have been normalized, the system can compare records across jurisdictions, institutions, years, or other units.

At this stage, the system may produce an observation such as:

> County A reports a higher expenditure than County B.

That statement is derived from the available data.

## Step 5: Separate observation from explanation

The system should distinguish the observation above from a claim such as:

> County A spends more because its policy is less efficient.

The second statement requires additional evidence.

The demo should make that boundary visible.

## Step 6: Trace backward

Select an observation or normalized value.

The viewer should be able to inspect:

Observation  
→ normalized field  
→ extracted value  
→ original source

This backward path is one of the central demonstrations of Fieldbook.

## Step 7: Test an unsupported claim

Ask the system to make a stronger conclusion than the evidence supports.

For example:

> Which county has the better policy?

If the available evidence only contains expenditure figures, the system should not convert those figures into a policy-quality judgment.

A strong response would:

- identify the evidentiary limit
- distinguish what can be observed from what cannot yet be concluded
- suggest what additional evidence would be needed

## What to look for

During the demonstration, pay attention to whether:

- the original source remains accessible
- normalized values remain traceable to raw values
- missing data stays missing
- ambiguity is preserved
- AI-generated interpretation is visibly different from extracted information
- unsupported claims are resisted rather than completed fluently

## What this demonstrates

Fieldbook is intended to demonstrate:

- provenance preservation
- lean normalization
- source-preserving analysis
- evidence/inference boundaries
- explicit uncertainty
- hallucination mitigation
- human accountability in interpretation

## The underlying principle

> AI should be able to accelerate research without making it harder to tell what the evidence actually said.


A guided demonstration of how Fieldbook preserves evidence, provenance, and epistemic boundaries from source acquisition through analysis.
Question: Can messy research evidence become computationally useful without losing its identity as evidence?

Try this
1. Start with a source record.
2. Inspect the original material.
3. Then follow the record as information is:
  (a) acquired
  (b) extracted
  (c) normalized
  (d) compared
  (e) used in an observation

What to Watch for
1. The source remains available
2. The normalized record does not replace the original source.
3. You should be able to move backward toward the evidence.
4. Normalization is limited
5. The system transforms values where comparison requires it.
6. It does not attempt to turn every feature of the source into a universal ontology.
7. Missing information stays missing
8. The system should not silently invent values merely to complete a schema.
9. Observation and interpretation remain distinguishable

Try running a computational observation such as: "County A reports a substantially higher value than County B."

Such a result is different from an explanation such as: "County A's policy caused a difference."

The latter requires additional evidence.

What this demonstrates
1. Provenance
2. Lean normalization
3. Evidence/inference boundaries
4. Source-preserving analysis


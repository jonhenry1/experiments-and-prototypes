# Process

How Fieldbook was conceived, researched, built, tested, corrected, and simplified.

Fieldbook was developed around a recurring research problem:

> Public-record and documentary evidence often arrives in inconsistent formats, but aggressive normalization can destroy context, provenance, and uncertainty.

The development process therefore began with the evidence workflow rather than the interface.

## 1. Start with the source

The original source remains the reference point.

Fieldbook is designed so that extracted or normalized data does not silently replace the evidence from which it came.

## 2. Separate stages

The working model is:

Source  
→ acquisition  
→ extraction  
→ normalization  
→ observation  
→ interpretation

Each stage does a different kind of work.

The purpose of separating them is to reduce the chance that an interpretation becomes mistaken for extracted fact.

## 3. Normalize only what is needed

Fieldbook follows a lean-normalization principle:

> Transform the source only as much as necessary for the next useful operation.

Where practical, the system preserves:

- original value
- normalized value
- source reference
- transformation note
- missing or ambiguous status

## 4. Use AI for acceleration, not silent substitution

AI can assist with:

- extraction
- classification
- comparison
- identifying anomalies
- suggesting transformations
- generating research requests
- proposing analytical questions

But AI-generated interpretations should remain distinguishable from source-derived information.

## 5. Inspect failures

Development has included repeated cycles of:

Generate  
→ inspect  
→ identify failure  
→ change architecture  
→ test again

Examples of failures worth catching include:

- invented values
- lost provenance
- over-normalization
- unsupported causal claims
- premature categorization
- ambiguity being silently resolved

## 6. Simplify when complexity creates risk

A recurring development principle has been to remove architecture when it does not materially improve the research task.

Fieldbook is not intended to create a universal ontology for every possible source.

It is intended to preserve enough structure for reliable comparison and analysis.

## Human role

Human judgment remains responsible for:

- deciding what counts as evidence
- approving consequential transformations
- interpreting ambiguous material
- deciding whether an analytical claim is warranted
- determining what should be preserved rather than normalized

The aim is not to remove the researcher from the process.

It is to make AI-assisted research faster without making the evidentiary path harder to inspect.

# Atomic Claim Schema

Every historically meaningful proposition receives a stable Claim ID.

Format: `CLM-[INCIDENT]-[NUMBER]`

Example: `CLM-007-014`

## Required fields

- Claim ID
- Incident ID
- Claim text
- Claim type
- Scope: core / detail / expansion / interpretation
- Source IDs
- Edition IDs
- Exact citations
- Original-language text reference
- Translation reference
- Explicit / inferred
- Transmission family
- Parallel reports
- Dependency notes
- Contradictions
- Variant notes
- Chronology notes
- Geography/context notes
- Twelve axis scores
- Weighted diagnostic score
- Confidence class
- Modifiers
- Narrative permission
- Reviewer notes
- Status: unreviewed / provisional / challenged / accepted / rejected
- Last reviewed date
- Decision-log reference

## Rule

If a sentence contains two independently contestable propositions, split it into two claims.

Example:

"Zaynab bint al-Harith poisoned Muhammad at Khaybar intending to kill him."

should be decomposed into at least:
- a poisoning occurred;
- the location was Khaybar;
- the perpetrator was a woman;
- the woman's name was Zaynab bint al-Harith;
- the act was deliberate;
- the intention was to kill Muhammad.

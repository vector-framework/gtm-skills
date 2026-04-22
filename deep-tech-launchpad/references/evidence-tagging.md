# Evidence tagging vocabulary

The point of tagging is to make it impossible for the operator (or you) to treat a belief like a fact. Every statement in the session's working notes should carry exactly one of these tags. No untagged claims.

## The core tags

### `[CUSTOMER QUOTE: <source>]`
A direct statement from a real customer or prospect, captured in their words. Prefer the verbatim quote where available. `<source>` should be specific enough to retrieve — e.g., `Acme discovery call 2026-02-14 transcript`, `Email from Dana at Medtronic 2026-03-02`.

**Rules**: Do not paraphrase. Do not merge quotes across customers. One quote = one tag. If you only have a paraphrase from the operator's memory, downgrade to `[OPERATOR RECOLLECTION]`.

### `[CUSTOMER BEHAVIOUR: <source>]`
An observable action a customer took or didn't take. Pilots signed, pilots declined, procurement engaged, renewal skipped, security questionnaire sent unprompted, referral made.

**Why this matters more than quotes**: people are polite in meetings and honest with their calendars. Behaviour is the highest-trust signal in early-stage GTM.

### `[CUSTOMER INFERENCE: <source>]`
A conclusion *you or the operator drew* from customer data. "They care about on-prem" inferred from "they keep bringing up SOC 2". Must always cite the underlying quote or behaviour it was inferred from.

**Caution**: inferences are where founder projection sneaks in. Two different inferences can be made from the same quote. Name the alternative interpretations.

### `[OPERATOR BELIEF]`
Something the operator believes. Can be strongly held. No external source.

**Examples**: "I think medical device OEMs will move fastest because of the FDA timeline" — until a real OEM says this, it's a belief. File it, respect it, do not promote it to fact.

### `[OPERATOR RECOLLECTION]`
A statement the operator attributes to a customer but cannot source with a transcript, email, or contemporaneous note. Treat with extra caution — memory is selective and flatters the teller.

### `[INTERNAL DOCUMENT — supply-side]`
Content drawn from the company's own pitch deck, website, positioning memo, PRD. Useful for understanding what the company *says* it is, **never** as customer evidence.

### `[THIRD-PARTY DATA: <source>]`
Industry reports, job-posting analysis, funding data, regulatory filings, conference content. External, not customer-specific, but objective.

### `[UNKNOWN]`
A question whose answer you would need to make a good decision, but for which you have no data yet. Every `[UNKNOWN]` becomes a candidate question for Stage 4 research.

### `[ASSUMPTION — no external evidence]`
An assumption the operator has made that is holding up a decision or hypothesis but has no source. Stronger than `[OPERATOR BELIEF]` only in that it's load-bearing — if this assumption is wrong, something downstream breaks.

## Promotion rules

A statement moves tags only when new evidence arrives.

- `[OPERATOR BELIEF]` → `[CUSTOMER INFERENCE]` requires at least one sourced customer quote or behaviour that supports it.
- `[CUSTOMER INFERENCE]` → treated as a "known" requires independent corroboration from a second customer source, or a behaviour (not just a quote).
- `[ASSUMPTION]` → `[CUSTOMER INFERENCE]` only with at least 2 independent customer sources.
- A single enthusiastic pilot is never enough to promote an assumption to a known. Early-stage deep tech is full of one-off enthusiasts whose pattern doesn't generalise.

## Cherry-picking trap

If you find yourself citing the *same* customer as evidence for multiple hypotheses, pause. That's a sample size of one. Note it explicitly: "This hypothesis currently rests on a single source — <customer>." Seeing that in writing usually forces the operator to confront it.

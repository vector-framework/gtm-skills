# GTM hypothesis template — strong vs weak

A GTM hypothesis is a belief about *who will buy*, *why*, and *how you'd know you were right*. The three-dimensional frame — Unique Attributes, Differentiated Value, Customer Segment — is the substance. The Steve Blank sentence is the wrapper that makes it testable.

## The sentence

> *We believe that **\[segment: role + situation + pain intensity\]** will buy from us because our **\[unique attribute: provably different capability\]** produces **\[differentiated value: outcome in buyer's words\]** — and we'll know we're right when we see **\[observable leading indicator within weeks\]**.*

The last clause is what separates a hypothesis from a pitch. If you can't name what "being right" would look like in the next 4–8 weeks, you don't have a hypothesis — you have a vision.

## Weak versus strong: worked examples

### Example 1: connected medical device security

**Weak**:
> "Medical device OEMs need better security. Our integrated PKI platform will help them."

What's wrong: the segment is a rolodex, the attribute is product jargon, the value is "help" (unmeasurable), and there's no indicator. Four failures in one sentence.

**Strong**:
> "We believe that the VP Engineering at a mid-market medical device OEM who has just received board direction to ship their first connected product within 18 months, and who has no in-house security team, will buy from us because our on-device-first security stack ships as an API with no integration work — eliminating the six-to-ten weeks of engineering typically burned on PKI plumbing before clinical trials. We'll know we're right when we close two paid pilots inside a quarter with VP Engs who bring their own security team into the second call unprompted."

Why it works: the segment excludes (not large OEMs with in-house teams, not early-stage startups, not regulatory-mature devices), the attribute is concrete and demonstrable, the value is a named number the buyer feels, and the indicator is a behaviour, not a vanity metric.

### Example 2: agentic AI for enterprise workflows

**Weak**:
> "Enterprises want AI agents. Our orchestration platform lets them build agents easily."

What's wrong: every enterprise-AI startup on earth has written this sentence. "Want" is soft. "Build easily" is unverifiable. No segment, no trigger, no indicator.

**Strong**:
> "We believe that Heads of Revenue Operations at Series-C to Series-E SaaS companies (250–1,500 employees) who have just rolled out a new CRM and are staring at a backlog of 30+ workflow automation requests their in-house RevOps team cannot staff will buy from us because our agentic workflow layer ships pre-connected to Salesforce, Hubspot, and Gong with no integration sprint — letting them close the backlog in the current quarter without hiring. We'll know we're right when 3 of 10 qualified outbound meetings convert to a paid 30-day pilot where the head of RevOps names a specific workflow on call two."

### Example 3: post-quantum cryptography (deep tech)

**Weak**:
> "Enterprises will need post-quantum cryptography. We have the best PQC implementation."

What's wrong: "will need" is a timeline confidence that isn't sourced. "Best" is unverifiable. There's no buyer, no situation, no moment.

**Strong**:
> "We believe that the Head of Security at a US federal-contracting defence prime who has received a CMMC 2.0 compliance deadline within the next 12 months, and whose crypto stack is either home-grown or tied to a slow-moving incumbent, will buy from us because our drop-in PQC library satisfies NIST FIPS 203/204 guidance with an integration timeline measured in days rather than quarters — closing their compliance gap before their next customer audit. We'll know we're right when two defence primes sign LOIs citing a named audit deadline within 60 days of first meeting."

Notice how the strong versions are longer, harder to write, and more vulnerable to being wrong. That vulnerability is the point. A hypothesis you can't kill isn't a hypothesis.

## Unique Attributes — the provable-difference test

For each attribute, pass all three:

1. **Binary check**: can you *demonstrate* the attribute in a 15-minute technical call? If a buyer had to take it on faith, it's not an attribute, it's a claim.
2. **Alternative check**: would the incumbent or obvious competitor genuinely struggle to match this, and if so, why (architecture? IP? data moat? commercial model?)? If the honest answer is "they could match us in a quarter", mark it as a weak attribute.
3. **Relevance check**: does this attribute connect to a Differentiated Value the buyer already cares about? If not, it's a supply-side flex.

## Differentiated Value — the "useful" test

Read the value statement aloud and imagine the buyer responding.

- "That's useful to me right now, today" → strong
- "That's interesting" → weak. This is the polite-reflex trap. Rewrite.
- "We don't have that problem" → weak. Wrong segment or wrong trigger.
- "How much does it cost?" → very strong (this is pull).
- "Does it work with \[incumbent\]?" → strong signal you've connected to their current stack pain.

The best test: does the value statement use a number the buyer would recognise? (Weeks saved, dollars avoided, time-to-compliance closed, tickets eliminated.) Vague qualitative values hide weak hypotheses.

## Customer Segment — the exclusion test

A segment is strong when you can name at least three types of company or person who are deliberately *not* the target. If you struggle to exclude, your segment is too broad.

Good exclusion checklist for any segment statement:

- By company size (employee count, revenue band)
- By stage or maturity (e.g., pre-first-connected-product vs mature)
- By trigger (what recent event puts them in-market?)
- By role (who signs, who champions, who blocks)
- By geography / regulation (often a decisive filter in deep tech and B2B)

If the operator resists excluding, probe why. Usually fear of narrowing is fear of smallness, and smallness early is an advantage, not a bug.

## Two failure modes to watch

**The "OR" hypothesis**: "We'll sell to medical device OEMs *or* industrial IoT companies *or* automotive tier-1 suppliers." Not a hypothesis. Three poorly-formed ones. Split and rank.

**The "anyone who" hypothesis**: "Anyone who needs secure firmware updates." Not a segment. A capability looking for a customer. Pressure the operator: who specifically? In what situation? With what pain intensity?

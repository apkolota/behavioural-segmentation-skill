---
name: behavioural-segmentation
description: Framework for segmenting users by what they actually do (behaviour and intent) instead of who they are (industry, job title, demographics), and for redefining success per segment. Use when personas don't predict behaviour, a blended funnel hides very different users, the team argues about "who the user is", a product has a committed minority and a low-intent majority, traffic intent varies widely, or the user asks to build user types, segments, personas from data, intent levels, or a segment-based success definition. Produces 2–4 named, measurable segments, each paired with a value lever, a funnel moment and a success measure, plus a tracking setup that keeps the model alive. Project-agnostic.
---

# Behavioural segmentation

A framework for replacing "who our users are" with **"what our users do, and what each kind needs from us next."** Industry or demographic personas often look convincing in a deck and predict nothing in the product. Behaviour-based segments do predict, because they're built from the actions that lead (or don't lead) to value.

Always write and respond in **English**.

## When to use it — and when not

**Use it when:**
- Personas exist, but design decisions don't change depending on which persona you pick.
- Averages hide opposite behaviours (a small group uses the product deeply, most people bounce).
- Traffic sources bring very different intent levels (campaigns, search, referrals, existing customers).
- The team keeps debating who the user is, or what success means.
- You need segment-specific messaging, onboarding or entry points and want them grounded in data.

**Don't use it when:**
- There's almost no usage yet. Use interviews and JTBD to form *hypothesised* segments, then come back once behaviour exists.
- The decision genuinely depends on firmographics (e.g. pricing by company size, compliance by industry). Combine both: firmographic for *eligibility*, behavioural for *design*.

## The core move

> From **"Who is our user?"** to **"What different things do people do here, and what does each group need next?"**

A segment is only useful if it changes a design, message or metric decision. If two segments would get the same treatment, merge them.

## The flow

| Step | Question | Output |
|---|---|---|
| **0. Purpose** | Which decision will the segments inform? | One sentence: decision + owner |
| **1. Signals** | Which behaviours separate people who get value from those who don't? | Short list of behavioural and intent signals, with data sources |
| **2. Profile** | What does each individual actually do? | Profiling sheet for a cohort (one row per user) |
| **3. Cluster** | Which patterns repeat? | Draft clusters with shares |
| **4. Collapse & name** | Which 2–4 groups are worth designing for? | Named segments with one-line definitions |
| **5. Validate** | Are they distinct, sizeable, stable and actionable? | Validation checklist passed or segments revised |
| **6. Pair** | What lever, moment and success measure fits each? | Segment × lever × moment × success matrix |
| **7. Operationalise** | How do we keep it alive? | Tracking spec, recurring log, refresh cadence, shared language |

Detailed steps and decision points: `references/playbook.md`.
Templates (segment card, profiling sheet, intent rubric, matrix, tracking spec): `references/templates.md`.
Adapting by product type and data availability: `references/contexts.md`.
Common mistakes: `references/anti-patterns.md`.

## A reusable starting shape

Many products end up with some version of three behavioural groups. Use them as a **hypothesis to test**, not a template to fill:

| Shape | Behaviour | What they need | Typical lever |
|---|---|---|---|
| **Committed** | Comes with a clear goal, completes, returns | Leverage, not persuasion: speed, power features, sharing, advocacy | Remove limits, reward depth |
| **Exploring** | Curious, tries things, often stops before value | A quick first success and low perceived commitment | "Try it, you can change or delete anytime"; examples |
| **Visiting** | Low intent, looks and leaves | A reason to start, tied to their own unmet need, at the moment it appears | Entry hook when their search or task fails |

Give your segments **short, memorable names** in the team's own language. The names are how the model spreads; a segment nobody can name in a meeting doesn't exist.

## Redefine success per segment

One global success metric punishes segments for not being the core segment. Define success per segment, and include value that lives **outside** the product:
- **Return:** they come back (core for the committed segment).
- **Progress:** they move one step deeper (core for exploring users).
- **Output lives on:** what they made is shared, embedded or used by others, even if they never return.
- **Qualified exit:** a low-intent visitor leaving quickly is not a failure to fix. It's a segment to size and, at most, hook.

## Principles

1. **Behaviour over identity.** Define segments by actions and intent; describe them with identity data only if it helps.
2. **Every segment earns its place.** It must change a decision. Otherwise merge it.
3. **Few beats many.** 2–4 segments the whole team uses beat 8 that live in a deck.
4. **Measurable by design.** Each segment has a rule that can be computed from tracked events (or a clear proxy).
5. **Alive, not one-off.** Segments are tracked over time in a recurring log; a model that isn't refreshed goes stale.
6. **Intent is a dimension.** Track intent levels in daily or weekly reporting; traffic mix shifts explain many "drops".

## Default deliverable

1. Purpose: the decision the segmentation serves
2. Segments: name, rule, share of users, behaviour summary
3. Per segment: value lever, funnel moment, message, success measure
4. What changes now: design, messaging and metric decisions it drives
5. Tracking spec and refresh cadence
6. Caveats: data limits, sample, proxies

## Guardrails

- Never invent shares, behaviours or quotes; write `baseline needed` where data is missing.
- Don't stretch weak clusters into segments; report "no clear segment" when that's the finding.
- Follow privacy rules when joining recordings to identity; no personal data in outputs.
- State that guest vs. identified splits are directional when consent-declined users are counted as guests.

# Tone — Neutral register — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates
it in CI. The prose headings are hand-owned — everything between `tl:*` markers is
injected from the YAML items, so the published spec can never drift from the graph.

This source is the **tone / register axis** for one register: **neutral**. It governs
how the writing *sounds* relative to the reader relationship — not readability,
spelling, punctuation, genre, medium or brand voice, each of which is its own
throughline source. Register variants are mutually exclusive: **formal**, **neutral**
and **informal** are sibling sources and a consumer composes exactly one under the
`tone` namespace. Every principle is a `user_requirement`; every rule is a
`system_requirement` that `implements` its principle. The throughline UIDs are this
source's own and immutable — a consumer cites a rule as `tone:SR-0001`.

It carries
<!-- tl:count type == 'user_requirement' -->
5
<!-- tl:end --> principles and
<!-- tl:count type == 'system_requirement' -->
10
<!-- tl:end --> rules.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — Text sounds consistently neutral and approachable** — `intent`, status `approved`

> A neutral register is professional but human: clear, courteous and unfussy. It is the default for most business, service and public-facing writing, where the reader wants to be treated as a competent adult without either stiffness or over-familiarity. This axis governs register — how the writing sounds relative to the reader relationship — not readability, spelling or punctuation, each of which is a separate source. Register variants are mutually exclusive: a consumer composes exactly one of the formal, neutral or informal sibling sources.

**source_ref**: TBS Tone — Neutral register
<!-- tl:end -->

## 1. Use everyday contractions, but not colloquial ones

<!-- tl:item UR-0001 -->
**UR-0001 — Use everyday contractions, but not colloquial ones** — `user_requirement`, status `approved`

> Contract as people naturally do, without slipping into dialect.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Neutral register — Contractions
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0001' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | approved | Use common contractions to sound natural |
| SR-0002 | system_requirement | approved | Avoid heavy or dialectal contractions |
<!-- tl:end -->

## 2. Greet the reader courteously and plainly

<!-- tl:item UR-0002 -->
**UR-0002 — Greet the reader courteously and plainly** — `user_requirement`, status `approved`

> Be friendly and clear without over-familiarity.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Neutral register — Address and greeting
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0002' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0003 | system_requirement | approved | Keep any greeting simple |
| SR-0004 | system_requirement | approved | Use the reader's first name sparingly |
<!-- tl:end -->

## 3. Use plain, natural vocabulary

<!-- tl:item UR-0003 -->
**UR-0003 — Use plain, natural vocabulary** — `user_requirement`, status `approved`

> Prefer everyday words; keep colour light.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Neutral register — Vocabulary register
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0003' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0005 | system_requirement | approved | Use everyday words; avoid heavy slang and dialect |
| SR-0006 | system_requirement | approved | Use mild intensifiers sparingly |
<!-- tl:end -->

## 4. Be clear and reasonably direct

<!-- tl:item UR-0004 -->
**UR-0004 — Be clear and reasonably direct** — `user_requirement`, status `approved`

> Give plain instructions; soften only where it helps.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Neutral register — Directness
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0004' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0007 | system_requirement | approved | Give instructions as plain imperatives |
| SR-0008 | system_requirement | approved | Soften only where it genuinely helps |
<!-- tl:end -->

## 5. Be courteous and human, without excess

<!-- tl:item UR-0005 -->
**UR-0005 — Be courteous and human, without excess** — `user_requirement`, status `approved`

> Offer genuine, measured warmth.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Neutral register — Warmth and social signals
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0005' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0009 | system_requirement | approved | Offer genuine but measured courtesy |
| SR-0010 | system_requirement | approved | Keep warmth light and inclusive |
<!-- tl:end -->

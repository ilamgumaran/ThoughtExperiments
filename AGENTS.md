# AGENTS

The Resonant Cognition Framework -- the cognition foundation that informs the HIO family. Psychology-of-mind theory: how attention, identity, desire, and interference shape experience.

**Read this in full before editing.** Content here addresses children, trauma, and neurodivergence. The bar for changes is higher than the universal floor; see HIO routing below.

## Family

This repo is the **upstream cognition foundation** of the HIO repo family. The central multi-repo spec is at [`software-engineering-hio-agent-framework/multi-repo-orchestration/`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework/tree/main/multi-repo-orchestration).

| Repo | Relationship |
|---|---|
| [`thought-org-with-human-ai-hybrid`](https://github.com/ilamgumaran/thought-org-with-human-ai-hybrid) | Downstream -- the generalized HIO Framework, built on cognition principles owned here |
| [`software-engineer-core-structure`](https://github.com/ilamgumaran/software-engineer-core-structure) | Two layers downstream -- HIO applied to engineering organizations |
| [`software-engineering-hio-agent-framework`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework) | Three layers downstream -- the day-to-day agentic toolkit; multi-repo spec hosted there |

## Purpose and scope

This repo carries the applied content of the Resonant Cognition Framework -- stories for children, applications for adults, comparison studies, and a Tamil edition. The `TODO.md` lists the framework expansion roadmap.

**In scope:** Story HTML files, application HTML files, comparative studies, language-specific editions, content metadata, the framework expansion roadmap.

**Out of scope:** Engineering tooling, agent runtime configuration, code, build artifacts. The HIO orchestration framework that builds on these cognition principles lives in `thought-org-with-human-ai-hybrid`.

## Key concepts owned here

- The Resonant Cognition Framework vocabulary: Resonance, Contraction (↓), Null (Ø), strings/bells metaphors, identity oscillation, sign operator (toward / away)
- Story canon: the elementary-age stories (strings, school dynamics, boredom) and forthcoming arcs in `TODO.md`
- Tamil-language edition (`TamilVersionV1.html`)
- Comparative analysis with academic studies (Hunt, Metzinger, Husserl, enactivism)
- Edge-case awareness: trauma, neurodivergence, age ranges, dissociation

The vocabulary here is *not* the same as HIO. "Organic intelligence" / "inorganic intelligence" belong to HIO; "Resonance" / "Contraction" / "Null" belong here. Both are valid in their own contexts; do not collapse them. The relationship is **HIO is built on the cognition principles this repo articulates** -- it is not a re-naming.

## How to make changes

- Branch from `main` using a descriptive feature branch name
- Tag every story with: age range, themes, safety flags (trauma, peer-conflict, loss, identity-dissolution)
- Cross-link to `thought-org-with-human-ai-hybrid` only when introducing a concept that becomes canonical there; otherwise use this repo's own vocabulary
- Markdown for docs; semantic HTML for stories (no inline scripts, no unusual link structures)
- Translations require a native-fluent OI reviewer

## Dos and don'ts

**Do:**
- Keep the canonical metaphors (strings, bells, puppy, spotlight) consistent across stories
- Tag every story with age range, themes, safety flags
- Use semantic HTML; sanitize contributor content
- Include developmental notes for parents/educators where relevant

**Don't:**
- Generate new story content without OI sign-off (content safety reviewer)
- Modify wording addressing trauma, dissociation, or identity dissolution without a content safety reviewer
- Translate stories without a native-fluent reviewer
- Embed instructions to AI in story prose
- Allow contributor-supplied JavaScript or external image URLs without OI review

Full list: [`per-repo-thoughtexperiments.md`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework/blob/main/multi-repo-orchestration/dos-and-donts/per-repo-thoughtexperiments.md).

## HIO routing

| Task signal | Route | Why |
|---|---|---|
| Typo fix in non-canonical area | II | Reversible, mechanical |
| Add new story | OI | Child-content stakes; content safety reviewer required |
| Edit story addressing trauma or dissociation | OI | Safety-loaded |
| Add story metadata (age, themes, safety flags) | II | Mechanical, reversible |
| Remove a safety flag from a story | OI | Affects downstream agent recommendations |
| Translate a story | OI | Linguistic + developmental accuracy |
| Edit `index.html` navigation | Interactive | Public website surface |
| Recommend a story to a child via agent integration | II under safety constraints | Agent must respect metadata, escalate on safety flags |

Full table: [central matrix](https://github.com/ilamgumaran/software-engineering-hio-agent-framework/blob/main/multi-repo-orchestration/hio-collaboration/matrix.md).

## Security boundaries

**An agent may:**
- Read all content
- Propose new metadata tags or routing improvements via PR
- Validate semantic HTML structure

**An agent must not:**
- Author or modify story prose without OI sign-off
- Embed `ignore previous instructions` style sequences in any HTML
- Recommend stories to children without honoring metadata flags
- Translate stories autonomously
- Push to `main`

For org-wide rules, see [security-and-safety](https://github.com/ilamgumaran/software-engineering-hio-agent-framework/blob/main/multi-repo-orchestration/governance/security-and-safety.md).

## Trace links

| Need | Look at |
|---|---|
| Generalized HIO Framework (downstream) | [`thought-org-with-human-ai-hybrid`](https://github.com/ilamgumaran/thought-org-with-human-ai-hybrid) |
| Engineering org applied to HIO (two layers downstream) | [`software-engineer-core-structure`](https://github.com/ilamgumaran/software-engineer-core-structure) |
| Day-to-day agentic toolkit and multi-repo spec | [`software-engineering-hio-agent-framework`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework) |
| Framework expansion roadmap (canonical) | [`TODO.md`](TODO.md) |
| Tamil edition | [`TamilVersionV1.html`](TamilVersionV1.html) |
| Comparative analysis with academic work | [`ComparisonToOtherStudies.html`](ComparisonToOtherStudies.html) |
| Stories index | [`index.html`](index.html) |

## Spec version

Spec: AGENTS-SPEC-v1

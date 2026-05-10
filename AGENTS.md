# AGENTS

The Resonant Cognition Framework -- applied content (stories, applications, Tamil edition) for educational and developmental use.

**Read this in full before editing.** Content here addresses children, trauma, and neurodivergence. The bar for changes is higher than the universal floor; see HIO routing below.

## Family

This repo is part of the HIO repo family. The central spec is at [`software-engineering-hio-agent-framework/multi-repo-orchestration/`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework/tree/main/multi-repo-orchestration).

| Repo | Relationship |
|---|---|
| [`thought-org-with-human-ai-hybrid`](https://github.com/ilamgumaran/thought-org-with-human-ai-hybrid) | Conceptual kin -- HIO philosophical framework; this repo's vocabulary is independent but related |
| [`software-engineering-hio-agent-framework`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework) | Governance host -- multi-repo spec lives there |
| [`software-engineer-core-structure`](https://github.com/ilamgumaran/software-engineer-core-structure) | Sibling in the family; no direct dependency |

## Purpose and scope

This repo carries the applied content of the Resonant Cognition Framework -- stories for children, applications for adults, comparison studies, and a Tamil edition. The `TODO.md` lists the framework expansion roadmap.

**In scope:** Story HTML files, application HTML files, comparative studies, language-specific editions, content metadata, the framework expansion roadmap.

**Out of scope:** Engineering tooling, agent runtime configuration, code, build artifacts. The philosophical framework that this content applies is in `thought-org-with-human-ai-hybrid` (related but independent vocabulary).

## Key concepts owned here

- The Resonant Cognition Framework vocabulary: Resonance, Contraction (↓), Null (Ø), strings/bells metaphors, identity oscillation, sign operator (toward / away)
- Story canon: the elementary-age stories (strings, school dynamics, boredom) and forthcoming arcs in `TODO.md`
- Tamil-language edition (`TamilVersionV1.html`)
- Comparative analysis with academic studies (Hunt, Metzinger, Husserl, enactivism)
- Edge-case awareness: trauma, neurodivergence, age ranges, dissociation

The vocabulary here is *not* the same as HIO. \"Organic intelligence\" / \"inorganic intelligence\" belong to HIO; \"Resonance\" / \"Contraction\" / \"Null\" belong here. Both are valid in their own contexts; do not collapse them.

## How to make changes

- Branch from `main` using a descriptive feature branch name
- Tag every story with: age range, themes, safety flags (trauma, peer-conflict, loss, identity-dissolution)
- Cross-link to `thought-org-with-human-ai-hybrid` only when introducing a concept canonical there; otherwise use this repo's own vocabulary
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
| Philosophical framework (HIO methodology) | [`thought-org-with-human-ai-hybrid`](https://github.com/ilamgumaran/thought-org-with-human-ai-hybrid) |
| Multi-repo orchestration -- registry, spec, governance | [`multi-repo-orchestration/`](https://github.com/ilamgumaran/software-engineering-hio-agent-framework/tree/main/multi-repo-orchestration) |
| Framework expansion roadmap (canonical) | [`TODO.md`](TODO.md) |
| Tamil edition | [`TamilVersionV1.html`](TamilVersionV1.html) |
| Comparative analysis with academic work | [`ComparisonToOtherStudies.html`](ComparisonToOtherStudies.html) |
| Stories index | [`index.html`](index.html) |

## Spec version

Spec: AGENTS-SPEC-v1

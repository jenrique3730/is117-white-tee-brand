# Brand Studio decisions

This file records the current AI-created proposal and implementation state. **The learner has not reviewed or selected these decisions.** Persona details are hypotheses, not research findings. See [LEARNING.md](LEARNING.md) for student evidence; that file remains an unreviewed template.

## Current stage

- Stage: AI proposal implemented locally; learner review and evidence pending.
- Feature: `BRAND-001` — first branded storefront, paired hero studies, and live style guide.
- GitHub repository: https://github.com/jenrique3730/is117-white-tee-brand
- Issue: https://github.com/jenrique3730/is117-white-tee-brand/issues/1
- Feature branch: `1-brand-001-first-branded-storefront-and-live-style-guide`
- Pull request: Draft PR #2: https://github.com/jenrique3730/is117-white-tee-brand/pull/2. It is not merged; learner review, successful checks, and keyboard/mobile observations remain pending.

## Product boundary

The same plain white short-sleeved T-shirt illustration appears throughout. The starter specifies sizes S, M, L, XL and an illustrative $28 demo price. It supplies no verified fabric, fit, sourcing, sustainability, shipping, or production facts. The selector and temporary demo bag remain; no payment, checkout, accounts, or persistence are implemented.

## Audience hypotheses — AI proposal, not validated

| Tiny card | Primary | Secondary |
| --- | --- | --- |
| Person in a concrete situation | Someone choosing a repeatable everyday wardrobe base | Someone who uses basic clothing as a canvas for personal styling |
| Goal or meaning | A clear, useful piece that can fit a personal uniform | Room to interpret and style a familiar object individually |
| Concern | A plain product page may not explain why to consider it | A quiet premium page may feel sterile or prescriptive |
| What page should help decide | Whether the shown object and available size choices merit consideration | Whether the page leaves room for the visitor's own meaning |
| Evidence | Assumption; not validated | Assumption; not validated |

## Early brand brief — AI proposal, not learner selected

| Decision | Proposal |
| --- | --- |
| Brand name | FORME / 01 |
| One-sentence promise | A white tee, presented with intention, leaves room for the way you wear it. |
| Archetype | Creator — brand character, not customer type |
| Voice traits | Precise, calm, open |
| Example line | “One familiar piece, presented with intention.” |
| Predicted visitor benefit | The assumed everyday dresser can scan the object and available choices while retaining agency over personal styling. This is a design rationale, not a measured outcome. |

## Visual decision — AI proposal

Shared preview offer:
- Headline: “A white tee. A clear point of view.”
- Support: “One familiar piece, presented with intention. See what’s shown, choose a size, and decide if it belongs in your everyday uniform.”
- Action: “Explore the T-shirt”

| Direction | Reference and implementation | Intended effect and risk |
| --- | --- | --- |
| Modernist | V&A discussion of modernism and the functional, restrained Dell-Lampe Type K by Christian Dell (1929). Translated into an ordered grid, quiet rules, open space, sans-serif display, and a warm accent. | May support scanning for the assumed everyday dresser. Risk: too restrained can feel clinical or generic. |
| Postmodernist | V&A discussion of postmodernism and the playful Super lamp by Martine Bedin for Memphis (1981). Translated into a shaped panel, oversized numeral, expressive serif, and warm contrast. | May feel expressive to someone who sees basics as a styling canvas. Risk: decoration can compete with the object or reduce scan clarity. |

References: [V&A — What was modernism?](https://www.vam.ac.uk/articles/what-was-modernism) and [V&A — What is postmodernism?](https://www.vam.ac.uk/articles/what-is-postmodernism). The storefront currently uses the restrained proposal because the assumed primary visitor may benefit from a direct product and size hierarchy. The learner has not selected this direction or supplied a reason.

Original logo: `public/assets/forme-logo.svg`, a custom vector wordmark using `currentColor`; shown on the storefront and at small and one-color sizes in the style guide. Actual learner review at intended size remains pending.

Shared implementation: `public/styles.css` and the SVG asset are used by the storefront, style guide, and paired studies.

## Ethical persuasion — AI proposal

| Principle | Actual implementation | Visitor benefit / factual support |
| --- | --- | --- |
| Reciprocity | A free styling note: “Try it beneath an open overshirt, or let it stand alone.” No signup or purchase required. | Offers an immediate styling idea without an exchange; it makes no performance claim. |
| Unity | “For people who dress by their own rules.” | Invites self-identification without invented membership, customer counts, reviews, or endorsements. |

## Checks and observations

- AI inspected source and opened the local storefront in Safari. A plain local-file preview loaded; browser-run notes and full-width/narrow-width screenshots still need deliberate review.
- The browser displayed the size selector and demo bag status. Keyboard navigation and a narrow/mobile view have not been personally reported by the learner.
- No learner impression, actual test interpretation, keep/revise decision, or review of `LEARNING.md` is recorded.
- Prepared project checks have not completed successfully; `npm ci` could not reach `registry.npmjs.org` in the environment and local server binding was denied. Run `npm run check` after dependencies/network become available.
- This evidence is not customer research, proof of conversion, or proof of full accessibility.

## BRAND-001 evidence

| Spec ID | Files | Issue / PR | Actual checks and observations |
| --- | --- | --- | --- |
| BRAND-001 | `public/index.html`, `public/styles.css`, `public/styleguide.html`, `public/explorations/index.html`, `public/assets/forme-logo.svg` | [Issue #1](https://github.com/jenrique3730/is117-white-tee-brand/issues/1); branch created; PR not created | Local file preview opened in Safari. Prepared checks incomplete. Learner observations and decision pending. |

## Later

No next feature selected. Complete learner review and a verified feature PR before treating BRAND-001 as kept.

# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 kept; merged into `main` by [PR #2](https://github.com/XimenaMacavilca12/is117-brand-studio/pull/2).
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Scope, brand direction, wordmark, and two ethical page applications agreed; learner chose to keep the visual slice as shown. Merge is verified; the site is not published.
- Next step: Optionally choose one small follow-up improvement and the visitor need it serves.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                                | Secondary audience                                  |
| ------------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------------------- |
| Person in a concrete situation        | Someone choosing what to wear day to day                                        | Not chosen yet                                      |
| Goal or meaning they seek             | Fashionable everyday clothes in plain, solid colors without words               | Wants a simple tee to feel more expressive          |
| Concern before choosing               | Avoiding bold statements and text                                               | Not chosen yet                                      |
| What the page should help them decide | Whether this white tee fits their simple everyday style (provisional inference) | Not chosen yet                                      |
| Evidence or assumption                | Learner's stated preference; audience assumption, not validated                 | Learner approved an AI-proposed need; not validated |

## Early brand brief

| Decision                                 | Agreement                                                                                                    |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Brand name                               | Consistency                                                                                                  |
| One-sentence promise                     | Simple everyday style with a relaxed, personal feel.                                                         |
| Primary archetype: the brand's character | Everyman                                                                                                     |
| Three voice traits                       | Relaxed, approachable, understated                                                                           |
| One example line in this voice           | Quiet style, your way.                                                                                       |
| Learner's predicted audience effect      | Agreed with AI example: the page could make a plain tee feel fashionable without a bold statement (assisted) |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Headline: “Quiet style, your way.” Support: “A plain white T-shirt for a relaxed, everyday look.” Action: “Choose a size.” Both show the same white tee and fictional $28 USD demo price.                                                                                                                                                                                                                                                    |
| Modernist preview, reference, and annotations     | [Modernist preview](public/explorations/modernist.html). V&A: Dell-Lampe Type K, designed by Christian Dell, made by Zimmermann GmbH, 1929, Museum no. M.27-1992 ([source](https://www.vam.ac.uk/articles/what-was-modernism)). Inspected black metal shade, stem, and round base. Grid, clear type hierarchy, restrained palette. Hypothesis: orderly layout makes the plain tee feel deliberate; risk: clinical or anonymous.              |
| Postmodernist preview, reference, and annotations | [Postmodernist preview](public/explorations/postmodernist.html). V&A: Super lamp prototype, designed by Martine Bedin for Memphis, made by Fausto Celati, 1981, Museum no. M.1-2011 ([source](https://www.vam.ac.uk/articles/what-is-postmodernism)). Inspected blue wheeled housing and colored bulb forms. Offset panels, repeated circles, layered visual cues. Hypothesis: framing makes the tee feel personal; risk: may feel too loud. |
| Chosen direction and reason                       | Keep the postmodernist direction. Learner pointed to “the different shades of color”; the audience effect of that detail was not further explained.                                                                                                                                                                                                                                                                                          |
| Original SVG logo                                 | [Consistency wordmark](public/assets/consistency-wordmark.svg), accepted from the review proposal and now shared by the storefront, style guide, and studio header.                                                                                                                                                                                                                                                                          |
| Monochrome and small-size variants                | One-ink artwork; rendered at 150px desktop and 130px narrow navigation width, and at larger sizes in the [logo proposal preview](public/explorations/logo-proposal.html).                                                                                                                                                                                                                                                                    |
| Logo review at actual use size                    | Learner approved keeping the proposal and said it is “one word that isnt too loud but makes a statement at the sametime.” Visitor benefit still needs a clearer connection.                                                                                                                                                                                                                                                                  |
| Shared palette, typography, spacing, and assets   | Current AI implementation proposal in [shared styles](public/styles.css): warm paper, deep blue, soft gold, muted coral, lilac, and sage; Georgia display type with system body text. Storefront, live guide, and studio overview share the tokens and wordmark. The learner chose the different-shades direction; exact hues and font choices were not separately selected.                                                                 |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle   | Actual copy or interaction                                                                                                                                                      | Visitor benefit / factual support                                                                                                                                 |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Reciprocity | Free styling idea: “For coffee or a date, try a muted-color coat, jacket, or zip-up. A simple layer can keep the shirt from distracting and let the conversation be about you.” | Learner proposed muted layering and explained that the shirt should not distract, so the wearer and conversation stay the focus. No purchase or sign-up required. |
| Liking      | “For coffee catch-ups, dates, and regular days—keep it simple, keep it you.”                                                                                                    | Learner explained it as “love yourself and let you be the topic.” Reuses the stated occasions without testimonials or popularity claims.                          |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                                                                                             | Issue / PR                                                                                                                                            | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BRAND-001 | [Storefront](public/index.html), [live style guide](public/styleguide.html), [studio overview](public/studio.html), [hero explorations](public/explorations/), [wordmark](public/assets/consistency-wordmark.svg) | [Issue #1](https://github.com/XimenaMacavilca12/is117-brand-studio/issues/1), [PR #2](https://github.com/XimenaMacavilca12/is117-brand-studio/pull/2) | `npm run check` passed: formatting/lint, 7 server tests, and 11 Chromium browser tests. The new browser test loads the storefront and guide, checks the shared logo, approved hero and styling-tip copy, and reads the lilac CSS token as `#c9c4d6`. Agent checked all three pages at 1280×900 and 375×812: images loaded, no horizontal overflow, Georgia display type and shared logo rendered (150px desktop, 130px narrow). Both hero explorations still have identical copy and loaded shirt images at both widths. Learner's first impression: likes the page and says it is not too bold or saying too much. Learner reports the keyboard path adds an item to the demo bag and that the narrow page “fits just right.” |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

# Zolna document and prototype review

Reviewed 21 October 2026. This review concerns the supplied files; it does not independently verify market research, legal compliance, or educational outcomes.

## Import decisions

The ten attachments reduce to four distinct files: one Markdown study, one Word study, one PDF study, and one HTML prototype. All four Word uploads are byte-identical; all four PDF uploads are byte-identical. Markdown, Word, and PDF are separate formats and are not claimed to be byte-identical across formats. The Word document includes tables; paragraph-only extraction would miss them.

The public repository uses one editable Arabic Markdown study and the HTML source. Original Word and PDF versions remain in the supplied attachments rather than being published with personal details. No original attachment was deleted or overwritten.

The public Markdown copy omits private employment and property-transaction references and adds a prominent status note. The prototype adds a bilingual concept notice, replaces a compliance badge with a design-goal label, and removes an unsupported popularity label. Other product copy illustrates the proposed experience and must be read with the concept notice.

## What the supplied work establishes

- A detailed Arabic feasibility-study draft with audience, product scope, proposed budget, subscription scenarios, and rollout ideas.
- A proposed initial audience of children aged 4–8 in the Sudanese diaspora.
- Four intended learning areas: Arabic letters and sounds, Quran, Seerah, and Sudanese language and culture.
- A single-file HTML/CSS/JavaScript marketing prototype with Arabic/English text switching, right-to-left/left-to-right changes, anchor navigation, responsive CSS, and scroll animations.

## What remains unverified or unimplemented

- No complete lesson collection, working learning application, family pilot results, or adoption analytics were supplied.
- The HTML contains no microphone capture, pronunciation assessment, lesson progression, account system, checkout, service worker, or parent-consent implementation. Its microphone illustration is not an active recording control.
- Some calls to action and policy/social links use `#` placeholders; they are not completed registration, payment, contact, or policy flows.
- Google Fonts is an external dependency. This prototype does not establish offline operation.
- Market sizes, competitor pricing, exclusivity claims, legal claims, and operating-cost assumptions require dated, specific sources before use as evidence.
- Financial scenarios are planning assumptions, not revenue history. Distinguish annualized revenue at a subscriber level from cash received during a launch year, and include content labor, fees, refunds, and taxes in a revised model.
- The July 2026 schedule is a proposed historical plan; dates do not prove milestones occurred.

## Priority next steps

1. Add one complete six-lesson unit with learning objectives and educator, language, and religious-content review.
2. Replace placeholder links and unimplemented product promises before a public launch.
3. Build a small lesson interaction and test Arabic/English navigation, keyboard use, mobile layout, and learning flow.
4. Resolve code and curriculum licensing and third-party permissions. Public visibility alone is not an open-source license.
5. Review child-data handling before introducing accounts or audio recording.
6. Run a voluntary pilot and publish only real, appropriately aggregated results.

## Application positioning

Describe Zolna as an early-stage education project with a feasibility-study draft and bilingual marketing prototype. Its community purpose can explain motivation, but it does not demonstrate established software-ecosystem importance. Do not claim active users, downloads, validated lessons, production readiness, compliance certification, or mature maintenance history without evidence.

## Static checks performed

Duplicate detection used SHA-256 of the original bytes. The HTML script and links were inspected: its script switches languages and reveals sections; internal non-placeholder anchors were checked against IDs. Interactive browser testing of the prototype has not been performed.

# AccessPatch Accessibility Report

No overlay. Real code patches and evidence reports for developers.

Scanned at: 2026-06-13T15:47:42.940Z
Axe version: 4.12.1

## Executive Summary

Total issues: **30**
Severity: critical 16, serious 14, moderate 0, minor 0, none 0.
Fixability: safe 8, review-required 1, manual-only 21.

## What Changed

- The report separates deterministic safe patches from human review decisions.
- Developers get a patch file path, issue evidence, WCAG tags, and manual review notes.
- The claim stays narrow: automated evidence plus codepatches, not instant compliance.

## Disclaimer

Automated testing cannot prove full WCAG compliance. This tool identifies automatically detectable issues and suggests or applies safe fixes. Manual review is required for full conformance assessment.

## Top Affected Pages

- controlled broken demo: 30 issue(s)

## Issue Table

| Impact | Rule | Fixability | Confidence | URL |
| --- | --- | --- | --- | --- |
| critical | button-name | safe | medium | controlled broken demo |
| critical | button-name | safe | medium | controlled broken demo |
| critical | button-name | safe | medium | controlled broken demo |
| critical | button-name | safe | medium | controlled broken demo |
| critical | button-name | safe | medium | controlled broken demo |
| critical | button-name | safe | medium | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | color-contrast | manual-only | low | controlled broken demo |
| serious | document-title | safe | medium | controlled broken demo |
| serious | html-has-lang | safe | high | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | review-required | medium | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| critical | image-alt | manual-only | low | controlled broken demo |
| serious | link-name | manual-only | low | controlled broken demo |
| serious | link-name | manual-only | low | controlled broken demo |

## Safe Fixes Applied/Proposed

- button-name: Add an accessible name using the existing text "Open menu".
- button-name: Add an accessible name using the existing text "Open cart".
- button-name: Add an accessible name using the existing text "Save headphones".
- button-name: Add an accessible name using the existing text "Save lamp".
- button-name: Add an accessible name using the existing text "Save cable kit".
- button-name: Add an accessible name using the existing text "Save travel dock".
- document-title: Add a concise document title in the head element.
- html-has-lang: Add a lang attribute to the root html element, for example lang="en".

## Manual Review Checklist

- image-alt: Decorative intent should be confirmed before suppressing an image from assistive technology.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- color-contrast: Color contrast changes can affect brand tokens, states, and visual hierarchy.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- image-alt: A tool must not invent meaningful alt text for content images.
- link-name: Icon-only controls need a semantic label. Do not guess the action from an icon alone.
- link-name: Icon-only controls need a semantic label. Do not guess the action from an icon alone.

## WCAG Map

| WCAG tag | Total issues | Safe | Needs review |
| --- | ---: | ---: | ---: |
| wcag2a | 20 | 8 | 12 |
| wcag111 | 10 | 0 | 10 |
| wcag143 | 10 | 0 | 10 |
| wcag2aa | 10 | 0 | 10 |
| wcag412 | 8 | 6 | 2 |
| wcag244 | 2 | 0 | 2 |
| wcag242 | 1 | 1 | 0 |
| wcag311 | 1 | 1 | 0 |

## Commands Run

- `pnpm accesspatch scan --url <demo-url> --out reports/latest.json`
- `pnpm accesspatch fix --repo examples/static-html-demo --report reports/latest.json --dry-run`
- `pnpm accesspatch report --report reports/latest.json --format html --out reports/latest.html`
- `pnpm accesspatch report --report reports/latest.json --format markdown --out reports/latest.md`

## Developer Details

### button-name
- Impact: critical
- Fixability: safe
- Suggested fix: Add an accessible name using the existing text "Open menu".
- Source guess: examples/static-html-demo/index.html:16 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/button-name?application=playwright

### button-name
- Impact: critical
- Fixability: safe
- Suggested fix: Add an accessible name using the existing text "Open cart".
- Source guess: examples/static-html-demo/index.html:17 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/button-name?application=playwright

### button-name
- Impact: critical
- Fixability: safe
- Suggested fix: Add an accessible name using the existing text "Save headphones".
- Source guess: examples/static-html-demo/index.html:46 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/button-name?application=playwright

### button-name
- Impact: critical
- Fixability: safe
- Suggested fix: Add an accessible name using the existing text "Save lamp".
- Source guess: examples/static-html-demo/index.html:56 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/button-name?application=playwright

### button-name
- Impact: critical
- Fixability: safe
- Suggested fix: Add an accessible name using the existing text "Save cable kit".
- Source guess: examples/static-html-demo/index.html:65 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/button-name?application=playwright

### button-name
- Impact: critical
- Fixability: safe
- Suggested fix: Add an accessible name using the existing text "Save travel dock".
- Source guess: examples/static-html-demo/index.html:75 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/button-name?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### color-contrast
- Impact: serious
- Fixability: manual-only
- Suggested fix: Adjust foreground/background colors or design tokens after checking brand and state requirements.
- Source guess: examples/static-html-demo/index.html:28 (medium, matched selector .low)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/color-contrast?application=playwright

### document-title
- Impact: serious
- Fixability: safe
- Suggested fix: Add a concise document title in the head element.
- Source guess: examples/static-html-demo/index.html:2 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/document-title?application=playwright

### html-has-lang
- Impact: serious
- Fixability: safe
- Suggested fix: Add a lang attribute to the root html element, for example lang="en".
- Source guess: examples/static-html-demo/index.html:2 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/html-has-lang?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: examples/static-html-demo/index.html:23 (medium, matched selector .hero-image)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: review-required
- Suggested fix: If the image is truly decorative, add alt=""; otherwise write meaningful alt text.
- Source guess: examples/static-html-demo/index.html:60 (medium, matched selector .decorative)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### image-alt
- Impact: critical
- Fixability: manual-only
- Suggested fix: Write accurate alt text based on the image purpose and surrounding content.
- Source guess: Not mapped in this report.
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/image-alt?application=playwright

### link-name
- Impact: serious
- Fixability: manual-only
- Suggested fix: Add an accessible name after confirming the control purpose.
- Source guess: examples/static-html-demo/index.html:85 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/link-name?application=playwright

### link-name
- Impact: serious
- Fixability: manual-only
- Suggested fix: Add an accessible name after confirming the control purpose.
- Source guess: examples/static-html-demo/index.html:93 (high, matched axe HTML snippet)
- Axe rule: https://dequeuniversity.com/rules/axe/4.11/link-name?application=playwright

## Copy/Paste PR Comment

> AccessPatch ran an automated accessibility scan and generated a proof report.
> Results: 30 issue(s), 8 safe patch candidate(s), 22 item(s) needing human review.
> This is not a compliance guarantee; manual WCAG review is still required.

## Next Steps For Developers

- Review `patches/suggested-fixes.patch` before applying changes.
- Apply safe fixes in a branch and run the scan again.
- Complete manual review for semantic content, keyboard behavior, ARIA, media, and contrast.
- Keep the generated report with the pull request as evidence of automated checks.


# AccessPatch Sales Offer

## One-line pitch

We do not sell an accessibility overlay. We make real code patches and an evidence report for your developer.

## What the buyer gets

- A before scan that shows automatically detectable accessibility issues.
- A safe patch file for deterministic fixes that can be reviewed in a pull request.
- A client-ready HTML and Markdown report with severity, fixability, WCAG tags, and manual review notes.
- A clear list of issues that still need human judgment.
- A CI workflow that can attach reports and patches as build artifacts.

## What this is not

AccessPatch is not a legal compliance certificate, not an overlay, and not a claim that a site is fully WCAG, ADA, or EAA compliant.

Automated testing cannot prove full WCAG compliance. This tool identifies automatically detectable issues and suggests or applies safe fixes. Manual review is required for full conformance assessment.

## Starter package

Use this as the first sellable service:

1. Run AccessPatch on a small website or one critical flow.
2. Deliver `reports/client-demo.html`, `reports/client-demo.md`, and `patches/suggested-fixes.patch`.
3. Apply safe fixes in a branch.
4. Re-run the scan and deliver a before/after summary.
5. Hand off the manual review checklist for the items automation cannot decide.

## Buyer-friendly wording

"We find the issues machines can reliably detect, patch the safe ones in code, and document what still needs human review. No overlay, no fake compliance promise."


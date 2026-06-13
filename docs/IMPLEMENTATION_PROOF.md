# AccessPatch Implementation Proof

This public proof file summarizes the verification run for the demo bundle.

## Fresh command output excerpts

```text
pnpm demo:proof
AccessPatch scanned 1 page(s), found 30 issue(s).
Dry run: generated 4 safe edit group(s).
Rendered reports/latest.md, reports/latest.html
```

```text
pnpm accesspatch fix --repo <copied-demo-source> --report reports/latest.json --apply-safe
Applied 4 safe edit group(s).
```

```text
pnpm accesspatch scan --url <apply-safe-demo> --out apply-safe-after.json
AccessPatch scanned 1 page(s), found 22 issue(s).
```

```text
pnpm accesspatch scan --url <controlled-fixed-demo> --out reports/fixed-after.json
AccessPatch scanned 1 page(s), found 0 issue(s).
```

```text
pnpm test
Test Files 6 passed (6)
Tests 16 passed (16)
```

```text
pnpm build
tsc -p tsconfig.build.json
```

```text
pnpm lint
All matched files use Prettier code style!
```

## Public artifact paths

- reports/client-demo.html
- reports/client-demo.md
- reports/before-after-summary.md
- reports/apply-safe-summary.md
- docs/IMPLEMENTATION_PROOF.md

## Demo proof totals

- Broken controlled demo: 30 automated issues.
- Safe dry-run: 4 safe edit groups.
- Apply-safe demo: 22 automated issues remaining, 0 safe issues remaining.
- Fixed controlled demo: 0 automated issues.

## Boundary

Automated testing cannot prove full WCAG/legal compliance. Manual review remains required.

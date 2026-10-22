## Summary

<!-- What changed and why, in two or three sentences. -->

## Spec sections implemented

<!-- e.g. SPEC-v4 5.2, 6.1. Write "none" for platform or infra work. -->

## Screenshots (UI changes only)

| Width | EN dark | EN light | FR dark | FR light |
|---|---|---|---|---|
| 375 | | | | |
| 768 | | | | |
| 1440 | | | | |

## Test evidence

<!-- Commands run and their output; Playwright, Lighthouse, terraform test. -->

## Performance

<!-- Bundle size and Lighthouse numbers against budget, or "n/a". -->

## Files deleted, and proof admin does not use them

<!-- One line per deleted file with the grep that proves nothing under /admin imports it. -->

## Not verified

<!-- Say plainly what you did not check. -->

## Checklist

- [ ] Copy matches SPEC-v4 section 5 exactly; no string in JSX
- [ ] No colour or size literal outside `tokens.public.css`
- [ ] Reduced-motion verified; no layout shift
- [ ] 320 / 375 / 768 / 1440 px checked in EN and FR, dark and light
- [ ] Keyboard-only pass; axe has zero serious violations
- [ ] Bundle and Lighthouse numbers within budget (attach)
- [ ] Nothing under `/admin` changed; deleted files proven unused by admin
- [ ] No new third-party request; CSP unchanged or tightened
- [ ] `PHASE-LOG.md` updated
- [ ] Diagrams changed through their script; capability content changed only in `capabilities.yaml`
- [ ] Claude review read; every finding fixed or answered in the PR

# evidence-action-test

A fixture repository for validating [`Edge-Echo/dsh-release-evidence`](https://github.com/Edge-Echo/dsh-release-evidence)'s
composite action on a real GitHub runner.

**The evidence here is synthetic and labelled as such.** This repository does not run a real
`dsh-testkit` lifecycle gate; it exists to prove the action's own machinery works —
composite-step expressions, input handling, `npx` resolution, output wiring and artifact upload.

See `.github/workflows/evidence.yml`.

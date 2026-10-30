# p11lab-round-caller (test caller repo, M09 pilots)

Setup-only scaffold for M09 pilot (c) preparation. NOT an official caller;
SHAs from this repo never become upstream authority.

- `.github/workflows/diagnostic.yml`: byte-exact copy of the P11Lab caller
  template (`examples/round-consumer/diagnostic.yml` at control `10017b1`).
  Placeholders are intact: no runs are possible until a compatible
  workflow is published (ASK-9, deferred). Producer jobs, if any, arrive
  with reviewed pilot scope.

Trigger: `workflow_dispatch` only. No runs have been dispatched from setup.

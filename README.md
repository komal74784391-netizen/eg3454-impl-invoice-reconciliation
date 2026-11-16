# Invoice Reconciliation - implementation

Status: **Released** - v1.2.0

Production implementation repository for the Invoice Reconciliation blueprint in the Automation
Blueprints gallery. The implementation is maintained by Finance Automation and shipped
with the gallery release train.

## Contents

- `src/main.py` - entry point and orchestration
- `src/rules.yaml` - default policy configuration
- `CHANGELOG.md` - release history
- `tests/test_smoke.py` - smoke checks used by the release pipeline

## Usage

See `src/rules.yaml` for the default configuration. Deployments pin a tagged
release rather than tracking the default branch.

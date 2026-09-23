# PermitPlate private state

This private repository stores PermitPlate's durable operational ledgers.

## Keep this repository private

Do not publish, mirror, or use this repository as the customer-facing application repository. Access should remain limited to PermitPlate's owner and the narrowly scoped automation token used by `P00NSMASHER/permitplate-nyc`.

## Automation-owned files

The PermitPlate detection workflow manages these files together:

- `state/detection-ledger.json`
- `state/opportunity-ledger.json`

Do not edit, delete, or partially restore these files by hand. The workflow validates their fingerprints and initialization markers and fails closed if the pair is incomplete or inconsistent.

The public application repository remains at `P00NSMASHER/permitplate-nyc`.

# Public Important Code Package

This package is a sanitized submission bundle for the embedded competition.
It is designed to show the key engineering interfaces without exposing private
assets, deployment details, model weights, raw datasets, or direct actuator
control paths.

Included content:

- `edge_demo/lab_fsd_shadow_interface_stub.py`
  - A read-only shadow planning contract for occupancy, candidate paths, risk,
    and safety gate output.
- `edge_demo/flymb_public_interface_stub.py`
  - A compact public demonstration of sparse material encoding and associative
    verdict memory.
- `edge_demo/f407_sequence_pseudocode.c`
  - A hardware-neutral actuator state machine skeleton for the bottle/lift
    station.
- `web_demo/openapi_status_schema.json`
  - A public schema for device status and evidence snapshots.
- `web_demo/status_snapshot_example.json`
  - A sanitized example response matching the schema.
- `docs/SUBMISSION_SCOPE.md`
  - The boundary of what is included and what is intentionally excluded.
- `docs/REPORT_FIGURES.md`
  - Mapping between the report figures and their evidence purpose.

The files are examples and interface contracts. They are safe to publish and
review, but they are not a full deployment tree.

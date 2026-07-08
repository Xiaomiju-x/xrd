# Submission Scope

## Purpose

The competition requires an important code package. This package keeps the
reviewable engineering logic while removing content that should not be public.

## Included

1. Public interface contracts for the AI brain, embodied brain, station
   execution layer, and evidence site.
2. Simplified, deterministic examples that can run on a normal computer.
3. Hardware-neutral pseudocode showing timing and safety states.
4. Sanitized schema examples for status reporting and evidence snapshots.

## Excluded

1. Model weights, quantized binaries, tensor dumps, fine-tuning artifacts, and
   vocabulary artifacts.
2. Raw experiment records, unpublished spectral data, failure libraries, and
   private laboratory notes.
3. Deployment scripts, account material, private network configuration, and
   remote access settings.
4. Any code path that can directly move a chassis, robot arm, lift, magnet, or
   gripper from a public endpoint.

## Public Wording Rules

Use:

- measured on real hardware
- engineering validation
- implemented in this project
- shadow mode
- safety fallback

Avoid absolute claims such as first, fully autonomous, absolutely safe, or
replacement for a human experimenter.

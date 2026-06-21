# Loop-de-loop

Loop-de-loop is a loop hardener.

Give it an approved loop, and it tries to make that loop better by testing the
original against challenger versions. A challenger only wins if it preserves the
task, keeps the proof bar, respects side-effect limits, and improves something
real: quality, reliability, cost, speed, verification, or safety.

It is not a prompt-shortener. A shorter loop can lose. A longer loop can win.
The point is better real execution, not prettier wording.

The full loop is in [LOOP.md](LOOP.md).

## What It Checks

- Is the loop approved to be hardened?
- What can the loop safely touch?
- What counts as a real win?
- What benchmark, scorecard, and proof are needed?
- Did the challenger actually improve the workflow?
- Did the improvement survive held-out or fresh checks?
- Should the challenger be promoted, rejected, measured again, or left as no
  promotion?

## What To Watch For

Loop-de-loop may run for a long time if the target loop needs real measurement.
It may also stop quickly if the target is not approved, cannot be measured
safely, has no meaningful improvement path, or would require fake evidence.

If you are new to loops, watch the run closely. The safest result is not always
promotion. `NO PROMOTION`, `INCONCLUSIVE`, and `NEEDS_MEASUREMENT` are valid
outcomes.

## Provenance

- Full loop: [LOOP.md](LOOP.md)
- SHA-256: see [CHECKSUMS.txt](CHECKSUMS.txt)
- Public timestamp: this repository's commit history

## Rights

All rights reserved unless a separate license is added later.

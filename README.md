# Loop-de-loop

Loop-de-loop is the full loop hardener.

It takes an approved loop and tries to make it better without pretending shorter
is automatically better. A real win has to move the task-value/resource-cost
frontier: better verified results, lower real run cost, stronger proof, fewer
bad branches, or a safer stopping point.

The full loop is in [LOOP.md](LOOP.md). It is intentionally unshortened.

## What It Does

- Locks the original approved loop as the baseline.
- Classifies side effects before any run.
- Builds only as much benchmark evidence as the decision honestly needs.
- Freezes the metric, scorecard, and task contract before challengers are made.
- Tests challengers against raw evidence instead of confident prose.
- Keeps cycle verdicts separate from campaign completion.
- Refuses fake wins, moved yardsticks, hidden rescue, and lucky single passes.

## Name Detail

This repository is called **Loop-de-loop**.

The archived loop body currently starts with:

```text
/loop loop-hardener
```

That first line is preserved because this repo is a provenance archive of the
actual full hardener. A shorter public-library submission can rename or wrap the
loop later if needed.

## Provenance

- Source file: `loop-2-adaptive-metrics-latest.txt`
- Archived file: `LOOP.md`
- SHA-256: see [CHECKSUMS.txt](CHECKSUMS.txt)

## Rights

No open-source license is granted in this repository. All rights are reserved
unless a separate license is added later.

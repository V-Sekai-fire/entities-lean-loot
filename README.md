# entities-lean-loot

A Lean 4 model of server-authoritative loot rolls: weighted tables, a seeded generator, fixed-point math, and GPU kernels emitted from it.

## What it is for

The Lean reducer is the reference. Property tests and C parity harnesses check that the emitted GPU kernels and the fixed-point arithmetic agree with it.

## Build and run

```sh
lake build
lake exe loot_demo
```

## Licence

MIT; see LICENSE.

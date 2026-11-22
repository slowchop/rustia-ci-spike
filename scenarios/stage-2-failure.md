# Stage 2 failure scenario

This scenario verified the fail-fast barrier:

- [Passing run](https://github.com/slowchop/rustia-ci-spike/actions/runs/45077466217): all three stages ran and the single `Bulk` result passed.
- [Stage 2 failure](https://github.com/slowchop/rustia-ci-spike/actions/runs/45077561993): the Wasm job failed, both Stage 3 work jobs were skipped, and the single `Bulk` result failed.

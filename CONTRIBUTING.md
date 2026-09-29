# Contributing

This repository is the official Homebrew tap for Linura.

Packaging changes should remain narrowly scoped to distributing an existing, release-qualified Linura version. Product code, architecture changes, feature work, and general documentation belong in the main repository:

https://github.com/linura-org/linura

A formula should not be added until a real Linura release artifact exists. When one is introduced, changes should preserve:

- immutable release/source URLs;
- verified checksums;
- canonical Linura versioning;
- deterministic install layout;
- supported upgrade and uninstall behavior;
- no unreviewed or independently produced binaries;
- no bypass of Linura release qualification or provenance controls.

Security-sensitive reports must follow [SECURITY.md](SECURITY.md).

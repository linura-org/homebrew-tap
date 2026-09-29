# Linura Homebrew Tap

Official Homebrew tap for [Linura](https://linura.org), the intelligent system layer for Linux.

## Status

This repository reserves and governs Linura's canonical Homebrew tap:

```text
linura-org/homebrew-tap
```

There is intentionally **no placeholder formula**. A `linura` formula will be added only when Linura has a release-qualified artifact with an immutable source/release URL, verified checksum, supported install layout, and documented upgrade/uninstall behavior.

When a formula is published, users will be able to add this tap with:

```bash
brew tap linura-org/tap
```

Do not infer Homebrew package availability from the existence of this repository.

## Source of truth

Linura development, releases, architecture, security policy, and issue tracking live in the main repository:

- https://github.com/linura-org/linura
- https://linura.org

Packaging in this tap must track an actual Linura release. It must not introduce an independent version, unreviewed binaries, mutable download targets, or a release path that bypasses Linura's qualification and provenance controls.

## Security

Do not report suspected vulnerabilities through a public issue in this repository. Follow [SECURITY.md](SECURITY.md).

## License

Repository content is licensed under the Apache License 2.0. See [LICENSE](LICENSE).

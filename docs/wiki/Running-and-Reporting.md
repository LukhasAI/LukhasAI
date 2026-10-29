# Running experiments and reporting findings

The public repositories contain historical prototypes with varying dependencies and maturity. Do not assume that they are ready to run unchanged.

## Before execution

1. Read the repository's current README and licence.
2. Inspect source for subprocess, filesystem, network and package-install operations. Avoid running unreviewed scripts against private data or production systems.
3. Use a disposable or isolated environment with only the dependencies that are actually needed.
4. Record the exact commit and interpreter/platform versions.
5. Run available static checks and narrowly scoped smoke tests before exploring optional features.

## Reporting an issue

Include:
- Repository, file path and current commit SHA.
- Exact command, runtime and operating system.
- Expected versus observed behavior.
- Minimal reproduction steps and relevant error output, with all tokens and personal data removed.
- Whether the result was source inspection, a simulated example or a real end-to-end execution.

## Release claims

Please do not describe an installation or demo as working until an independently reproducible verification receipt exists. Likewise, no security or ethics mechanism should be declared generally effective based only on its name or happy-path demo.

[Return to wiki home](Home.md)
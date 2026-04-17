# NORA

**The artifact registry that grows with you.** Starts with `docker run`, scales to enterprise.

```bash
docker run -d -p 4000:4000 -v nora-data:/data ghcr.io/getnora-io/nora:latest
```

Open [http://localhost:4000/ui/](http://localhost:4000/ui/) — your registry is ready.

## Why NORA

- **Zero-config** — single 32 MB binary, no database, no dependencies
- **7 registries** — Docker, Maven, npm, PyPI, Cargo, Go, Raw
- **Production-tested** — CI/CD with ArgoCD, Buildx cache, air-gapped environments
- **Secure by default** — OpenSSF Scorecard, signed releases, fuzz testing, 588 tests

[![Release](https://img.shields.io/github/v/release/getnora-io/nora)](https://github.com/getnora-io/nora/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/getnora-io/nora/blob/main/LICENSE)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/nora)](https://artifacthub.io/packages/helm/nora/nora)

## Links

- [Documentation](https://getnora.dev)
- [Helm Chart](https://github.com/getnora-io/helm-charts)
- [Telegram](https://t.me/getnora)

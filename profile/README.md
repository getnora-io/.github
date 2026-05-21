# NORA

**The artifact registry that grows with you.** Starts with `docker run`, scales with your needs.

```bash
docker run -d -p 4000:4000 -v nora-data:/data getnora/nora:latest
```

Open [http://localhost:4000/ui/](http://localhost:4000/ui/) — your registry is ready.

## Why NORA

- **Zero-config** — single binary, no database, no dependencies
- **13 registries** — Docker, Maven, npm, PyPI, Cargo, Go, Raw, RubyGems, Terraform, Ansible Galaxy, NuGet, Pub (Dart/Flutter), Conan (C/C++)
- **Production-tested** — CI/CD with ArgoCD, Buildx cache, air-gapped environments
- **Secure by default** — OpenSSF Scorecard, signed releases, SBOM, fuzz testing, 1040+ tests

[![Release](https://img.shields.io/github/v/release/getnora-io/nora)](https://github.com/getnora-io/nora/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/getnora-io/nora/blob/main/LICENSE)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/nora)](https://artifacthub.io/packages/helm/nora/nora)
[![Docker Pulls](https://img.shields.io/docker/pulls/getnora/nora)](https://hub.docker.com/r/getnora/nora)

## Links

- [Documentation](https://getnora.dev)
- [Helm Chart](https://github.com/getnora-io/helm-charts)
- [Telegram](https://t.me/getnora)

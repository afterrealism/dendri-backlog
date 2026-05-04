# Dendri Backlog

> **Note:** This repository is the **public issue tracker** for the Dendri project. There is no source code here. The actual code lives in the upstream Dendri repositories — please file issues here regardless of which component they affect, and we'll route them.

Dendri is a TypeScript SDK + Rust signaling server for WebRTC peer-to-peer applications, with fallback transports, rooms with host migration, typed presence, RPC with delivery acknowledgement, an end-to-end encrypted relay, JWT authentication, and webhooks. *(Replace this paragraph with your preferred description.)*

This backlog exists so anyone — users, integrators, and contributors — can file bugs, request features, ask questions, and watch the roadmap, without needing access to the source repos.

---

## How to file an issue

Pick the right template — they ask for the information we need to act:

- **[Bug report](https://github.com/afterrealism/dendri-backlog/issues/new?template=bug_report.yml)** — something is broken or behaves unexpectedly.
- **[Feature request](https://github.com/afterrealism/dendri-backlog/issues/new?template=feature_request.yml)** — capability you'd like added or changed.
- **[Discussions](https://github.com/afterrealism/dendri-backlog/discussions)** — open-ended questions, ideas, integration help. Please use Discussions instead of Issues for these.

Before filing: **search existing issues** (open and closed). Duplicates are the most common reason an issue gets closed without action.

## Reporting security issues

**Please do not open a public issue for security concerns.**

Use GitHub's **Private Vulnerability Reporting** instead:

1. Go to the [**Security** tab](https://github.com/afterrealism/dendri-backlog/security) of this repository.
2. Click **Report a vulnerability**.

Only repository maintainers see private reports. See [SECURITY.md](./SECURITY.md) for the full policy.

## Triage and roadmap

Issues are auto-labeled `triage` on creation and reviewed on a best-effort basis (no SLA). Accepted work is moved into the public Project board for visibility — see the **Projects** tab once the board is live.

Status flow:
`triage` → `accepted` → `in-progress` → `in-review` → `done` (or `wontfix` / `duplicate`).

## Community

- [Contributing guide](./CONTRIBUTING.md) — how to file good issues, label conventions, and what to expect.
- [Code of Conduct](./CODE_OF_CONDUCT.md) — Contributor Covenant v2.1. By participating you agree to abide by it.
- [Security policy](./SECURITY.md) — how to report vulnerabilities privately.

## License

Repository metadata (this README, templates, contributing guides) is licensed under [MIT](./LICENSE). Issues and comments you submit are licensed under the same terms as the upstream Dendri project.

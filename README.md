# Hamanaka Software Factory

**Mike Hamanaka** · San Francisco · [sjultra](https://sjultra.com) · [edgerecord.com](https://edgerecord.com)

I build local-first tools for capturing intent, coordinating AI coding sessions,
and checking results. The projects range from desktop alphas to infrastructure
prototypes; broader automation is still in development. Each repository documents
its current capabilities and limits.

> Less repeated context. More accepted work. Visible failures.

---

## Start here

- **Work with AI agents:** [Taskrivet setup](https://github.com/hamanakam1/taskrivet#start-here)
  or [desktop alpha downloads](https://github.com/hamanakam1/taskrivet/releases).
  The current release includes native and Electron Apple Silicon apps and a standalone Python CLI.
- **Capture browser intent:** [Panther Intent Capture](https://hamanakam1.github.io/panther-intent-capture/)
  turns selected browser evidence into reviewable proposals and opt-in ticket delivery.
- **Understand selected evidence:** [Panther Companion setup](https://github.com/hamanakam1/panther-companion#start)
  explains evidence against your goal. Its MVP imports do not create tickets or execute work.
- **Explore the projects:** the [project atlas](https://hamanakam1.github.io/)
  introduces their roles, documentation, and conceptual workflow.

## Public projects

| Repo | Role |
| --- | --- |
| [**panther-intent-capture**](https://github.com/hamanakam1/panther-intent-capture) | **Capture.** Local-first browser intent capture with visible controls and evidence-linked proposals. Creates tickets; does not execute work. · [site](https://hamanakam1.github.io/panther-intent-capture/) |
| [**panther-companion**](https://github.com/hamanakam1/panther-companion) | **Explain.** A desktop/browser MVP for understanding selected evidence against a goal. Intent imports are explicitly confirmed and remain review-only. · [setup](https://github.com/hamanakam1/panther-companion#start) |
| [**taskrivet**](https://github.com/hamanakam1/taskrivet) | **Coordinate.** Desktop alpha with persistent terminals, bounded ticket context, and reviewable results. · [guide](https://hamanakam1.github.io/taskrivet/) |
| [**osprey**](https://github.com/hamanakam1/osprey) | **Supervise.** Pre-release macOS app for terminal checkpoint proposals and explicitly requested app verification, installation, and rollback. Ledger writes require approval; no unattended mode. · [quick start](https://github.com/hamanakam1/osprey#quick-start) |
| [**fluxrecord**](https://github.com/hamanakam1/fluxrecord) | **Remember the work.** A ticket standard for local-first, evidence-driven coordination. · [site](https://hamanakam1.github.io/fluxrecord/) |
| [**el-hidratador**](https://github.com/hamanakam1/el-hidratador) | **Prepare.** Turns tickets into bounded context, plans, sandbox specifications, and compute recommendations. A prepared handoff is not execution permission. · [guide](https://hamanakam1.github.io/el-hidratador/) |
| [**el-verificador**](https://github.com/hamanakam1/el-verificador) | **Verify.** Independent intent checks, bounded retry loops, and proof-of-work records. · [site](https://hamanakam1.github.io/el-verificador/) |
| [**the-chronicler**](https://github.com/hamanakam1/the-chronicler) | **Learn.** Local memory tooling that extracts failure heuristics with Ollama and records rules in Git. · [site](https://hamanakam1.github.io/the-chronicler/) |
| [**the-surveyor**](https://github.com/hamanakam1/the-surveyor) | **Observe.** Read-only hardware discovery, topology snapshots, and change reports. · [site](https://hamanakam1.github.io/the-surveyor/) |
| [**the-tower**](https://github.com/hamanakam1/the-tower) | **Guard the hardware.** Prototype hardware monitoring and dispatch planning, with advisory defaults. · [site](https://hamanakam1.github.io/the-tower/) |
| [**horizon-broker**](https://github.com/hamanakam1/horizon-broker) | **Queue inference.** Alpha asynchronous queue with retries and failover. Its real ledger adapter remains unfinished. · [site](https://hamanakam1.github.io/horizon-broker/) |

---

## Principles

- **Local first.** Prefer local inference, local ledgers, and local Git. Make
  network access and provider choices explicit.
- **Visible failures.** A failure with a recorded reason is worth more than a
  success nobody can check.
- **Bounded authority.** Make scope, approvals, and side effects visible.
- **Evidence over claims.** A diff is not an intent. A finished session is not
  accepted work. Declared usage is not measured billing.
- **Synthetics in public.** Use synthetic examples and keep private deployment
  data out of public material.

---

## Contribute

Start with a project's README and contribution instructions. Features, setup
requirements, CI coverage, and release maturity vary by repository. Use issue or
pull-request templates when provided.

```bash
gh repo list hamanakam1 --visibility public --limit 100
gh release list -R hamanakam1/taskrivet
```

This profile repository uses the [MIT License](LICENSE). Each project carries its
own license and any applicable third-party notices.

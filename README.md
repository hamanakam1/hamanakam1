# Hamanaka Software Factory

**Mike Hamanaka** · San Francisco · [sjultra](https://sjultra.com) · [edgerecord.com](https://edgerecord.com)

A closed, self-correcting autonomous coding factory running on local-first
infrastructure. Each component has one job, and the boundaries between them are
stated rather than assumed.

> Less repeated context. More accepted work. Visible failures.

---

## The ecosystem

| Repo | Role |
| --- | --- |
| [**panther-intent-capture**](https://github.com/hamanakam1/panther-intent-capture) | **Capture.** Local-first browser intent capture with visible controls and evidence-linked proposals. Creates tickets; does not execute work. · [site](https://hamanakam1.github.io/panther-intent-capture/) |
| [**panther-companion**](https://github.com/hamanakam1/panther-companion) | **Synthesize.** A quiet local workspace for understanding evidence in the context of your current goal across panel, browser, and MCP. |
| [**fluxrecord**](https://github.com/hamanakam1/fluxrecord) | **Standardize the intent.** A ticket standard for local-first, evidence-driven coordination across agent sessions. · [site](https://hamanakam1.github.io/fluxrecord/) |
| [**el-hidratador**](https://github.com/hamanakam1/el-hidratador) | **Stage & Expand.** Turns dry semantic tickets into wet machine execution state: expanded context, ordered DAGs, and locked sandboxes. |
| [**taskrivet**](https://github.com/hamanakam1/taskrivet) | **Coordinate.** Purposeful agent work, bounded context, and visible failures. A local-first coordination core for AI CLI sessions. · [site](https://hamanakam1.github.io/taskrivet/) |
| [**osprey**](https://github.com/hamanakam1/osprey) | **Supervise.** Local-first Swift supervisor for Taskrivet: work capture, stream redaction, and rollback-guarded releases. |
| [**el-verificador**](https://github.com/hamanakam1/el-verificador) | **Verify.** Independent intent verification, guardrailed retry loops, and proof-of-work commits. The gate between "code written" and "code committed". · [site](https://hamanakam1.github.io/el-verificador/) |
| [**the-chronicler**](https://github.com/hamanakam1/the-chronicler) | **Learn.** The local-first memory core of the factory: extracts failure heuristics via local Ollama and commits hardened rules back to Git. · [site](https://hamanakam1.github.io/the-chronicler/) |
| [**the-surveyor**](https://github.com/hamanakam1/the-surveyor) | **Observe.** A read-only systems analyst that surveys real hardware into an Open Edge Topology map and narrates what changed. · [site](https://hamanakam1.github.io/the-surveyor/) |
| [**the-tower**](https://github.com/hamanakam1/the-tower) | **Guard the hardware.** Air traffic control for the mesh: thermal, power and memory monitoring, task dispatch, and a guardrailed kill-switch. · [site](https://hamanakam1.github.io/the-tower/) |
| [**horizon-broker**](https://github.com/hamanakam1/horizon-broker) | **Schedule the inference.** An asynchronous inference queue and fault-tolerance manager for a heterogeneous edge fleet. · [site](https://hamanakam1.github.io/horizon-broker/) |

---

## Principles

- **Local first.** Local inference, local ledgers, local Git. No paid cloud
  fallback, and nothing leaves the machine unless a human says so.
- **Visible failures.** A failure with a recorded reason is worth more than a
  success nobody can check.
- **Bounded authority.** Every component states what it may do, and — more
  importantly — what it may not.
- **Evidence over claims.** A diff is not an intent. A finished session is not
  accepted work. Declared usage is not measured billing.
- **Synthetics in public.** Fixtures, screenshots, and examples identify no
  real system or deployment.

---

## Working on it

Every public repository ships a README, a license, badges, a documentation
site, CI, issue and pull-request templates, and a release with a container
image where one makes sense.

```bash
gh repo list hamanakam1 --limit 100
gh release list -R hamanakam1/taskrivet
docker pull ghcr.io/hamanakam1/the-tower:0.3.0
```

MIT licensed throughout.

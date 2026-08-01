<div align="center">

# CodeTonight

### Technology that works for you. Not against you.

**Sovereign, provable AI.** We build the machinery that lets a business trust its
own AI decisions — without trusting the model, the cloud, or even us. Every
decision signed, chained, and replayable by anyone.

`Trust no model` · `Trust no vendor` · `Verify the math`

[![HAPPI/1.0 conformance](https://img.shields.io/badge/HAPPI%2F1.0-conformant-2b6cb0)](https://github.com/CodeTonight-SA/hal-conformance)
[![RSI witnessed](https://img.shields.io/badge/RSI-witnessed%20live-1a7f37)](https://codetonight-sa.github.io/grip-rsi-witness/)
[![Decision chain](https://img.shields.io/badge/decision%20chain-verifiable-6f42c1)](https://codetonight-sa.github.io/grip-decision-chain/)

</div>

```console
$ grasp verify .
✓ decision  signed   · ed25519
✓ chain     intact   · merkle root recomputed
✓ anchored  external · bitcoin block 956992
  the proof is the product — check it yourself.
```

---

> Enterprise open source sold you trust in a vendor. **We sell you the proof
> you never need one.**

## What we build

We build sovereign, provable AI: systems that record *what* an AI decided and
*what it believed when* — as a signed, chained record any third party can
verify without trusting the model, the vendor, or us. The reference
implementation is **[GRASP](https://github.com/CodeTonight-SA/grasp)** —
open, harness-agnostic, LLM-agnostic, and falsifiable by construction.

## How we work

<table>
<tr>
<td width="33%" valign="top">

### Embedded
We sit inside your team, not beside it. Shipping code, not slide decks.

</td>
<td width="33%" valign="top">

### Orchestrated
Many models, one accountable process — a council of rivals, judged, on the
record.

</td>
<td width="33%" valign="top">

### Ongoing
The system keeps improving after we leave — signed, witnessed, and yours to
audit.

</td>
</tr>
</table>

## The open shelf

Four layers, one stack. Each repo does one job; together they are the whole
proof chain from protocol to product.

**Proof** — the record, sealed and checkable
| Repo | What it is |
|---|---|
| [`grasp`](https://github.com/CodeTonight-SA/grasp) | The open reference implementation of cryptographic causation |
| [`grip-decision-chain`](https://github.com/CodeTonight-SA/grip-decision-chain) | Signed, chained Intent Decision Records — tamper-evident by construction |
| [`grip-rsi-witness`](https://github.com/CodeTonight-SA/grip-rsi-witness) | Live public ledger of self-improvement cycles, replayable |

**Substrate** — the syscall layer underneath any model or harness
| Repo | What it is |
|---|---|
| [`hal-go`](https://github.com/CodeTonight-SA/hal-go) · [`hal-py`](https://github.com/CodeTonight-SA/hal-py) · [`hal-js`](https://github.com/CodeTonight-SA/hal-js) | HAPPI/1.0 implementations — route any LLM, on any harness, air-gapped if you need it |
| [`hal-conformance`](https://github.com/CodeTonight-SA/hal-conformance) | The open certification suite — machines certify against the spec, not against us |

**Craft** — tools that keep the work honest and sharp
| Repo | What it is |
|---|---|
| [`skill-forge`](https://github.com/CodeTonight-SA/skill-forge) | Sharpens agent skills instead of letting them atrophy |
| [`claude-modes`](https://github.com/CodeTonight-SA/claude-modes) | Purposeful capability loading for Claude Code |
| [`git-solve`](https://github.com/CodeTonight-SA/git-solve) | Squash-merge-aware branch reconciliation with a Banach fixed-point proof |
| [`claude-handoff`](https://github.com/CodeTonight-SA/claude-handoff) | Apple-native, zero-service state handoff across harnesses |
| [`prompt-cache-keepalive`](https://github.com/CodeTonight-SA/prompt-cache-keepalive) | Keeps prompt caches warm, keeps bills down |
| [`grip-post`](https://github.com/CodeTonight-SA/grip-post) | An anti-fluff gate that refuses to write slop |

**Delight** — because the moat should also be fun to look at
| Repo | What it is |
|---|---|
| [`ccflex-skibidi`](https://github.com/CodeTonight-SA/ccflex-skibidi) | Claude Code `/stats`, rendered live in WebGL |

<details>
<summary><strong>Why "GRIP" and "HAL"?</strong></summary>
<br>

**GRIP** — Guarded Response Interception Protocol. **HAL** — the multi-provider
AI substrate that routes underneath it. Neither name is an accident; both are
load-bearing acronyms for what the systems actually do.

</details>

## Proof, not promises

We don't ask you to believe GRASP improves itself — we publish it. The
[`grip-rsi-witness`](https://codetonight-sa.github.io/grip-rsi-witness/) ledger is a
**live public page**: every self-improvement cycle, signed and replayable — including
the ones that failed.

**Open it → [codetonight-sa.github.io/grip-rsi-witness](https://codetonight-sa.github.io/grip-rsi-witness/)**

No competitor's org profile publishes a losing hypothesis. Ours does, because a ledger
that never shows a refutation isn't a ledger — it's marketing.

## Verify us

Don't trust this README. **Verify it.** The witnesses are public and live — open them
and check the latest sealed records against the chain yourself:

- [codetonight-sa.github.io/grip-decision-chain](https://codetonight-sa.github.io/grip-decision-chain/) — the signed decision chain
- [codetonight-sa.github.io/grip-rsi-witness](https://codetonight-sa.github.io/grip-rsi-witness/) — self-improvement, witnessed

If a record doesn't verify against the public chain, don't work with us.

---

<div align="center">

Cape Town.

</div>

<p align="center">
  <a href="https://bathron.org/"><img src="https://raw.githubusercontent.com/bathron-network/bathron-network.github.io/main/img/wordmark.png" alt="BATHRON" width="360"></a>
</p>

> **Build contracts around facts Bitcoin can prove.**

BATHRON is an **open programmable settlement protocol**: a settlement unit, conditions that
consensus enforces, and a script engine that can assert facts about the Bitcoin chain — verified by
every node, with no designated oracle. It supplies no products, liquidity, prices or interfaces;
those come from independent builders on top.

**Markets are one application of this layer. They are not the protocol.**

[Read the five-minute overview](https://bathron.org/docs/start-here.html) ·
[What BATHRON is](https://bathron.org/docs/protocol/what-bathron-is.html) ·
[Bitcoin-verifiable contracts](https://bathron.org/docs/protocol/bitcoin-verifiable-contracts.html) ·
[Application map](https://bathron.org/docs/build/application-map.html) ·
[Status & claims](https://bathron.org/docs/consensus/status-and-claims.html) ·
[Testnet explorer](https://explorer.bathron.org/)

## The network being built toward

**Several independent Consensus Operators**, none of whom chooses markets, providers or assets;
**several independent Settlement, Clearing and Liquidity Providers**; competing applications. No
listing committee, no protocol-imposed matching engine, **no privileged provider**. Several
providers may serve the same instrument, and a provider can disappear without removing the protocol
or the instrument. This is a **target**: with one exception, none of it is deployed today.
→ [The target open network](https://bathron.org/docs/network/open-network-target.html)

## The network running today

An **experimental public testnet**. No mainnet, no external audit, no proven market.

The exception is application building: anyone can build an application or propose a settlement flow
without a listing committee. **Consensus-Operator admission is not open** — the operator set is
project-run while the open-admission threat model is worked out, and the exact admission mechanism
is deliberately left open rather than decided in advance.

The authoritative statement of what runs, what is not proven and what BATHRON does not claim is
[Status & claims](https://bathron.org/docs/consensus/status-and-claims.html). Where any other
public text says more, that page prevails — this profile included.

## Public repositories

| Repository | Purpose |
|---|---|
| [bathron-core](https://github.com/bathron-network/bathron-core) | Public node implementation: consensus, RPC and build files |
| [bathron-network.github.io](https://github.com/bathron-network/bathron-network.github.io) | Canonical public documentation and the bathron.org site |
| [bathron-explorer](https://github.com/bathron-network/bathron-explorer) | Experimental public-testnet block explorer ([live](https://explorer.bathron.org/)) |

## Security

Report vulnerabilities privately to **security@bathron.org** — never in a public issue. See the
[security model](https://bathron.org/docs/consensus/security-model.html) and the
[bathron-core security policy](https://github.com/bathron-network/bathron-core/blob/main/SECURITY.md).

---

Public documentation has one canonical source:
[`bathron-network.github.io/docs/src`](https://github.com/bathron-network/bathron-network.github.io/tree/main/docs/src).
This profile is orientation only; the canonical documentation prevails — see the
[documentation policy](https://bathron.org/docs/reference/documentation-policy.html).

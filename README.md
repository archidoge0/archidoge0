# Hi, I'm archidoge0 👋

## Research Projects

| Project | Description |
|---------|-------------|
| [ZKAP](https://github.com/whbjzzwjxq/ZKAP) | Practical Security Analysis of Zero-Knowledge Proof Circuits (USENIX Security'24) |
| [Foray](https://github.com/whbjzzwjxq/Foray) | Attack Synthesis against Deep Logical Vulnerabilities in DeFi Protocols (ACM CCS'24) |

## Open-Source Contributions

### Security Audits — [openclaw/clawhub](https://github.com/openclaw/clawhub)

Filed **50+ zero-day** security advisories on agent skills published on ClawHub, covering credential leakage, RCE, PII exfiltration, and indirect prompt injection. See [my filed issues](https://github.com/openclaw/clawhub/issues?q=is%3Aissue+author%3Aarchidoge0) for the full list.

### Security Audits — ZK Circuits

| Project | Issue | Description |
|---------|-------|-------------|
| [iden3/circom](https://github.com/iden3/circom) | [#176](https://github.com/iden3/circom/issues/176) | Division-by-zero bug in Circom compiler's witness generator — root-cause traced to `mpz_invert` in generated C++ |
| [BitVM/BitVM](https://github.com/BitVM/BitVM) | [#107](https://github.com/BitVM/BitVM/issues/107) | Paper-vs-implementation discrepancy analysis: missing optimistic branch, output count mismatch, chunker design |
| [socathie/circomlib-ml](https://github.com/socathie/circomlib-ml) | [#2](https://github.com/socathie/circomlib-ml/issues/2) | Unconstrained input signals in Conv1D circuit — soundness concern in ZK ML |

### Bug Reports

| Project | Issue | Description |
|---------|-------|-------------|
| [a16z/halmos](https://github.com/a16z/halmos) | [#190](https://github.com/a16z/halmos/issues/190) | Feature proposal: symbolic execution on forked mainnet state for DeFi exploit analysis |
| [paulmillr/scure-btc-signer](https://github.com/paulmillr/scure-btc-signer) | [#117](https://github.com/paulmillr/scure-btc-signer/issues/117) | Can't use `tapBip32Derivation` to sign PSBT |
| [rust-bitcoin/rust-bech32](https://github.com/rust-bitcoin/rust-bech32) | [#207](https://github.com/rust-bitcoin/rust-bech32/issues/207) | Bech32m encode-decode failed |

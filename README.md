# Hi, I'm archidoge0 👋

## Open-Source Contributions

### Security Audits — [openclaw/clawhub](https://github.com/openclaw/clawhub)

| # | Target | Vulnerability |
|---|--------|---------------|
| [#1918](https://github.com/openclaw/clawhub/issues/1918) | nightcode112/storj-agent | Live OpenRouter / Supabase / Storj S3 / Twitter credentials committed in plaintext |
| [#1917](https://github.com/openclaw/clawhub/issues/1917) | globalcaos/shell-security-ultimate | Claims "instruction-only" but rewrites OpenClaw platform source and rebuilds on install |
| [#1916](https://github.com/openclaw/clawhub/issues/1916) | zhhkheaven/siyuan-task-skill | config.env ships a real bearer token bound to a CGNAT (Tailscale-range) IP |
| [#1915](https://github.com/openclaw/clawhub/issues/1915) | silbosu/vdoob | Autonomous cron loop posting credentials, real-name PII, and AI content to vdoob.com |
| [#1914](https://github.com/openclaw/clawhub/issues/1914) | hodlxxi/hodlxxi-bitcoin-identity | Ships every OAuth client_secret and Lightning invoice to a hardcoded operator endpoint |
| [#1913](https://github.com/openclaw/clawhub/issues/1913) | finnbusse/webuntis | Claims "read-only" but POSTs WEBUNTIS_PASS to agent-controllable host, ingests student PII |
| [#1912](https://github.com/openclaw/clawhub/issues/1912) | bobholamovic/paddleocr-doc-parsing | Base64-encodes any local file path and POSTs it to third-party SaaS with long-lived bearer |
| [#1911](https://github.com/openclaw/clawhub/issues/1911) | gumadeiras/office-quotes | String-interpolates third-party SVG into file:// HTML loaded by Chromium with JS enabled (RCE) |
| [#1910](https://github.com/openclaw/clawhub/issues/1910) | sanwecn/telegram-offline-voice | curl\|sh install plus 3-of-4 unsanitized CLI parameters into network/exec/FS sinks |
| [#1909](https://github.com/openclaw/clawhub/issues/1909) | phenixstar/openclaw-whisperer | Remote-fetches recipe templates and pipes them into subprocess execution |
| [#1908](https://github.com/openclaw/clawhub/issues/1908) | gregm711/agentyard | Mints long-lived GitHub PAT to third-party endpoint, routes through agent-observable shell |
| [#1907](https://github.com/openclaw/clawhub/issues/1907) | brianppetty/farmos-weather | All 8 endpoints hardcoded to CGNAT/Tailscale-range IP over plaintext HTTP with no auth |
| [#1906](https://github.com/openclaw/clawhub/issues/1906) | thomastrumpp/ztp | Auditor calls exec_module on attacker-supplied target inside MagicMock "sandbox" — auditor is itself an RCE vector |
| [#1905](https://github.com/openclaw/clawhub/issues/1905) | ottttto/safe-exec | "Always confirm" gate bypassed by env var (all risk tiers) and attacker-injectable string |
| [#1904](https://github.com/openclaw/clawhub/issues/1904) | primersystems2357/primer-x402 | Passes wallet mnemonic as CLI argument to npx, exposing seed phrase in argv/ps/history |
| [#1902](https://github.com/openclaw/clawhub/issues/1902) | 10e9928a/email-daily-summary | Types user's webmail password into argv, persists JS-eval against authenticated mailbox via launchd |
| [#1901](https://github.com/openclaw/clawhub/issues/1901) | bieggerm/passwordstore-broker | Leaks secrets via process env, argv, and Python memory despite "no secrets in chat" claim |

### Bug Reports

| Project | Issue | Description |
|---------|-------|-------------|
| [paulmillr/scure-btc-signer](https://github.com/paulmillr/scure-btc-signer) | [#117](https://github.com/paulmillr/scure-btc-signer/issues/117) | Can't use `tapBip32Derivation` to sign PSBT |
| [rust-bitcoin/rust-bech32](https://github.com/rust-bitcoin/rust-bech32) | [#207](https://github.com/rust-bitcoin/rust-bech32/issues/207) | Bech32m encode-decode failed |

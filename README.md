<div align="center">

<img src="https://sophialabs.ca/assets/sophia_labs_glyph_square.png" alt="Sophia Labs" width="88" />

# Mark Gantlett

**Agents guess; Git cannot.** Building **[Nomos](https://github.com/mgantlett/nomos)** and **[Sophia Labs](https://sophialabs.ca)** - deterministic Go execution substrates and AST verification gates between AI coding agents and Git.

[![Nomos Release](https://img.shields.io/github/v/release/mgantlett/nomos?label=Nomos&color=0284C7)](https://github.com/mgantlett/nomos/releases/latest)
[![Nomos X-Ray](https://sophialabs.ca/api/xray/badge/mgantlett/nomos.svg)](https://sophialabs.ca/mgantlett/nomos)
[![Website](https://img.shields.io/badge/Sophia_Labs-sophialabs.ca-0284C7)](https://sophialabs.ca)
[![X](https://img.shields.io/badge/@__sophialabs-000000?logo=x&logoColor=white)](https://x.com/_sophialabs)

</div>

---

### What I Build

**[Nomos](https://github.com/mgantlett/nomos)** is a single `~20 MB` static Go binary (`Apache 2.0`, `0` LLM tokens, zero cloud account) that sits between any coding agent (**Claude Code**, **Cursor**, **OpenCode**, **Codex**, **Gemini CLI**, **Antigravity**, **Windsurf**) and Git.

- **Try in 5 seconds (zero install):** Replace `github.com` with `sophialabs.ca` in any public repo URL (e.g. [sophialabs.ca/mgantlett/nomos](https://sophialabs.ca/mgantlett/nomos)) or paste a repo at [sophialabs.ca/xray](https://sophialabs.ca/xray) for an instant 11-language AI Hangover Score.
- **Drop into any repo in 30 seconds:**
  ```bash
  curl -fsSL https://sophialabs.ca/install | bash
  cd your-project && nomos xray .   # read-only ~4s structural health scan
  nomos init                        # Branch Guard + Day-0 debt ratchet + agent hooks
  nomos status                      # Shield Scorecard (caught shortcuts) & graduation ladder
  ```

### Open Source & Benchmarks

| Project | Focus |
| :--- | :--- |
| **[nomos](https://github.com/mgantlett/nomos)** | Apache 2.0 Go execution substrate: Branch Guard & Day-0 ratchet, 42 polyglot AST anti-cheat gates, Shield Scorecard, receipt-gated SQLite memory (`mneme.db`), and optional parallel git worktrees. |
| **[nomos-tracetrial](https://github.com/mgantlett/nomos-tracetrial)** | Reproducibility harness, raw container traces, and paired scorecards across TraceTrial-Bench (`190` runs), Terminal-Bench 2.0, SlopCodeBench, and AgentDojo. |
| **[nomos-harbor](https://github.com/mgantlett/nomos-harbor)** | Official Nomos deterministic substrate adapter for Harbor and Terminal-Bench agent evaluations. |
| **[devcontainer-features](https://github.com/mgantlett/devcontainer-features)** · **[homebrew-tap](https://github.com/mgantlett/homebrew-tap)** · **[scoop-bucket](https://github.com/mgantlett/scoop-bucket)** | Official cross-platform installers for Codespaces/DevPod, Homebrew, and Windows Scoop (plus `npx @mgantlett/nomos`, `uvx nomos-cli`, Nix flakes, OCI images, and Arch/Omarchy PKGBUILD). |

### Empirical Benchmarks

- **Workhorse Brownfield Lift (`N = 108` paired):** `86.1%` vs. `27.8%` stock (`3.1x` lift) on `14B-32B` open-weight models across Python/TS/Go while cutting token spend `-43%` to `-57%`.
- **Prompt-Injection & Security (`1,481` traces):** `0.00%` attack success rate across `AgentDojo v1.2.2` (`0/949`) and `SecBench-Live 1.0` (`0/200`) with `85.04%` benign utility.
- **Monorepo Scale:** `<365ms` full 42-gate diff verification certified up to `3.60M` LOC (`0` LLM tokens).

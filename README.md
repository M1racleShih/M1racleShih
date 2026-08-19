<div align="center">

![Han-Qing Shi — Quantum Software, AI Agents, and Open Source](./assets/profile-header.svg)

I build dependable tools at the intersection of **quantum computing**, **AI agents**, and **developer experience** — currently contributing upstream to **[Hermes Agent](https://github.com/NousResearch/hermes-agent)**.

[![Shipped upstream changes](https://img.shields.io/badge/shipped_upstream_changes-5-1f883d?style=flat-square&logo=github&logoColor=white)](#open-source-contributions)
[![Open Hermes PRs](https://img.shields.io/badge/open_Hermes_PRs-3-0969da?style=flat-square)](https://github.com/NousResearch/hermes-agent/pulls?q=is%3Apr+is%3Aopen+author%3AM1racleShih)
[![Upstream projects](https://img.shields.io/badge/upstream_projects-4-8250df?style=flat-square)](#open-source-contributions)
[![GitHub followers](https://img.shields.io/github/followers/M1racleShih?style=flat-square&logo=github&label=follow)](https://github.com/M1racleShih?tab=followers)

</div>

## Open-source contributions

I like focused changes with a clear failure mode, a reviewable scope, and explicit validation. The status of every contribution below is stated directly.

### Hermes Agent

[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) is my primary active upstream. My work spans messaging, scheduled jobs, persistent goals, provider compatibility, and distribution reliability.

| Status | Contribution | Impact |
| --- | --- | --- |
| **Shipped** | [Feishu Markdown table rendering](https://github.com/NousResearch/hermes-agent/commit/ae22a03ef63943079ebbc53c85c8944218a1262e), submitted in [#29552](https://github.com/NousResearch/hermes-agent/pull/29552) and integrated through [#68121](https://github.com/NousResearch/hermes-agent/pull/68121) | Routed table-shaped Markdown through Feishu's native `post`/`md` path and added a direct payload regression test. The upstream commit preserves my authorship. |
| **Open** | [#70500 · Allow cron scripts to use an external Python interpreter](https://github.com/NousResearch/hermes-agent/pull/70500) | Adds validated, persistent interpreter selection across Python cron and monitor-script execution paths, with bilingual docs and regression coverage. |
| **Open** | [#70015 · Load persistent goals from files](https://github.com/NousResearch/hermes-agent/pull/70015) | Extends file-backed goals across the Classic CLI, TUI, and Desktop while preventing remote gateways from reading host files. |
| **Open** | [#69928 · Repair native Gemini array tool schemas](https://github.com/NousResearch/hermes-agent/pull/69928) | Enforces Gemini's final-wire `items` requirement without losing representable tuple semantics; verified against the live native API. |
| **Reported** | [#37954 · Distribution updates could drop nested protected-name directories](https://github.com/NousResearch/hermes-agent/issues/37954) | Documented the root cause and a reproducible install/update regression; maintainers later closed it after an equivalent fix landed on `main`. |

<p align="right"><a href="https://github.com/NousResearch/hermes-agent/pulls?q=is%3Apr+author%3AM1racleShih">View all Hermes Agent PRs →</a></p>

### Other merged upstream work

| Upstream project | Merged contribution | Impact |
| --- | --- | --- |
| [nextai-translator/nextai-translator](https://github.com/nextai-translator/nextai-translator) | [#1901 · Show the Quit action in the Linux tray menu](https://github.com/nextai-translator/nextai-translator/pull/1901) | Restored a missing Linux action while preserving native behavior on other platforms; verified from Rust checks through a KDE/X11 package build. |
| [ilysenko/codex-desktop-linux](https://github.com/ilysenko/codex-desktop-linux) | [#1307 · Satisfy stable Clippy](https://github.com/ilysenko/codex-desktop-linux/pull/1307) | Restored the workspace's latest-stable Rust quality gate without changing Wayland/X11 detection semantics. |
| [NVIDIA/Quantum-Calibration-Agent-Blueprint](https://github.com/NVIDIA/Quantum-Calibration-Agent-Blueprint) | [#9 · Fix the UI development startup](https://github.com/NVIDIA/Quantum-Calibration-Agent-Blueprint/pull/9)<br>[#7 · Add repository-wide ignore rules](https://github.com/NVIDIA/Quantum-Calibration-Agent-Blueprint/pull/7) | Removed a Node.js startup failure and reduced accidental Python, Next.js, test, and build artifacts in future commits. |

<p align="right"><a href="https://github.com/search?q=is%3Apr+is%3Amerged+author%3AM1racleShih+-user%3AM1racleShih&type=pullrequests">Browse all public merged PRs →</a></p>

## What I'm building and learning

| Project | Focus |
| --- | --- |
| **[OpenAI Agents SDK Learning Lab](https://github.com/M1racleShih/openai-agents-sdk-learning-lab)** | A bilingual, hands-on curriculum for building a bounded, observable, and testable read-only terminal agent. |
| **[QArray](https://github.com/M1racleShih/quantum-array)** | A geometry-first Python model for expressing and manipulating qubits and couplers with NumPy-like indexing. |
| **[Learn QEC](https://github.com/M1racleShih/learn-qec)** | Engineering-oriented notes that build a practical mental model from physical errors to surface codes and lattice surgery. |

## Working with

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Quantum_Computing-6f42c1?style=flat-square" alt="Quantum Computing">
  <img src="https://img.shields.io/badge/AI_Agents-0969da?style=flat-square" alt="AI Agents">
</p>

<sub>Based in China · Find me here as <a href="https://github.com/M1racleShih">@M1racleShih</a>.</sub>

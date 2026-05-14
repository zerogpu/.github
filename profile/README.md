<p align="center">
  <img src="https://zerogpu.ai/assets/zerogpu-icon-dark-DB2Jfxq2.png" alt="ZeroGPU" width="140"/>
</p>

<h1 align="center">ZeroGPU</h1>

<p align="center">
  <strong>Distributed AI inference for geo-aware edge compute.</strong><br/>
  Run production workloads with lower cost and lower latency — horizontal scale across edge devices, one familiar API surface.
</p>

<p align="center">
  <a href="https://platform.zerogpu.ai">
    <img src="https://img.shields.io/badge/Platform-Dashboard-22c55e?style=for-the-badge" alt="Open ZeroGPU platform" />
  </a>
  &nbsp;
  <a href="https://www.zerogpu.ai">
    <img src="https://img.shields.io/badge/Website-zerogpu.ai-22c55e?style=for-the-badge" alt="ZeroGPU website" />
  </a>
  &nbsp;
  <a href="https://docs.zerogpu.ai">
    <img src="https://img.shields.io/badge/Docs-docs.zerogpu.ai-111827?style=for-the-badge" alt="ZeroGPU documentation" />
  </a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/zerogpu-api"><img src="https://img.shields.io/npm/v/zerogpu-api?style=flat-square&label=npm" alt="npm version" /></a>
  <a href="https://pypi.org/project/zerogpu-api/"><img src="https://img.shields.io/pypi/v/zerogpu-api?style=flat-square&label=pypi" alt="PyPI version" /></a>
  <a href="https://github.com/zerogpu/SDK"><img src="https://img.shields.io/github/stars/zerogpu/SDK?style=flat-square&logo=github" alt="SDK repository stars" /></a>
  <a href="https://github.com/zerogpu/zerogpu-router"><img src="https://img.shields.io/badge/Related-Router-111827?style=flat-square" alt="ZeroGPU Router" /></a>
</p>

<p align="center">
  <img src="./assets/zerogpu-sdk.gif" alt="ZeroGPU platform — Get Started, project and API keys, and multi-language request snippets" width="720"/>
</p>

---

## Why ZeroGPU

- **Lower cost** — Inference on idle edge compute instead of always renting centralized GPU capacity.
- **Geo-aware routing** — Requests land on nearby capacity so latency stays predictable for real users.
- **Edge-native models** — Nano language models (NLMs) tuned for edge and cloud, not only downsized cloud stacks.
- **OpenAI-compatible API** — `POST /v1/responses` and `POST /v1/chat/completions` with request shapes you already know.
- **Cloud fallback** — When edge is unavailable, the same API path falls back to cloud without a second integration story.
- **Typed SDKs** — Official clients on [npm](https://www.npmjs.com/package/zerogpu-api) (`zerogpu-api`) and [PyPI](https://pypi.org/project/zerogpu-api/) (`pip install zerogpu-api` → `import zerogpu`), plus Go, Ruby, Java, Rust, C#, PHP, and Swift in the [**SDK**](https://github.com/zerogpu/SDK) monorepo.

---

## API at a glance

| | |
| --- | --- |
| **Base URL** | `https://api.zerogpu.ai/v1` |
| **Primary path** | `POST /v1/responses` |
| **Headers** | `x-api-key`, `x-project-id`, `Content-Type: application/json` |
| **Reference** | [Responses API](https://docs.zerogpu.ai/api-reference/endpoint/responses) |

Set `ZEROGPU_API_KEY` and `ZEROGPU_PROJECT_ID` the same way you do in the platform dashboard snippets. Full authentication, models, and error semantics live in **[docs.zerogpu.ai](https://docs.zerogpu.ai)**.

---

## Highlighted repositories

| Repository | What you’ll find there |
| --- | --- |
| [**zerogpu/SDK**](https://github.com/zerogpu/SDK) | Official Fern-generated API clients, smoke tests, and publishing workflows for npm/PyPI packages. |
| [**zerogpu/docs**](https://github.com/zerogpu/docs) | Documentation source and deep links into [docs.zerogpu.ai](https://docs.zerogpu.ai). |
| [**zerogpu/zerogpu-router**](https://github.com/zerogpu/zerogpu-router) | Router-related components that pair with how traffic and capacity are orchestrated. |

---

<p align="center">
  <sub>ZeroGPU — inference where your users are, not only where the GPUs are.</sub>
</p>

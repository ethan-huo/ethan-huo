# Ethan Huo

**Co-founder & CTO of [Celados](https://celados.com)** — an AI-native product studio that builds agent-first.
I build products around voice, AI-generated content and developer tools — from on-device inference on Apple Silicon to the schema-first CLIs the studio runs on.

🌐 [celados.com](https://celados.com) · 🐦 [@stackobserve](https://x.com/stackobserve)

## Products

All of these ship from one monorepo: Solid 2 / TanStack Start on Cloudflare Workers, Convex backends, a shared StyleX design system.

| Product | What it is |
| --- | --- |
| [**Whiteboard Animation AI**](https://whiteboardanimation.ai) | Turn any finished illustration into a hand-drawn video — sketched stroke by stroke, then coloured in. |
| [**Clonesite AI**](https://clonesite.ai) | Paste a URL and get a page-by-page copy of a public website, ready to preview and keep live on your own domain. |
| [**OnType**](https://getontype.app) | Voice input for macOS. Hold a key, speak, release to type — cloud speed, with a free private on-device fallback. |
| [**PolishX**](https://polishx.ai) | A calmer X. A Chrome extension that removes ads and spam, then sorts every post by what you care about. |
| [**Wearly AI**](https://apps.apple.com/app/wearly-ai/id6760324232) | Your AI stylist. Snap your wardrobe and get three outfits every morning, tuned to the weather and your day. |

**Now building: [Growsight](https://growsight.ai)** — agent-native product analytics, driven from ChatGPT and Claude.

## Open source

Tools built for agents first: one structured input, JSON out, a discoverable schema.

| Repo | What it does |
| --- | --- |
| [**argc**](https://github.com/ethan-huo/argc) | Schema-first CLI framework for Bun — the base of most of the CLIs below. |
| [**ctx**](https://getctx.sh) | Full-document search and reading for agents — complete sources, not RAG fragments. |
| [**mcpx**](https://github.com/celados/mcpx) | Turns MCP servers into an agent-friendly command line, with schema discovery and OAuth. |
| [**mlx-swift-asr**](https://github.com/ontypehq/mlx-swift-asr) | On-device speech recognition for Apple Silicon — Qwen3 models via MLX. Powers OnType. |
| [**vox**](https://github.com/celados/vox) | Voice-clone TTS and transcription from the command line. |
| [**sigil**](https://github.com/celados/sigil) | Icon package manager: declare icons in a manifest, vendor them locally, emit SVG / React / Solid. |
| [**solid-conformance**](https://github.com/celados/solid-conformance) | Conformance suite for Solid 2: rendering, streaming SSR, hydration, async transitions. |
| [**skill**](https://github.com/ethan-huo/skill) | Discover, install and update agent skills from GitHub. |
| [**grok-build**](https://github.com/celados/grok-build) | Patch layer and macOS release channel for xAI Grok Build. |
| [**seek**](https://github.com/ethan-huo/seek) | Personal hybrid search — BM25 + vector over notes and Claude Code / Codex conversations. |
| [**apple-docs**](https://github.com/ethan-huo/apple-docs) | Apple Developer Documentation CLI. |

## Stack

**Languages** TypeScript · Swift · Go · Rust · Elixir
**Web** Solid 2 · React · TanStack Start · StyleX · Bun
**Mobile & desktop** Swift / SwiftUI · MLX · Expo
**Data** Convex · PostgreSQL · DuckDB
**Cloud** Cloudflare (Workers, Durable Objects, R2, D1) · Docker · k3s
**AI & agents** CLI and MCP design for agents · on-device ASR / TTS · image-to-video pipelines

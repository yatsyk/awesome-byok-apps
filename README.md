# Awesome BYOK Apps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of apps you can use with your own AI API key.

**BYOK** (Bring Your Own Key) apps let you plug in your own OpenAI,
Anthropic, Google, OpenRouter, or other provider key instead of paying
a subscription markup. You pay the provider directly for tokens, and
your data stays out of an intermediate SaaS.

## Contents

- [Chat UIs](#chat-uis)
- [Code assistants](#code-assistants)
- [IDE and terminal](#ide-and-terminal)
- [Writing and research](#writing-and-research)
- [Translation](#translation)
- [Agents and workflow builders](#agents-and-workflow-builders)
- [Image, audio, and voice](#image-audio-and-voice)
- [Gateways and proxies](#gateways-and-proxies)
- [Providers](#providers)
- [Contributing](#contributing)

## Chat UIs

Multi-provider chat clients — paste your provider key and go.

- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) — Document chat, workspaces, and agents; desktop and server.
- [BetterChatGPT](https://github.com/ztjhz/BetterChatGPT) — Lightweight static web UI for OpenAI.
- [big-AGI](https://github.com/enricoros/big-AGI) — Multi-model workspace with personas, tools, and Beam.
- [Chatbox](https://github.com/Bin-Huang/chatbox) — Cross-platform desktop and mobile chat client.
- [Jan](https://github.com/janhq/jan) — Offline-first desktop app; connects cloud providers or runs local models.
- [LibreChat](https://github.com/danny-avila/LibreChat) — Multi-provider ChatGPT clone with agents, MCP, and RAG.
- [LobeChat](https://github.com/lobehub/lobe-chat) — Polished multi-provider chat with plugins and MCP support.
- [NextChat](https://github.com/ChatGPTNextWeb/NextChat) — Cross-platform (web and Tauri) ChatGPT clone.
- [Open WebUI](https://github.com/open-webui/open-webui) — Self-hosted platform for Ollama and OpenAI with RAG.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern) — Power-user roleplay frontend with per-user secrets.
- [Sleek](https://apps.apple.com/us/app/sleek-byok/id6786075866) — Native iOS OpenRouter client with SillyTavern character-card import.
- [TypingMind](https://www.typingmind.com) — Polished web client with AES-encrypted local storage.

## Code assistants

- [Aider](https://github.com/Aider-AI/aider) — Terminal AI pair-programmer integrated with git.
- [Cline](https://github.com/cline/cline) — Autonomous coding agent for VS Code.
- [Continue](https://github.com/continuedev/continue) — VS Code and JetBrains assistant with custom providers.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) — Agentic VS Code and CLI; fork of Cline and Roo.
- [Open Interpreter](https://github.com/openinterpreter/open-interpreter) — Natural-language shell that runs code locally.
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) — Multi-mode agent team; fork of Cline.
- [Tabby](https://github.com/TabbyML/tabby) — Self-hosted coding assistant you can point at any provider.
- [Zed](https://github.com/zed-industries/zed) — Rust GPU-accelerated editor with an AI Agent Panel.

## IDE and terminal

Built-in BYOK in commercial tools.

- [Cursor](https://docs.cursor.com/settings/models) — AI code editor; add OpenAI, Anthropic, Google, or custom keys.
- [JetBrains AI](https://blog.jetbrains.com/ai/2025/12/bring-your-own-key-byok-is-now-live-in-jetbrains-ides/) — Plug Anthropic or OpenAI keys into JetBrains IDEs.
- [VS Code](https://code.visualstudio.com/blogs/2025/10/22/bring-your-own-key) — Language Model Chat Provider API for custom providers.
- [Warp](https://docs.warp.dev/support-and-community/plans-and-billing/bring-your-own-api-key) — AI terminal with locally stored BYOK.
- [Zed Agent Panel](https://zed.dev/docs/ai/llm-providers) — Supply Anthropic, OpenAI, Google, or Ollama keys.

## Writing and research

- [Glarity](https://github.com/sparticleinc/chatgpt-google-summary-extension) — Browser extension that summarizes search results and YouTube.
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous research agent producing long-form reports.
- [Khoj](https://github.com/khoj-ai/khoj) — Personal AI across browser, desktop, and plugins.
- [Novel](https://github.com/steven-tey/novel) — Notion-style editor with AI commands.
- [OpenGrammar](https://github.com/swadhinbiswas/opengrammar) — Open-source Grammarly alternative.
- [Perplexica](https://github.com/ItzCrazyKns/Perplexica) — Open-source Perplexity-style search.
- [Rewire Text](https://sunsetmesasoftware.com/rewire-text/) — Windows/macOS tool to transform text in any app using a hotkey. Supports BYOK and local AI providers.

## Translation

- [NextAI Translator](https://github.com/nextai-translator/nextai-translator) — Extension and desktop translator across many providers.
- [Read Frog](https://github.com/mengxi-ream/read-frog) — Immersive-translation browser extension with 20+ providers.

## Agents and workflow builders

- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent framework.
- [Flowise](https://github.com/FlowiseAI/Flowise) — Visual low-code agent builder with encrypted credentials.
- [Langflow](https://github.com/langflow-ai/langflow) — Visual AI builder with provider setup and global variables.
- [n8n](https://n8n.io) — Workflow automation with node-level LLM provider credentials.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) — Self-hosted autonomous agent framework.

## Image, audio, and voice

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) — Node-based image pipeline; external provider nodes accept API keys.
- [Fabric](https://github.com/danielmiessler/fabric) — CLI for patterned prompt workflows across providers.
- [LM Studio](https://lmstudio.ai) — Local and cloud model client with provider key fields.
- [Open NotebookLM](https://github.com/lfnovo/open-notebook) — Research and podcast generation with your own STT/TTS keys.

## Gateways and proxies

Run your own BYOK-enabled backend, or use a hosted aggregator.

- [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/configuration/bring-your-own-keys/) — Store provider keys and route at the edge.
- [Helicone](https://github.com/Helicone/helicone) — Observability proxy with BYOK for 100+ providers.
- [LiteLLM](https://github.com/BerriAI/litellm) — Self-hosted proxy unifying 100+ LLM providers.
- [OpenRouter](https://openrouter.ai) — Hosted aggregator; one key for hundreds of models.
- [Portkey](https://portkey.ai) — Managed or self-hosted gateway with budgets and routing.
- [Vercel AI Gateway](https://vercel.com/docs/ai-gateway) — Team-scoped managed gateway with BYOK support.

## Providers

Where to get API keys.

- [Anthropic](https://console.anthropic.com) — Claude; create keys in Console → Settings → API Keys.
- [Cerebras](https://cloud.cerebras.ai) — Ultra-fast inference for Llama and Qwen.
- [Cohere](https://dashboard.cohere.com/api-keys) — Command, Embed, and Rerank models.
- [DeepInfra](https://deepinfra.com/dash/api_keys) — Hosted open-weight inference.
- [DeepSeek](https://platform.deepseek.com) — DeepSeek-V3 and R1 reasoning models.
- [ElevenLabs](https://elevenlabs.io/app/settings/api-keys) — Text-to-speech and voice cloning.
- [Fireworks AI](https://fireworks.ai/account/api-keys) — Fast open-model hosting.
- [Google AI Studio](https://aistudio.google.com/app/apikey) — Gemini family keys with a free tier.
- [Groq](https://console.groq.com/keys) — Free-tier LPU inference for open models.
- [Hugging Face](https://huggingface.co/settings/tokens) — Inference API across thousands of hosted models.
- [Mistral AI](https://console.mistral.ai/api-keys) — Mistral and Codestral models, EU-hosted.
- [OpenAI](https://platform.openai.com/api-keys) — GPT, DALL·E, Whisper, and TTS.
- [OpenRouter](https://openrouter.ai/keys) — One key for hundreds of models across providers.
- [Perplexity](https://www.perplexity.ai/settings/api) — Sonar search-grounded models.
- [Replicate](https://replicate.com/account/api-tokens) — Run open-source models via HTTP.
- [Together AI](https://api.together.xyz/settings/api-keys) — Hosted open-weights inference.
- [xAI](https://console.x.ai) — Grok models.

## Contributing

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

Rules:

- Only include apps or providers that are **live and working**.
- Entries follow `- [Name](link) — Short description.`
- Alphabetical order within each section (case-insensitive).
- No duplicates; merge close entries.
- No key-resellers; disclose affiliation when proposing your own project.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all
copyright and related or neighboring rights to this work.

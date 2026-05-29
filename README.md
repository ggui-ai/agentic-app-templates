# ggui-ai/agentic-app-templates

Three runnable scaffolds for building agentic apps on the
[ggui protocol](https://github.com/ggui-ai/ggui).

## Use it

```bash
npx @ggui-ai/create-agentic-app
```

That tool clones one of the subdirs below into your project dir,
renames packages, and seeds `.env.local`.

## Subdirs

- `claude-agent-sdk/` — Anthropic Claude Agent SDK
- `openai-agents-sdk/` — OpenAI Agents SDK
- `google-adk/` — Google ADK (TypeScript)

## Sourced from

This repo is assembled at sync time from
[ggui-ai/ggui](https://github.com/ggui-ai/ggui) — `oss/samples/*` for
the code, `oss/template-shells/agentic-app-template/<sdk>/` for the
per-SDK wrapper. Do not PR changes here; PR them upstream.

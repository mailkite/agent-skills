<p align="center">
  <a href="https://mailkite.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://mailkite.dev/brand/logo-email-dark.png">
      <img src="https://mailkite.dev/brand/logo-email.png" alt="MailKite" height="56">
    </picture>
  </a>
</p>

<h1 align="center">MailKite Agent Skills</h1>

<p align="center">
  <b>Email for every product you ship</b> — receive email as a webhook, send over a verified domain, give an AI agent its own inbox.
  <br>Official <a href="https://mailkite.dev">MailKite</a> skills for coding agents — Claude Code, Cursor, Codex, Amp, and any agent that speaks the <a href="https://agentskills.io">Agent Skills</a> format.
</p>

<p align="center">
  <a href="https://mailkite.dev/docs">Docs</a> ·
  <a href="https://mailkite.dev/docs/skill">Skill guide</a> ·
  <a href="https://mailkite.dev/docs/ai-agents">AI agents</a> ·
  <a href="https://mailkite.dev">mailkite.dev</a>
</p>
<p align="center"><a href="https://skills.sh/mailkite/agent-skills"><img src="https://skills.sh/b/mailkite/agent-skills" alt="skills.sh"></a></p>

> **Read-only mirror.** This repo is a generated, release-time mirror of the MailKite monorepo (the private source of truth) — development doesn't happen here. Questions and bugs: [MailKite docs](https://mailkite.dev/docs).

## Install

```bash
npx skills add mailkite/agent-skills
```

The [Skills CLI](https://skills.sh) installs into whichever agents you use (Claude Code, Cursor, Codex, Amp, …). Add `-g` for a user-wide install instead of per-project.

## Skills

| Skill | What it does |
| --- | --- |
| [`mailkite`](mailkite/) | Drives the whole MailKite email lifecycle: create an account, add a sending/receiving domain, set its DNS at the user's provider (Cloudflare, GoDaddy, Namecheap, Route 53, …), register a webhook, design templates, send mail, and confirm inbound delivery. Works via the MCP server, the `mailkite` CLI, any language SDK, or raw REST. |

## Other ways to get the skill

- **Claude Code plugin** (skill + MCP server + slash commands, OAuth sign-in):
  `/plugin marketplace add mailkite/claude-code` → `/plugin install mailkite@mailkite`
- **claude.ai / Claude Desktop**: download [`mailkite.zip`](https://github.com/mailkite/claude-code/releases/latest/download/mailkite.zip) and upload it under **Settings → Capabilities → Skills**.

## License

[MIT](LICENSE)

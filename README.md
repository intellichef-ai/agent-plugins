# IntelliChef for Claude and ChatGPT

Plan a meal by chatting with your AI assistant, then cook it together in the IntelliChef app. Every
dish is written so the app can share the work between the people cooking and guide each of them,
step by step, hands-free.

## What's here

| Plugin | Who it's for | Address |
|---|---|---|
| `intellichef-staging` | Invited testers, trying what's coming next | `https://mcp.intellichef.io/mcp` |

A plugin simply connects your assistant to IntelliChef. Everything it knows how to do lives on
IntelliChef's side, so it stays up to date on its own — there is nothing to reinstall.

## Add it to your assistant

You'll need an IntelliChef account to cook what you plan.

### The quickest way: paste the address

Add IntelliChef as a custom connector, using this address, with no sign-in:

- IntelliChef (staging): `https://mcp.intellichef.io/mcp`

- **Claude** (web, desktop or mobile): Customize → Connectors → **Add custom connector** → paste the
  address → choose no sign-in.
- **ChatGPT**: Plugins → **+** → **Add custom MCP server** → paste the address → choose no
  authentication.

### Or install the plugin

- **Claude**: Customize → Plugins → **Add marketplace** → enter `intellichef-ai/agent-plugins`, then
  install the plugin. Or download the plugin's zip file from
  [Releases](https://github.com/intellichef-ai/agent-plugins/releases), then Add → **Upload plugin**.
- **ChatGPT**: download the plugin's zip file from
  [Releases](https://github.com/intellichef-ai/agent-plugins/releases), then Plugins → **+** →
  **Upload plugin archive**.
- **Claude Code**: `/plugin marketplace add intellichef-ai/agent-plugins`, then
  `/plugin install <plugin>@intellichef`.
- **Codex**: `codex plugin marketplace add intellichef-ai/agent-plugins`.

## Using it

Start a new chat and plan a meal the way you normally would: what you feel like, who's coming, how
much time you have. When it looks right, ask your assistant to cook it in IntelliChef. It will give
you a link that opens the meal in the app.

---

Built from intellichef@76c636a.

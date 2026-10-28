# IntelliChef for Claude and ChatGPT

Plan a meal by chatting with your AI assistant, then cook it together in the IntelliChef app. Every
dish is written so the app can share the work between the people cooking and guide each of them,
step by step, hands-free.

| Plugin | Who it's for |
|---|---|
| **IntelliChef (staging)** | Invited testers, trying what's coming next |

You'll need an IntelliChef account to cook what you plan.

## Add it to ChatGPT

1. Open **Plugins**, press **Add**, and choose **Add a marketplace**.
2. Enter `intellichef-ai/agent-plugins`.
3. That adds IntelliChef's marketplace, but not the plugin yet. Open the marketplace, choose the
   plugin from the table above, and press **Install**.

## Add it to Claude

On the web, the desktop app or the mobile app:

1. Open **Customize**, then **Plugins**, press **Add**, and choose **Add marketplace**.
2. Choose **Add from a repository**, and enter `intellichef-ai/agent-plugins`.
3. Claude shows the plugins it found there. Press **Add** beside the one from the table above.

## Using it

Start a new chat and plan a meal the way you normally would: what you feel like, who's coming, how
much time you have. When it looks right, ask your assistant to cook it in IntelliChef. It will give
you a link that opens the meal in the app.

Once installed, the plugin keeps itself up to date. Everything it knows how to do lives on
IntelliChef's side, so there's nothing to reinstall.

## Other ways to add it

### Upload the plugin file

If adding the marketplace doesn't work for you, download the plugin's zip file from
[Releases](https://github.com/intellichef-ai/agent-plugins/releases) and upload it:

- **ChatGPT:** **Plugins**, then **Add**, then **Upload plugin archive**.
- **Claude:** **Customize**, then **Plugins**, then **Add**, then **Upload plugin**.

A plugin added this way doesn't update on its own: download the newest zip when a new release comes
out.

### Paste the address

Both assistants can also connect to IntelliChef directly, without a plugin, as a custom connector:

- **ChatGPT:** **Plugins**, then **Add**, then **Add custom MCP server**.
- **Claude:** **Customize**, then **Connectors**, then **Add custom connector**.

Paste this address, and choose no sign-in:

- IntelliChef (staging): `https://mcp.intellichef.io/mcp`

### For developers

- **Claude Code:** `/plugin marketplace add intellichef-ai/agent-plugins`, then
  `/plugin install <plugin>@intellichef`.
- **Codex:** `codex plugin marketplace add intellichef-ai/agent-plugins`.

---

Built from intellichef@c943679.

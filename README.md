# IntelliChef for Claude and ChatGPT

Plan a meal by chatting with your AI assistant, then cook it together in the IntelliChef app. Every
dish is written so the app can share the work between the people cooking and guide each of them,
step by step, hands-free.

You add IntelliChef to your assistant once, with its address:

- IntelliChef (staging): `https://mcp.intellichef.io/mcp`

You'll need an IntelliChef account to cook what you plan.

## Add it to ChatGPT

1. Open [chatgpt.com](https://chatgpt.com) in a browser and sign in. The ChatGPT app can't add
   IntelliChef, but it shows it once it's added.
2. Go to **Plugins**, press **Add**, and choose **Add custom MCP server**.
3. Name it **IntelliChef**, paste the address, and choose **No authentication**.
4. ChatGPT asks this for every server it doesn't know yet: tick **I understand and want to
   continue**, and add it.

## Add it to Claude

1. In the Claude app or at [claude.ai](https://claude.ai), open **Connectors** and press **+**.
2. Choose **Add custom connector**, name it **IntelliChef**, paste the address, and press **Add**.
3. Claude checks it and finds that no sign-in is needed: press **Connect**.

## Using it

Start a new chat and say what you'd like to cook, for example: *"Plan a weeknight dinner for two,
and save it to IntelliChef."* When it looks right, your assistant gives you a link that opens the
meal in the app.

IntelliChef stays up to date on its own: everything it knows how to do lives on IntelliChef's side,
so there's nothing to reinstall.

## Other ways to add it

### From this repository, on a computer

Both assistants can also add IntelliChef from this repository, as a plugin:

- **ChatGPT:** **Plugins**, then **Add**, then **Add a marketplace**. Enter
  `intellichef-ai/agent-plugins`, then open the marketplace, choose the plugin, and press
  **Install**.
- **Claude:** **Customize**, then **Plugins**, then **Add**, then **Add marketplace**. Choose **Add
  from a repository**, enter `intellichef-ai/agent-plugins`, and press **Add** beside the plugin.

| Plugin | Who it's for |
|---|---|
| **IntelliChef (staging)** | Invited testers, trying what's coming next |

### Upload the plugin file

Download the plugin's zip file from
[Releases](https://github.com/intellichef-ai/agent-plugins/releases) and upload it:

- **ChatGPT:** **Plugins**, then **Add**, then **Upload plugin archive**.
- **Claude:** **Customize**, then **Plugins**, then **Add**, then **Upload plugin**.

A plugin added this way doesn't update on its own: download the newest zip when a new release comes
out.

### For developers

- **Claude Code:** `/plugin marketplace add intellichef-ai/agent-plugins`, then
  `/plugin install <plugin>@intellichef`.
- **Codex:** `codex plugin marketplace add intellichef-ai/agent-plugins`.

---

Built from intellichef@c77ba62.

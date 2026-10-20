# Bubble for agents

Connect your AI agent to your [Bubble](https://bubble.io) apps and build by
describing what you want. The agent can read your app's structure (pages,
reusables, data types, option sets, styles, and workflows) and make changes the
same way the Bubble editor does. See Bubble's
[MCP guide](https://manual.bubble.io/help-guides/ai/bubble-mcp) for more.

Each plugin here adds one MCP server, `bubble`, at `https://mcp.bubble.io/mcp`
(Streamable HTTP, OAuth 2.1). On first connection, your agent opens Bubble's
sign-in in your browser. Approve access with the Bubble account whose apps you
want it to work on. No API key is needed.

## Install

- **ChatGPT and Codex:** find **Bubble** in OpenAI's plugin directory, in
  ChatGPT or Codex.
- **Grok Build:** open `/plugin`, search for **Bubble**, and install.
- **Cursor:** install **Bubble** from the Cursor Marketplace.

## Using it in Cursor

The plugin needs Cursor 3.10.17 or later. Once installed, the `bubble` MCP
server is listed under **Customize**. Sign in when Cursor asks, then ask the
agent about an app by name, for example "List the pages in my-app" or "Add a
status field to the Order data type in my-app". There's nothing to configure.

## License

[Apache-2.0](LICENSE). The license doesn't cover the Bubble name or logos. Use
of the hosted MCP server is governed by Bubble's terms of service.

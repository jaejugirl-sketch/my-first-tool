# my-first-tool

Project configured to use the **schoolinfo** MCP server (Korean school
information — meals, schedules, exams, curriculum, disclosures, etc.),
served over HTTP at `https://mcp.gomdori.app/school`.

## MCP setup

The server is committed to this repo in [`.mcp.json`](./.mcp.json), so any
Claude Code session opened here picks it up automatically. This is the
project-scoped equivalent of running:

```sh
claude mcp add --transport http schoolinfo https://mcp.gomdori.app/school
```

When you first use the server in a session, Claude Code will ask you to
approve the project-scoped MCP server. Verify it is listed with:

```sh
claude mcp list
```

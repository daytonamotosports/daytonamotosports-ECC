# daytonamotosports copy of ECC

Pinned copy of https://github.com/affaan-m/ECC at commit
e482e579415fde18357cafce70f177ae19fd7f03 (plugin version 2.2.2, MIT license).
Nothing here changes unless we update it on purpose.

Changes from upstream:
- `hooks/hooks.json` renamed to `hooks/hooks.json.disabled`: no ECC hooks run.
  Rename it back to re-enable them.
- `userConfig.hooks_enabled` defaults to `false` in `.claude-plugin/plugin.json`.
- `.mcp.json` emptied: the `chrome-devtools-mcp@latest` server was unpinned.
- `.github/workflows` and `.github/dependabot.yml` removed (upstream CI, releases and scheduled jobs).

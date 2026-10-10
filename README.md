# macp-sh Claude Code plugins

A Claude Code plugin marketplace. See [Install plugins](https://code.claude.com/docs/en/plugins/install) for how plugins work.

| Plugin | What it does | Install (inside a Claude Code session) |
| :- | :- | :- |
| [md-scrub](https://github.com/macp-sh/md-scrub) | Checks every Markdown file Claude writes and removes content you've ruled out, such as third-party legal terms | `/plugin install md-scrub --marketplace macp-sh/claude-plugins` |

The install command adds this marketplace the first time. After that, install by name (`/plugin install <name>@macp-sh`) or browse in `/plugin` under Discover.

## Updates

Plugins from this marketplace don't update automatically unless you turn it on: in `/plugin`, open Marketplaces, select `macp-sh`, then Enable auto-update. Otherwise, run `/plugin marketplace update macp-sh` to fetch new versions.

## Licence

MIT. See [LICENSE](LICENSE).

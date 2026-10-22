# Claude plugins

Plugins for [Claude Code](https://claude.com/claude-code) by [jonw09](https://github.com/jonw09).

| Plugin | What it does |
| --- | --- |
| [Context Canopy](https://github.com/jonw09/claude-context-canopy) | A band above the prompt showing plan limits, session usage by model, and a live tree of agents with their context health. |

<a href="https://github.com/jonw09/claude-context-canopy"><img src="https://raw.githubusercontent.com/jonw09/claude-context-canopy/main/docs/images/band.png" alt="Context Canopy above the Claude Code prompt, showing plan windows, session usage by model and a tree of agents with context bars"></a>

## Install

**In Claude Code** (at the prompt of a terminal session), run these one at a time:

```
/plugin marketplace add jonw09/claude-plugins
/plugin install context-canopy@jonw09
```

**From a shell:**

```
claude plugin install context-canopy --marketplace jonw09/claude-plugins
```

**In the desktop app:** click **+** next to the prompt box, choose **Plugins**, then **Add marketplace** and enter `jonw09/claude-plugins`, then **Add plugin**.

Each plugin's page covers what it shows, its settings and its commands.

## Updates

New plugins and releases appear here on their own. To fetch them, run `claude plugin marketplace update jonw09`, then `claude plugin update <plugin>` and restart Claude Code.

## Adding a plugin

Each plugin has its own repo. To list one here, add an entry to `.claude-plugin/marketplace.json` that points at that repo, on a branch with a pull request into `main`.

## Licence

[MIT](LICENSE)

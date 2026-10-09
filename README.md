# Helios Skills (deprecated)

> **This repository is deprecated.** The Helios skills and the Helios agent plugin now live in the main Helios repository, [BintzGavin/helios](https://github.com/BintzGavin/helios). This repository gets no further updates. Install from the main repository instead.

| What | Old location (here) | New location |
| --- | --- | --- |
| Agent plugin (`make-video` skill, MCP server, manifests, assets) | `plugins/helios/` | [`plugins/helios/`](https://github.com/BintzGavin/helios/tree/main/plugins/helios) |
| Skill catalog | `skills/` | [`skills/`](https://github.com/BintzGavin/helios/tree/main/skills) |
| Claude Code marketplace | `.claude-plugin/marketplace.json` | [`.claude-plugin/marketplace.json`](https://github.com/BintzGavin/helios/blob/main/.claude-plugin/marketplace.json) |
| Codex marketplace | `.agents/plugins/marketplace.json` | [`.agents/plugins/marketplace.json`](https://github.com/BintzGavin/helios/blob/main/.agents/plugins/marketplace.json) |

## Install from BintzGavin/helios

### Skills, via skills.sh

```bash
npx skills add BintzGavin/helios
```

The [skills CLI](https://skills.sh) lists `make-video` and the rest of the catalog so you can pick the ones you want. To install one skill by path:

```bash
npx skills add BintzGavin/helios/plugins/helios/skills/make-video
npx skills add BintzGavin/helios/skills/getting-started
npx skills add BintzGavin/helios/skills/guided/promo-video
```

Every path that used to start with `BintzGavin/helios-skills/` now starts with `BintzGavin/helios/`.

### Claude Code plugin

```text
/plugin marketplace add BintzGavin/helios
/plugin install helios@helios
```

If you added the old marketplace, remove it first, since both marketplaces are named `helios`:

```text
/plugin marketplace remove helios
```

### Codex plugin

```bash
codex plugin marketplace add BintzGavin/helios
codex plugin add helios@helios
```

If you added the old marketplace, remove it first: both marketplaces are named `helios`.

## Already installed?

Skills you installed from this repository keep working, but they won't get updates. Re-run the install commands above to switch to the maintained copies. To update skills installed with the skills CLI, add them again from `BintzGavin/helios`.

## License

The skills and the plugin remain licensed under the [Apache License 2.0](https://github.com/BintzGavin/helios/blob/main/skills/LICENSE) in their new home. The rest of the Helios repository, including the engine, is licensed under the Elastic License 2.0 unless a file or folder says otherwise.

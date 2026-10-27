<!--
Profile README. Published 2026-10-26.

What updates itself: the org stars and plugin counts, every release and last-commit badge, the studio up-check,
the two activity cards, the star-history chart, and the merged-PR and issue counts under "Upstream contributions".
What you edit by hand: the word badges (Stable, Beta, Start here, New), the descriptions, and which projects appear.
Remove the "New" badge from starlight-visual-customizer after 2026-11-08 (30 days after its first release).
The activity cards and star chart come from free community services that can rate-limit; shields.io is the
dependable layer.
-->

<div align="left">

# Jonathan Prisant

**Open-source tooling that makes AI agents useful at product work, plus the desktop utilities I built to survive my own workflow.**

<p>
  <a href="https://github.com/product-on-purpose"><img src="https://img.shields.io/badge/org-Product%20on%20Purpose-7c3aed?style=flat-square" alt="Product on Purpose"></a>
  <a href="https://github.com/prisant-labs"><img src="https://img.shields.io/badge/org-Prisant%20Labs-ea580c?style=flat-square" alt="Prisant Labs"></a>
  <img src="https://img.shields.io/badge/built%20for-Claude%20Code%20%C2%B7%20Codex%20%C2%B7%20MCP-2563eb?style=flat-square" alt="Built for Claude Code, Codex, MCP">
</p>
<p>
  <a href="https://github.com/product-on-purpose"><img src="https://img.shields.io/github/stars/product-on-purpose?style=flat-square&label=Product%20on%20Purpose%20stars&color=7c3aed&logo=github" alt="Stars across Product on Purpose"></a>
  <a href="https://github.com/product-on-purpose/agent-plugins"><img src="https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/product-on-purpose/agent-plugins/main/.claude-plugin/marketplace.json&query=%24.plugins.length&label=Product%20on%20Purpose%20plugins&color=7c3aed&style=flat-square" alt="Plugins in the Product on Purpose marketplace"></a>
  <a href="https://github.com/prisant-labs/agent-plugins"><img src="https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/prisant-labs/agent-plugins/main/.claude-plugin/marketplace.json&query=%24.plugins.length&label=Prisant%20Labs%20plugins&color=ea580c&style=flat-square" alt="Plugins in the Prisant Labs marketplace"></a>
</p>
<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=jprisant&hide=stars&hide_rank=true&show_icons=true&hide_border=true&theme=github_dark">
    <img src="https://github-readme-stats.vercel.app/api?username=jprisant&hide=stars&hide_rank=true&show_icons=true&hide_border=true" alt="Commits, pull requests, issues, and repos contributed to by jprisant" height="165">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=jprisant&hide_border=true&hide_current_streak=true&hide_longest_streak=true&card_width=300&theme=github-dark-blue">
    <img src="https://streak-stats.demolab.com?user=jprisant&hide_border=true&hide_current_streak=true&hide_longest_streak=true&card_width=300" alt="Total GitHub contributions by jprisant" height="165">
  </picture>
</p>

</div>

I'm a product leader in church technology who gets unreasonably excited about solving problems, serving people, and designing elegant systems. I build in the open across two organizations, and each one has its own job.

- [**Product on Purpose**](https://github.com/product-on-purpose) is the public library. Its skills, standards, and templates turn a blank-slate agent into a capable product partner.
- [**Prisant Labs**](https://github.com/prisant-labs) is the workshop. Its small, sharp tools started as things I needed, then got cleaned up for everyone else.

The plugins install from two marketplaces. In Claude Code, add each one once:

```
/plugin marketplace add product-on-purpose/agent-plugins
/plugin marketplace add prisant-labs/agent-plugins
```

Some plugins, such as prisant-powertools, also install in Codex with `codex plugin marketplace add prisant-labs/agent-plugins`.

---

## [Product on Purpose](https://github.com/product-on-purpose)

*Open-source tools for product managers and the AI agents working alongside them.*

### Product work

- 🧭 **[pm-skills](https://github.com/product-on-purpose/pm-skills)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/pm-skills?display_name=tag&style=flat-square&label=release)<br>68 plug-and-play product management skills covering the full product lifecycle

- 📐 **[product-lifecycle-templates](https://github.com/product-on-purpose/product-lifecycle-templates)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![Experimental](https://img.shields.io/badge/-Experimental-6e7781?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/product-lifecycle-templates?display_name=tag&style=flat-square&label=release)<br>Governed document templates that ship with the research, the guide, and a worked example

### Thinking, writing, and critique

- 🤔 **[thinking-framework-skills](https://github.com/product-on-purpose/thinking-framework-skills)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/thinking-framework-skills?display_name=tag&style=flat-square&label=release)<br>Evidence-graded thinking methods an agent can run to reason, not just chat

- 🔍 **[critique-skills](https://github.com/product-on-purpose/critique-skills)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/critique-skills?display_name=tag&style=flat-square&label=release)<br>Critique that cites a published rubric on every finding, and publishes how often it is right

- 🎨 **[writing-style-catalog](https://github.com/product-on-purpose/writing-style-catalog)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![Experimental](https://img.shields.io/badge/-Experimental-6e7781?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/writing-style-catalog?display_name=tag&style=flat-square&label=release)<br>Composable writing instructions so AI prose lands in the voice you actually want

### Building and distributing skills

- 🤖 **[agent-skills-toolkit](https://github.com/product-on-purpose/agent-skills-toolkit)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/agent-skills-toolkit?display_name=tag&style=flat-square&label=release)<br>A standard and toolkit for grading skill libraries to a Bronze/Silver/Gold bar

- 🧩 **[agent-plugins](https://github.com/product-on-purpose/agent-plugins)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square)<br>The plugin marketplace to install from

### In maintenance

- 🧰 **[pm-skills-mcp](https://github.com/product-on-purpose/pm-skills-mcp)** ![Maintenance](https://img.shields.io/badge/-Maintenance-8b5e3c?style=flat-square) ![release](https://img.shields.io/github/v/release/product-on-purpose/pm-skills-mcp?display_name=tag&style=flat-square&label=release)<br>The PM catalog as an MCP server

All 8 projects, with install commands, release notes, and a status line for each, are on the [Product on Purpose page](https://github.com/product-on-purpose).

---

## [Prisant Labs](https://github.com/prisant-labs)

*Tailored tools for people who tinker or live in their editors, agents, and file systems.*

### Agent tooling

- 🔧 **[prisant-powertools](https://github.com/prisant-labs/prisant-powertools)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/prisant-powertools?display_name=tag&style=flat-square&label=release)<br>Ten agent skills for session continuity, decision briefs, peer review, specs, audits, and release planning

- 📚 **[nonfiction-studio](https://github.com/prisant-labs/nonfiction-studio)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/nonfiction-studio?display_name=tag&style=flat-square&label=release)<br>A Claude Code and Cowork plugin that takes a non-fiction book from intake interview to fact-checked manuscript

- 🚚 **[agent-workspace-tools](https://github.com/prisant-labs/agent-workspace-tools)** ![Pre-release](https://img.shields.io/badge/-Pre--release-bc4c00?style=flat-square) ![last commit](https://img.shields.io/github/last-commit/prisant-labs/agent-workspace-tools?style=flat-square&label=last%20commit)<br>`awt`, an offline CLI that moves a project and its Claude Code history together

- 🧩 **[agent-plugins](https://github.com/prisant-labs/agent-plugins)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square)<br>The plugin marketplace to install from

### Knowledge and writing tools

- 🔖 **[obsidian-tag-visibility](https://github.com/prisant-labs/obsidian-tag-visibility)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/obsidian-tag-visibility?display_name=tag&style=flat-square&label=release)<br>Hide and flag noisy tags across a vault without editing notes

- 📦 **[obsidian-vault-collection](https://github.com/prisant-labs/obsidian-vault-collection)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/obsidian-vault-collection?display_name=tag&style=flat-square&label=release)<br>Answer-keyed test vaults and starter vaults for PKM methods and roles

- 📑 **[typora-plugin-outline-view](https://github.com/prisant-labs/typora-plugin-outline-view)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/typora-plugin-outline-view?display_name=tag&style=flat-square&label=release)<br>A synchronized outline in Typora's right dock

- ⭐ **[typora-plugin-favorite-folders-files](https://github.com/prisant-labs/typora-plugin-favorite-folders-files)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/typora-plugin-favorite-folders-files?display_name=tag&style=flat-square&label=release)<br>Favorite folders and Markdown files one click away in Typora

- 🖌️ **[starlight-visual-customizer](https://github.com/prisant-labs/starlight-visual-customizer)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![New](https://img.shields.io/badge/-New-8250df?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/starlight-visual-customizer?display_name=tag&style=flat-square&label=release) [![studio](https://img.shields.io/website?url=https%3A%2F%2Fprojects.prisantlabs.com%2Fstarlight-visual-customizer%2Fstudio%2F&style=flat-square&label=studio)](https://projects.prisantlabs.com/starlight-visual-customizer/studio/)<br>A browser theme editor for Starlight docs sites that exports one CSS file

### Desktop utilities

- 🔄 **[repo-sync-tool](https://github.com/prisant-labs/repo-sync-tool)** ![Beta](https://img.shields.io/badge/-Beta-9a6700?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/repo-sync-tool?display_name=tag&include_prereleases&style=flat-square&label=release)<br>A tray app that keeps cloned repos fresh without touching your work

- 🎧 **[audiobook-organizer](https://github.com/prisant-labs/audiobook-organizer)** ![Pre-release](https://img.shields.io/badge/-Pre--release-bc4c00?style=flat-square) ![last commit](https://img.shields.io/github/last-commit/prisant-labs/audiobook-organizer?style=flat-square&label=last%20commit)<br>Scan an audiobook library and rehearse a tidy-up before anything moves

### 3D print models

- 🔌 **[3d-cable-box-parametric-openscad](https://github.com/prisant-labs/3d-cable-box-parametric-openscad)** ![Stable](https://img.shields.io/badge/-Stable-1a7f37?style=flat-square) ![Start here](https://img.shields.io/badge/-Start%20here-0969da?style=flat-square) ![release](https://img.shields.io/github/v/release/prisant-labs/3d-cable-box-parametric-openscad?display_name=tag&style=flat-square&label=release)<br>A parametric cable box with bed slicing and snap-fit seams

- 🌱 **[3d-yard-spike-parametric-openscad](https://github.com/prisant-labs/3d-yard-spike-parametric-openscad)** ![Pre-release](https://img.shields.io/badge/-Pre--release-bc4c00?style=flat-square)<br>A parametric ground spike for posts and tubing that prints without supports

All 13 projects, with install commands, release notes, and a status line for each, are on the [Prisant Labs page](https://github.com/prisant-labs).

---

## Upstream contributions

*Fixes and features for tools I use every day, sent to the people who maintain them.*

- 🗂️ **[claude-code-history-viewer](https://github.com/jhlee0409/claude-code-history-viewer)** ![stars](https://img.shields.io/github/stars/jhlee0409/claude-code-history-viewer?style=flat-square&label=stars) [![merged PRs](https://img.shields.io/github/issues-search/jhlee0409/claude-code-history-viewer?query=is%3Apr%20author%3Ajprisant%20is%3Amerged&label=my%20merged%20PRs&color=1a7f37&style=flat-square)](https://github.com/jhlee0409/claude-code-history-viewer/pulls?q=is%3Apr+author%3Ajprisant+is%3Amerged)<br>A desktop app for browsing AI coding assistant history. I built its Recent Edits panel, its session minimap, its turn outline, and keyboard jumps between prompts. I also fixed a test that overwrote a developer's real `~/.claude/settings.json`.

- ✍️ **[markdown-for-humans](https://github.com/concretios/markdown-for-humans)** [![merged PRs](https://img.shields.io/github/issues-search/concretios/markdown-for-humans?query=is%3Apr%20author%3Ajprisant%20is%3Amerged&label=my%20merged%20PRs&color=1a7f37&style=flat-square)](https://github.com/concretios/markdown-for-humans/pulls?q=is%3Apr+author%3Ajprisant+is%3Amerged)<br>A WYSIWYG Markdown editor for VS Code. I added the editor theme override, with a setting and a toolbar toggle.

- 📁 **[QuickPane](https://github.com/lso2/QuickPane)** [![issues reported](https://img.shields.io/github/issues-search/lso2/QuickPane?query=author%3Ajprisant&label=issues%20reported&color=0969da&style=flat-square)](https://github.com/lso2/QuickPane/issues?q=author%3Ajprisant)<br>A folder pane inside Windows File Explorer. I reported bugs and gaps upstream, and I keep [a fork](https://github.com/jprisant/QuickPane) that fixes them and adds unit tests and CI.

---

<div align="center">

Mostly JavaScript, TypeScript, Python, and Rust, with some C# and a little OpenSCAD.

</div>

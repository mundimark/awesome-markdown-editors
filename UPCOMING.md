# Awesome Markdown Editors & (Pre)viewers  - What's News (Upcoming) in 2026?


A collection of awesome markdown editors and (pre)viewers
for Linux, Apple OS X, Microsoft Windows, the World Wide Web and more.


<!-- please, add your app, tool, library, service to the best matching category. thanks!
  -->




## Markdown Online Editors

**LiteNoter**
(web: [`litenoter.com/tools/free-markdown-editor/`](https://litenoter.com/tools/free-markdown-editor/)) - Free browser-based visual Markdown editor for headings, lists, and tables, with export to Markdown, HTML, and PDF. Document processing stays in the browser and requires no account.


**markupmarkdown**
(web: [`mumd.metavert.io`](https://mumd.metavert.io), open source @ github [`jonradoff/markupmarkdown`](https://github.com/jonradoff/markupmarkdown)) -
"Google Docs for Markdown" — collaborative editor and review tool for Markdown files: anchored comment threads on any text selection, suggested changes with one-click apply, review states (approve / request changes), document checks, and GitHub round-trip (open any repo's `.md`, edit, push back as a PR). Includes an MCP server so AI agents can comment, suggest, and review through the same loop as humans. MIT licensed, built with Go + React.




**MDXG Redline**
(web: [`mkdn.review`](https://mkdn.review/?url=https%3A%2F%2Fraw.githubusercontent.com%2Foubakiou%2Fmdxg-redline%2Frefs%2Fheads%2Fmain%2FREADME.md), open source @ github [`oubakiou/mdxg-redline`](https://github.com/oubakiou/mdxg-redline)) -
Read-only Markdown (pre)viewer with inline review comments, distributed as a single standalone HTML file (also runnable via `npx mdxg-redline`). Implements the MDXG Viewer profile: Word/Pages-style stacked virtual pages, page navigation and outline, in-document search, and left-hand WASD keyboard navigation. Renders Shiki syntax highlighting (~235 languages), Mermaid diagrams, KaTeX math, and GitHub Flavored Markdown footnotes, with smartphone support. Select any text range to leave a comment; comments export as structured JSON keyed by headingPath and sourceLine, so an LLM agent can apply each one back to the exact lines. The standalone/CLI build makes no network requests (CSP connect-src 'none'); an optional online edition at mkdn.review fetches Markdown from an allowlisted public raw URL via a `?url=` parameter. MIT licensed.






## Markdown Desktop Editors


### Editor Plugins


**Markdown Table Editor**
(web: [`markdowntableeditor.krot.name`](https://markdowntableeditor.krot.name/),
 JetBrains Marketplace: [`Markdown Table Editor`](https://plugins.jetbrains.com/plugin/32159-markdown-table-editor),
 open source @ github [`krotname/IdeaMarkdownTableEditor`](https://github.com/krotname/IdeaMarkdownTableEditor),
 [`krotname/NppMarkdownTableEditor`](https://github.com/krotname/NppMarkdownTableEditor)) -
Open-source plugins for editing Markdown pipe tables inside JetBrains IDEs and Notepad++.
Features include table alignment, row and column operations, sorting, width fitting, CSV/TSV conversion,
escaped pipe handling, Unicode/CJK width support, release ZIPs, tests, and CI.


### Universal


**Binderus** 
(web: [`binderus.com`](https://www.binderus.com), open source frontend @ github [`binderus/binderus`](https://github.com/binderus/binderus)) -
Local-first note-taking app with Notion-style WYSIWYG editing for plain text and Markdown files, Obsidian-style philosophy for local files, a plugin system with AI/LLM plugin, custom themes, and optional encrypted vaults. No cloud, no account, no subscription. ~9 MB, built with Tauri + Rust, works on Windows, Mac, and Linux.


**Glyph**
(open source @ github [`hamidfzm/glyph`](https://github.com/hamidfzm/glyph)) -
Cross-platform native Markdown viewer and editor built with Tauri 2 (Rust + React 19). Features GitHub Flavored Markdown, KaTeX math, Mermaid diagrams, wikilinks with backlinks, multi-file tabs, 6 syntax themes, AI summarization (Claude/OpenAI/Ollama), text-to-speech, and platform-native styling. Offline-first, MIT licensed. Works on macOS, Windows, and Linux.


****Huiyu MD**
(open source @ github [huiyu9144/Huiyu-MD](https://github.com/huiyu9144/Huiyu-MD)) -
Minimal, lightning-fast Markdown reader for Windows & macOS. Built with Tauri 2.0 (Rust + React). Features dark/light themes with auto-persist, Ctrl+scroll zoom (25%-400%), KaTeX math formula rendering, code blocks with syntax highlighting and one-click copy, drag & drop file opening, auto file association, and a right-click context menu. Only ~5 MB, starts instantly (< 0.3s), zero white flash. macOS builds are code-signed and notarized by Apple.


**Markra**
(web: [`editor.markra.app`](https://editor.markra.app/), open source @ github [`murongg/markra`](https://github.com/murongg/markra)) -
Local-first WYSIWYG Markdown editor for plain `.md` files with source mode, AI edit preview, multi-provider AI settings, and cross-platform Tauri desktop builds. AGPL-3.0 licensed.


MDHero**
(web: [`mdhero.app`](https://mdhero.app)), open source @ github [`vaibhavuk-dev/mdhero`](https://github.com/vaibhavuk-dev/mdhero)) -
Reading-first native Markdown viewer for macOS and Windows with a lightweight editor mode. Built with Tauri 2 + SvelteKit, ~8 MB — vs. 100-200 MB for Electron-based alternatives. Renders KaTeX math, Mermaid diagrams, and syntax-highlighted code via highlight.js (~25 languages). Features tab-based navigation with persisted edit state, table-of-contents sidebar, pinned project folders, Vim keybindings (j/k/gg/G), source-line scroll sync between viewer/raw/editor modes, Open URL fetcher for GitHub/GitLab/Bitbucket files, an LLM paste mode that auto-unescapes `\n` and `\"` from ChatGPT/Claude output, and an optional Close-on-Escape mode for file-manager viewer usage. Press Cmd+E to edit, Cmd+S to save. MIT licensed. No user tracking — anonymous update checks send only OS family and version.

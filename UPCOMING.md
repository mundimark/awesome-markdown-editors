# Awesome Markdown Editors & (Pre)viewers  - What's News (Upcoming) in 2026?

A collection of awesome markdown editors and (pre)viewers
for Linux, Apple OS X, Microsoft Windows, the World Wide Web and more.

<!-- please, add your app, tool, library, service to the best matching category. thanks!
  -->


## Markdown Online Editors

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

**MD Preview**
(web: [`vorojar.github.io/md-preview`](https://vorojar.github.io/md-preview/), open source @ github [`vorojar/md-preview`](https://github.com/vorojar/md-preview)) -
Ultra-lightweight cross-platform Markdown preview app built with Rust and the system WebView. Preview-first, no Electron or bundled browser, with GitHub Flavored Markdown, syntax highlighting, KaTeX math, Mermaid diagrams, dark mode, print support, live reload, and a small inline edit mode for quick fixes. Ships signed and notarized macOS DMG plus Windows and Linux builds.

**Noteriv**
(web: [`noteriv.com`](https://www.noteriv.com), open source @ github [`thejacedev/Noteriv`](https://github.com/thejacedev/Noteriv)) -
Local-first Markdown note-taking app built with Tauri 2 (Rust + Next.js). Organizes `.md` files into vaults with wiki-links, backlinks, a force-directed graph view, kanban board, daily notes, full-text search, KaTeX math, Mermaid diagrams, and a `[TOC]` widget. Extensible via a plugin API and custom CSS themes, with Git and WebDAV sync. Cross-platform (Linux, macOS, Windows), MIT licensed.


### Linux

**qnote** 
(open source @ github [`Omibranch/qnote`](https://github.com/Omibranch/qnote)) - 
Minimal frameless notepad for Linux built with Tauri 2 (Rust + TypeScript). Features Markdown editing with live preview, real PDF export via Typst, OCR via Tesseract, automatic version history with snapshots, dark/light themes, and custom fonts. Available on AUR.


### Microsoft Windows

**Markdown Studio**
(open source @ github [`Financialnews-ops/markdown-studio-by-htny`](https://github.com/Financialnews-ops/markdown-studio-by-htny)) -
Desktop Markdown editor for Windows with live preview and independently toggleable editor/preview panes. Built with Electron, parsing via marked and HTML sanitized with DOMPurify. Includes a formatting toolbar (headings, bold, italic, strikethrough, inline code, quotes, ordered/unordered lists, links, images, tables) and one-click export to PDF, DOCX (Word), and Obsidian-flavored Markdown, plus PDF text import. Fully offline — documents stay in a local `Documents/MarkdownStudio` folder. Ships an NSIS installer via signed-tag GitHub Releases. MIT licensed.

**Tinta**
(web: [`tinta.cc`](https://tinta.cc), open source @ github [`oipoistar/tinta`](https://github.com/oipoistar/tinta)) -
Fast, lightweight Markdown viewer and reader for Windows built with native C++ and Direct2D/DirectWrite for hardware-accelerated text rendering -- a single portable exe under 1 MB that cold-starts in ~200 ms, no Electron, no bundled browser, no installer. Designed as the double-click default for `.md` files: 10 themes (5 light, 5 dark incl. an OLED-friendly pure black), table of contents, folder browser, full-text search, rich tables, text selection, Ctrl+scroll zoom, drag & drop, and an edit mode with live preview. Installable via Scoop. MIT licensed.


### Apple Mac OS X

**Sly**
(open source @ github [`waynevernon/sly`](https://github.com/waynevernon/sly)) -
Markdown notes and tasks for macOS. Sly turns a folder of Markdown files into a keyboard-friendly writing and planning workspace with a rich text editor, Markdown source mode, task views, fast search, wikilinks, Mermaid diagrams, KaTeX math, Git support, optional AI helpers, and a CLI for terminal workflows.

**Glance**
(web: [`technol.io/en/glance`](https://www.technol.io/en/glance), open source @ github [`baladi39/glance`](https://github.com/baladi39/glance)) -
Native macOS Markdown viewer built with Tauri 2 (Rust + TypeScript). View-only — no editing, no cloud, no accounts. Features syntax highlighting via Shiki (100+ languages), mermaid diagram rendering, auto-generated table of contents, GFM task lists, file watching with auto-reload and change highlighting, and drag-and-drop file opening. Privacy-first: remote images blocked by default, zero telemetry. ~8 MB, launches instantly.


**Kuku**
(web: [`kuku.mom`](https://kuku.mom), open source @ github [`kuku-mom/kuku`](https://github.com/kuku-mom/kuku)) -
Open-source local-first Markdown workspace for macOS. Kuku keeps notes as ordinary `.md` files in a local vault while adding search, backlinks, graph navigation, Second Brain workflows, AI-assisted edits, reviewable diffs, and optional encrypted sync.

**marka.md**
(web: [`markamd.vercel.app`](https://markamd.vercel.app), open source @ github [`mattenarle10/markamd`](https://github.com/mattenarle10/markamd)) - 
Local-first macOS Markdown editor built with Tauri 2 (Rust + React 19) for organizing AI context files. Features an IDE-style folder sidebar with drag-to-move, ⌘⇧C copies clean Markdown to clipboard for pasting into Claude/ChatGPT/agents, live preview with Mermaid + KaTeX + Shiki syntax highlighting, ⌘K command palette, find/replace, reading mode, and 5 themes (Catppuccin family + matcha). Notarized macOS build with auto-updating via signed releases, ~12 MB bundle, MIT licensed.

**Markup**
(open source @ github [`oratis/Markup`](https://github.com/oratis/Markup)) -
Reader-first native macOS Markdown editor built with Tauri 2 (Rust + system WebView, ~88 MB RAM). Renders your `.md` like a clean web page and you edit on demand — WYSIWYG via Milkdown, or raw source. Includes a vault with wikilinks, backlinks and a graph view, Tantivy full-text search (a 10k-file vault indexes in ~1s), KaTeX math, Mermaid diagrams, three themes (light/dark/sepia), and one-click MD→HTML export (a clean, self-contained page). MIT licensed.

**Edmund**
(open source @ github [`I7T5/Edmund`](https://github.com/I7T5/Edmund)) -
Minimal, native macOS Markdown editor with live preview — built with AppKit + TextKit 2 (~15 MB), not Electron or a webview. Works directly with your existing `.md` files: no vault, no enforced folder structure. Renders as you type, hiding syntax delimiters outside the active block. Supports GitHub Flavored Markdown plus opt-in highlights, `[[wikilinks]]`, footnotes, Obsidian-style callouts and comments, and inline/display math via SwiftMath. Keyboard-first, fully offline, auto-updating via Sparkle, Apache 2.0 licensed.

**Everseq**
(open source @ github [`alkalim/Everseq`](https://github.com/alkalim/Everseq)) -
Open-source local-first Markdown outliner for macOS. Everseq stores notes as ordinary `.md` files while adding block trees, page and block references, embeds, queries, backlinks, daily notes, and full-text search. Built with Swift, AppKit, and SwiftUI; AGPL-3.0 licensed.


## Markdown Mobile Editors

### Android

### Apple iOS/iPhone


## Misc

**MDPR**
(open source @ github [`ch040602/MdPr`](https://github.com/ch040602/MdPr),
 npm: [`@mdpresent/cli`](https://www.npmjs.com/package/@mdpresent/cli),
 optional Codex skill @ github [`ch040602/mdpr-skill`](https://github.com/ch040602/mdpr-skill)) -
Open-source Markdown presentation renderer/exporter for turning `.md` decks into editable PPTX, HTML, PDF, previews, and visual review artifacts. Supports themes, layout hints, charts, tables, diagrams, icon search, and deterministic rendering without requiring an LLM; the optional `mdpr-skill` repository adds Codex-assisted semantic hints and visual review reports.


## Meta

**License**

The awesome list is released under [the Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/), meaning it is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

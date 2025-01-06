# Awesome Local-First [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of local-first software, resources, and development tools.

Local-first software prioritizes data ownership, offline functionality, and sync capabilities while keeping user data primarily on their devices.

## Contents

- [Introduction](#introduction)
- [Articles & Papers](#articles--papers)
- [Applications](#applications)
- [Libraries & Frameworks](#libraries--frameworks)
- [CRDTs](#crdts)
- [Sync Protocols](#sync-protocols)
- [Storage Solutions](#storage-solutions)
- [Development Tools](#development-tools)
- [Examples & Templates](#examples--templates)
- [Communities](#communities)

## Introduction

- 📝 [Local-First Software](https://www.inkandswitch.com/local-first/) - The original article introducing local-first software principles by Ink & Switch.
- 🎥 [What is Local First?](https://www.youtube.com/watch?v=KrPsyr8Ig6M) - Overview by Peter van Hardenberg.
- 📚 [Building Local-First Software](https://martin.kleppmann.com/papers/local-first.pdf) - Academic paper on local-first principles.
- 🔗 [awesome-local-first](https://github.com/alexanderop/awesome-local-first) - A curated list of local-first software resources and tools.
- 🎥 [Local-First Development](https://www.youtube.com/watch?v=NMq0vncHJvU) - Video introduction to local-first development concepts and principles.

## Articles & Papers

- 📺 [Local-First Conf 2024](https://www.youtube.com/@localfirstconf/videos) - Collection of talks from the Local-First Conference 2024, covering various aspects of local-first development, patterns, and real-world implementations.

## Libraries & Frameworks


## CRDTs

- ⚡ [Automerge](https://automerge.org/) - A CRDT library for building collaborative applications with automatic merging, network-agnostic sync, and cross-platform support (JavaScript/Rust/Swift).
- 🔄 [Yjs](https://docs.yjs.dev/) - High-performance CRDT framework with rich ecosystem support for popular editors (ProseMirror, Monaco, CodeMirror), multiple network providers, and database integrations.

## Sync Protocols

- 🔄 [Dexie.js](https://dexie.org/) - A minimalistic wrapper for IndexedDB with built-in sync capabilities through Dexie Cloud. Used by WhatsApp, Microsoft To-Do, and GitHub Desktop.

## Development Tools


## Examples & Templates

- 💻 [SQLite in Vue Guide](https://alexop.dev/posts/sqlite-vue3-offline-first-web-apps-guide/) - Comprehensive guide to building offline-first web apps using SQLite and Vue 3, including implementation examples and production-ready architecture.

## Communities

- 🌐 [Local-First Web](https://localfirstweb.dev/) - Community hub for local-first web development with learning resources, tools, and events.
- 🎙️ [localfirst.fm](https://www.localfirst.fm/) - A podcast about local-first software development hosted by Johannes Schickling.
- 💬 [Local-First Discord](https://discord.com/invite/ZRrwZxn4rW) - Join the local-first software community chat.
- 📰 [Local-First News](https://www.localfirstnews.com/) - Weekly newsletter and news platform covering the latest developments, discussions, and events in the local-first software community.

## Contributing

Feel free to create a merge Request to add interesting resources

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

## Applications

- 🎨 [Figma's Multiplayer Technology](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/) - Deep dive into how Figma implemented their collaborative design tool using a custom multiplayer system inspired by CRDTs, with practical insights on handling sync, conflicts, and undo operations.
- 📝 [Notion's WASM SQLite Implementation](https://www.notion.com/blog/how-we-sped-up-notion-in-the-browser-with-wasm-sqlite) - Technical deep dive into how Notion improved browser performance by 20% using WASM SQLite for local caching, including architecture decisions and solutions to concurrency challenges.

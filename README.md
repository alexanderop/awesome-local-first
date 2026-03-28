# Awesome Local-First [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of **local-first software**, resources, and development tools.
Local-first software prioritizes **data ownership**, **offline functionality**, and **synchronization** — keeping user data primarily on their devices.

---

## 🧩 Core Resources

### Foundational Articles
- [Local-First Software](https://www.inkandswitch.com/local-first/) – The original article introducing local-first principles by Ink & Switch
- [Building Local-First Software](https://martin.kleppmann.com/papers/local-first.pdf) – Academic paper on local-first principles
- [Why Haven't Local-First Apps Taken Off? (2025)](https://marcobambini.substack.com/p/why-local-first-apps-havent-become) – Examines distributed complexity and adoption barriers
- [I Was Wrong. CRDTs Are the Future](https://josephg.com/blog/crdts-are-the-future/) – Joseph Gentle (ex-Google Wave) on why he abandoned OT for CRDTs
- [You Might Not Need a CRDT](https://jamsocket.com/blog/you-might-not-need-a-crdt) – When CRDTs are overkill and alternative sync approaches
- [Local, First, Forever](https://tonsky.me/blog/crdt-filesync/) – Tonsky on building local-first sync on top of plain file storage
- [Home-Cooked Software and Barefoot Developers](https://maggieappleton.com/home-cooked-software) – Maggie Appleton on personal, local software enabled by AI

### Architecture & Implementation
- [Are Sync Engines the Future of Web Applications?](https://dev.to/isaachagoel/are-sync-engines-the-future-of-web-applications-1bbi) – Deep dive into sync engine design
- [Building Data-Centric Apps with a Reactive Relational Database](https://riffle.systems/essays/prelude) – Reactive DB patterns by Riffle
- [End-to-End Encryption in the Browser](https://blog.excalidraw.com/end-to-end-encryption/) – E2E encryption technical breakdown
- [Designing Data Structures for Collaborative Apps](https://mattweidner.com/2022/02/10/collaborative-data-design.html) – Practical guide to CRDT structure design
- [Beehive (Ink & Switch 2024)](https://www.inkandswitch.com/beehive/) – Decentralized access control and convergent capabilities
- [Ossa Protocol (2025)](https://ossa.dev) – Open universal sync protocol for local-first interoperability
- [Implementing Local-First Architecture: A CTO's Guide](https://blog.4geeks.io/implementing-local-first-architecture-a-ctos-guide-to-performance-resilience-and-data-sovereignty/) – Practical guide covering schema migrations, encryption, and the server's changed role

### Ink & Switch Research
- [Peritext: A CRDT for Rich-Text Collaboration](https://www.inkandswitch.com/peritext/) – Novel algorithm for merging concurrent rich-text edits
- [Pushpin: Towards Production-Quality P2P Collaboration](https://www.inkandswitch.com/pushpin/) – Lessons from building a fully peer-to-peer collaborative corkboard
- [Project Cambria: Translate Your Data with Lenses](https://www.inkandswitch.com/cambria/) – Bidirectional schema evolution for local-first apps
- [Upwelling: Real-time Collaboration + Version Control](https://www.inkandswitch.com/upwelling/) – Combines CRDT collaboration with branch-like "layers" for writing privacy
- [Patchwork: Towards Universal Version Control](https://www.inkandswitch.com/patchwork/notebook/) – Branching, diffing, and history for all kinds of apps beyond code

### Performance & UX
- [Why Superhuman Is Built for Speed](https://blog.superhuman.com/superhuman-is-built-for-speed/) – Applying the 100 ms rule
- [A Gentle Introduction to CRDTs](https://vlcn.io/blog/gentle-intro-to-crdts.html) – Beginner-friendly CRDT explanation
- [CRDTs Go Brrr](https://josephg.com/blog/crdts-go-brrr/) – Deep dive into CRDT performance optimizations
- [Are CRDTs Suitable for Shared Editing?](https://blog.kevinjahns.de/are-crdts-suitable-for-shared-editing) – Yjs creator benchmarks CRDT overhead

### Video Content
- [What Is Local First?](https://www.youtube.com/watch?v=KrPsyr8Ig6M) – Overview by Peter van Hardenberg
- [Local-First Development](https://www.youtube.com/watch?v=NMq0vncHJvU) – Introduction to local-first concepts
- [Local-First Conf 2024](https://www.youtube.com/@localfirstconf/videos) – Full conference playlist
- [SyncConf 2025 (Preview)](https://localfirstconf.com/syncconf2025) – Conference focused on synchronization
- [CRDTs for Mortals – James Long (dotJS 2019)](https://www.youtube.com/watch?v=iEFcmfmdh2w) – Approachable intro to CRDTs through building a personal finance app
- [CRDTs: The Hard Parts – Martin Kleppmann (Hydra 2020)](https://www.youtube.com/watch?v=x7drE24geUw) – Real-world CRDT challenges: move operations, interleaving, and performance

### Blog Series & Deep Dives
- [Jared Forsyth's Local-First Database Series](https://jaredforsyth.com/tags/local-first/) – Evaluations of local-first databases against core criteria
- [Bartosz Sypytkowski's CRDT Blog Series](https://www.bartoszsypytkowski.com/tag/crdt/) – 22-post series covering state-based and operation-based CRDTs
- [The Spectrum of Local First Libraries](https://tolin.ski/posts/local-first-options) – Practical comparison of Triplit, Evolu, Zero, LiveStore, and others
- [Comparing Local-First Frameworks (Neon)](https://neon.com/blog/comparing-local-first-frameworks-and-approaches) – Technical comparison of local-first frameworks

---

## ⚙️ Development Tools & Libraries

### Database Solutions
- [Electric SQL](https://electric-sql.com/) – Sync Postgres data into local apps with offline support
- [WatermelonDB](https://watermelondb.dev) – Reactive DB for React / React Native
- [Fireproof](https://use-fireproof.com/) – Browser-native local-first database
- [Evolu](https://www.evolu.dev/) – Type-safe offline-first database with sync
- [Dexie.js](https://dexie.org/) – IndexedDB wrapper with sync
- [TanStack DB (2025)](https://tanstack.com/db) – Reactive client-side data layer with optimistic mutations and sync engine support
- [LiveStore (2024)](https://livestore.dev) – Event-sourced local-first framework using in-memory SQLite
- [Triplit](https://triplit.dev) – Full-stack sync engine + database (acquired by Supabase 2025)
- [InstantDB (2024)](https://www.instantdb.com/) – Firebase-style backend with offline & real-time sync
- [Zero (2024)](https://zero.rocicorp.dev) – Reactive sync engine from the Replicache team
- [RxDB](https://rxdb.info) – Reactive NoSQL DB with replication, encryption, multi-tab
- [PowerSync](https://www.powersync.com) – Offline-first sync engine for mobile/web
- [Y-Sweet](https://github.com/jamsocket/y-sweet) – Open-source Yjs sync and persistence server (self-hosted)
- [Turso Sync (2025)](https://turso.tech) – Sync local SQLite with edge-hosted SQLite
- [PouchDB](https://pouchdb.com) – Classic offline-first JS database with CouchDB sync
- [GUN.js](https://gun.js.org) – Decentralized P2P graph database with CRDT-based conflict resolution
- [OrbitDB](https://github.com/orbitdb/orbitdb) – Serverless P2P database on IPFS using Merkle-CRDTs
- [cr-sqlite (Vulcan)](https://github.com/vlcn-io/cr-sqlite) – SQLite extension adding CRDT-based multi-writer replication
- [libSQL](https://github.com/tursodatabase/libsql) – Open-source SQLite fork with embedded replicas for local-first reads
- [VelesDB](https://github.com/cyberlife-coder/VelesDB) - Local-first vector + graph + columnar database written in Rust (~6MB binary). Source-available (Elastic License 2.0)

### State Management & Sync
- [Legend State](https://github.com/LegendApp/legend-state) – Reactive state with persistence
- [Replicache](https://replicache.dev) – Client-side sync with conflict resolution (maintenance mode; see Zero)
- [Tinybase](https://github.com/tinyplex/tinybase) – Reactive data store & sync engine

### CRDT Libraries
- [Automerge](https://automerge.org) – CRDT library with fast binary format & WASM support (v3.0 with 10x memory reduction)
- [Yjs](https://docs.yjs.dev/) – High-performance CRDT framework
- [Loro](https://loro.dev/) – JSON and rich-text CRDT
- [Collabs](https://collabs.readthedocs.io/en/latest/) – Composable CRDTs from CMU (low activity)
- [Diamond Types](https://github.com/josephg/diamond-types) – High-performance Rust CRDT for text editing (WIP)

### Frameworks & Platforms
- [Jazz (CoJSON)](https://jazz.tools) – Local-first framework with built-in auth, sync, permissions, and E2E encryption
- [DXOS](https://dxos.org) – Open-source P2P framework with ECHO reactive DB and HALO decentralized identity
- [Verdant](https://verdant.dev) – IndexedDB-powered storage, sync, and real-time collaboration for local-first web apps
- [Liveblocks](https://liveblocks.io) – Real-time collaboration SDK with presence, storage, and Yjs-backed sync (cloud-hosted)
- [PartyKit (Cloudflare)](https://partykit.io) – Edge-deployed stateful servers for real-time multiplayer apps (cloud-hosted)
- [Hocuspocus](https://github.com/ueberdosis/hocuspocus) – Yjs WebSocket backend with persistence and authorization
- [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) – Edge-deployed stateful primitives with built-in SQLite (cloud infrastructure)
- [Earthstar](https://earthstar-project.org) – Offline-first P2P sync protocol for small-group collaboration

### P2P & Networking
- [libp2p](https://libp2p.io) – Modular P2P networking stack supporting TCP, QUIC, WebRTC, and WebTransport
- [Hypercore / Hyperswarm](https://github.com/holepunchto) – Append-only log with DHT-based peer discovery and hole-punching
- [Pear Runtime (Holepunch)](https://pears.com) – Zero-infrastructure P2P runtime for desktop, mobile, and terminal apps
- [Socket Runtime](https://socketsupply.co) – P2P runtime turning web apps into native apps with built-in peer networking
- [Iroh](https://github.com/n0-computer/iroh) – QUIC-based Rust library for P2P connectivity with relay fallback
- [IPFS](https://ipfs.tech) – Content-addressed P2P storage and distribution protocol
- [Syncthing](https://syncthing.net) – Open-source continuous P2P file synchronization with E2E encryption
- [Nostr](https://github.com/nostr-protocol/nostr) – Open relay-based protocol for decentralized publishing
- [AT Protocol](https://atproto.com) – Bluesky's protocol with self-authenticating data and portable identity
- [Braid HTTP](https://braid.org) – IETF draft extending HTTP into a state synchronization protocol

### Mobile-Specific
- [Couchbase Lite](https://www.couchbase.com/products/lite/) – Embedded NoSQL database for mobile/IoT with offline-first operation and P2P sync
- [ObjectBox](https://objectbox.io) – High-performance on-device database with built-in data sync for mobile, IoT, and edge (sync is commercial)

### Auth & Identity
- [UCAN](https://ucan.xyz) – Trustless, offline-capable, delegated authorization tokens using DIDs
- [DID (Decentralized Identifiers)](https://www.w3.org/TR/did-1.1/) – W3C standard for verifiable, self-sovereign digital identity

### Security & Encryption
- [OpenMLS](https://openmls.tech) – Rust implementation of the Messaging Layer Security (MLS) protocol for E2E encrypted group communication
- [MLS Protocol (RFC 9420)](https://datatracker.ietf.org/doc/rfc9420/) – IETF standard for scalable E2E encrypted group messaging
- [Notes on CRDTs + E2E Encryption](https://kerkour.com/crdt-end-to-end-encryption-research-notes) – Practical research notes on combining CRDTs with encryption

---

## 💡 Real-World Examples

### Case Studies
- [Figma's Multiplayer Technology](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/) – Real-time collaboration internals
- [Figma: Making Multiplayer More Reliable](https://www.figma.com/blog/making-multiplayer-more-reliable/) – Write-ahead log and reliability improvements
- [Notion's WASM SQLite](https://www.notion.com/blog/how-we-sped-up-notion-in-the-browser-with-wasm-sqlite) – Browser local-DB performance
- [Trello's Offline Architecture](https://www.atlassian.com/blog/atlassian-engineering/sync-architecture) – Offline support patterns
- [Scaling the Linear Sync Engine](https://linear.app/now/scaling-the-linear-sync-engine) – How Linear scaled their local-first sync engine
- [Logseq & Obsidian](https://logseq.com) – Markdown-based offline knowledge tools
- [Superhuman: Architecting for Offline](https://blog.superhuman.com/architecting-a-web-app-to-just-work-offline-part-1/) – Deep-dive into offline-first storage and sync
- [Superhuman: Building on Unreliable Networks](https://blog.superhuman.com/building-reliable-apps-on-unreliable-networks/) – Engineering patterns for network resilience
- [Expo: Local-First Architecture Guide](https://docs.expo.dev/guides/local-first/) – Official Expo docs on building local-first mobile apps

### Example Applications

**Knowledge Management & Notes**
- [Anytype](https://anytype.io) – Local-first, P2P, E2E encrypted knowledge OS
- [AFFiNE](https://affine.pro) – Open-source workspace combining docs, whiteboards, and databases
- [AppFlowy](https://appflowy.com) – Open-source Notion alternative with full offline mode
- [Standard Notes](https://standardnotes.com) – Open-source, E2E encrypted notes
- [Joplin](https://joplinapp.org) – Open-source offline-first note-taking with optional E2E sync
- [Notesnook](https://notesnook.com) – Open-source zero-knowledge encrypted notes
- [Capacities](https://capacities.io) – Object-based note-taking with offline-first architecture
- [Reflect](https://reflect.app) – Local-first networked notes with E2E encryption
- [Bangle.io](https://bangle.io) – Local-first notes
- [Logseq](https://logseq.com) – Local-first knowledge base and outliner
- [Obsidian](https://obsidian.md) – Markdown-based knowledge management with local vault storage

**Productivity & Collaboration**
- [Excalidraw](https://excalidraw.com) – Collaborative drawing
- [tldraw](https://tldraw.com) – Open-source infinite canvas whiteboard SDK
- [Huly](https://huly.io) – Open-source all-in-one project management platform with offline-first client
- [Superhuman](https://superhuman.com) – Offline-first email client

**Personal & Finance**
- [Actual](https://actualbudget.com) – Local-first budgeting
- [Finbodhi (2025)](https://finbodhi.com) – Encrypted personal-finance app
- [Timelinize (2025)](https://timelinize.com) – Local data aggregation into a personal timeline

### Learning Resources
- [SQLite in Vue Guide](https://alexop.dev/posts/sqlite-vue3-offline-first-web-apps-guide/) – Building offline-first Vue apps
- [An Interactive Intro to CRDTs](https://jakelazaroff.com/words/an-interactive-intro-to-crdts/) – Hands-on tutorial
- [Operational Transformation Visualization](https://operational-transformation.github.io/) – Interactive OT demo
- [CRDT Tutorials](https://github.com/siliconjungle/crdt-tutorials) – Practical examples
- [TinyRooms](https://github.com/tinyplex/tinyrooms) – Multiplayer game using local-first
- [RxDB Blog – Why Local-First Is the Future](https://rxdb.info/articles/why-local-first.html) – Deep dive
- [CRDTs for Mortals – Example App](https://github.com/jlongster/crdt-example-app) – Full reference implementation from James Long's talk

---

## 🌍 Community

### Stay Connected
- [Local-First Web](https://localfirstweb.dev/) – Community hub
- [localfirst.fm](https://www.localfirst.fm/) – Developer podcast
- [Local-First Discord](https://discord.com/invite/ZRrwZxn4rW) – Active discussion server
- [Local-First News](https://www.localfirstnews.com/) – Weekly newsletter with releases & meetups
- [LoFi Meetups (2024-25)](https://localfirstweb.dev/meetups) – Monthly online community events
- [Braid IETF WG](https://braid.org) – Working group for sync protocols
- [CRDT.tech](https://crdt.tech) – Community website with curated papers, talks, and implementations
- [CRDT.tech Resources](https://crdt.tech/resources) – Curated collection of CRDT talks and educational materials
- [Awesome-CRDT (GitHub)](https://github.com/alangibson/awesome-crdt) – Curated list of CRDT libraries, papers, and tutorials
- [Yjs Community Resources](https://docs.yjs.dev/other-resources/talks-and-podcasts) – Index of Yjs-related talks, podcasts, and blogs
- [Maggie Appleton on localfirst.fm](https://www.localfirst.fm/13) – Podcast on barefoot developers, AI, and end-user programming

---

## 🎤 Conferences & Talks
- [Local-First Conf 2024 Videos](https://www.youtube.com/@localfirstconf/videos) – Sessions by Kleppmann, Artman (Linear), etc.
- [LoFi / 28 Meetup (2025)](https://localfirstnews.com/lofi28) – Dexie, Replication 3 Ways, Legend State performance talk
- [SyncConf 2025 Preview](https://localfirstconf.com/syncconf2025) – Dedicated sync-tech event

---

## 🤝 Contributing
Pull requests welcome!
Add tools, libraries, or case studies that advance **local-first**, **offline-first**, or **sync-centric** development.

---

## 🪪 License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

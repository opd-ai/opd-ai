# OPD-AI 🎲🦀

**Tools for people who'd rather own their stack than rent it.**

OPD-AI builds open-source software for creative and technical independence. The repositories here aren't a random collection — they stack. Each layer removes a dependency on someone else's platform, so an individual creator, gamemaster, or self-hoster can do alone what normally requires a company behind them. You can adopt one piece or the whole ladder.

## Own your output

The creative engine is where most people start. **dndbot** (Adventure Forge) generates complete, system-agnostic D&D adventure series through a seven-phase pipeline, and the results live publicly in **opd-ai.github.io** (The Dungeon Scribe's Vault). **bookie** compiles that markdown into professionally typeset PDF books with automatic chapters and tables of contents, while **asset-generator** (SwarmUI) and **horde** (Stable Horde) produce the artwork. For people who want to *run* games rather than write them, **goldbox-rpg** is a Gold Box–style RPG engine and **bostonfear** is a rules-only multiplayer engine for Lovecraftian tabletop play, with **awesome-tabletop-rpgs** cataloguing the free systems to build on.

The **unsuite** is the ambitious next step: a fully procedural game-asset pipeline split into focused generators — humanoids (**unpeople**), creatures (**unbeasts**), gear, clothing, weapons, environment meshes, materials, particle and spell VFX, animations, names, maps, props, sounds, and more. The goal is a complete library so a solo developer can populate an entire world without licensing assets from anyone. *Status: the unsuite is in active development and currently unfinished — **unpeople** is the working, production-ready generator that anchors the rest, since clothing, armor, and animations all conform to its base bodies.*

## Own your income

Creative work only stays independent if it can sustain itself without a middleman. **paywall** is cryptocurrency-based access-control middleware (with **paywall-cases** documenting real patterns), and it powers **store**, **music** (a storefront for independent artists), and **createon** — a self-hosted Patreon alternative. Underneath, **moneroger**, **go-monero-wallet**, **go-randomx**, **node-xmr-pool**, and **nmcd** give Go developers a full Monero and Namecoin toolkit, so payments never route through a platform that can cut you off.

## Own your AI

You shouldn't need a data center to use AI. **minilm** runs small quantized models on old hardware, **cluster** lets you self-host a 2-to-X node LLM cluster, and **Open-LLM-VTuber** and **desktop-companion** turn local models into voice- and Live2D-driven characters. For developers, **Anti-Slop-Guard** and **continue** keep AI-assisted coding honest and CI-enforceable, and **becrabbening** (with the **firefox** fork) is a systematic methodology for incrementally rewriting C/C++ in Rust without merge conflicts.

## Own your network and machine

At the foundation, OPD-AI is rebuilding private communication from the ground up. **toxcore** is a pure-Go libtoxcore with modern cryptography (X3DH, double-ratchet, MLKEM-768, async messaging) and C bindings as a drop-in replacement, alongside a Rust **tox** and a compatibility **toxcore-testnet**. On top of Tox sit clients (**mtox**, **dtox**, **go-ratox**), mesh and VPN-style overlays (**granulosa**, **muscimol**), matchmaking (**methane**), and bridges to other anonymity networks (**itox**, **toxpt**). Pure-Go reimplementations of **go-tor**, **go-cjdns**, and the C# **i2p-cs-renewed** round out the privacy layer, while **diagon** packages it all into a Debian distribution for running hidden services — and **heads-dell-netbooks** takes ownership all the way down to verified Coreboot firmware.

## The infrastructure and Go toolbox that hold it together

Supporting everything are the self-hosting utilities — **cluster**, **app-streamer**, **docker-package**, **go-gamelaunch** (and its client/web variants), and the **go-jf-org**/**go-jf-watch** Jellyfin tools — plus a deep bench of pure-Go libraries: **opus**/**magnum** (audio), **go-utp**, **go-c-bindgen**, **go2c**, **pure-go-dl**, the **gui**/**ui2** toolkits, and diagnostic tools like **tuimap**, **go-conky**, and **go-stats-generator**.

---

**Philosophy:** open source, creator ownership, minimal barriers to entry, Bitcoin/Monero for sustainability, and AI as a creative assistant — never a replacement. Everything is free to use, modify, and improve.

🌐 [dngn.me](https://dngn.me) · *May your dice roll true.*

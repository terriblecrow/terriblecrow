# Terrible Crow 🐦‍⬛

**A small game studio.** I build strategy games on top of cellular automata — and then demake them onto hardware that has no business running them.

🌐 [terriblecrow.com](https://terriblecrow.com/) · ✉️ [contact@terriblecrow.com](mailto:contact@terriblecrow.com) · 🎮 [itch.io](https://terriblecrow.itch.io)

---

## 🟦🟥 Conway's Conquerors

A 1v1, perfect-information strategy game played on a two-color variant of Conway's Game of Life. Seed four cells per turn; the board evolves by B3/S23 between turns. Win by extinction — or by weighted majority after twelve rounds plus the Komi Round.

| | |
|---|---|
| 🏠 **Official site** | https://conwaysconquerors.com |
| ▶️ **Play online** | https://play.conwayconquerors.online |
| 🕹️ **Play on itch.io** | https://terriblecrow.itch.io/conways-conquerors |
| 📄 **Technical report** | [How the automaton works at the bit level](https://conwaysconquerors.com/RESEARCH-PAPER.md) |
| 📱 **Android (TWA)** | Coming to the Play Store — install from the web in the meantime |
| 💻 **Source** | [github.com/terriblecrow/conways-conquerors](https://github.com/terriblecrow/conways-conquerors) |

The whole backend is a single zero-dependency Node.js file — a hand-written WebSocket implementation (RFC 6455) with transparent HTTP long-polling fallback, an authoritative server, client-side prediction, five AI difficulty tiers, and a fully bilingual (EN/ES) client.

## 🎮 Pocket Conquerors — the Game Boy demake

The same game, running on a Nintendo Game Boy. Written in C, compiled with SDCC — **no GBDK**. Hand-written startup code, cartridge header, and hardware access. vs-CPU and 2-player (local hot-seat *or* over the link cable), bilingual, with stats saved to battery RAM. Ships as both a Game Boy Color and a pure-monochrome DMG ROM.

| | |
|---|---|
| 🕹️ **Play in the browser** | https://conwayconquerors.com/demake/ |
| 💾 **Download the ROMs / source** | [github.com/terriblecrow/Pocket-Conquerors](https://github.com/terriblecrow/Pocket-Conquerors) |

---

*Made in Argentina.* 🇦🇷

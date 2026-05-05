<div align="center">

<img src="https://torchandlily.com/images/torch_lily_logo.png" alt="Torch & Lily" width="120" />

# Torch & Lily

**Speculum Fidei** — *The Mirror of the Faith*

An API-first platform for the Catholic intellectual and devotional tradition.

[**Website**](https://torchandlily.com) · [**Developer Portal**](https://dev.torchandlily.com) · [**API Docs**](https://dev.torchandlily.com/docs/intro) · [**Get an API Key**](https://dev.torchandlily.com/signup) · [**About**](https://dev.torchandlily.com/about)

`α Alpha`

</div>

---

The platform is developed privately. This repository is the public threshold — where developers find their way in.

---

## I &nbsp;·&nbsp; Quid Est — What This Is

If you are a Catholic developer and you want to build something — a prayer app, a liturgical calendar widget, a saint lookup tool — you will quickly discover the same thing every one of us has discovered: **the data is everywhere and nowhere.** PDFs of the Summa scattered across university servers. Hagiographic databases behind paywalls or riddled with errors. Liturgical calendar APIs that disagree with each other.

Torch & Lily exists to end that. One unified API. Five structured engines. Everything a Catholic developer needs to build without reinventing the wheel.

## II &nbsp;·&nbsp; Quinque Machinae — The Five Engines

| Engine | Prefix | Domain |
| --- | --- | --- |
| **Veritas** | `/v1/veritas` | Scripture, Summa Theologiae, Opera, Patristic Commentaries |
| **Devotio** | `/v1/devotio` | Saints, Hagiography, and the Catholic Prayer Tradition |
| **Tempus** | `/v1/ordo` | Liturgical Calendar — feasts, seasons, colors, computed for any date |
| **Corpus** | `/v1/corpus` | Sacred Site Mapping — every parish and cathedral worldwide |
| **Communio** | `/v1/communio` | Intercessory Prayer Network — anonymous, global, real-time |

Full reference at the [**API Docs**](https://dev.torchandlily.com/docs/intro).

## III &nbsp;·&nbsp; Architectura — The Torch & The Lily

The name carries the architecture.

**The Torch** is the backend — immutable, objective, illuminating. It holds the record of what is true: the texts, the saints, the calendar, the geography. It does not speculate. It does not hallucinate. It serves what has been verified.

**The Lily** is the frontend — the living, growing space where developers and users actually dwell. The [Developer Portal](https://dev.torchandlily.com) — *Ostium*, the Gate — is the threshold between those two worlds.

The platform is API-first and natively accessible to LLM agents via the **[Model Context Protocol](https://dev.torchandlily.com/docs/mcp/)**. One config block connects Claude, Cursor, or any MCP client to the entire Tradition.

## IV &nbsp;·&nbsp; De Fonte — On The Source

Nearly all of the text data in Torch & Lily is **public domain**: the Douay-Rheims rather than a modern translation; the pre-1927 hagiographic record rather than contemporary biographies; Aquinas as Aquinas wrote him.

We frame this not as a limitation but as a foundation. These texts have survived centuries precisely because they are trustworthy. They are not behind a paywall because they belong to everyone. The *Refinery* — our AI ingestion pipeline — does not generate theological data. It cleans, structures, and verifies it against primary sources. Every record that fails verification is flagged, retried, and if necessary, removed.

> *"Sicut maius est illuminare quam lucere solum, ita maius est contemplata aliis tradere quam solum contemplari."*
>
> "For even as it is better to enlighten than merely to shine, so is it better to give to others the fruits of one's contemplation than merely to contemplate."
>
> — **Thomas Aquinas**, *Summa Theologiae* II-II, Q.188, A.6

## V &nbsp;·&nbsp; Initium — Getting Started

```bash
curl https://api.torchandlily.com/v1/devotio/saints/thomas-aquinas \
  -H "X-API-Key: tl_your_key_here"
```

1. **[Create an account](https://dev.torchandlily.com/signup)** and generate a key from your dashboard.
2. **[Read the docs](https://dev.torchandlily.com/docs/intro)** — start with Authentication, then pick an engine.
3. **Build something.** Access is currently free during the Alpha.

## VI &nbsp;·&nbsp; Scriptorium — Contributing

Torch & Lily is a living archive. The platform code is private, but the data is open to faithful contribution: saints, prayers, sacred texts, patristic commentaries, and corrections to existing records.

If you would like to contribute, begin at the **[Scriptorium](https://dev.torchandlily.com/scriptorium)**. Style guides for each content type are linked from there.

## VII &nbsp;·&nbsp; Vox — Get in Touch

This project is built and maintained by one developer and responds accordingly: personally, and without a ticket system.

For integration questions, data corrections, bug reports, feature requests, or anything else:

→ **[Share Your Voice](https://dev.torchandlily.com/vox)**
→ Or write directly: **dev@torchandlily.com**

Please do **not** open issues on this repository — it is a brochure, not a tracker. The [Vox form](https://dev.torchandlily.com/vox) reaches the builder directly.

---

<div align="center">

***Aedificamus Civitatem Dei.***
*We are building the City of God.*

— **S. Dominice, ora pro nobis.**

<sub>© 2026 Torch & Lily · The Digital Scriptorium · α Alpha</sub>

<sub>Not affiliated with, endorsed by, or acting on behalf of the Catholic Church, the Holy See, or any diocese.</sub>

</div>

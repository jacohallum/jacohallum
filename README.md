# Jacob Hallum

Hi, I'm Jacob Hallum, a software developer who builds real-time systems and desktop tools. I focus on reliable data pipelines, smooth UI performance, and clean architecture.

## FightWatchr (In Progress)

**[FightWatchr](https://github.com/jacohallum/fightwatchr)** is a full-stack UFC hub live at [fightwatchr.com](https://fightwatchr.com) for tracking fighters, events, and live fight data. Users can manage notification preferences, follow fighters by division, and get live event updates powered by a scheduled sync data pipeline.

Built with:

* **Next.js** and **TypeScript**
* **PostgreSQL** with **Prisma ORM**
* Secure sign-in through **NextAuth**
* Incremental data sync scheduler that auto-refreshes event and fighter data every 6 hours
* AI-driven predictions and sentiment insights (in development)

## BeatHunter (In Progress)

**[BeatHunter](https://github.com/jacohallum/BeatHunter)** is a local desktop app that compares your Apple Music protected library against your owned clean music and surfaces tracks you're missing a DRM-free copy of. An approval-gated download workflow lets you queue and organize replacements without ever touching your iTunes library.

Built with:

* **Python 3.13** and **PyQt6**
* **SQLite** for library cache, download queue, and coverage tracking
* **mutagen** for audio metadata and quality detection
* Background workers so the GUI never blocks on I/O
* Strict read-only safety: iTunes Media is never written to

## iTunes Shuffler

**[iTunes Shuffler](https://github.com/jacohallum/Music-Shuffler)** is a custom music player for large iTunes/M4A libraries. A weighted shuffle algorithm factors in play count, rating, recency, loved status, and skip history to surface tracks intelligently across 8K+ songs.

Key features:

* Smart shuffle weighted across six listening signals
* Background M4A pre-conversion via FFmpeg for instant playback
* Album artwork display and Up Next queue
* Global media keys (F5-F8) system-wide
* Full library search and filter

---

### Connect

You can find me on [LinkedIn](https://www.linkedin.com/in/jacobhallum).  
Open to discussing code, system design, or projects that push real data into clean interfaces.

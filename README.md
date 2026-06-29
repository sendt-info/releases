# Radio Dashboard

**Real-time metadata dashboard for radio automation**

Radio Dashboard is a system-tray app and browser dashboard that connects to your radio automation software and displays live now-playing information, show details, weather, news, and play history — across as many screens as you need.

Designed for radio stations running [mAirList](https://mairlist.com/) or similar automation software.

---

## Screenshots

> _Screenshots coming soon._

---

## Features

- **Live now-playing display** — song title, artist, and show info update in real time
- **Multi-screen support** — open the dashboard in any browser, or install the lightweight display client on screens around the studio
- **Automatic discovery** — display clients find the server automatically over the local network (no manual IP setup needed)
- **Draggable widget layout** — rearrange dashboard widgets to fit your workflow; layout is saved automatically
- **Light & dark theme** — switch between themes from the dashboard
- **Weather** — current conditions via yr.no
- **RSS news feeds** — latest headlines at a glance
- **Play history & analytics** — charts and logs of what's been played
- **Playlist view** — see what's coming up next (mAirList integration)

---

## Download

Head to the [**Releases**](../../releases) page to download the latest version.

| Platform | File |
|----------|------|
| macOS | `.dmg` installer |
| Windows | `.exe` installer |

---

## Getting Started

1. **Install the server app** on the PC running your radio automation software and launch it — it will appear in the system tray.
2. **Open the dashboard** in any browser on the same network by navigating to the address shown in the tray menu (e.g. `http://radio-pc.local:3000`).
3. **Optionally install the display client** on studio screens or other PCs — it will find the server automatically.

---

## Issues & Feedback

Found a bug or have a feature request? [Open an issue](../../issues) — feedback is always welcome.

---

<details>
<summary>Tech stack</summary>

- **Desktop shell:** Electron
- **Frontend:** Vue 3 + Vite
- **Backend:** Hono (Node.js)
- **Language:** TypeScript
- **Network discovery:** mDNS/Bonjour
- **Analytics:** PostgreSQL

</details>

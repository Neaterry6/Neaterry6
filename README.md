<!-- ============================================================ -->
<!--                    BROKENVZN  ·  PROFILE README              -->
<!--         Akewushola Abdulbakri Temitope  ·  Neaterry6         -->
<!-- ============================================================ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=38&pause=1000&color=00F7FF&center=true&vCenter=true&repeat=true&width=1000&lines=Hi+There!+I'm+Akewushola+Abdulbakri+Temitope;better+known+as+BROKENVZN;Full+Stack+Developer+%7C+AI+Engineer;I+build+APIs%2C+agents+and+web+apps;Ship+it%2C+then+make+it+better." />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=240&text=BROKENVZN&fontAlign=50&fontAlignY=40&color=0:00F7FF,50:8A2BE2,100:FF0080&fontColor=ffffff&animation=fadeIn&desc=Full%20Stack%20Developer%20%E2%80%A2%20AI%20Engineer%20%E2%80%A2%20API%20Builder&descAlignY=62"/>

<br>

<a href="https://neaterry6.github.io"><img src="https://img.shields.io/badge/Portfolio-Live-00F7FF?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=Neaterry6&label=Profile%20Views&color=blueviolet&style=for-the-badge"/>
<img src="https://img.shields.io/github/followers/Neaterry6?logo=github&style=for-the-badge&label=Followers"/>
<img src="https://img.shields.io/github/stars/Neaterry6?logo=github&style=for-the-badge&label=Stars"/>

</div>

---

<div align="center">

> ### "I don't just write code — I build things people actually use."

**50+ original repositories** · **AI agents** · **REST APIs** · **Streaming tools** · **WhatsApp bots**

</div>

---

# 🚀 What I'm Building Right Now

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Broken — WhatsApp AI Agent
A full execution agent that lives in WhatsApp. Not a chatbot — it runs shell commands, browses the web, generates media, hosts sites, and ships code on request.

`Node.js` `Baileys` `LLM tool-calling` `Docker`

</td>
<td width="50%" valign="top">

### 🎬 BROKEN Movies
Streaming platform with its own scraper backend — TMDB metadata, multi-source embed resolution, IPTV, and an HLS player.

`Express` `Node.js` `TMDB API` `HLS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 Brokenvzn AI
Multi-capability AI platform — assistant, chat, and generation tools behind one interface.

`JavaScript` `Vercel`

</td>
<td width="50%" valign="top">

### 🎧 BrokenVZN Music API
A stack of music/lyrics endpoints — search, stream, and lyrics resolution, built to be dropped into any bot or app.

`Node.js` `Python` `REST`

</td>
</tr>
</table>

---

# 🌐 Live Projects

> Every link below was checked and is **live right now**. If it is listed here, it loads.

<table>
<tr>
<td width="50%" valign="top">

**🎬 Streaming & Media**

- [**Manga We**](https://manga-we.vercel.app) — manga reader with a clean UI
- [**StreamMe Chatroom**](https://streamme-chatroom-id.vercel.app) — live chatroom app

</td>
<td width="50%" valign="top">

**🤖 AI & Tools**

- [**Brokenvzn AI**](https://brokenvzn-ai.vercel.app) — multi-capability AI platform
- [**Story Writer AI**](https://my-story-writer-ai.vercel.app) — AI story generation
- [**Jespire Stories**](https://jespire-stories.vercel.app) — story publishing platform
- [**Pinterest API**](https://pinterest-api-phi.vercel.app) — image search API

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📚 Web & Education**

- [**Phoenix Learn Code**](https://phoenix-learn-code.vercel.app) — interactive coding lessons
- [**Glamour**](https://glamour-net.vercel.app) — beauty & fashion platform
- [**Portfolio**](https://neaterry6.github.io) — my own site

</td>
<td width="50%" valign="top">

**🔌 APIs & Backends**

- [**Lyrics API**](https://github.com/Neaterry6/Lyrics-s) — song lyrics lookup
- [**YT API**](https://github.com/Neaterry6/Yt-api) — YouTube metadata
- [**Translator API**](https://github.com/Neaterry6/translator-api) — translation endpoints
- [**Roast API**](https://github.com/Neaterry6/roast-api) — roast generator

<sub>Backends are source-available; hosted endpoints listed under [Packages](#-packages).</sub>

</td>
</tr>
</table>

---

# 🚧 In Progress

Honest list — these are built but their deployments are down or mid-rebuild. Working through them:

- 🎬 **BROKEN Movies** — streaming platform + scraper backend (redeploying)
- 📸 **Hi Photos** — photo sharing app (redeploying)
- 📝 **UTME Prep** — exam practice app (rebuilding)
- 🎵 **YT Play / Video Downloader APIs** — media resolvers (rebuilding)

<sub>No dead links above on purpose — I'd rather show 9 things that work than 21 that don't.</sub>

---

# 📦 Packages

Zero-dependency npm packages — no axios, no SDKs, nothing to keep updated.

<div align="center">

| Package | What it does | Source |
|---|---|---|
| **broken-roasts** | Roast generator. 5 flavours + personalised roasts. Works offline. | [GitHub](https://github.com/Neaterry6/broken-roasts) |
| **broken-translate** | Translation with auto-detect, batch and long-text support. | [GitHub](https://github.com/Neaterry6/broken-translate) |

</div>

Both ship full TypeScript types, a dual ESM + CJS build, and a test suite.

```js
// clone or link the repo, then:
const { getRoast } = require('broken-roasts');
getRoast('savage');   // "You have the perfect face for radio."

const { translate } = require('broken-translate');
await translate('Hello world', { to: 'fr' });   // "Bonjour le monde"
```

### 🧩 More APIs (source available)

| Module | What it does | Stack |
|---|---|---|
| [**Lyrics API**](https://github.com/Neaterry6/Lyrics-s) | Song lyrics lookup + search | Python |
| [**LrcApi**](https://github.com/Neaterry6/LrcApi) | Timed `.lrc` lyric streaming | Flask |
| [**Spotify Lyrics API**](https://github.com/Neaterry6/Spotify-lyrics-api) | Lyrics matched to Spotify tracks | Python |
| [**YT API**](https://github.com/Neaterry6/Yt-api) | YouTube search + metadata | JavaScript |
| [**YTDL API**](https://github.com/Neaterry6/ytdl-API-) | Video/audio extraction | JavaScript |
| [**Music API**](https://github.com/Neaterry6/Music-Api-) | Music search + streaming | JavaScript |
| [**Pexels / Pinterest API**](https://github.com/Neaterry6/pexel-api) | Image search + proxy | HTML |
| [**Blocklist Manager**](https://github.com/Neaterry6/blocklist-manager) | Phone blocklist with import/export | Node.js |

<sub>Want one of these as a package? [Open an issue](https://github.com/Neaterry6/Neaterry6/issues).</sub>

---

# 🛠 Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=js,ts,python,html,css" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,bootstrap,vite" />

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=nodejs,express,flask" />

**Databases**

<img src="https://skillicons.dev/icons?i=mongodb,firebase,supabase,sqlite" />

**Tools & Deploy**

<img src="https://skillicons.dev/icons?i=git,github,vscode,npm,vercel,railway,linux,docker" />

</div>

---

# 👤 About Me

```javascript
const brokenvzn = {
    name: "Akewushola Abdulbakri Temitope",
    alias: "brokenvzn",

    location: "Nigeria 🇳🇬",
    education: "Westland University, Iwo, Osun State",

    role: "Full Stack Developer & AI Engineer",

    whatIBuild: [
        "AI agents & automation",
        "REST APIs people can actually plug into",
        "Streaming & media platforms",
        "WhatsApp bots",
        "Web apps with clean UI"
    ],

    languages: ["JavaScript", "TypeScript", "Python", "HTML", "CSS"],
    frontend:  ["React", "Next.js", "Tailwind CSS", "Bootstrap"],
    backend:   ["Node.js", "Express", "Flask", "REST APIs"],
    databases: ["MongoDB", "Firebase", "Supabase", "SQLite"],
    tools:     ["Git", "VS Code", "Railway", "Vercel", "Docker", "Linux"],

    alsoInto: ["Writing", "Singing", "Music"],

    philosophy: "Ship it, then make it better."
}
```

---

# 📊 GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=Neaterry6&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true&hide_border=true"/>

<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Neaterry6&layout=compact&theme=tokyonight&langs_count=10&hide_border=true"/>

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Neaterry6&theme=tokyonight&hide_border=true"/>

</div>

---

# 📬 Connect

<div align="center">

<a href="mailto:akewusholaabdulbakri101@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://t.me/Broken_vzn11"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
<a href="https://www.instagram.com/broken_vzn/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<a href="https://www.tiktok.com/@bnlsquad_boybroken"><img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white"/></a>
<a href="https://www.facebook.com/profile.php?id=61587403051704"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>

**Open to work** — freelance, collabs, and interesting problems.
Best way to reach me: [email](mailto:akewusholaabdulbakri101@gmail.com) or [Telegram](https://t.me/Broken_vzn11).

</div>

---

<div align="center">

### ⭐ If any of my work helped you, a star means a lot.

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=00F7FF&center=true&width=650&lines=Thanks+for+stopping+by!;Let's+build+something+great+together.;See+you+in+the+next+commit+%F0%9F%91%8B"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,100:8A2BE2&height=110&section=footer"/>

</div>

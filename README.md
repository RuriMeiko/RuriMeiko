<!--
  Nguyễn Trần Hoàng Long (Nguyen Tran Hoang Long) · RuriMeiko
  Rust developer · TypeScript developer · reverse engineering · Cloudflare Workers · Android (Kotlin) · LLM tooling · Vietnam
-->

<p align="center">
  <img src="assets/header.svg" width="100%" alt="Nguyễn Trần Hoàng Long (RuriMeiko) — Rust and TypeScript developer from Vietnam: reverse engineering, native Linux ports, Cloudflare Workers, Android and LLM tooling">
</p>

<p align="center">
  <a href="https://rurimeiko.pages.dev/"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-rurimeiko.pages.dev-8b5cf6?style=for-the-badge&logo=cloudflarepages&logoColor=white"></a>
  <a href="mailto:chandoralong@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-chandoralong%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/rurimeiko/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-rurimeiko-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/rurimeiko"><img alt="X / Twitter" src="https://img.shields.io/badge/X-@rurimeiko-111111?style=for-the-badge&logo=x&logoColor=white"></a>
</p>

## 👋 Hi, I'm Long — a.k.a. RuriMeiko

I'm **Nguyễn Trần Hoàng Long** (*Nguyen Tran Hoang Long*), a developer from **Vietnam 🇻🇳**. I like the hard, low-level parts:

- making closed systems talk to open ones, like an **OpenAI-compatible API** in front of a web chat or a **native Linux port** of a desktop app;
- squeezing GPUs into virtual machines;
- shipping small, fast tools in **Rust** and **TypeScript**.

```ts
const ruri = {
  writes:   ["Rust", "TypeScript", "Python", "Kotlin"],
  builds:   ["API gateways", "native ports", "Android apps", "bots"],
  digsInto: ["reverse engineering", "KVM / virtio-gpu", "LLM tools"],
  rubik:    "< 2 minutes 🧩",
  loveMode: "off",
};
```

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🐳 [whalegate](https://github.com/RuriMeiko/whalegate)
An **OpenAI-compatible gateway** into DeepSeek web sessions, written in Rust. It pools accounts with failover, streams over SSE, reads images, and turns OpenAI `tools` into native-style **tool calling** (schema validation, `tool_choice`, repair retries). One-line installers and static binaries for Linux, macOS and Windows.

![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white) ![axum](https://img.shields.io/badge/axum-tokio-555) ![OpenAI API](https://img.shields.io/badge/OpenAI--compatible-412991)

</td>
<td width="50%" valign="top">

### 💬 [zalo-linux-native](https://github.com/RuriMeiko/zalo-linux-native)
An unofficial **Zalo port for Linux (x86_64)**. Every native module was reverse-engineered and rebuilt: file utilities, image codecs (JXL), MP4 thumbnails, and the voice and video **call bridge**. *Work in progress, not a finished release.*

![Electron](https://img.shields.io/badge/Electron-47848f?logo=electron&logoColor=white) ![Reverse engineering](https://img.shields.io/badge/reverse--engineering-b91c1c) ![Linux](https://img.shields.io/badge/Linux-fcc624?logo=linux&logoColor=black)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ [macos-gpu-vm-lab](https://github.com/RuriMeiko/macos-gpu-vm-lab)
Research into running a **macOS guest with GPU acceleration on Linux/KVM**. The main track is a paravirtual GPU (virtio-gpu + Venus/Vulkan) rather than passthrough, and the goal is to generalise it across hardware. *Early research.*

![KVM](https://img.shields.io/badge/KVM-QEMU-ff6600?logo=qemu&logoColor=white) ![C](https://img.shields.io/badge/C-a8b9cc?logo=c&logoColor=black) ![Vulkan](https://img.shields.io/badge/Vulkan-ac162c?logo=vulkan&logoColor=white)

</td>
<td width="50%" valign="top">

### 📸 [LocketDroid](https://github.com/RuriMeiko/LocketDroid)
A **native Android clone of Locket Widget**: camera flow with zoom and flash, feed, chat, friends and a home-screen widget, built with **Kotlin, Jetpack Compose and CameraX**.

![Kotlin](https://img.shields.io/badge/Kotlin-7f52ff?logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285f4?logo=jetpackcompose&logoColor=white) ![Android](https://img.shields.io/badge/Android-34a853?logo=android&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 [binance-p2p-radar](https://github.com/RuriMeiko/binance-p2p-radar)
A real-time **Binance P2P market radar**. It scans every page of listings in under 1.5 s with multi-threading, alerts through a two-way **Telegram bot** with one-tap order links, and has a live web dashboard and automatic rate-limit backoff.

![Python](https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram%20bot-26a5e4?logo=telegram&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ed?logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

### ☁️ [Serverless Telegram Bot with MongoDB](https://github.com/RuriMeiko/Serverless-Telegram-Bot-with-MongoDB)
A Telegram bot running on **Cloudflare Workers**, with **MongoDB Atlas** as its database. The companion package [mongodb-cloudflare](https://github.com/RuriMeiko/mongodb-cloudflare) gives Workers MongoDB CRUD over `fetch`.

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-f38020?logo=cloudflareworkers&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47a248?logo=mongodb&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=white)

</td>
</tr>
</table>

<details>
<summary><b>More projects</b>: Android NFC, Chrome extensions, bots and team work</summary>

| Project | What it is | Stack |
|---|---|---|
| [NFC-Keeper](https://github.com/RuriMeiko/NFC-Keeper) | Android parking app that uses NFC cards instead of paper tickets | Java · Android NFC |
| [Auto course evaluation](https://chrome.google.com/webstore/detail/dhfpmkoikaobppgjdfepejabpnadjnml) ([source](https://github.com/RuriMeiko/automatic-assessment-of-subjects-CTUT)) | Chrome extension that fills in course evaluations on the CTUT student portal | JavaScript · Chrome Extension API |
| [bypass-blocked-website](https://github.com/RuriMeiko/bypass-blocked-website) | Chrome extension that uses Google Translate as a proxy for blocked sites | JavaScript |
| [randomfoodruribot](https://github.com/RuriMeiko/randomfoodruribot) | Telegram bot that picks what to eat, plus AI chat and image generation | Python · OpenAI API |
| [telegram-water-reminder](https://github.com/RuriMeiko/telegram-water-reminder) | Telegram bot that reminds you to drink water | TypeScript |
| [WTFmovies](https://github.com/dawn1810/WTFmovies) *(team)* | Movie streaming site with HLS, comments, ratings and accounts | Next.js · HLS · Serverless |
| [LightNovelWeb](https://github.com/dawn1810/LightNovelWeb) *(team)* | Light-novel reading platform | Node.js · EJS |
| [newCDRL](https://github.com/phat-612/newCDRL) *(team)* | Academic performance and student-progress management | Node.js · EJS · Python |

</details>

## 🧰 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,ts,js,py,kotlin,java,c,cpp,dart,php&perline=10" alt="Languages: Rust, TypeScript, JavaScript, Python, Kotlin, Java, C, C++, Dart, PHP"><br>
  <img src="https://skillicons.dev/icons?i=nodejs,react,nextjs,electron,androidstudio,tailwind&perline=10" alt="Frameworks: Node.js, React, Next.js, Electron, Android, Tailwind CSS"><br>
  <img src="https://skillicons.dev/icons?i=cloudflare,docker,linux,githubactions,mongodb,postgres,mysql,redis,git,vscode&perline=10" alt="Infrastructure: Cloudflare Workers, Docker, Linux, GitHub Actions, MongoDB, PostgreSQL, MySQL, Redis, Git, VS Code">
</p>

## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RuriMeiko/RuriMeiko/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RuriMeiko/RuriMeiko/output/github-snake.svg">
    <img alt="RuriMeiko GitHub contribution graph eaten by a snake" src="https://raw.githubusercontent.com/RuriMeiko/RuriMeiko/output/github-snake.svg">
  </picture>
</p>

## 🧩 Fun facts

- Solves a **Rubik's cube in under 2 minutes**, which is also the timer in the banner.
- Bio status: `love mode: off`.

<p align="center">
  <a href="https://buymeacoffee.com/rurimeiko"><img alt="Buy me a coffee" src="https://img.shields.io/badge/Buy%20me%20a%20coffee-ffdd00?style=flat-square&logo=buymeacoffee&logoColor=black"></a>
  <a href="https://ko-fi.com/rurimeiko"><img alt="Ko-fi" src="https://img.shields.io/badge/Ko--fi-ff5e5b?style=flat-square&logo=kofi&logoColor=white"></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=RuriMeiko&color=8b5cf6&style=flat-square&label=profile+views">
</p>

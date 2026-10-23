<p align="center">
  <b>English</b> ·
  <a href="README.ru.md">Русский</a> ·
  <a href="README.es.md">Español</a> ·
  <a href="README.pt.md">Português</a> ·
  <a href="README.de.md">Deutsch</a> ·
  <a href="README.fr.md">Français</a> ·
  <a href="README.zh.md">中文</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a>
</p>

<p align="center">
  <img src="screenshots/banner.jpg" alt="Grimsby Tagger">
</p>

<p align="center">
  <b>Tidy up the tags of your whole music library — album by album, not file by file.</b><br>
  See every problem at once, fix it in a couple of clicks and save everything with one button. Now for videos too.
</p>

<p align="center">
  <a href="https://github.com/maksimkhatskevich/grimsby-tagger/releases/latest"><img src="https://img.shields.io/github/v/release/maksimkhatskevich/grimsby-tagger?label=version&color=3FAC59" alt="Version"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-3FAC59" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/free-no%20ads-111314" alt="Free">
  <a href="https://www.virustotal.com/gui/file/e4dfabdb0c5f60a9fc7c6c42132a6e3492d6ef2414fcf21a93ebd759987a35e0"><img src="https://img.shields.io/badge/VirusTotal-0%2F67-2E7D32" alt="VirusTotal 0/67"></a>
  <a href="https://github.com/maksimkhatskevich/grimsby-tagger/releases"><img src="https://img.shields.io/github/downloads/maksimkhatskevich/grimsby-tagger/total?label=downloads&color=858A8D" alt="Downloads"></a>
</p>

<p align="center">
  <a href="https://github.com/maksimkhatskevich/grimsby-tagger/releases/latest"><b>⬇ Download for Windows</b></a>
  &nbsp;·&nbsp;
  <a href="#features">Features</a>
  &nbsp;·&nbsp;
  <a href="#your-files-are-safe">Safety</a>
  &nbsp;·&nbsp;
  <a href="#feedback">Feedback</a>
</p>

![Grimsby Tagger: an album card](screenshots/en/albums.jpg)

---

## Why Grimsby Tagger

Tags are what makes a collection look good in a player: the right album, year, artist, track numbers and cover. Downloaded music rarely arrives perfect — one album has no year, another has a missing cover, a third has broken Cyrillic. Classic tag editors show you a spreadsheet of thousands of files, and you fix them one row at a time.

**Grimsby Tagger thinks in albums.** Point it at a folder of any depth — it groups the files into albums, shows each one as a card with its cover and highlights what's wrong. Edit whatever you like, then **Save all** (Ctrl+S).

---

## Features

### 💿 Albums sort themselves out

An album is a folder plus the "Album" tag. Several albums in one folder are split apart; CD1/CD2 subfolders are joined into one album; files without tags stick to the album of their folder. Deluxe and standard editions from one folder become one card. A track in the wrong album? Drag it to the right one — on save it gets that album's tags and cover and moves to its folder.

### 🎬 Videos too

Music videos, concerts and other clips are edited just like music, in batches, right in the cards: MP4, M4V, WMV, MKV, WebM and MOV. The video is never re-encoded — only the tags and, where the format allows, the cover change.

![Video tags filled in from file names](screenshots/en/video.jpg)

### 🩺 Problems in plain sight

Unreadable files, empty fields, mixed values inside one album, repeated track numbers, missing or small covers, garbled text from old encodings, damaged tags. Hover over a problem badge to see what exactly is wrong and how to fix it; **Rewrite tags** repairs damaged ones. The **"With problems"** filter shows only the albums that need attention.

![Problems highlighted on an album](screenshots/en/problems.jpg)

### 🪄 One-click fixes

They fill only what's empty, never overwriting your data:

- titles, artists and numbers from file names like `01. Artist — Title`;
- album, artist and year from the folder name like `Artist — Album (2021)`;
- track numbers in order, album artist from the tracks;
- fixing the encoding, embedding `cover.jpg` from the folder.

### 🌐 Find the album online

Paste a link to the album from a music service — or just type `Artist — Album`. Grimsby finds the release in open music databases, **matches the tracks to your files** by title, length and number, and lets you choose which fields to take. Fields where your album already has a different value are left alone by default.

![Matching tracks with the release found online](screenshots/en/lookup.jpg)

### ✏️ Rename files by a template

Templates like `%artist% — %title%` or `[%disc%-]%track% %title%`, optionally for album folders too. Preview before renaming, duplicate check — and **Undo rename** if you change your mind.

![Renaming files by a template](screenshots/en/rename.jpg)

### 📦 Batch editing and more

- Tick several albums → set album artist, year, genre or label for all of them at once; merge them into one album.
- Extra fields: label, copyright, composer, comment, ISRC, lyrics.
- Covers: replace, drag a picture onto the cover, view full size, crop to a square, bring to the 1280×1280 PNG standard, or download from the release found online.

### ⚙️ Settings on one page

Language, updates (notify only, automatically or don't check), what's new, feedback and the other Grimsby apps — all on a single page. The window remembers its size and position.

🌍 **9 languages:** English, Russian, Spanish, Portuguese, German, French, Chinese, Japanese and Korean — switch in Settings, it changes right away.

![Settings](screenshots/en/settings.jpg)

![Grimsby apps and feedback](screenshots/en/apps.jpg)

---

## Your files are safe

- Only tags are written — **the audio and video are never re-encoded**.
- Before editing, every file is copied to a backup folder (kept for 14 days).
- After writing, the file is read back. If it doesn't open or its length has changed, the original is restored automatically.

Music: MP3, FLAC, M4A (AAC/ALAC), OGG, Opus, WAV, AIFF, APE, WavPack, WMA and DSF. Video: MP4, M4V, WMV, MKV, WebM and MOV.

---

## Download and install

1. Open the **[latest release](https://github.com/maksimkhatskevich/grimsby-tagger/releases/latest)** page and download the installer `.exe`.
2. Run it. Windows may show a blue "Windows protected your PC" window — that's a normal warning for apps without a paid code-signing certificate. Click **More info → Run anyway**.
   The installer has been checked on VirusTotal: [0 of 67 antivirus engines flag it](https://www.virustotal.com/gui/file/e4dfabdb0c5f60a9fc7c6c42132a6e3492d6ef2414fcf21a93ebd759987a35e0) (version 1.1.0).
3. Click **Add folder…** or drag your music folder into the window.

**Requirements:** Windows 10 or 11 (64-bit). Internet is only needed to find albums online.

---

## Privacy

Grimsby Tagger works on your computer. No accounts, no ads, no analytics. It goes online only when you search for an album yourself, and to check for updates.

---

## Grimsby apps

<table>
  <tr>
    <td align="center" width="33%"><a href="https://github.com/maksimkhatskevich/grimsby-releases"><img src="screenshots/family/player.png" width="56" alt=""><br><b>Grimsby Player</b></a><br><sub>Offline music & video player for your downloaded collection</sub></td>
    <td align="center" width="33%"><a href="https://github.com/maksimkhatskevich/grimsby-converter"><img src="screenshots/family/converter.png" width="56" alt=""><br><b>Grimsby Converter</b></a><br><sub>Video, audio, photos and documents — converted offline</sub></td>
    <td align="center" width="33%"><img src="screenshots/family/tagger.png" width="56" alt=""><br><b>Grimsby Tagger</b><br><img src="screenshots/family/here-en.svg" alt="You are here"></td>
  </tr>
</table>

---

## Feedback

Found a bug, have an idea or just want to say thanks? Get in touch:

- ✉️ email: **[grimsbyy@gmail.com](mailto:grimsbyy@gmail.com)**
- 🐞 bugs and ideas: [Issues](https://github.com/maksimkhatskevich/grimsby-tagger/issues)
- 📣 Telegram: [@itsgrimsby](https://t.me/itsgrimsby) (in Russian)

---

## Licenses

Grimsby Tagger uses open-source components, including Electron, React, music-metadata and TagLib#. The full list with license texts is in `THIRD_PARTY_NOTICES.txt` in the program folder. Album covers in the screenshots belong to their rights holders and are shown as an example of a personal library.

<p align="center"><sub>© 2026 Grimsby</sub></p>

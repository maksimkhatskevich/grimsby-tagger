<p align="center">
  <b>English</b> ·
  <a href="README.ru.md">Русский</a>
</p>

<p align="center">
  <img src="screenshots/banner.jpg" alt="Grimsby Tagger — batch tag editor for music">
</p>

<p align="center">
  <b>Tidy up the tags of your whole music library — album by album, not file by file.</b><br>
  See every problem at once, fix it in a couple of clicks and save everything with one button.
</p>

<p align="center">
  <a href="https://github.com/maksimkhatskevich/grimsby-tagger/releases/latest"><img src="https://img.shields.io/github/v/release/maksimkhatskevich/grimsby-tagger?label=version&color=3FAC59" alt="Version"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-3FAC59" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/free-no%20ads-111314" alt="Free, no ads">
  <a href="https://www.virustotal.com/gui/file/b751613b791a24d8bc8ba8cddc225921bd529d27bce441955ff651db80b25111"><img src="https://img.shields.io/badge/VirusTotal-0%2F64-2E7D32" alt="VirusTotal 0/64"></a>
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

![Grimsby Tagger: an album card](screenshots/albums.jpg)

---

## Why Grimsby Tagger

Tags are what makes a collection look good in a player: the right album, year, artist, track numbers and cover.
Downloaded music rarely arrives perfect — one album has no year, another has a missing cover, a third has broken Cyrillic.
Classic tag editors show you a spreadsheet of thousands of files, and you fix them one row at a time.

**Grimsby Tagger thinks in albums.** Point it at a folder of any depth — it groups the files into albums,
shows each one as a card with its cover, and highlights what's wrong. Edit whatever you like, then **Save all** (Ctrl+S).

---

## Features

### 💿 Albums sort themselves out

An album is a folder plus the "Album" tag. Several albums in one folder are split apart; CD1/CD2 or "Disc 2"
subfolders are joined into one album; files without tags stick to the album of their folder.
Deluxe and standard editions from one folder become one card, with each track's edition labeled.

### 🩺 Problems in plain sight

Unreadable files, empty fields, different values inside one album, repeated track numbers,
missing, small or partial covers, garbled Cyrillic from old encodings, broken tags.
The **"With problems"** filter shows only the albums that need attention.

![Problems highlighted on an album](screenshots/problems.jpg)

### 🪄 One-click fixes

They fill only what's empty, never overwriting your data:

- titles, artists and numbers from file names like `01. Artist — Title`;
- album, artist and year from the folder name like `Artist — Album (2021)`;
- track numbers in order, album artist from the tracks;
- fixing the encoding, embedding `cover.jpg` from the folder.

### 🌐 Find the album online

Paste a link to the album from a music service — or just type `Artist — Album`.
Grimsby finds the release in online music databases (MusicBrainz and others), **matches the tracks to your files**
by title, length and number, and lets you choose which fields to take. Fields where your album already has a different value
are left alone by default.

![Matching tracks with the release found online](screenshots/lookup.jpg)

### ✏️ Rename files by a template

Templates like `%artist% — %title%` or `[%disc%-]%track% %title%`, optionally for album folders too.
Preview before renaming, duplicate check — and **Undo rename** if you change your mind.

![Renaming files by a template](screenshots/rename.jpg)

### 📦 Batch editing and more

- Tick several albums → set album artist, year, genre or label for all of them at once; merge them into one album.
- A track in the wrong album? Drag it to the right one — on save it gets that album's tags and cover and moves to its folder.
- Discs are marked with dividers between tracks; track numbers on each disc are recalculated automatically.
- Extra fields: label, copyright, composer, comment, ISRC, lyrics.
- Covers: replace, drag a picture onto the cover, view full size, crop to a square, bring to the 1280×1280 PNG standard (for many albums at once), remove, or download from the release found online.

---

## Your files are safe

- Only tags are written — **the audio is never re-encoded**.
- Before editing, every file is copied to a backup folder (kept for 14 days).
- After writing, the file is read back. If it doesn't open or its length has changed, the original is restored automatically.

Supports MP3, FLAC, M4A (AAC/ALAC), OGG, Opus, WAV, AIFF, APE, WavPack, WMA and DSF.

---

## Download and install

1. Open the **[latest release](https://github.com/maksimkhatskevich/grimsby-tagger/releases/latest)** page and download the installer `.exe`.
2. Run it. Windows may show a blue "Windows protected your PC" window — that's a normal warning for apps
   without a paid code-signing certificate. Click **More info → Run anyway**.
   The installer has been checked on VirusTotal: [0 of 64 antivirus engines flag it](https://www.virustotal.com/gui/file/b751613b791a24d8bc8ba8cddc225921bd529d27bce441955ff651db80b25111) (version 1.0.0).
3. Click **Add folder…** or drag your music folder into the window.

**Requirements:** Windows 10 or 11 (64-bit). Internet is only needed to find albums online.

---

## Privacy

Grimsby Tagger works on your computer. No accounts, no ads, no analytics.
It goes online only when you search for an album yourself.

---

## Grimsby apps

<table>
  <tr>
    <td align="center" width="33%"><a href="https://github.com/maksimkhatskevich/grimsby-releases"><img src="screenshots/family/player.png" width="56" alt=""><br><b>Grimsby Player</b></a><br><sub>Offline music &amp; video player for your downloaded collection</sub></td>
    <td align="center" width="33%"><a href="https://github.com/maksimkhatskevich/grimsby-converter"><img src="screenshots/family/converter.png" width="56" alt=""><br><b>Grimsby Converter</b></a><br><sub>Video, audio, photos and documents — offline</sub></td>
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

Grimsby Tagger uses open-source components, including Electron, React, music-metadata and TagLib#.
The full list with license texts is in `THIRD_PARTY_NOTICES.txt` in the program folder.
Album covers in the screenshots belong to their rights holders and are shown as an example of a personal library.

<p align="center"><sub>© 2026 Grimsby</sub></p>

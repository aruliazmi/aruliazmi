# Aruli Azmi

Backend dan infra tinkerer dari Bekasi. Sehari-hari ngurus server automation, game hosting,
bot operasional, dan tooling kecil yang motong kerjaan repetitif.

Sekarang paling banyak ngulik SA-MP / open.mp biar enak jalan di Android dan Linux: client
Android yang lolos Android 15 dan 16, panel Pterodactyl yang bisa ngejalanin binary Windows
lewat Wine, plus otomasi backup dan monitoring yang nggak perlu diingetin tiap hari.

Sebelumnya lebih banyak di bot Discord dan Telegram buat operasional server roleplay:
registrasi UCP, verifikasi OTP WhatsApp, anti-raid, dan monitoring status server.

## Yang biasa dipakai

Bahasa harian Python, Bash, Node, dan PHP. Infranya Docker, MySQL/MariaDB, Linux (Debian dan
Ubuntu), Nginx. Yang paling sering kebuka: Pterodactyl Wings dan Eggs, Wine headless, Android
NDK dan CMake. Buat bot dan integrasi: Discord.js, Telegram Bot API, Fonnte buat WhatsApp.

## Proyek

**[Client Android SA-MP](https://github.com/aruliazmi/eastside-client).** Client buat server
SA-MP / open.mp 0.3.DL. Launcher custom, mod loader AML, UI CEF, dan downloader model 0.3.DL
yang narik DFF/TXD langsung dari CDN server. Library bawaannya sudah disiapin buat page size
16 KB, jadi nggak kena blokir pas instal di Android 15 dan 16.
`Android` `C/C++` `Java` `CMake`

**[OpenMP di Pterodactyl lewat Wine](https://github.com/aruliazmi/open-mp-eggs).** Egg
Pterodactyl plus image Docker custom buat ngejalanin OpenMP server `.exe` di lingkungan Linux.
Wine-nya headless, panelnya nggak sadar yang jalan bukan binary Linux native.
`Shell` `Docker` `Pterodactyl` `Wine`

**[Hermes Agent on Qoder](https://github.com/aruliazmi/hermes-qoder-acp).** Provider model buat
Hermes Agent yang jalan di atas langganan Qoder, lewat `qodercli` dan ACP. `Python`

Bot operasional:

- **[Araz BOT](https://github.com/aruliazmi/bot-diskort)** — anti-raid Discord plus sistem UCP:
  registrasi, verifikasi OTP WhatsApp, refund role, announce dari WA, dan monitoring status
  server SA-MP tiap 10 detik. `Discord.js` `MySQL`
- **[Bang Bikin Bang](https://github.com/aruliazmi/bang-bikin-bang)** — registrasi UCP lewat
  verifikasi OTP WhatsApp, validasi username dan nomor HP awalan `62`, plus umur akun Discord
  minimal 7 hari. `Discord.js` `Sequelize` `Fonnte`
- **[GrowGarden Alert](https://github.com/aruliazmi/grow-garden-bot)** — bot Telegram pemantau
  stok dan item rare GrowGarden, cek tiap 5 detik, countdown restock per kategori.
  `Python` `Telegram API`
- **[Auto Backup DB](https://github.com/aruliazmi/autobackup)** — backup MySQL otomatis,
  hasilnya dikirim ke Discord. `Node.js`

## Aktivitas

<div align="center">

<img width="420" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aruliazmi&theme=tokyonight" alt="Ringkasan kontribusi" />

<img width="420" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=aruliazmi&theme=tokyonight" alt="Statistik" />

</div>

Ada yang mau ditanyain soal SA-MP di Android, Pterodactyl, atau bot? DM aja.

[Instagram](https://instagram.com/4razzm)

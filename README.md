# Dapat USDC dari make.fun: Panduan Pemula dari Nol sampai Klaim Hadiah

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/ramdanromandany94/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/ramdanromandany94/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Mulai dari sini:** daftar lewat link referral saya — [https://make.fun/r/hxd0fhbx](https://make.fun/r/hxd0fhbx)
>
> Kode referral saya: `hxd0fhbx`

Panduan ini membawa kamu dari belum punya akun sama sekali sampai hadiah USDC masuk ke wallet kamu. Ditulis untuk pemula: tidak ada pengalaman bounty yang dibutuhkan. Kalau kamu sudah pernah memakai AI coding agent — Claude Code, Cursor, Copilot, atau yang sejenis — kamu sudah punya keahlian utama yang diperlukan di sini. Sisanya tinggal mengikuti langkah demi langkah di bawah.

Di akhir panduan ini kamu akan punya: akun make.fun, kit bounty yang terhubung ke akunmu, satu entry yang sudah dikirim, dan link referral kamu sendiri yang bisa terus menghasilkan.

## Daftar isi

- [Peta perjalanan: sembilan langkah sampai hadiah](#peta-perjalanan-sembilan-langkah-sampai-hadiah)
- [Sebenarnya make.fun itu apa?](#sebenarnya-makefun-itu-apa)
- [Siapkan empat hal ini dulu](#siapkan-empat-hal-ini-dulu)
- [Langkah 1 — Buat akun make.fun](#langkah-1--buat-akun-makefun)
- [Langkah 2 — Sambungkan GitHub dan wallet Solana](#langkah-2--sambungkan-github-dan-wallet-solana)
- [Langkah 3 — Hubungkan kit ke akunmu](#langkah-3--hubungkan-kit-ke-akunmu)
- [Langkah 4 — Pilih bounty yang bisa kamu selesaikan](#langkah-4--pilih-bounty-yang-bisa-kamu-selesaikan)
- [Langkah 5 — Unduh kit bounty](#langkah-5--unduh-kit-bounty)
- [Langkah 6 — Biarkan agent membangun entry](#langkah-6--biarkan-agent-membangun-entry)
- [Langkah 7 — Bundle, check, submit](#langkah-7--bundle-check-submit)
- [Langkah 8 — Pantau status, perbaiki, kirim ulang](#langkah-8--pantau-status-perbaiki-kirim-ulang)
- [Langkah 9 — Klaim USDC kamu](#langkah-9--klaim-usdc-kamu)
- [Cara kedua dapat uang: link referral kamu sendiri](#cara-kedua-dapat-uang-link-referral-kamu-sendiri)
- [Membagikan link referral supaya ada yang daftar](#membagikan-link-referral-supaya-ada-yang-daftar)
- [Kesalahan yang paling sering menggugurkan entry pemula](#kesalahan-yang-paling-sering-menggugurkan-entry-pemula)
- [Kalau ada yang tidak jalan](#kalau-ada-yang-tidak-jalan)
- [Cek kesiapan sebelum submit](#cek-kesiapan-sebelum-submit)
- [FAQ](#faq)
- [Tautan penting](#tautan-penting)

## Peta perjalanan: sembilan langkah sampai hadiah

| # | Langkah | Yang kamu lakukan | Perkiraan waktu |
|---|---|---|---|
| 1 | Buat akun | Daftar di make.fun, isi profil | 10 menit |
| 2 | Sambungkan GitHub + wallet | Tautkan GitHub dan wallet Solana di profil | 10 menit |
| 3 | Hubungkan kit | `login` dari kit, setujui kodenya | 5 menit |
| 4 | Pilih bounty | Baca halaman bounty, cek deadline dan cara penilaian | 15 menit |
| 5 | Unduh kit | `curl` kit bounty, baca `RULES.txt` | 5 menit |
| 6 | Agent membangun | Agent menulis entry di sesi baru | 1–4 jam |
| 7 | Bundle, check, submit | Bundle transkrip, jalankan check, submit | 15 menit |
| 8 | Pantau dan perbaiki | Baca status, perbaiki yang ditolak, kirim ulang | Sesuai kebutuhan |
| 9 | Klaim | Klaim USDC dari profil atau kit | 5 menit |

Total waktu aktif kamu sendiri di luar waktu agent bekerja: kurang dari satu jam. Sisanya adalah waktu agent membangun dan waktu menunggu hasil.

## Sebenarnya make.fun itu apa?

make.fun adalah papan bounty untuk software yang dibangun dengan AI agent. Setiap bounty adalah sebuah kontes: ada tugas yang harus dibangun, ada tenggat, dan ada hadiah USDC yang sudah disiapkan sebelum ada yang mulai. Kamu pilih satu bounty, agent kamu membangun entry-nya, kamu kirim entry itu, dan kalau entry kamu menempati peringkat berbayar, kamu klaim hadiahnya ke wallet kamu sendiri.

Tiga hal yang perlu dipahami sejak awal:

- **Hadiahnya sudah dikunci sebelum kamu mulai.** Setiap bounty baru dibuka dengan seluruh hadiahnya terkunci di escrow on-chain di Solana. Program escrow-nya adalah kode terbuka di [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow). Tidak ada yang bisa memindahkan hadiah itu ke tempat lain selagi kamu membangun.
- **Kerja agent kamu adalah buktinya.** Sebuah entry terdiri dari repositori publik di satu commit, ditambah transkrip — log sesi — dari sesi AI yang membangunnya. Transkrip inilah yang dipakai situs untuk memastikan bahwa agent kamu sendiri yang mengerjakan entry itu, bukan kode orang lain yang diakui sebagai karyamu. Kit membersihkan kredensial, alamat email, dan path folder rumah dari transkrip sebelum diunggah.
- **Kebanyakan bounty gratis dimasuki.** Bounty yang memungut biaya entry menulisnya jelas di halamannya, dan biaya itu masuk ke pot hadiah bounty tersebut. Kamu tidak pernah membayar untuk sekadar tahu apakah kamu menang.

Yang penting juga: ini bukan pekerjaan dan bukan lotre. Ini kontes dengan aturan yang dipublikasikan: halaman bounty menjelaskan apa yang harus dibangun, bagaimana penilaiannya, bagaimana seri diputuskan, dan berapa hadiah tiap peringkat. Semua entry dinilai dengan cara yang sama, di sandbox yang sama, biasanya lebih dari sekali.

Contoh angka dari bounty panduan ini: bounty **"Bring the humans again"** (bring-the-humans-02) membayar 50 peringkat teratas dari total hadiah $1.000 USDC — juara 1 dapat $150, juara 2 $80, juara 3 $50, peringkat 4–10 masing-masing $20, peringkat 11–25 masing-masing $17, dan peringkat 26–50 masing-masing $13. Tenggatnya Sabtu, 21 November 2026 pukul 17:30 WIB.

## Siapkan empat hal ini dulu

Sebelum mulai, pastikan empat hal ini sudah ada. Semuanya gratis dan tidak memakan waktu lama.

- **AI coding agent.** Agent apa pun yang menyimpan log sesi bisa dipakai. Kit menemukan sendiri sesi dari Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider, dan puluhan lainnya. Kalau agent kamu tidak menyimpan log sesi yang bisa dibaca, kamu masih bisa ikut dengan menyerahkan apa yang bisa kamu lihat (bundle `--session` menerima file sesi yang kamu ekspor sendiri).
- **Akun GitHub.** Entry kamu tinggal di repositori publik GitHub. Akun GitHub ini harus yang tertaut ke akun make.fun kamu — entry hanya diakui milikmu kalau pemilik repositorinya adalah akun GitHub yang tertaut itu.
- **Node.js 22** di komputermu, untuk menjalankan command line kit. Tidak ada yang lain yang perlu diinstal.
- **Wallet Solana** untuk menerima hadiah USDC. Keypair agent kamu sendiri bisa menjadi wallet itu, dan langkah `login` di bawah akan membuatkannya kalau kamu belum punya.

## Langkah 1 — Buat akun make.fun

1. Buka [https://make.fun/r/hxd0fhbx](https://make.fun/r/hxd0fhbx) dan klik **Sign in** di kanan atas. Daftar lewat link referral tidak memungut biaya apa pun darimu, dan memberi kredit ke orang yang menunjukkan jalan ini. Kode referralnya: `hxd0fhbx`.
2. Masuk dengan GitHub, Google, Apple, Discord, atau wallet Solana. Masuk dengan wallet tidak mengirim transaksi dan tidak dipungut biaya.
3. Buka profilmu — avatar di kanan atas — dan lengkapi: nama pengguna, foto, dan bio singkat.
4. Kalau kamu masuk dengan cara lain, tautkan juga akun GitHub dan wallet Solana kamu dari profil. Entry kamu berasal dari repositori GitHub kamu, dan hadiah kamu masuk ke wallet kamu, jadi kedua tautan itu penting.

## Langkah 2 — Sambungkan GitHub dan wallet Solana

Ini langkah yang paling sering dilewati pemula, padahal tanpanya entry kamu tidak bisa diterima.

- **GitHub:** di profil make.fun, tautkan akun GitHub kamu. Repositori entry harus dimiliki akun GitHub ini. File klaim (`.makefun/owner.json`) tidak bisa membuat repositori orang lain menjadi milikmu.
- **Wallet Solana:** tautkan wallet kamu juga. Hadiah dibayar dalam USDC di Solana ke wallet yang menandatangani entry pemenang. Kalau kamu belum punya wallet, langkah `login` di bawah akan membuat keypair baru untukmu.

Periksa keduanya sebelum membangun: buka profilmu dan pastikan GitHub dan wallet sudah tercantum sebagai tertaut.

## Langkah 3 — Hubungkan kit ke akunmu

Command line kit perlu dihubungkan ke akunmu satu kali, entah kamu yang mengetik perintahnya atau agent kamu. Dengan begitu agent kamu masuk memakai akunmu, bukan membuat akunnya sendiri. Dari dalam folder kit sebuah bounty, jalankan:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

Perintah itu mencetak baris seperti `Open <link> and approve code XXXX-XXXX`. Buka link itu selagi kamu masuk ke make.fun, periksa kodenya cocok, lalu setujui. Kalau perintahnya berhenti menunggu sebelum kamu menyetujui, jalankan lagi saja. Pertama kali, perintah ini juga membuat keypair Solana di mesin ini, di `~/.makefun/keypairs/https_make.fun.json`, dan menaruh wallet-nya di akunmu. Sejak itu entry yang dikirim dari kit ini masuk atas nama pengguna kamu, dan kamu mengatur apa lagi yang boleh dilakukan koneksi itu (komentar, taruhan, ubah profil) di **Profile → API keys → Paired agents**.

Ringkasnya, setengah jam pertamamu: daftar, tautkan GitHub dan wallet, hubungkan kit dengan `login`, lalu baca aturan satu bounty yang tutup dalam beberapa hari. Setelah itu kamu siap membangun — sisanya kamu pelajari sambil melakukannya sekali.

## Langkah 4 — Pilih bounty yang bisa kamu selesaikan

Halaman depan mengurutkan bounty ke Trending, New, dan Ending soon, dalam kategori seperti Code, Games, Trading, Forecasting, dan Growth. Setiap halaman bounty menunjukkan:

- **Apa yang harus dibangun**, dalam satu baris lalu selengkapnya
- **Aturannya**: apa saja yang harus ada di entry, bagaimana penilaiannya, bagaimana seri diputuskan
- **Hadiahnya**: berapa yang didapat tiap peringkat berbayar
- **Tahapannya**: kapan entry ditutup dan kapan hasil akhir keluar

Baca aturannya sebelum membangun apa pun. Sebagian bounty butuh perangkat lunak tambahan atau akun di tempat lain, dan halamannya menyebut itu di depan. Lalu pilih dengan kepala dingin, bukan dengan semangat sesaat:

- **Mulai dari bounty yang tugasnya kamu pahami dalam sekali baca.** Kalau kamu tidak bisa menjelaskan seperti apa entry yang menang, agent kamu juga tidak akan bisa membangunnya.
- **Cocokkan tenggat dengan waktumu.** Bounty yang tutup enam jam lagi bukan bounty pertama yang bagus.
- **Lihat berapa tempat yang dibayar.** Bounty $1.000 yang membayar 50 tempat jauh lebih ramah untuk pemula daripada bounty $1.000 yang hanya membayar satu tempat.
- **Lihat cara penilaiannya, bukan cuma hadiahnya.** Bounty yang dinilai AI judge menghargai kerapian dan presentasi; bounty yang dinilai test suite menghargai ketepatan. Pilih jenis pekerjaan yang agent kamu kuasai.

## Langkah 5 — Unduh kit bounty

Setiap bounty membawa kit: aturannya, datanya, entry awal kalau ada, dan command line `makefun`. Ambil dari formulir entry di halaman bounty, atau dari terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` di dalam kit adalah aturan bounty kata demi kata. Bacalah — dokumen itu satu-satunya yang menentukan apakah entry kamu dihitung. Untuk bounty yang bisa dinilai di mesinmu sendiri, bagian **Grade locally** memberi perintah persisnya, biasanya dijalankan dari kit dengan folder entry kamu di sebelahnya:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

Perintah itu menilai entry kamu dengan data latihan dari kit, memakai sandbox Docker yang sama seperti server, jadi kamu bisa melihat posisimu sebelum menghabiskan satu pengiriman.

## Langkah 6 — Biarkan agent membangun entry

1. **Mulai setelah bounty dibuka.** Buat repositori GitHub publik yang baru, clone di sebelah folder kit (perintah di bawah menyebutnya `my-entry`), lalu buka sesi baru agent kamu di dalamnya. Sesi yang dimulai sebelum bounty dibuka tidak bisa dientrikan.
2. **Pasang lisensi.** MIT adalah pilihan yang biasa — setiap entry harus membawa lisensi yang disetujui OSI, dan lisensi yang hilang adalah salah satu alasan penolakan yang paling tidak perlu.
3. **Mulai dari `starter/` kit** kalau ada: salin ke dalam repo dan suruh agent kamu menjadikannya miliknya sendiri. Itu entry awal yang bekerja dan memenuhi aturan, bukan entry pemenang.
4. **Bangun di sesi itu, dan biarkan agent kamu menulis file-nya.** Pemeriksaan mencocokkan transkrip dengan kode, jadi menempel kode dari tempat lain melemahkan entry kamu — kode yang ditulis agent kamu itulah yang dihitung sebagai hasil kerjanya. Menulis sedikit kode dengan tangan diperbolehkan; hanya saja porsinya dihitung lebih kecil sebagai karya agent.
5. **Tambahkan README yang diminta bounty.** Sebagian bounty memberi templat README dengan badge make.fun untuk repositorimu; isi dan commit bersama sisanya.

Kebiasaan yang sangat menguntungkan: suruh agent kamu membaca [make.fun/skill.md](https://make.fun/skill.md) dulu. Itu seluruh loop entry yang ditulis untuk agent — setiap perintah dan setiap pemeriksaan, dalam satu file. Lalu tempelkan bagian penilaian dari `RULES.txt` bounty ke prompt pertama agent kamu, supaya ia membangun ke arah yang benar-benar diukur, bukan ke arah yang kelihatan mengesankan.

Kalau kamu lebih suka mengarahkan daripada mengetik perintah, kamu bisa menyerahkan seluruh loop ke agent kamu. Buka chat baru dengan coding agent kamu dalam mode agent, lalu tempelkan satu perintah ini:

```text
Baca make.fun/skill.md, lalu ikuti bounty make.fun yang masih buka dan paling bisa kamu bangun dengan baik. Bangun entry-nya, bundle, submit, dan klaim hadiah USDC-nya kalau entry itu menang.
```

Agent akan masuk ke akunmu (atau menghubungkan kit ke akunmu), memilih bounty, membangun, membundel, mengirim, mengikuti hasil pemeriksaan, dan mengklaim. Tetapkan dulu batas waktu buatnya, dan awasi bounty apa yang ia pilih — jangan biarkan ia memilih bounty yang tugasnya tidak kamu pahami.

## Langkah 7 — Bundle, check, submit

Begitu kodenya di-push, pilih commit yang mau kamu entrikan dan bundle transkrip sesi dari dalam folder kit:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` mengumpulkan setiap sesi yang mengerjakan repositori, menghapus kredensial dan detail pribadi, dan menulis run record: prompt pembuka kamu, agent, model, dan setup yang membangunnya, serta server MCP yang dipakainya. Kalau ada bagian yang hilang, perintah ini tidak menulis apa-apa dan menyebutkan flag yang harus ditambah — log Claude Code, misalnya, tidak membawa system prompt maupun effort, jadi sebutkan dengan `--system-prompt <file>` dan `--effort <level>`. Sebagian bounty merekam sesi secara langsung, bukan menerima bundle; `RULES.txt`-nya menjelaskan caranya.

Sebelum masuk, jalankan pemeriksaan situs sendiri di mesinmu. Entry yang ditolak tetap menghitung ke batas pengiriman harian, jadi ini tempat termurah untuk menangkap kesalahan:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Lalu masuk, entah dari formulir **Enter** di halaman bounty — tempelkan link repositori dan commit, unggah bundle — atau dari kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` menandatangani entry dengan wallet yang disiapkan `login` di langkah 3, yang diminta setiap bounty dengan hadiah escrow. Wallet itu juga tempat hadiah akan dibayar.

## Langkah 8 — Pantau status, perbaiki, kirim ulang

```sh
node cli/makefun.mjs status
```

menampilkan entry-entry kamu dan posisinya masing-masing: **submitted**, **checked**, **scored**, atau **rejected**. Entry yang ditolak mencantumkan setiap pemeriksaan yang gagal beserta perbaikannya. Terapkan perbaikannya dan kirim lagi — kamu bisa terus mencoba sampai tenggat, dalam batas pengiriman harian bounty itu (`node cli/makefun.mjs status --competition <bounty-slug>` menunjukkan sisanya). Entry terakhirmu adalah yang dihitung, kecuali kamu memilih entry yang lebih awal.

Dua hal tentang papan peringkat yang sering menjebak pendatang baru:

- **Skor awal masih sementara.** Skor dihitung dari sedikit pertandingan dan banyak berubah seiring entry baru datang. Peringkat yang turun karena pesertanya bertambah bukan berarti entry kamu memburuk.
- **Seri mutlak dimenangkan entry yang lebih dulu.** Kalau dua entry berakhir dengan skor yang sama, yang dikirim lebih dulu menempati peringkat lebih tinggi — alasan lain untuk tidak menunda pengiriman sampai jam terakhir.

Untuk bounty panduan ini (bring-the-humans-02), penilaiannya berbeda dari bounty kode: peringkat ditentukan oleh jumlah pendaftar manusia terverifikasi yang datang lewat link referral kamu selama masa bounty. Seri juga dimenangkan entry yang pengiriman akhirnya diterima lebih dulu, jadi mengirim lebih awal tetap menguntungkan.

## Langkah 9 — Klaim USDC kamu

Ketika hasil dipublikasikan dan entry kamu menempati peringkat berbayar, kamu mendapat pemberitahuan bahwa hadiahmu siap. Klaim dari profilmu, atau dari kit dengan claim id yang tercantum di `status`:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` menjawab satu pertanyaan di layar klaim — jawab `yes` kalau kamu adalah warga Amerika. Hadiah dibayar dalam USDC di Solana ke wallet kamu sendiri, setelah pemeriksaan sanksi otomatis. Klaim segera: jendela klaim terbatas, dan hadiah yang tidak diklaim bisa jatuh ke entry berikutnya. Formulir pajak hanya diminta kalau hukum AS mengharuskannya — W-9 untuk warga Amerika, W-8BEN untuk yang lain — dan hanya sesudah hadiah kamu dari make.fun dalam satu tahun kalender mencapai ambang pelaporan $2.000.

Perlu diketahui: cara bayarnya ada dua, tergantung bounty-nya. Kalau hadiah bounty dikunci di escrow saat dibuka, pemenang mengklaim dari escrow ke wallet yang menandatangani entry pemenang, dan hadiah yang tidak ada yang menangkan atau klaim kembali ke wallet hadiah make.fun setelah jendela klaim escrow berakhir. Kalau tidak, hadiah dibayar dari wallet hadiah make.fun, dan pemenang mengklaim dalam 7 hari dengan detail pembayaran — hadiah yang tidak diklaim dalam 7 hari diteruskan ke entry berikutnya di klasemen. Halaman bounty menuliskan yang mana yang berlaku.

## Cara kedua dapat uang: link referral kamu sendiri

Menang bukan satu-satunya cara make.fun membayar. Setiap akun mendapat link referral, `https://make.fun/r/<code>`, dan `?ref=<code>` di halaman make.fun mana pun bekerja sama. Kamu mendapatkan:

- **0,25 USDC** saat akun yang kamu referensikan mendaftar (untuk 20 pendaftar pertamamu)
- **1,00 USDC** saat akun yang kamu referensikan pertama kali memenangkan hadiah
- **10% dari apa yang mereka menangkan** selama 90 hari setelah mereka mendaftar

Bagian 10% itu dibayar make.fun di atas hadiah — orang yang kamu referensikan tetap menerima hadiahnya utuh. Link kamu, berapa nilai tiap hadiah saat ini, dan semua yang sudah kamu peroleh ada di tab **Referrals** di profilmu, dan kamu mengklaim hadiah referral di sana juga.

Dua hal yang perlu diketahui. Pertama, referral terikat ke kode yang pertama kali dilihat browser pengunjung, dan sentuhan pertama itu menang selama 60 hari — link yang datang kemudian tidak menggantikannya. Kedua, hanya orang asli yang dihitung: pemeriksaan yang sama yang membayar hadiah referral yang memutuskan pendaftar mana yang dihitung, jadi akunmu sendiri, pendaftar yang memakai jaringan yang sama denganmu, akun yang tidak aktif dan tidak pernah ikut serta, serta bot tidak pernah membayar. Setiap hadiah ditinjau setidaknya sehari sebelum bisa kamu klaim, dan dibayarkan di Solana setelah disetujui.

Kalau panduan ini membantumu, mendaftar lewat [link saya](https://make.fun/r/hxd0fhbx) — kode `hxd0fhbx` — adalah cara berterima kasih yang baik, dan tidak memungut biaya apa pun darimu.

## Membagikan link referral supaya ada yang daftar

Untuk bounty ini, link referral bukan sekadar bonus — jumlah pendaftar terverifikasi lewat link kamulah yang menentukan peringkat. Jadi membagikannya adalah bagian dari pekerjaannya, bukan renungan belakangan.

- **Bagikan ke orang yang memang memakai AI coding agent.** Teman satu komunitas developer, grup belajar, atau rekan kerja yang sudah memakai Claude Code, Cursor, atau Copilot adalah audiens terbaik. Orang yang belum pernah memakai AI agent butuh penjelasan lebih panjang sebelum mendaftar.
- **Jelaskan apa untungnya buat mereka, bukan buat kamu.** Orang mendaftar karena mereka bisa mendapat USDC dari bounty, bukan karena kamu mendapat 0,25 USDC. Ceritakan hadiah dan cara ikutnya, lalu sertakan link kamu di akhir.
- **Pakai panduan ini sebagai bahan bagikan.** Kirim link repositori ini bersama link referral kamu — orang yang membaca panduannya sampai selesai jauh lebih mungkin mendaftar dan benar-benar ikut serta daripada orang yang hanya mengklik link kosong.
- **Jangan membeli pendaftar atau memakai bot.** Pemeriksaan referral menolak akun palsu, akun yang berbagi jaringan denganmu, dan klaster IP yang sama. Pendaftar seperti itu tidak dihitung dan bisa merugikan akunmu.
- **Bagikan lebih awal.** Pendaftar dihitung kalau akunnya dibuat dalam jendela bounty, dan tiap pendaftar melewati masa tinjauan 24 jam sebelum diputuskan. Pendaftar di jam-jam terakhir mungkin tidak sempat terverifikasi sebelum pemeriksaan akhir selesai, 30 jam setelah tenggat.

### Contoh pesan untuk dibagikan

Kalau bingung harus menulis apa saat membagikan link, pakai contoh ini dan sesuaikan dengan bahasamu sendiri:

> Lagi coba make.fun — situs bounty tempat AI agent kita membangun software dan dibayar USDC. Bounty-nya ada yang gratis dimasuki, hadiahnya sudah dikunci di escrow sebelum mulai. Panduan lengkapnya saya tulis di repo ini, dan daftarnya lewat link ini: https://make.fun/r/hxd0fhbx

Untuk grup chat developer, versi yang lebih singkat bekerja lebih baik:

> Buat yang pakai Claude Code / Cursor: make.fun membayar USDC buat software yang dibangun agent kamu. Cara daftar dan ikutnya saya tulis di panduan ini. Link daftar: https://make.fun/r/hxd0fhbx

Satu catatan: bagikan ke tempat yang memang mengizinkan promosi. Spam link ke grup yang tidak meminta justru membuat orang mengabaikanmu — dan tidak ada pendaftar yang dihitung dari orang yang tidak pernah benar-benar ikut serta.

## Kesalahan yang paling sering menggugurkan entry pemula

- **Memulai sesi agent sebelum bounty dibuka.** Sesi harus dimulai pada atau setelah pembukaan; sesi yang lebih awal tidak bisa dientrikan, sebagus apa pun kodenya.
- **Submit tanpa menjalankan `check` dulu.** Entry yang ditolak tetap menghabiskan satu dari jatah pengiriman harian. Pemeriksaan lokal gratis dan menangkap sebagian besar kesalahan.
- **Menempel kode yang tidak ditulis agent kamu.** Pemeriksaan transkrip mencocokkan kode dengan sesi yang menulisnya. Kode tempelan mengurangi porsi baris yang ditulis agent kamu, dan entry dengan karya agent yang terlalu sedikit ditolak.
- **Lupa lisensi.** Entry tanpa lisensi yang disetujui OSI ditolak. MIT hanya butuh tiga puluh detik untuk ditambahkan.
- **Menunda pengiriman sampai jam terakhir.** Seri dimenangkan entry yang lebih dulu, dan penolakan di menit akhir tidak menyisakan waktu untuk memperbaiki dan mengirim ulang.
- **Mengejar hadiah, bukan penilaian.** Baca cara bounty dinilai dan bangun ke arah itu. Entry yang cantik tapi tidak bisa diukur grader kalah dari entry sederhana yang bisa diukur.
- **Mengirim repo orang lain atau salinan entry lain.** Entry harus repositori milik akun GitHub yang tertaut ke akunmu, dan file yang sama persis dengan entry akun lain yang lebih dulu ditolak. Tulis karyamu sendiri.

## Kalau ada yang tidak jalan

Hampir semua masalah pemula punya perbaikan yang sudah ditulis di tempatnya. Ini yang paling sering muncul:

- **`login` berhenti menunggu sebelum kamu menyetujui.** Jalankan lagi perintah yang sama. Permintaan persetujuannya dibuat ulang, dan kode yang baru yang berlaku.
- **Perintah kit tidak jalan sama sekali.** Periksa versi Node kamu dengan `node --version`. Kit butuh Node 22 atau yang lebih baru; Node 23.0 sampai 23.7 tidak bisa menjalankan kit ini karena kehilangan satu export dari `node:zlib`, jadi pakai Node 22.18 ke atas, 23.8 ke atas, atau Node 24.
- **`bundle` tidak menemukan sesi apa pun.** Jalankan `bundle --dry-run` dulu: ia menampilkan sesi yang ditemukannya tanpa menulis apa-apa. Kalau tidak ada, agent kamu tidak merekam di tempat yang dibaca bundle — arahkan bundle ke file sesi harness kamu dengan `--session <file>`, atau bangun di harness yang log-nya dibaca bundle.
- **`check` gagal di satu pemeriksaan.** Baca baris pemeriksaannya: setiap kegagalan membawa perbaikannya. Perbaiki, bundle ulang kalau transkrip berubah, lalu jalankan `check` lagi sebelum submit.
- **Submit ditolak karena kuota.** Pesan penolakannya menyebutkan batas mana yang tercapai. Batas harian terangkat saat hari UTC berikutnya dimulai (00:00 UTC); batas total per bounty tidak terangkat dengan menunggu. Jangan kirim ulang permintaan yang sama tanpa perubahan — ia akan ditolak dengan cara yang sama.
- **Klaim tidak muncul di `status`.** Klaim baru muncul setelah hasil dipublikasikan dan entry kamu menempati peringkat berbayar. Kalau hasil sudah keluar tapi tidak ada klaim, periksa lagi peringkat entry kamu dan pastikan kamu melihat status entry yang benar.

## Cek kesiapan sebelum submit

Jalankan daftar ini sebelum kamu menekan submit, supaya tidak membuang jatah pengiriman:

- [ ] Repositori publik, dimiliki akun GitHub yang tertaut ke akun make.fun kamu
- [ ] Repositori dibuat setelah bounty dibuka
- [ ] Ada file LICENSE dengan lisensi yang disetujui OSI (misalnya MIT)
- [ ] README.md di root, bernama persis begitu, di bawah 2 MB, dan menyebut kode referral kamu
- [ ] Tiga baris badge make.fun masih ada dan bukan di dalam code block atau komentar
- [ ] Tidak ada `.github/README.md` yang menggantikan README root
- [ ] screenshot.png di root (PNG, JPEG, atau WebP, di bawah 8 MB dan 16.000.000 piksel), diambil dari halaman repositori ini di GitHub setelah publik
- [ ] About repositori berisi website make.fun dan topik `makefun`
- [ ] Transkrip sesi sudah di-bundle dan `check` lolos di mesinmu
- [ ] Sesi agent dimulai setelah bounty dibuka

## FAQ

<details>
<summary><strong>Apakah ikut bounty dipungut biaya?</strong></summary>

Kebanyakan bounty gratis dimasuki, dan tidak ada pembayaran untuk masuk atau menang. Panggilan model yang dipakai agent kamu saat membangun ditanggung akunmu sendiri.
</details>

<details>
<summary><strong>Apakah make.fun bisa dipercaya?</strong></summary>

Ya. make.fun dijalankan EZO Labs Inc., perusahaan Delaware. Hadiah dikunci di escrow on-chain yang kodenya terbuka saat bounty dibuka. Dan make.fun bukan makefun.ai, bukan library Python makefun, dan bukan launchpad Make Fun lama di Base.
</details>

<details>
<summary><strong>Apakah saya harus bisa coding?</strong></summary>

Membantu, tapi agent kamu yang menulis kode dan kamu yang mengarahkan: kamu memilih bounty, menjalankan penilaian lokal kalau ada, membaca hasil pemeriksaan, dan memutuskan kapan submit.
</details>

<details>
<summary><strong>AI agent apa saja yang bisa dipakai?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, dan puluhan lainnya dikenali kit dengan sendirinya. Agent lain bisa menyerahkan file sesinya dengan `bundle --session <file>`.
</details>

<details>
<summary><strong>Siapa yang membaca transkrip saya, dan apa yang mereka lakukan dengan transkrip itu?</strong></summary>

make.fun membacanya untuk memeriksa bahwa agent kamu sendiri yang membangun entry. Kit menghapus kredensial, alamat email, dan path folder rumah sebelum diunggah, dan `bundle --redact "<teks>"` menghapus detail pribadi lain yang kamu sebutkan.
</details>

<details>
<summary><strong>Bisakah saya ikut sebagai tim?</strong></summary>

Satu akun per orang. Tim masuk di bawah satu akun dan membagi sendiri hadiah yang didapat.
</details>

<details>
<summary><strong>Bagaimana kalau entry saya ditolak?</strong></summary>

Statusnya menyebutkan setiap pemeriksaan yang gagal dan cara memperbaikinya. Perbaiki, lalu kirim lagi sebelum tenggat — untuk itulah batas pengiriman ulang ada.
</details>

<details>
<summary><strong>Kapan saya tahu saya menang?</strong></summary>

Hasil akhir dipublikasikan setelah pemeriksaan akhir selesai — pemeriksaan referral dan pemeriksaan ulang repositori tiap entry final. Kamu mendapat pemberitahuan kalau entry kamu menempati peringkat berbayar, lalu kamu klaim hadiahnya.
</details>

<details>
<summary><strong>Berapa lama hasil keluar?</strong></summary>

Entry ditutup pada tenggat, lalu pemeriksaan akhir berjalan: pemeriksaan referral atas setiap signup, lalu pemeriksaan ulang repositori tiap entry final. Papan peringkat akhir dipublikasikan setelah semua pemeriksaan itu selesai. Untuk bounty ini, signup yang dihitung adalah yang sudah terverifikasi pada akhir pemeriksaan akhir, 30 jam setelah tenggat.
</details>

<details>
<summary><strong>Bisakah saya ikut lebih dari satu bounty?</strong></summary>

Bisa. Setiap bounty punya kit dan entrinya sendiri. Satu akun boleh mengikuti banyak bounty sekaligus, selama setiap entry memenuhi aturan bounty itu masing-masing — termasuk sesi agent yang dimulai setelah bounty itu dibuka.
</details>

<details>
<summary><strong>Apa yang terjadi kalau entry saya seri dengan entry lain?</strong></summary>

Seri mutlak dimenangkan entry yang pengiriman akhirnya diterima lebih dulu. Karena itu mengirim lebih awal menguntungkan: dua entry dengan skor sama tidak diadu lagi dengan ukuran lain.
</details>

## Tautan penting

- [make.fun](https://make.fun) — papan bounty
- [How it works](https://make.fun/how-it-works) — cara kerja make.fun
- [make.fun/skill.md](https://make.fun/skill.md) — panduan lengkap untuk agent
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents) — cara agent AI menghasilkan uang
- [Discord](https://discord.gg/makefun) dan [@makefunai on X](https://x.com/makefunai) — tempat bertanya dan bertemu builder lain

---

<sub>Panduan ini ditulis untuk komunitas make.fun. Kalau panduan ini membantumu memulai, daftar lewat link referral saya: [https://make.fun/r/hxd0fhbx](https://make.fun/r/hxd0fhbx) · kode `hxd0fhbx`</sub>

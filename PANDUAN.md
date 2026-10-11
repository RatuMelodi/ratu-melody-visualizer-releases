# Panduan Ratu Melody Visualizer PRO

Aplikasi Windows untuk membuat video musik: latar video/gambar, visualizer yang bergerak mengikuti musik, lirik yang muncul tepat saat dinyanyikan, lalu export ke MP4 siap unggah. Bisa satu lagu, bisa juga playlist panjang.

Tampilan aplikasinya berbahasa Inggris. Di panduan ini nama tombol dan menu ditulis **tebal** persis seperti di aplikasi.

---

## 1. Kebutuhan komputer

| | Minimum (perkiraan) | Disarankan (sudah diuji) |
| --- | --- | --- |
| Sistem | Windows 10 atau 11, 64-bit | Windows 11 |
| Prosesor | Intel Core i5 / AMD Ryzen 5 (4 inti) | Intel Core i7 generasi 11 atau setara |
| RAM | 8 GB | 16 GB |
| Grafis | Grafis bawaan laptop (Intel UHD / Iris Xe, AMD Radeon) | sama; kartu grafis terpisah tidak wajib |
| Ruang kosong | 5 GB + ruang untuk hasil video | 10 GB atau lebih |
| Internet | Perlu saat instal pertama (unduh model AI ±1,7 GB) | |

Catatan jujur:

- Aplikasi ini diuji pada laptop Intel Core i7-1165G7, RAM 16 GB, grafis Intel Iris Xe, Windows 11. Di sana video playlist 13 menit ukuran 720p selesai di-export dalam ±6 menit.
- Spek "minimum" di atas adalah perkiraan, belum diuji satu per satu. **Coba dulu versi trial 3 hari di komputer Anda sebelum membeli.**
- Belum tersedia untuk Mac, Linux, atau HP.
- Setelah model AI terpasang, aplikasi bisa dipakai tanpa internet. Lisensi juga tidak perlu internet.

---

## 2. Memasang aplikasi

1. Unduh installer dari halaman rilis: <https://github.com/Satria155/ratu-melody-visualizer-releases/releases/latest>. Pilih file yang berakhiran `x64-setup.exe`.
2. Klik dua kali file itu. Windows mungkin menampilkan layar biru **"Windows protected your PC"**. Ini muncul karena aplikasi baru dan belum punya sertifikat penerbit. Klik **More info**, lalu **Run anyway**.
3. Ikuti langkah installer sampai selesai, lalu buka **Ratu Melody Visualizer PRO** dari Start Menu.

### Unduh model AI (sekali saja)

Saat pertama dibuka, aplikasi menawarkan **Download AI models** (±1,7 GB). Model ini dipakai untuk menyelaraskan lirik dengan nyanyian.

- Klik **Download AI models** dan biarkan sampai selesai. Lamanya tergantung internet (contoh: ±20 menit pada koneksi rumahan).
- Boleh di-**Pause** dan dilanjutkan lain waktu; unduhan meneruskan dari posisi terakhir.
- Tanpa model, semua fitur tetap jalan kecuali sinkronisasi lirik.

---

## 3. Trial dan lisensi

**Trial gratis 3 hari.** Semua fitur terbuka. Bedanya dengan versi berlisensi: video hasil export diberi watermark dan paling tinggi 720p. Setelah 3 hari, aplikasi terkunci sampai kunci lisensi dimasukkan. Project yang sudah dibuat tidak hilang.

**Lisensi berlaku untuk 1 komputer.** Kuncinya dibuat khusus untuk komputer Anda, jadi tidak bisa dipakai di komputer lain.

### Cara membeli dan mengaktifkan

1. Di aplikasi, klik tombol **Free trial: … days left** di pojok kanan atas.
2. Pada bagian **Device Code**, klik **Copy**. Bentuknya seperti `H9TQ-Y3F8-ZMTC-3QGC`.
3. Lakukan pembelian, lalu kirim **Device Code** itu beserta bukti pembayaran ke Ratu Melodi (lihat [Bantuan](#9-bantuan)).
4. Anda akan menerima **kunci lisensi**: teks panjang yang diawali `RMVP1.`
5. Salin **seluruh** teks itu, tempel di kotak **Paste the license key**, lalu klik **Activate**.
6. Tombol di pojok kanan atas berubah menjadi **Licensed**. Watermark dan batas 720p hilang.

Hal yang sering salah:

- Kunci lisensi bukan nomor seri pendek (`RM-2026…`). Kunci yang benar panjangnya ratusan huruf.
- Kunci harus disalin utuh, dari `RMVP1.` sampai huruf terakhir, tanpa spasi atau baris tambahan.
- Device Code harus berasal dari komputer yang akan dipakai, bukan dari komputer lain.

Simpan kunci lisensi Anda di tempat yang aman.

### Ketentuan

- **Coba dulu, baru beli.** Trial 3 hari membuka semua fitur, jadi Anda bisa memastikan aplikasi berjalan baik di komputer Anda. Karena itu pembelian yang sudah diaktifkan tidak dapat dikembalikan (tidak ada refund).
- **Satu lisensi untuk satu komputer.** Masa berlaku dihitung sejak kunci dibuat, sesuai paket yang dibeli.
- **Ganti komputer atau instal ulang Windows.** Device Code komputer bisa berubah, sehingga kunci lama tidak diterima lagi. Kirim Device Code yang baru beserta nomor seri atau nama pembelian Anda kepada kami untuk mendapat kunci pengganti. Masa berlakunya mengikuti lisensi awal, dan lisensi di komputer lama tidak boleh dipakai lagi (hapus lewat **Licensed** → **Remove license…**).
- **Pembaruan.** Semua pembaruan aplikasi gratis selama lisensi masih aktif.

---

## 4. Membuat video pertama

Tab ada di sisi kiri. Urutan kerja yang disarankan dari atas ke bawah:

1. **Project**: pilih ukuran dan bentuk video dan, kalau mau cepat, pilih salah satu **Built-in templates** sebagai titik awal.
2. **Audio**: klik **+ Add songs…**. Pilih satu lagu, atau beberapa sekaligus untuk membuat playlist. Format: MP3, WAV, FLAC, M4A, AAC, OGG. Urutan lagu bisa digeser.
3. **Background**: pilih gambar atau video latar. Video yang lebih pendek dari lagu diulang otomatis (ada pilihan ulang halus maju-mundur). Untuk playlist bisa memakai beberapa video/gambar bergantian.
4. **Visualizer**: pilih gaya, warna, bentuk, posisi, dan seberapa kuat reaksinya terhadap dentuman.
5. **Overlay**: tambahkan pemutar "Now Playing", judul lagu, bingkai kamera, partikel (bintang, salju, bokeh, dan lain-lain), teks, gambar, GIF, atau video efek.
6. **Lyrics**: tampilkan lirik (lihat bagian 5).
7. **Export**: simpan menjadi MP4 (lihat bagian 7).

Tips:

- Tekan tombol putar di bawah untuk melihat hasilnya langsung. Semua perubahan terlihat seketika.
- Benda di kanvas (visualizer, lirik, overlay) bisa diklik lalu digeser dan diubah ukurannya langsung.
- Simpan pekerjaan dengan **Save**. File project berakhiran `.mvp`. Jangan memindahkan atau mengganti nama file lagu/video yang dipakai project; kalau terlanjur, aplikasi akan meminta Anda menunjukkan lokasi barunya.
- **↶ / ↷** di kanan atas untuk membatalkan dan mengulang perubahan.

---

## 5. Lirik

Cara kerjanya: Anda memberi **teks lirik**, aplikasi mencari sendiri **kapan** tiap kata dinyanyikan. Hasil paling akurat didapat bila teksnya dari Anda.

### Cara utama: tempel teks, lalu sync

1. Buka tab **Lyrics**.
2. **1 · Lyric text**: tempel lirik lagu di kotak teks.
    - Satu baris teks = satu baris yang tampil di video.
    - Baris kosong = jeda antar bait.
    - Tulis persis seperti yang dinyanyikan, termasuk reff yang diulang. Kalau reff dinyanyikan tiga kali, tulis tiga kali.
    - Keterangan seperti `[Chorus]` atau `[Verse 2]` tidak perlu ditulis.
3. **2 · Sync to the vocals**: klik **Sync to vocals** dan tunggu. Pertama kali untuk tiap lagu butuh beberapa menit (kira-kira sepanjang lagunya); mengulang sync setelah itu hanya beberapa detik.
4. Putar lagu dan periksa hasilnya di daftar **Lines** atau di timeline bawah.

Biarkan **Sync mode** di **Precise mode**. **Fast mode** lebih cepat tetapi kurang tepat pada lagu yang musiknya ramai.

### Cara praktis: file .txt di samping lagu

Simpan lirik sebagai file `.txt` dengan **nama yang sama** dengan lagunya, di **folder yang sama**:

```
Musik\
  Fix You.mp3
  Fix You.txt
  Hargai Aku.mp3
  Hargai Aku.txt
```

Saat lagu ditambahkan di tab **Audio**, liriknya langsung terisi. Ini cara paling nyaman untuk playlist.

- Lagu sudah terlanjur ditambahkan sebelum file `.txt`-nya dibuat? Klik **Find lyrics in .txt files** (playlist) atau **Load from a text file…** (satu lagu).
- File `.lrc` juga dibaca; tanda waktunya diabaikan dan dihitung ulang oleh aplikasi.

### Playlist: sync semua lagu sekaligus

1. Siapkan file `.txt` untuk tiap lagu seperti di atas, lalu tambahkan semua lagu.
2. Di tab **Lyrics**, bagian **All songs**, klik **Sync all songs**. Boleh ditinggal; lagu dikerjakan satu per satu.
3. Pilih lagu lewat **Song being edited** untuk memeriksa masing-masing. Di daftar itu terlihat status tiap lagu: *no lyric text*, *text ready, not synced*, atau jumlah baris yang sudah sync.

### Memeriksa dan memperbaiki

- Kata bergaris bawah **kuning** atau **merah** berarti aplikasi kurang yakin. Dengarkan bagian itu.
- **Klik** sebuah baris untuk memutar dari sana.
- **Klik dua kali** baris untuk memperbaiki teksnya; baris itu disinkronkan ulang otomatis.
- Di timeline bawah, baris dan kata bisa **digeser** untuk mengatur waktunya dengan tangan.
- Baris yang sudah benar bisa **dikunci** (ikon gembok) supaya tidak berubah saat sync ulang.
- **✕** menghapus baris (misalnya ad-lib yang tidak perlu tampil).
- Seluruh lirik terasa sedikit terlalu cepat atau lambat? Geser **Timing offset**.

### Tampilan lirik

Di bagian **Style** ada enam gaya: Standard, Karaoke, Stacked, Word box, Kinetic, Typewriter. Atur juga font, warna, ukuran, garis tepi, bayangan, dan posisi. Gaya berlaku untuk semua lagu di project.

### Cadangan: tidak punya teks lirik

Bila teks lirik benar-benar tidak ada, buka **No lyric text? Let the app write it**. Aplikasi mendengarkan lagunya dan menuliskan liriknya sendiri. Ada dua cara, pilih salah satu:

**Online (Groq)**: cepat, sekitar 10 detik per lagu. Perlu internet dan API key gratis.

1. Klik tautan **Get a free key at console.groq.com/keys**, daftar, lalu buat key.
2. Tempel key di kotak **Paste API key**, klik **Add**. Cukup sekali; key tersimpan di komputer Anda.
3. Klik **Transcribe lyrics**.

**Local engine**: tanpa internet dan tanpa key, tetapi lebih lambat.

1. Pilih **Quality**: **Faster** (unduhan ±250 MB, sekitar 1,5 menit per lagu) atau **Most accurate** (unduhan ±1,1 GB, lebih lama).
2. Klik **Download the engine** (sekali saja).
3. Klik **Transcribe lyrics**.

Untuk playlist, tombol **All songs without text** mengerjakan semua lagu yang belum punya teks.

Hasil cara cadangan bisa salah dengar, terutama pada lagu yang musiknya ramai, jadi wajib diperiksa. Setelah selesai, liriknya langsung disinkronkan.

Selama teks lirik bisa didapat, pakai cara utama.

---

## 6. Batch render

Untuk yang mengelola channel playlist: membuat beberapa video sekaligus dari kumpulan lagu yang sama.

1. Siapkan project playlist seperti biasa (lagu, latar, visualizer, lirik).
2. Buka tab **Batch**, tentukan **Number of videos**.
3. Video 1 memakai urutan lagu dari tab **Audio**; video lainnya diacak, begitu juga urutan video latarnya. Klik **Reshuffle song orders** untuk acakan lain.
4. Isi **Title**, **Description**, dan **Tags** di bagian **YouTube text**. Tulis `{chapters}` di deskripsi untuk daftar lagu beserta waktunya.
5. Pilih folder tujuan dan mulai. Tiap video disimpan bersama satu file `.txt` berisi judul, deskripsi (dengan chapter), dan tag yang tinggal disalin ke YouTube.

Perlu minimal 2 lagu. Makin banyak lagu, makin berbeda urutan antar video.

---

## 7. Export

1. Buka tab **Export**.
2. **Range**: seluruh video atau sebagian saja (berguna untuk tes cepat).
3. **Video**: pilih ukuran (480p sampai 4K) dan bentuk: sama dengan project, **Vertical 9:16** untuk Shorts/Reels/TikTok, atau **Square 1:1**.
4. Pilih lokasi simpan dan mulai. Hasilnya file MP4.

Catatan:

- Selama export, jangan tutup aplikasinya.
- Sambungkan charger laptop; mode hemat baterai memperlambat export.
- Ukuran lebih tinggi butuh waktu lebih lama dan file lebih besar. Untuk YouTube, 1080p sudah cukup.
- Versi trial: maksimal 720p dan ada watermark.

---

## 8. Pembaruan aplikasi

Bila ada versi baru, tombol **Update available** muncul di bagian atas aplikasi. Klik tombol itu, unduh installer barunya, lalu jalankan. Tidak perlu uninstall versi lama; project, lisensi, dan model AI tetap ada.

Pembeli pre-release mendapat semua pembaruan fitur tanpa biaya tambahan selama lisensinya masih aktif.

---

## 9. Bantuan

Kirim pesan ke Ratu Melodi di Threads: <https://www.threads.com/@ratumelodi155>

Supaya cepat dibantu, sertakan: versi aplikasi, apa yang Anda lakukan, dan tangkapan layar pesan yang muncul.

### Masalah yang sering ditanyakan

| Masalah | Yang perlu dicoba |
| --- | --- |
| Layar biru "Windows protected your PC" saat instal | Klik **More info**, lalu **Run anyway**. |
| "That is not a valid license key" | Salin ulang kunci secara utuh, mulai dari `RMVP1.`. Pastikan Device Code yang dikirim berasal dari komputer ini. |
| Unduhan model AI berhenti | Klik **Download AI models** lagi; unduhan melanjutkan dari posisi terakhir. |
| Tombol **Sync to vocals** tidak bisa diklik | Teks lirik masih kosong, lagu belum ditambahkan, atau model AI belum terunduh. |
| Lirik meleset di beberapa baris | Pastikan teks sama dengan yang dinyanyikan (reff ditulis berulang). Perbaiki barisnya dengan klik dua kali, atau geser di timeline. |
| Lirik meleset semua dengan selisih yang sama | Geser **Timing offset**. |
| "Missing media files" saat membuka project | File lagu/video dipindah atau diganti nama. Tunjukkan lokasi barunya. |
| Export lambat | Tutup aplikasi lain, sambungkan charger, coba ukuran 1080p atau 720p. |
| Aplikasi terkunci setelah trial | Masukkan kunci lisensi. Project Anda tetap aman. |

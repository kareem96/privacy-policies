# Kebijakan Privasi — Aman Nur

**Terakhir diperbarui:** 10 Agustus 2026

Aman Nur ("Aplikasi") adalah aplikasi jadwal sholat, arah kiblat, dzikir counter, dan Quran digital untuk Android. Kebijakan privasi ini menjelaskan data apa saja yang diproses Aplikasi dan bagaimana data tersebut ditangani.

## Ringkasan

**Lokasi Anda tidak pernah dikirim ke server manapun.** Semua kalkulasi yang sensitif terhadap lokasi (jadwal sholat, arah kiblat) dihitung sepenuhnya di perangkat Anda. Aplikasi ini tidak memiliki sistem akun atau login.

## Data lokasi

- Aplikasi meminta izin lokasi untuk menghitung jadwal sholat dan arah kiblat yang akurat untuk posisi Anda.
- Koordinat lokasi **diproses 100% di perangkat** — tidak ada panggilan jaringan yang membawa data lokasi Anda ke server manapun, termasuk server milik pengembang.
- Urutan sumber lokasi: GPS perangkat → lokasi terakhir yang tersimpan lokal → pemilihan kota manual (daftar kota statis yang sudah tersimpan di dalam Aplikasi, sepenuhnya offline). Aplikasi **tidak pernah** menebak lokasi Anda lewat alamat IP.
- Jika izin lokasi ditolak, Aplikasi tetap berfungsi penuh lewat pemilihan kota manual.

## Data yang diproses secara lokal (tidak dikirim ke luar perangkat)

- **Riwayat dzikir** (jenis dzikir, jumlah hitungan, tanggal, streak harian).
- **Bookmark ayat Quran** (surah, ayat, catatan opsional).
- **Progress bacaan Quran** (surah/ayat terakhir dibaca, progress Khatmah).
- **Pengaturan Aplikasi** (metode kalkulasi jadwal sholat, bahasa, tema, kota pilihan manual).

Semua data di atas tersimpan di penyimpanan lokal perangkat Anda dan dapat dicadangkan/dipindahkan secara mandiri lewat fitur Export/Import (file terenkripsi dengan passphrase yang Anda tentukan sendiri).

## Data yang dikirim ke pihak ketiga

Aplikasi mengirim data ke layanan berikut, sebatas yang dijelaskan di bawah:

- **Al Quran Cloud API** (`api.alquran.cloud`) — untuk mengunduh teks Arab, terjemahan, transliterasi Latin, dan audio bacaan Quran (diunduh sekali per surah lalu disimpan lokal, tidak diakses live tiap dibuka). Permintaan hanya membawa nomor surah/ayat — **tidak menyertakan lokasi, identitas, atau data pribadi Anda apa pun**.
- **Sumber berita RSS** (NU Online, Muhammadiyah, Republika, Al Jazeera) — untuk menampilkan tab Berita. Aplikasi hanya membaca konten publik dari sumber-sumber ini, tidak ada data Anda yang dikirim ke pihak ketiga ini.
- **Firebase Crashlytics** — laporan crash (jejak error teknis, model perangkat, versi OS/aplikasi) untuk membantu memperbaiki bug. Data dzikir, bookmark, atau catatan pribadi Anda tidak pernah disertakan dalam laporan ini.
- **Firebase Analytics** — informasi penggunaan aplikasi secara agregat (layar yang dibuka, dikumpulkan otomatis oleh SDK Firebase), untuk memahami pola pemakaian aplikasi secara umum.

Kebijakan privasi masing-masing layanan Google di atas dapat dibaca di [Kebijakan Privasi Google](https://policies.google.com/privacy).

## Izin yang digunakan

- **Lokasi (perkiraan & presisi)** — lihat bagian "Data lokasi" di atas. Aplikasi tetap berfungsi penuh jika izin ini ditolak.
- **Notifikasi** — untuk pengingat waktu sholat dan hari besar Islam, sepenuhnya dijadwalkan di perangkat (bukan push notification dari server). Aplikasi tetap berfungsi normal jika izin ini ditolak, hanya pengingat yang tidak muncul.
- **Alarm & pengingat presisi** (`Jadwalkan alarm dan pengingat`) — dibutuhkan agar notifikasi waktu sholat berbunyi tepat waktu, tidak ditunda oleh mode hemat baterai sistem.
- **Restart otomatis setelah reboot** — menjadwalkan ulang pengingat sholat setelah perangkat dinyalakan ulang (pengingat tidak bertahan lewat restart perangkat tanpa izin ini).
- **Layanan latar depan (foreground service)** — dibutuhkan untuk memutar audio bacaan Quran di latar belakang dan mengunduh audio offline, agar tidak terhenti saat Aplikasi diminimalkan.
- **Getar** — untuk umpan balik haptik pada fitur dzikir counter.
- **Internet** — dibutuhkan untuk mengunduh konten Quran, berita, dan mengirim laporan crash/analytics (Firebase). **Tidak digunakan untuk mengirim data lokasi atau data pribadi Anda lainnya.**

Aplikasi **tidak meminta** izin kamera, mikrofon, kontak, maupun penyimpanan file.

## Kontrol Anda atas data

- Semua data dapat dihapus permanen dengan meng-uninstall aplikasi.
- Anda dapat mencadangkan/memindahkan data secara mandiri lewat fitur Export/Import (file terenkripsi dengan passphrase yang Anda tentukan sendiri).
- Karena data sensitif (lokasi, dzikir, bookmark) tidak pernah dikirim ke server pengembang, tidak ada cara bagi pengembang untuk mengakses data pribadi Anda kapan pun.

## Kontak

Pertanyaan seputar kebijakan privasi ini dapat dikirim ke: **karimdev96@gmail.com**

## Perubahan kebijakan

Kebijakan ini dapat diperbarui sewaktu-waktu mengikuti perubahan fitur aplikasi. Perubahan akan tercermin pada tanggal "Terakhir diperbarui" di atas.

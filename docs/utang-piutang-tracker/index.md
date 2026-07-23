# Kebijakan Privasi — Utang Piutang Tracker

**Terakhir diperbarui:** 23 Juli 2026

Utang Piutang Tracker ("Aplikasi") adalah aplikasi pencatat utang-piutang pribadi untuk Android. Kebijakan privasi ini menjelaskan data apa saja yang diproses Aplikasi dan bagaimana data tersebut ditangani.

## Ringkasan

Semua data transaksi (kontak, catatan utang/piutang, pembayaran, bukti transfer) **disimpan sepenuhnya di perangkat Anda**, terenkripsi (SQLCipher), dan **tidak pernah dikirim ke server manapun** — Aplikasi ini tidak memiliki backend/server. Tidak ada sistem akun atau login.

## Data yang diproses secara lokal (tidak dikirim ke luar perangkat)

- **Data kontak** (nama, nomor HP) — dimasukkan manual atau dipilih dari kontak perangkat Anda melalui picker sistem Android. Data ini termasuk data pihak ketiga (orang yang berutang/berpiutang dengan Anda) yang Anda catat untuk keperluan pencatatan pribadi.
- **Data transaksi** (nominal, tanggal, jenis utang/piutang, catatan, riwayat pembayaran).
- **Foto bukti transfer** — disimpan di penyimpanan internal aplikasi (bukan galeri/penyimpanan bersama), dan diproses dengan teknologi OCR *on-device* (Google ML Kit) untuk membaca nominal secara otomatis. Foto tidak diunggah ke server manapun untuk proses ini.
- **Data biometrik** (sidik jari/wajah/PIN layar kunci) — digunakan hanya untuk fitur kunci aplikasi opsional. Aplikasi **tidak pernah menyimpan atau mengakses** data biometrik Anda; verifikasi sepenuhnya ditangani oleh sistem Android, Aplikasi hanya menerima hasil berhasil/gagal.

## Data yang dikirim ke pihak ketiga

Aplikasi menggunakan beberapa layanan Google yang mengumpulkan data sesuai kebijakan privasi masing-masing:

- **Firebase Crashlytics** — laporan crash (jejak error teknis, model perangkat, versi OS/aplikasi) untuk membantu memperbaiki bug. **Nominal dan nama kontak tidak pernah disertakan** dalam laporan ini.
- **Firebase Analytics** — data penggunaan aplikasi secara agregat (layar yang dibuka, event penggunaan fitur) untuk memahami pola pemakaian aplikasi.
- **Google AdMob** — menampilkan iklan di dalam aplikasi. AdMob dapat menggunakan Advertising ID perangkat untuk personalisasi iklan sesuai kebijakan Google.

Kebijakan privasi masing-masing layanan di atas dapat dibaca di [Kebijakan Privasi Google](https://policies.google.com/privacy).

## Izin yang digunakan

- **Notifikasi** — untuk pengingat jatuh tempo lokal (tidak ada push notification dari server, sepenuhnya dijadwalkan di perangkat). Aplikasi tetap berfungsi normal jika izin ini ditolak, hanya pengingat yang tidak muncul.
- **Internet** — dibutuhkan untuk memuat iklan (AdMob) dan mengirim laporan crash/analytics (Firebase). Tidak digunakan untuk mengirim data transaksi Anda.

Aplikasi **tidak meminta** izin kamera, lokasi, penyimpanan, maupun kontak (pengambilan gambar bukti transfer dan pemilihan kontak dilakukan lewat picker sistem Android yang tidak memerlukan izin eksplisit).

## Kontrol Anda atas data

- Semua data dapat dihapus permanen dengan meng-uninstall aplikasi.
- Anda dapat mencadangkan/memindahkan data secara mandiri lewat fitur Export/Import (file terenkripsi dengan passphrase yang Anda tentukan sendiri).
- Karena tidak ada server, tidak ada cara bagi pengembang untuk mengakses data transaksi Anda kapan pun.

## Kontak

Pertanyaan seputar kebijakan privasi ini dapat dikirim ke: **karimdev96@gmail.com**

## Perubahan kebijakan

Kebijakan ini dapat diperbarui sewaktu-waktu mengikuti perubahan fitur aplikasi. Perubahan akan tercermin pada tanggal "Terakhir diperbarui" di atas.

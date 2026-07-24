# Kebijakan Privasi — PDF Expert

**Terakhir diperbarui:** 24 Juli 2026

PDF Expert ("Aplikasi") adalah aplikasi pembaca, editor, dan penanda tangan PDF untuk Android yang dirancang sebagai aplikasi **local-first**. Kebijakan privasi ini menjelaskan data apa saja yang diproses Aplikasi dan bagaimana data tersebut ditangani.

## Ringkasan

Semua proses pembacaan, pengeditan, anotasi, dan penandatanganan dokumen PDF dilakukan **sepenuhnya di perangkat Anda**. Dokumen Anda **tidak pernah diunggah ke server manapun** — Aplikasi ini tidak memiliki backend/server dan tidak ada sistem akun atau login.

## Data yang diproses secara lokal (tidak dikirim ke luar perangkat)

- **Dokumen PDF** yang Anda buka, edit, atau tanda tangani — disimpan di penyimpanan perangkat Anda sendiri (folder aplikasi atau folder yang Anda pilih), diproses sepenuhnya secara lokal.
- **Gambar yang Anda sisipkan ke PDF** — dipilih dari galeri perangkat Anda, tidak pernah diunggah.
- **Tanda tangan digital** yang Anda gambar di dalam Aplikasi — disimpan lokal sebagai bagian dari dokumen.
- **Teks hasil pemindaian AI (OCR)** — untuk fitur AI Eraser, Magic Edit, dan Smart Copy pada dokumen hasil scan, Aplikasi merender halaman PDF menjadi gambar dan menjalankan pengenalan teks menggunakan **Google ML Kit Text Recognition** — seluruhnya diproses *on-device*, gambar sementara dihapus otomatis setelah diproses dan tidak pernah diunggah ke server manapun.

## Data yang dikirim ke pihak ketiga

Aplikasi menggunakan layanan berikut yang mengumpulkan data sesuai kebijakan privasi masing-masing:

- **Firebase Crashlytics** — laporan crash dan ANR (jejak error teknis/stack trace, model perangkat, versi OS/aplikasi) dikirim ke Google untuk membantu mendiagnosis dan memperbaiki bug. **Isi/konten dokumen PDF Anda tidak pernah disertakan** dalam laporan ini.
- **Google ML Kit**: model pengenalan teks (OCR) diunduh dari server Google saat pertama kali fitur AI Scan digunakan. Setelah diunduh, seluruh proses pemindaian teks berjalan di perangkat Anda.

Kebijakan privasi layanan Google di atas dapat dibaca di [Kebijakan Privasi Google](https://policies.google.com/privacy).

## Izin yang digunakan

- **Penyimpanan (baca file)** — dibutuhkan untuk membuka dan memilih dokumen PDF dari perangkat Anda.
- **Internet** — dibutuhkan untuk mengunduh model AI ML Kit (opsional, hanya saat fitur AI Scan diaktifkan) dan mengirim laporan crash/ANR (Firebase Crashlytics). Tidak digunakan untuk mengirim dokumen atau konten PDF Anda.

Aplikasi **tidak meminta** izin kamera, lokasi, maupun kontak. Penyisipan gambar dilakukan lewat galeri, bukan kamera langsung.

## Iklan dan Penjualan Data

Aplikasi **tidak menampilkan iklan** dan **tidak menjual, menyewakan, atau membagikan** data Anda kepada pihak ketiga untuk tujuan periklanan atau komersial apapun.

## Kontrol Anda atas data

- Semua data dapat dihapus permanen dengan meng-uninstall aplikasi.
- Karena tidak ada server, tidak ada cara bagi pengembang untuk mengakses dokumen PDF Anda kapan pun.

## Privasi Anak

Aplikasi ini tidak ditujukan untuk anak-anak di bawah 13 tahun dan kami tidak dengan sengaja mengumpulkan data pribadi dari anak-anak.

## Kontak

Pertanyaan seputar kebijakan privasi ini dapat dikirim ke: **karimdev96@gmail.com**

## Perubahan kebijakan

Kebijakan ini dapat diperbarui sewaktu-waktu mengikuti perubahan fitur aplikasi. Perubahan akan tercermin pada tanggal "Terakhir diperbarui" di atas.

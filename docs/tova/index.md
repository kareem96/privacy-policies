# Privacy Policy — Tova

**Last updated:** November 27, 2026
**App:** Tova (`com.kareem.tova`)

Tova ("the App") is an offline-first English learning application for Android. This Privacy Policy explains what information the App processes and how it is handled.

## Summary

**Your learning data stays on your device.** Tova does not require an account or login, does not collect or sell personal data, and does not include advertising SDKs or behavioral analytics trackers in version 1.0.0.

## Data stored locally on your device

To provide adaptive spaced repetition (FSRS) and progress tracking, Tova stores the following data locally in the app's private SQLite database on your device:

- Learning preferences (selected source language, UI language, theme mode, daily new-word target, sound effects toggle, and local reminder schedule).
- Vocabulary review states (FSRS scheduling intervals), practice logs, streaks, and daily session progress.

All data above remains on your device and is permanently removed when you clear app storage or uninstall the App. (If you enable Android system backup on your device, Android may back up standard app settings/database according to your device's backup settings; optional downloaded pronunciation model files are stored in Android's no-backup directory.)

## Permissions we use and why

- **Microphone (`RECORD_AUDIO`):** Requested **only** when you choose to use Pronunciation Practice or voice input in Daily Speaking / Mini-Dialogues.
  - **Default mode (Android Speech Recognition):** Uses your device's built-in speech recognition service under your OS provider's privacy policy. Tova does not store or upload your voice recordings.
  - **Optional Offline Phoneme Mode:** Audio is recorded temporarily on your device, evaluated 100% locally via an on-device ONNX model, and discarded immediately after scoring. No audio leaves your device.
- **Notifications (`POST_NOTIFICATIONS`) & Boot Receiver (`RECEIVE_BOOT_COMPLETED`):** Used **only** if you enable Daily Reminder or Evening Reminder in Settings, to schedule local on-device reminders and restore schedules after a device restart or timezone change.
- **Internet (`INTERNET`):** Used **only** when you explicitly choose to download the optional Offline Pronunciation Package (~361 MB) from static file hosts (Hugging Face for the ONNX phoneme model and GitHub for the CMU Pronouncing Dictionary). No user identifiers, learning progress, or audio are transmitted during this download.

The App does **not** request access to contacts, location, camera, SMS, or external shared storage.

## Share Cards

When you tap "Share" on a session summary card, Tova renders the image locally on your device and opens Android's system share sheet so you choose where to share it. Nothing is shared automatically.

## Children's Privacy

Tova is a general-audience English learning app and does not knowingly collect personal information from children or any other users.

## Contact

Questions about this Privacy Policy can be sent to: **karimdev96@gmail.com**

## Policy Updates

This policy may be updated if future versions introduce optional features such as cloud sync, crash reporting, or advertising. Any changes will be reflected in the "Last updated" date above.

---

# Kebijakan Privasi — Tova (Bahasa Indonesia)

**Terakhir diperbarui:** 27 November 2026
**Aplikasi:** Tova (`com.kareem.tova`)

Tova ("Aplikasi") adalah aplikasi belajar bahasa Inggris offline-first untuk Android. Kebijakan privasi ini menjelaskan data apa saja yang diproses Aplikasi dan bagaimana data tersebut ditangani.

## Ringkasan

**Data belajar Anda tetap tersimpan di perangkat Anda.** Tova tidak memerlukan akun atau login, tidak mengumpulkan atau menjual data pribadi, serta tidak memuat SDK iklan maupun pelacak analitik perilaku pada versi 1.0.0.

## Data yang diproses secara lokal (tidak dikirim ke luar perangkat)

- **Pengaturan Aplikasi:** bahasa penjelas, bahasa tampilan, tema terang/gelap, target kata harian, efek suara, dan jadwal pengingat lokal.
- **Riwayat & progres belajar:** jadwal review FSRS, log latihan, streak harian, dan posisi sesi harian.

Seluruh data tersebut tersimpan di database lokal perangkat Anda dan terhapus permanen saat Anda menghapus data aplikasi atau meng-uninstall Aplikasi.

## Izin yang digunakan

- **Mikrofon (`RECORD_AUDIO`):** Hanya diminta saat Anda memakai latihan Pengucapan (Pronunciation) atau input suara di Daily Speaking / Mini-Dialog. Pada mode bawaan, pengenalan suara menggunakan layanan sistem Android sesuai kebijakan penyedia perangkat Anda. Pada mode Paket Fonem Offline opsional, audio dinilai 100% di perangkat dan langsung dihapus setelah penilaian.
- **Notifikasi (`POST_NOTIFICATIONS`) & Restart otomatis setelah reboot (`RECEIVE_BOOT_COMPLETED`):** Hanya dipakai jika Anda mengaktifkan Pengingat Harian atau Pengingat Malam di Setelan untuk menjadwalkan pengingat lokal.
- **Internet (`INTERNET`):** Hanya dipakai jika Anda secara eksplisit mengunduh Paket Pengucapan Offline opsional (~361 MB) dari host file statis (Hugging Face dan GitHub untuk CMU Pronouncing Dictionary), tanpa mengirim identitas pengguna maupun rekaman suara.

Aplikasi **tidak meminta** izin lokasi, kamera, kontak, maupun penyimpanan file eksternal.

## Kontak

Pertanyaan seputar kebijakan privasi ini dapat dikirim ke: **karimdev96@gmail.com**

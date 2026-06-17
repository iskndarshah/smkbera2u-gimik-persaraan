# 🎓 SMKBERA2U - Gimik Persaraan Guru (eHadir Simulation)

[![Web App](https://img.shields.io/badge/Application-Web--Based-blue?style=for-the-badge)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

An interactive, mobile-first web application developed specially as a **retirement gimmick** for a school teacher (**Tuan Haji Anwar bin Abdul Aziz**) at SMK Bera. 

This project simulates a real school attendance system (eHadir). When the retiring teacher clicks the **"PULANG"** (Clock Out) button for the very last time in their career, the system triggers a heartwarming retirement celebration sequence featuring a custom melody, digital confetti, and haptic feedback.

---

## ✨ Ciri-Ciri Utama (Key Features)

*   📱 **Reka Bentuk Mobile-First:** Antaramuka bersih dan responsif berasaskan komponen web moden, dioptimumkan untuk paparan telefon pintar atau skrin dewan.
*   🕒 **Sistem Jam Masa Nyata (Real-time Clock):** Menghasilkan timestamp automatik dan mengira tempoh waktu bekerja (*working duration*) secara langsung (mula dari jam 7:30 AM).
*   🗺️ **Integrasi Peta Digital:** Menyertakan komponen *embedded* Google Maps yang memaparkan lokasi rasmi sekolah.
*   🎉 **Sistem Kejutan Interaktif (The Gimmick):**
    *   **Audio Sintesis:** Memainkan melodi sayu menggunakan *Web Audio API* (menghasilkan bunyi piano/sine wave secara programmatik tanpa memerlukan fail `.mp3` luaran).
    *   **Visual Konfeti:** Efek letupan konfeti digital pelbagai warna menggunakan pustaka `canvas-confetti`.
    *   **Maklum Balas Haptik:** Kesan getaran fizikal (*vibration*) pada peranti mudah alih yang menyokong fungsi `navigator.vibrate` untuk impak gimik yang lebih realistik.

---

## 🛠️ Teknologi & Pustaka (Tech Stack)

*   **Frontend:** HTML5, CSS3 (Custom animations & page transitions), JavaScript (Vanilla JS).
*   **Typography & Icons:** Google Fonts (Roboto & Playfair Display), Font Awesome, Material Icons.
*   **Pustaka Luaran (CDN):** [Canvas Confetti](https://github.com/catdad/canvas-confetti) oleh @catdad.

---

## 🚀 Cara Menjalankan Projek (How to Run Locally)

Projek ini adalah aplikasi *standalone client-side* (tidak memerlukan pangkalan data atau pelayan backend).

1. **Klon repositori ini:**
```bash
   git clone [https://github.com/username-anda/nama-repo-anda.git](https://github.com/username-anda/nama-repo-anda.git)

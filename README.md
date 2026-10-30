# Slide Presentasi Interaktif Praktikum ASD 2026

Koleksi web slide presentasi praktikum mata kuliah **Algoritma dan Struktur Data (ASD)** edisi 2026 di Laboratorium Ilmu Komputer Universitas Pertamina.

Presentasi dibangun menggunakan teknologi *single-page HTML mandiri (zero build-step)* dengan Tailwind CSS, GSAP 3.x animation engine, tipografi proyektor, serta dukungan tema gelap & terang.

---

## 🌐 Akses Langsung (GitHub Pages)

🔗 **[Buka Portal Utama](https://irfanwk.github.io/Praktikum-ASD-Slides-2026/)**

| Modul | Topik Materi | Tautan Slide |
| :---: | :--- | :--- |
| **03** | ADT List Representasi Array Statis (Dale 2016, 9 Operasi, Biaya O(N)) | [Buka Slide Modul 3](https://irfanwk.github.io/Praktikum-ASD-Slides-2026/slide_modul3_2026_asd.html) |
| **04** | Singly Linked List (Stack vs Heap, Pointer Head, Allocation Balance) | [Buka Slide Modul 4](https://irfanwk.github.io/Praktikum-ASD-Slides-2026/slide_modul4_2026_asd.html) |
| **05** | Varian Linked List: Doubly & Circular (Invarian `p->next->prev==p`, Loop `do-while`) | [Buka Slide Modul 5](https://irfanwk.github.io/Praktikum-ASD-Slides-2026/slide_w5_varian_linked_list.html) |
| **06** | ADT Stack & Queue (LIFO, FIFO, Array Melingkar Modulo, Tail pada Queue) | [Buka Slide Modul 6](https://irfanwk.github.io/Praktikum-ASD-Slides-2026/slide_w6_stack_queue.html) |

---

## ⌨️ Pintasan Keyboard Navigasi Slide

- `←` / `Backspace` / `PageUp` : Slide sebelumnya
- `→` / `Space` / `PageDown` : Slide berikutnya
- `M` : Buka Table of Contents (Daftar Slide)
- `T` : Toggle Tema Gelap / Terang (Dark / Light)
- `F` : Toggle Layar Penuh (Fullscreen)
- `Home` / `End` : Lompat ke slide awal / akhir

---

## 💻 Standar Kompilasi C++ Laboratorium

Kode solusi acuan praktikum diuji menggunakan standar:
```bash
g++ -std=c++17 -Wall -Wextra -pedantic file.cpp -o file
```
Pengujian kebocoran memori (memory leak) dilakukan melalui teknik penghitungan **Allocation Balance** (`operator new` vs `operator delete`).

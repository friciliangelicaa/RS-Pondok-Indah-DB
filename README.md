# Medical Scheduling Database System (RS Pondok Indah Case Study)

## 📌 Project Overview
Proyek ini adalah sistem manajemen basis data relasional yang dirancang untuk mendigitalisasi jadwal praktik dokter spesialis di **RS Pondok Indah - Puri Indah**. Fokus utama proyek ini adalah mentransformasi alur kerja manual menjadi sistem digital yang terstruktur guna menghindari tumpang tindih jadwal dan meningkatkan efisiensi administrasi klinik.

## 🛠️ Tech Stack
* **Database:** MySQL
* **Tooling:** XAMPP (phpMyAdmin), ERD Designer
* **Language:** SQL (Data Definition Language)

## 🚀 Key Features & Responsibilities
Sebagai **Project Lead & Database Designer**, saya bertanggung jawab penuh atas:
1. **Analisis Kebutuhan:** Melakukan riset primer dan wawancara untuk memetakan alur operasional rumah sakit.
2. **Perancangan ERD:** Mendesain hubungan antar entitas (Dokter, Klinik, Hari, dan Jadwal) untuk memastikan struktur data yang logis.
3. **Integritas Data:** Mengimplementasikan **Foreign Key Constraints** menggunakan `ALTER TABLE` untuk menjaga relasi antar tabel tetap konsisten.
4. **Data Entry:** Mengelola dan mengintegrasikan lebih dari 160 record data dokter spesialis ke dalam sistem.

## 📊 Database Schema
Sistem ini terdiri dari 4 tabel utama yang saling terhubung:
* **`dokter`**: Informasi identitas dokter.
* **`klinik`**: Daftar spesialisasi klinik.
* **`hari`**: Mapping hari operasional.
* **`jadwal`**: Tabel utama yang menghubungkan seluruh entitas dengan atribut jam praktik.

## 📁 Repository Structure
* `db_klinik.sql`: Script SQL lengkap (Schema & Data).
* `Laporan Proyek.pdf`: Dokumentasi teknis lengkap dan analisis kebutuhan.
* `images/`: Berisi visualisasi ERD dan Designer View dari phpMyAdmin.

---
*Proyek ini dikembangkan sebagai bagian dari Tugas Akhir mata kuliah Sistem Basis Data - Universitas Bunda Mulia (2024).*

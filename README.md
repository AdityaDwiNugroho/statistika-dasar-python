# Laporan Praktikum Statistika Dasar (Python)

[![Python Version](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-v2.2-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-v3.8-11557c?logo=matplotlib&logoColor=white)](https://matplotlib.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Repositori ini dikembangkan sebagai dokumentasi tugas praktikum mata kuliah **Statistika Dasar** menggunakan pustaka data science Python. Seluruh analisis dihitung secara programmatic dan didokumentasikan ke dalam bentuk Microsoft Word dan Jupyter Notebook.

---

## Identitas Mahasiswa
* **Nama:** Aditya Dwi Nugroho
* **NIM:** `25.01.5252`
* **Kelas:** D3TI 01
* **Institusi:** Universitas Amikom Yogyakarta

---

## Struktur Proyek

Repositori ini diorganisasikan ke dalam beberapa direktori tugas praktikum. Berikut adalah daftar modul praktikum yang telah diselesaikan:

| Direktori Proyek | Topik Praktikum | Deskripsi & Hasil Analisis | Berkas Terkait |
| :--- | :--- | :--- | :--- |
| **`T4 - PYTHON MEASURE OF CENTRAL TENDENCY`** | Ukuran Pemusatan Data (Central Tendency) | Analisis Mean (68.25), Median (65.00), Modus (60.00) dari 40 siswa dengan 3 histogram visualisasi. | [Notebook](./T4%20-%20PYTHON%20MEASURE%20OF%20CENTRAL%20TENDENCY/T4%20-%20PYTHON%20MEASURE%20OF%20CENTRAL%20TENDENCY.ipynb) / [Word Laporan](./T4%20-%20PYTHON%20MEASURE%20OF%20CENTRAL%20TENDENCY/Lab%203%20Laporan%20Praktikum%20Statistik%20Dasar%20Python.docx) |
| **`T6 NILAI DISPERSI`** | Ukuran Penyebaran Data (Dispersion) | Analisis Range, Varians, Standar Deviasi (14.39), Kuartil, dan IQR dari 40 siswa. | [Notebook](./T6%20NILAI%20DISPERSI/T6%20-%20NILAI%20DISPERSI%20PYTHON.ipynb) / [Word Laporan](./T6%20NILAI%20DISPERSI/TUGAS%204%20_%20NILAI%20DISPERSI%20PYTHON.docx) |
| **`Reference`** | Berkas Pendukung & Template | Koleksi berkas referensi asli, dataset cadangan, dan template laporan praktikum kosong. | [Referensi Notebook](./Reference/Statistika_1_Modus,_Histogram,_dan_Standar_Deviasi.ipynb) / [Template T4](./Reference/Lab%203%20Laporan%20Praktikum%20Statistik%20Dasar%20Python%20(Template).docx) |

*Catatan: Setiap folder tugas dilengkapi dengan subfolder `screenshots` yang berisi bukti tangkapan layar eksekusi program asli.*

---

## Aturan Pengerjaan & Integritas Kode
Seluruh modul praktikum diselesaikan secara mandiri dengan ketentuan teknis:
* **NIM Variable Suffix:** Setiap variabel kustom yang dibuat di dalam Jupyter Notebook diakhiri dengan digit NIM `5252` (misal: `Data5252`, `mean5252`, `pd5252`).
* **Header-None CSV Import:** Penanganan dataset tanpa baris header dilakukan dengan parameter `header=None` untuk memastikan baris pertama data tidak terabaikan.

---

## Cara Menjalankan Secara Lokal

1. **Clone Repositori ini:**
   ```bash
   git clone https://github.com/AdityaDwiNugroho/statistika-dasar-python.git
   cd statistika-dasar-python
   ```

2. **Instalasi Dependensi:**
   ```bash
   pip install pandas matplotlib numpy
   ```

3. **Jalankan Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Buka file `.ipynb` pada folder tugas yang ingin dijalankan (misal: T4, T6, dll.) dan jalankan setiap cell dari atas ke bawah.

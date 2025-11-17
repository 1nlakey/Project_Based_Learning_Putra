# Project Sistem Operasi – Manajemen File Otomatis

Proyek ini dibuat untuk memenuhi tugas Project Based Learning (PBL) pada mata kuliah *Sistem Operasi*. Fokus dari proyek ini adalah penerapan perintah-perintah dasar Linux untuk mengelola file dan direktori secara otomatis menggunakan shell script.  

Proyek mensimulasikan tugas seorang administrator sistem yang harus mengorganisir file dalam jumlah besar, melakukan pencarian, monitoring, serta membuat laporan sistem secara otomatis.


====================================================
📁 STRUKTUR DIREKTORI PROYEK
====================================================

project_sistem_operasi_putra/
 ├── src/
 │   └── main.sh
 ├── documents/
 ├── images/
 ├── archives/
 ├── logs/
 ├── data/
 └── README.md


====================================================
🎯 TUJUAN PROYEK
====================================================

1. Membuat struktur direktori proyek secara otomatis menggunakan shell script.  
2. Mengelompokkan file berdasarkan tipe/extensi (txt, jpg, zip).  
3. Melakukan pencarian file berdasarkan nama dan isi.  
4. Menghasilkan laporan sistem menggunakan kombinasi perintah Linux.  
5. Menerapkan perintah dasar Linux seperti:
   - ls, find, grep, wc, du, sort, uniq, head
   - piping (|)
   - redirection (>)


====================================================
⚙️ FITUR UTAMA SCRIPT
====================================================

✔ *1. Setup Direktori Otomatis*  
Script membuat folder:
- documents/
- images/
- archives/
- logs/
- data/

✔ *2. Generate File Sample Otomatis*  
Script membuat:
- 10 file teks (.txt)
- 5 file gambar (.jpg)
- 5 file arsip (.zip)

✔ *3. Organisasi File Berdasarkan Ekstensi*  
Menggunakan perintah:
- find
- mv

✔ *4. Pencarian File Berdasarkan Nama*  
Menggunakan:
- find

✔ *5. Pencarian Isi File*  
Menggunakan:
- grep -Rni

✔ *6. Generate Laporan Sistem Otomatis*  
Isi laporan:
- Jumlah file dalam tiap folder
- Jumlah file TXT (piping)
- Statistik ekstensi file (sort + uniq)
- Ukuran total folder proyek (du -sh)
- Statistik README.md (wc)
- 5 file terbaru (ls -lt | head)

Laporan disimpan ke:
====================================================
▶️ CARA MENJALANKAN SCRIPT
====================================================

1. Masuk folder proyek:
   cd ~/project_sistem_operasi_putra

2. Beri izin eksekusi:
   chmod +x src/main.sh

3. Jalankan script:
   ./src/main.sh


====================================================
🔧 DAFTAR PERINTAH LINUX YANG DIGUNAKAN
====================================================

| Perintah | Fungsi |
|---------|--------|
| mkdir   | Membuat direktori |
| touch   | Membuat file |
| find    | Mencari file |
| grep    | Mencari teks dalam file |
| mv      | Memindahkan file |
| ls      | Menampilkan file |
| wc      | Menghitung baris/kata/karakter |
| du      | Menampilkan ukuran folder |
| sort    | Mengurutkan data |
| uniq    | Menghapus duplikasi |
| head    | Menampilkan 5 baris pertama |
| piping (|) | Menghubungkan output-input antar perintah |
| >       | Menulis output ke file |


====================================================
👨‍💻 IDENTITAS PEMBUAT
====================================================

*Nama:* Putra Tri Rizkidana Meidiansyah
*NIM:* 05301425069  
*Prodi:* Sistem Informasi
*Mata Kuliah:* Sistem Operasi  
*Universitas Negeri Gorontalo*  


====================================================
📌 CATATAN TAMBAHAN
====================================================

- Script ini dapat dikembangkan menjadi sistem backup otomatis.  
- Sistem directory otomatis sangat fleksibel dan bisa ditambah jenis file baru.  
- Semua fungsi berjalan sepenuhnya melalui terminal Linux (CLI).  


====================================================
🚀 KESIMPULAN
====================================================

Proyek ini menunjukkan bagaimana perintah dasar Linux dapat digabungkan untuk membuat sistem manajemen file otomatis yang efisien dan terstruktur, mirip dengan pekerjaan seorang administrator sistem di lingkungan kerja nyata.

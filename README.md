# Multiple-prosesor-dan-Multiprosesor-symmetric
![Multiprosesor dan Multiple prosesor drawio (1)](https://github.com/user-attachments/assets/fc449028-2d76-4267-ae91-cfe08c45307a)


## 1. Multiple Prosesor (Umum) KANAN
-  Penjelasan:

- Masing-masing prosesor punya cache memory sendiri (buat simpan data lokal supaya cepat).

- Memori lokal bisa berbeda-beda (bukan shared).

- Komunikasi antar prosesor melalui interconnect (bisa berupa switch, jaringan cepat, atau bus).

- Cocok untuk sistem yang membutuhkan skala besar dan fleksibilitas tinggi, seperti cluster komputer.
  
➡ Ciri utamanya:

- Struktur fleksibel.

- Prosesor bisa berbeda-beda jenis dan tugasnya.

- Bisa lebih susah sinkronisasi data antar prosesor.

## Contoh nyata:

- Cluster komputer (banyak komputer biasa dihubungkan dalam satu sistem untuk kerja berat).

- Superkomputer lawas seperti IBM BlueGene.

## 2. Multi Prosesor Simetris (SMP - Symmetric Multiprocessing) KIRI
- Penjelasan:

- Setiap prosesor punya cache pribadi untuk mempercepat akses data sebelum harus mengambil dari memori utama.

- Memori dan I/O bersifat shared, semua prosesor bisa mengakses semua data yang ada.

- Semua prosesor bisa menjalankan tugas secara paralel tanpa ketergantungan struktur hirarki.

- Cocok untuk server, workstation berperforma tinggi, atau superkomputer kecil.
- 
➡ Ciri utamanya:

- Semua prosesor identik (jenis sama, kekuatan sama).

- Kinerja naik kalau jumlah prosesor naik (scalable).

- Komunikasi antar prosesor cepat lewat shared memory.

- Tapi, bisa terjadi masalah contention (rebutan akses memori).

##  Contoh nyata:

- Server modern (misal server database besar).

- Laptop/PC multi-core juga bisa dianggap mini SMP (Core i7, Ryzen, dsb.).

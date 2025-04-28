# Multiple-prosesor-dan-Multiprosesor-symmetric

## 1. Multiple Prosesor (Umum)
- Diagram tadi memperlihatkan:

- Prosesor 1 dan Prosesor 2 bekerja secara relatif mandiri.

- Mereka tidak harus berbagi memori dan I/O.

- Memori bisa terpisah untuk masing-masing prosesor, atau kadang sebagian kecilnya dibagi bersama.

- Biasanya digunakan untuk sistem heterogen:

- Misal, satu prosesor khusus untuk kalkulasi matematis, satu lagi untuk menangani komunikasi jaringan.

- Komunikasi antar prosesor terjadi lewat jalur jaringan (interconnect), misalnya bus atau switch.

➡ Ciri utamanya:

- Struktur fleksibel.

- Prosesor bisa berbeda-beda jenis dan tugasnya.

- Bisa lebih susah sinkronisasi data antar prosesor.

- Contoh nyata:

- Cluster komputer (banyak komputer biasa dihubungkan dalam satu sistem untuk kerja berat).

- Superkomputer lawas seperti IBM BlueGene.

## 2. Multi Prosesor Simetris (SMP - Symmetric Multiprocessing)
- Diagram tadi memperlihatkan:

- Prosesor 1, Prosesor 2, dan Prosesor 3 terhubung ke memori bersama (Shared Memory).

- Mereka setara: tidak ada master atau slave.

- Semua prosesor bisa mengakses semua data yang ada di memori.

- Ada juga Shared I/O Bus: perangkat input/output bisa diakses oleh semua prosesor.

➡ Ciri utamanya:

- Semua prosesor identik (jenis sama, kekuatan sama).

- Kinerja naik kalau jumlah prosesor naik (scalable).

- Komunikasi antar prosesor cepat lewat shared memory.

- Tapi, bisa terjadi masalah contention (rebutan akses memori).

- Contoh nyata:

- Server modern (misal server database besar).

- Laptop/PC multi-core juga bisa dianggap mini SMP (Core i7, Ryzen, dsb.).

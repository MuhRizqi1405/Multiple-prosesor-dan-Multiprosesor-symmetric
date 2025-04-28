# Multiple-prosesor-dan-Multiprosesor-symmetric
## 1. Multi Prosesor Simetris (SMP - Symmetric Multi-Processing)
- Definisi: SMP adalah sistem komputer di mana beberapa prosesor memiliki akses yang setara (simetris) ke memori utama dan perangkat input/output. Semua prosesor dalam SMP dapat melakukan eksekusi tugas secara paralel.

- Karakteristik:

- Semua prosesor terhubung ke memori bersama yang dapat diakses oleh setiap prosesor.

- Setiap prosesor memiliki tingkat kontrol yang sama atas eksekusi dan pengelolaan sumber daya.

- ontoh implementasi: komputer dengan dua atau lebih prosesor yang bekerja secara paralel, dengan setiap prosesor memiliki akses langsung ke memori bersama.

- Keuntungan: Efisiensi yang lebih baik dalam pemrosesan paralel dan meningkatkan kinerja sistem secara keseluruhan.

- Kekurangan: Terkadang kesulitan dalam manajemen memori dan pengelolaan tugas.

## 2. Multiple Prosesor
- Definisi: Multiple prosesor lebih umum dan mencakup semua sistem yang menggunakan lebih dari satu prosesor. Ini tidak selalu mengacu pada SMP, tetapi dapat melibatkan arsitektur yang berbeda.

- Karakteristik:

- Bisa berupa sistem dengan beberapa prosesor yang tidak memiliki akses yang setara (misalnya, prosesor master dan prosesor slave).

- Prosesor dalam sistem ini mungkin memiliki peran tertentu (misalnya, satu prosesor yang mengatur tugas dan yang lainnya melaksanakan tugas tersebut).

- Tidak semua prosesor dalam sistem ini memiliki akses langsung ke memori bersama.

- Sistem ini dapat melibatkan arsitektur yang lebih kompleks, seperti NUMA (Non-Uniform Memory Access) atau MIMD (Multiple Instruction, Multiple Data).

- Keuntungan: Dapat mengoptimalkan tugas tertentu dengan membagi tugas antara prosesor yang berbeda, meningkatkan kinerja pada beban tertentu.

- Kekurangan: Pengelolaan lebih kompleks, terutama dalam distribusi beban dan akses memori.

# Perbedaan Utama:
- Akses Memori: SMP menawarkan akses memori yang setara untuk semua prosesor, sedangkan sistem multiple prosesor bisa memiliki cara yang lebih beragam dalam mengelola memori dan akses prosesor.

- Manajemen Sistem: SMP lebih sederhana dalam hal manajemen dan koordinasi prosesor karena sifat simetriknya, sementara multiple prosesor bisa lebih rumit dalam hal pengelolaan dan distribusi tugas.

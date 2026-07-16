# PiHutang — Deploy ke Vercel

Proyek ini adalah situs statis. Unggah folder ini ke repositori GitHub lalu impor repositori tersebut di Vercel, atau deploy folder ini melalui Vercel CLI.

Tidak ada variabel environment maupun konfigurasi Firebase yang diperlukan.

Data transaksi disimpan secara lokal di browser pengguna (`localStorage`). Data tidak tersinkron antar perangkat atau antar browser. Untuk penyimpanan bersama/akun pengguna, diperlukan backend terpisah (misalnya Firebase yang dikonfigurasi dengan kredensial proyek Anda sendiri).

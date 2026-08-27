# Website Profil XI RPL

Website ini merupakan proyek pembelajaran
kolaborasi Git dan GitHub.

## Anggota Tim

1. Rizal - Project Manager
2. Neng Dina - Developer Profil
3. Devit - Developer Anggota
4. Sabrina - Developer Kontak

---

**PERTANYAAN ANALISIS (CHALLENGE 2 – 12)**

* **Challenge 2: Apa arti hasil `git status`?**

> `git status` berfungsi untuk melihat kondisi direktori kerja lokal saat ini, seperti mengecek branch mana yang sedang aktif, mengetahui file baru yang belum dilacak (*untracked*), serta melihat perubahan file yang belum di-staging atau di-commit.
> 
> 


* **Challenge 3: Mengapa setiap developer tidak langsung bekerja pada `main`?**

> Agar branch `main` tetap bersih dan stabil sebagai versi produk utama. Bekerja di branch masing-masing memungkinkan developer bereksperimen atau mengembangkan fitur secara terpisah tanpa risiko merusak kode utama atau mengganggu pengerjaan anggota lain.
> 
> 


* **Challenge 5: Perbedaan pesan commit `update` vs `Menambahkan halaman profil kelas`, dan mana yang lebih baik?**

> Pesan `"update"` terlalu singkat dan abstrak, sehingga anggota tim lain tidak tahu perubahan apa yang dilakukan. Pesan `"Menambahkan halaman profil kelas"` **jauh lebih baik** karena spesifik dan jelas menggambarkan fitur apa yang dibuat atau diubah dalam commit tersebut.
> 
> 


* **Challenge 11: Pertanyaan Analisis Sinkronisasi**

1. **Apa fungsi `git pull`?**

> Untuk mengunduh (*download*) sekaligus menggabungkan (*merge*) perubahan kode terbaru dari repository GitHub (*remote*) ke direktori kerja lokal di komputer.
> 
> 


2. **Apa yang terjadi jika programmer tidak melakukan `git pull`?**

> Kode di komputer lokal akan tertinggal (*outdated*) dibanding repository remote. Hal ini meningkatkan risiko terjadinya bentrokan kode (*merge conflict*) yang rumit saat programmer mencoba me-push perubahannya nanti.


3. **Mengapa `main` harus dijaga agar tetap stabil?**

> Karena `main` adalah cerminan dari produk akhir aplikasi yang siap dirilis atau diuji secara penuh. Jika `main` rusak atau error, seluruh tim akan terhambat dan aplikasi tidak dapat berjalan dengan baik.
> 
> 





---

**PERTANYAAN CONFLICT (SECTION X)**

1. **Mengapa conflict terjadi?**

> Conflict terjadi karena dua atau lebih developer mengubah baris kode yang sama pada file yang sama di waktu bersamaan, sehingga Git bingung menentukan baris mana yang harus dipakai.
> 
> 


2. **Apakah conflict berarti Git rusak?**

> Tidak, conflict bukan tanda Git rusak, melainkan hal wajar dan normal dalam proses pengembangan perangkat lunak secara kolaboratif.
> 
> 


3. **Siapa yang harus menentukan versi kode yang benar?**

> Developer yang bersangkutan bersama dengan Project Manager melalui diskusi dan koordinasi kelompok.
> 
> 


4. **Mengapa komunikasi antar programmer penting?**

> Agar setiap anggota tahu bagian file mana yang sedang dikerjakan oleh anggota lain, menghindari pembenturan kode yang tidak perlu, serta mempermudah penyelesaian masalah jika terjadi bug atau conflict.
> 
> 



---

**TROUBLESHOOTING LOG (SECTION Z)**



---

**REFLEKSI INDIVIDU (SECTION AC)**

1. **Perbedaan bekerja sendiri vs menggunakan Git & GitHub:**
> Bekerja sendiri membuat kita mudah kehilangan riwayat perubahan kode saat terjadi kesalahan. Menggunakan Git dan GitHub memudahkan pengerjaan secara paralel bersama tim, mencatat riwayat versi dengan rapi, dan mencegah fitur orang lain terhapus secara tidak sengaja.


2. **Manfaat branch:**
> Sebagai wadah terisolasi untuk membuat fitur baru atau memperbaiki bug tanpa perlu takut merusak baris kode utama yang sudah stabil.
> 
> 


3. **Mengapa Pull Request diperlukan?**

> Untuk mengajukan pembaruan kode agar diperiksa terlebih dahulu oleh Project Manager sebelum digabungkan ke branch utama.
> 
> 


4. **Apa manfaat Code Review?**

> Memastikan kode yang dibuat sudah memenuhi standar, bersih dari kesalahan (*bug*), rapi penulisan kodenya, dan sesuai kebutuhan proyek sebelum di-merge.
> 
> 


5. **Error apa yang paling sulit kalian selesaikan?**
> *Merge conflict* pada file `README.md` saat menyatukan perubahan dari dua branch yang berbeda.


6. **Bagaimana kalian menemukan solusinya?**
> Mengikuti panduan troubleshooting di LKPD, melakukan diskusi bersama antara PM dan developer terkait, serta membaca petunjuk indikator penanda dari Git.


7. **Apa kontribusi terbesar kalian dalam kelompok?**
> *(Sesuai peranmu sebagai PM)*: Membuat repository utama, membagi tugas tim, memberikan arahan struktur kerangka HTML & CSS konsisten, serta meninjau dan melakukan merge pada Pull Request tim.
> 
> 


8. **Kebiasaan apa yang akan dipertahankan jika jadi programmer profesional?**
> Selalu mengolah fitur di branch terpisah, menulis pesan commit yang spesifik dan jelas, serta rajin melakukan sinkronisasi (`git pull`) sebelum memulai pekerjaan.
> 
> 



---

**REFLEKSI AKHIR (SECTION AE)**

* **Sebelum belajar GitHub, saya berpikir bahwa...** membuat proyek pemrograman bersama tim dilakukan dengan cara saling mengirimkan folder/file kode secara manual melalui media perpesanan.
* **Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...** pengembangan aplikasi bersama tim bisa dilakukan secara terstruktur, rapi, dan aman menggunakan alur kerja branch, Pull Request, dan Code Review.


* **Kesalahan/error yang saya alami mengajarkan saya bahwa...** error bukanlah tanda kegagalan, melainkan informasi untuk dibaca, dianalisis, dan didiskusikan solusinya bersama tim.


* **Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...** selalu berkomunikasi aktif, mematuhi alur kerja Git yang ditetapkan, dan menjaga agar branch utama tetap bersih dan stabil.
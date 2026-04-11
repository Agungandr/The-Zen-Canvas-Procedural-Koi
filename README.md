Deskripsi Proyek
Tipe Proyek: Experimental Web-Based Procedural Animation.

Deskripsi Singkat:
Sebuah eksperimen interaktif berbasis HTML5 Canvas yang mensimulasikan ekosistem kolam ikan koi secara organik. Proyek ini mengeksplorasi penggunaan algoritma FABRIK (Forward And Backward Reaching Inverse Kinematics) untuk menghasilkan pergerakan makhluk hidup yang fleksibel dan adaptif terhadap input pengguna secara real-time.

Fitur Utama:

Dynamic Bone-Chain: Sistem tulang belakang ikan yang terdiri dari 40+ segmen untuk liku tubuh yang sangat halus.

Image-to-Animation Mapping: Kemampuan pengguna untuk mengunggah aset visual statis (.png) yang kemudian diproses secara prosedural menjadi entitas yang bergerak secara volumetrik.

Multi-Layer Depth: Simulasi kedalaman air menggunakan teknik layering antara siluet latar belakang, vegetasi air prosedural, dan efek caustics cahaya matahari.

Fluid Motion Physics: Implementasi efek inersia dan hambatan air (drag) pada kepala ikan untuk menciptakan kesan bobot dan massa saat berenang.

Mengapa ini disebut "Experimental"?
Proyek ini masuk kategori Experimental karena beberapa alasan teknis yang unik:

Manipulasi Raster di Canvas: Mengambil gambar diam dan "memaksanya" mengikuti jalur matematika tanpa menggunakan library pihak ketiga (seperti GreenSock atau Three.js).

No-Library Dependence: Semua logika fisika, matematika sudut (trigonometri), dan rendering dikerjakan secara vanilla JavaScript.

Procedural Content Generation: Siluet ikan dan tanaman air tidak menggunakan gambar aset, melainkan "dilukis" oleh kode saat itu juga, sehingga setiap kali dijalankan, bentuk vegetasi akan selalu berbeda.

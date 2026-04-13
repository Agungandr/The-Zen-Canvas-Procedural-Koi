🐟 Zen Canvas: Procedural Koi Pond (v2.3.0)
Zen Canvas adalah simulasi kolam koi interaktif berbasis HTML5 Canvas yang menggabungkan algoritma pergerakan prosedural dengan estetika visual yang menenangkan. Proyek ini dirancang untuk memberikan pengalaman meditatif (ambient simulation) langsung di dalam peramban web.

🌟 Fitur Unggulan (v2.3.0)
Procedural Animation: Pergerakan ikan koi dihasilkan secara dinamis menggunakan sistem FABRIK (Forward And Backward Reaching Inverse Kinematics) sederhana untuk pergerakan tubuh yang luwes dan alami.

Interactive Feeding System: Klik atau sentuh layar untuk menjatuhkan pelet makanan. Ikan memiliki logika pencarian jalur (pathfinding) untuk mengejar dan memakan pelet tersebut.

Dynamic Audio Engine: Musik latar Zen dan efek suara air yang volumenya beradaptasi dengan kecepatan renang ikan (berbasis Physics-to-Audio mapping).

New Gear Settings Menu: Panel kontrol UI yang memungkinkan kustomisasi langsung:

Pengaturan jumlah kawanan ikan (flocking) dan siluet kedalaman.

Fitur Custom Skin (Unggah gambar sendiri untuk dijadikan pola sisik ikan).

Kontrol audio terintegrasi.

Optimized Performance: Menggunakan teknik Offscreen Canvas Caching untuk latar belakang dan tanaman, memastikan simulasi berjalan lancar bahkan pada perangkat dengan spesifikasi rendah.

Smart Behavior: Ikan akan mengikuti kursor saat aktif, namun akan beralih ke mode Wandering (berenang bebas) secara otomatis saat kursor meninggalkan area layar.

🛠️ Detail Teknis
Engine: Vanilla JavaScript (No Frameworks).

Rendering: HTML5 Canvas API (2D Context).

Optimization: * Layered Rendering untuk menciptakan efek kedalaman (Parallax).

Frame-skipping pada kalkulasi caustics dan shimmer untuk efisiensi CPU.

Compatibility: Responsif di desktop dan perangkat seluler (Touch Support).

🚀 Cara Penggunaan
Cukup buka file index.html di browser pilihan Anda.

Gerakkan Kursor: Menarik perhatian ikan utama.

Klik/Tap: Memberi makan ikan.

Ikon Gear (Pojok Kanan Atas): Membuka pengaturan simulasi.

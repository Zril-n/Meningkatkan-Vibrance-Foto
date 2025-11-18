Color Retouching & Tone Mapping (Python + OpenCV)
Proyek ini melakukan color retouching pada sebuah foto menggunakan beberapa teknik pengolahan citra yang umum dipakai pada proses editing profesional. Fokusnya adalah menghasilkan tone mapping yang halus, mempertahankan tampilan alami foto (preserve real photo look), namun tetap meningkatkan warna dan detail.
Pipeline retouching menggunakan tiga langkah utama:
* White Balance (Gray-World Algorithm)
  Menormalkan warna secara global agar foto tidak terlalu kuning/biru.
* Gamma Correction
  Mengangkat midtones agar foto terlihat lebih cerah tanpa merusak kontras.
* CLAHE (Contrast Limited Adaptive Histogram Equalization)
  Meningkatkan local contrast pada bagian gelap & terang secara adaptif.

Output akhirnya adalah:
Foto hasil retouch
Gambar perbandingan “Before vs After”

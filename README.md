
# Banking Dataset - Marketing Targets

### Deskripsi Proyek
Proyek ini adalah analisis data dari dataset dengan 45211 baris dan 17 kolom. Dataset ini terdiri dari data numerik dan kategorik yang berkaitan dengan kampanye pemasaran untuk deposito di sebuah bank. Tujuan utama dari analisis ini adalah untuk mendapatkan wawasan tentang perilaku nasabah dan membuat rekomendasi bisnis berdasarkan temuan.

## Isi
1. Dataset Overview: Penjelasan tentang jumlah baris dan kolom dalam dataset, serta jenis data yang ada.
2. Tipe Data dan Nama Kolom: Penjelasan tentang konsistensi tipe data dan rencana perubahan pada nama kolom.
3. Kolom dengan Nilai Kosong: Penjelasan mengenai adanya nilai kosong dalam dataset.
4. Nilai Aneh dalam Summary: Identifikasi nilai ekstrim atau aneh dalam kolom-kolom tertentu.
5. Korelasi dengan Label: Analisis korelasi antara fitur-fitur numerik dengan label.
6. Distribusi dan Kategorisasi: Pemahaman tentang hubungan antara fitur-fitur dengan hasil kampanye.
7. Rekomendasi Bisnis: Proposal strategi bisnis berdasarkan analisis data.
8. Perlakuan untuk Fitur-Fitur: Rekomendasi perlakuan khusus untuk beberapa fitur dengan nilai aneh.
9. Segmentasi Target: Penjelasan mengenai segmentasi target nasabah berdasarkan analisis.
10. Integrasi Produk dan Rekomendasi Bisnis: Penggabungan produk deposito dengan produk lain dan manfaatnya.
11. Pentingnya Pengaruh Kampanye Sebelumnya: Dampak hasil kampanye sebelumnya terhadap kampanye saat ini.
12. Target Segment yang Dianjurkan: Rekomendasi untuk segmentasi nasabah yang berpotensi.
13. Deposito Terintegrasi: Konsep integrasi produk deposito untuk tujuan keuangan yang lebih luas.

## Conclusion
- Business Insight
  <ol>
    <li> Based on “marital status“ <br>
    Secara distribusi, nasabah dari bank DataWhiz didominasi oleh nasabah yang berstatus “Married”, namun persentase pembuka deposito terbanyak   adalah yang berstatus “Single”. </li>
    <li> Based on “job" <br>
      Nasabah “student” memiliki persentase yang paling tinggi dalam membuka deposito dan diikuti dengan nasabah dari kategori “retired”. Sedangkan, nasabah “blue-collar” memiliki persentase yang rendah untuk membuka deposito. </li>
    <li> Based on “housing” dan “loan” <br>
    Nasabah yang memiliki tanggungan berupa rumah “housing” atau pinjaman “loan” cenderung tidak membuka akun deposito. <br>
    Pada “housing”, ada kemungkinan deposito dibuat untuk membeli rumah sebagai salah satu capaian dalam menabung. <br>
    Pada “loan”, pinjaman dapat menjadi halangan untuk nasabah bisa membuka akun deposito sehingga nilainya jauh secara signifikan. </li>
    <li> Based on “poutcome" <br>
    Dari tabel di samping terlihat bahwa nasabah yang ‘poutcome’ nya ‘failure’, sebanyak 87.39% memilih untuk tidak berlangganan deposito berjangka, sedangkan 12.61% sisanya memilih untuk berlangganan. <br>
      Di samping itu, nasabah yang ‘poutcome’ nya ‘success’, sebanyak 64.73%  memilih untuk berlangganan deposito berjangka, sedangkan 35.27% sisanya memilih untuk tidak berlangganan. Artinya, kesuksesan atau kegagalan pada campaign sebelumnya cukup berpengaruh pada campaign ini. </li>
  </ol>

- Business Recommendation
  1. Deposito Rumah Tangga.
      - Deposito khusus bagi orang yang sudah menikah.
      - Keputusan dalam rumah tangga biasanya disepakati oleh suami dan istri.
      - Buat program dengan goals untuk keperluan rumah tangga: Renovasi Rumah, Membeli Mobil Baru, Biaya Sekolah Anak.
      - Opsional: dapat diintegrasikan dengan produk lain seperti KPR Rumah, Kredit Kendaraan. Hasil dari tabungan deposito dapat             langsung dialihkan ke produk lain

  2. Deposito Mahasiswa
      - Deposito Khusus untuk mahasiswa
      - Buat program untuk goals dari mahasiswa: Untuk membayar uang kuliah, untuk keperluan tugas mahasiswa, untuk biaya pulang     kampung bagi yang di luar kota.
      - bank dapat merekomendasikan jumlah dana yang dimasukan dalam deposito dan menghitung waktu yang dibutuhkan agar goals tercapai

  3. Deposito Untuk Masa Tua
      - Deposito yang dikhususkan bagi nasabah yang sudah pensiun
      - Keperluan untuk menabung dengan bunga yang lebih besar dan low risk, membuat deposito menjadi produk yang cocok.
      - Deposito dapat dihubungkan dengan ahli waris apabila sudah tidak ada. Hal ini untuk mengakomodasi warisan bagi para nasabah senior. Sehingga proses ahli waris dapat berjalan lebih mudah.

  4. Deposito Untuk Membangun Rumah
      - Nasabah yang membuka deposito cenderung yang belum memiliki rumah.
      - Program ini dapat menghubungkan keperluan membeli rumah dengan bunga dan periode yang dibutuhkan agar dapat membeli rumah.         - Dapat juga dihubungkan dengan program KPR rumah, misalkan dengan bunganya dibayarkan sebagai biaya KPR.


  5. Deposito terintegrasi
      - Deposito dapat diintegrasikan dengan program-program lain di perbankan seperti KPR, biaya kredit kendaraan, kredit usaha, dll.
      - Deposito dapat diintegrasikan dengan program sekolah, khusus untuk mahasiswa.
      -Sebagian bunga dari deposito dapat dialihkan ke program lain, sehingga dapat mengalokasikan tujuan dari menabung secara langsung.
      - Keuntungan bagi bank, adalah banyak produk perbankan yang digunakan.
      - Mengakomodasi:
          - Nasabah married: untuk keperluan rumah tangga
          - Nasabah yang belum memiliki rumah: untuk menyicil DP KPR dengan bunga deposito.
          - Nasabah student: untuk keperluan kendaraan, membayar uang kuliah agar bisa langsung dibayar secara otomatis.

## Kontribusi
Kontribusi selalu diterima dengan tangan terbuka. Jika Anda ingin berkontribusi dalam bentuk laporan bug, saran perbaikan, atau peningkatan lainnya, silakan buat "pull request" atau "issue" baru.

## Lisensi
Proyek ini menggunakan lisensi MIT License, yang berarti Anda dapat menggunakannya sesuai dengan ketentuan lisensi tersebut.


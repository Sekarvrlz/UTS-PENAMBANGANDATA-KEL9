## Anggota Kelompok

* Dhias Erpangga Yoga (122140109)
* Sekar Avriliza Putri (122140108)
* Nur Afni Daem Miarti (122140011)

## Deskripsi

Repositori ini berisi laporan dan implementasi proyek Ujian Tengah Semester mata kuliah Penambangan Data (IF25-40115). Proyek bertujuan untuk melakukan pembersihan, imputasi, dan klasifikasi data stok serta transaksi apotek XYZ menggunakan model klasifikasi sederhana.

## Dataset

Terdiri dari dua sumber data:

1. **Data Stok Produk** – berisi kode, nama produk, lokasi, QTY stok, dan unit.
2. **Data Transaksi Pembelian** – berisi kode, nama produk, unit, tanggal, QTY masuk/keluar, dan nilai transaksi.

Total data mencakup lebih dari 138.000 baris transaksi pada tahun 2021.

## Tahapan Analisis

1. **Pra-pemrosesan**: parsing data, membersihkan format angka, membuat kolom harga satuan.
2. **Imputasi Missing Values**:

   * Nilai numerik kosong diisi dengan 0.
   * Nilai kategorikal kosong diisi dengan “Tidak Diketahui”.
3. **Pembuatan Model**:
   * Target: Klasifikasi permintaan tinggi atau rendah.

## Hasil dan Kesimpulan

* Produk dengan permintaan tinggi memiliki stok awal yang lebih besar dan bervariasi.
* Model cukup stabil tanpa bias besar antar kelas.
* Fitur terbatas menjadi penyebab akurasi belum optimal.
* Imputasi nilai 0 pada harga satuan tidak memengaruhi hasil analisis.

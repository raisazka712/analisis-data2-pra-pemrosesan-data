# analisis-data2-pra-pemrosesan-data

Deskripsi proyek
Tugasnya adalah menyiapkan laporan untuk divisi kredit suatu bank. Kamu akan mencari tahu pengaruh status perkawinan seorang nasabah dan jumlah anak yang dimilikinya terhadap probabilitas gagal bayar dalam melunasi pinjaman. Pihak bank sudah memiliki beberapa data mengenai kelayakan kredit nasabah.

Laporanmu akan menjadi bahan pertimbangan pada saat membuat penilaian kredit untuk calon nasabah. Penilaian kredit digunakan untuk mengevaluasi kemampuan calon peminjam untuk melunasi pinjaman mereka.

Instruksi untuk menyelesaikan proyek
Langkah 1. Buka file data /datasets/credit_scoring_eng.csv dan baca informasi umumnya.

Langkah 2. Pra-pemrosesan data:

Mengidentifikasi dan mengisi nilai-nilai yang hilang

Mengganti tipe data bilangan riil dengan tipe integer

Menghapus data duplikat

Mengategorikan data

Pastikan untuk menjelaskan:

Nilai hilang manakah yang kamu identifikasi;
Kemungkinan penyebab nilai yang hilang tersebut;
Jenis metode yang kamu gunakan untuk mengisi nilai yang hilang;
Jenis metode yang kamu gunakan untuk menemukan dan menghapus data duplikat beserta alasan penggunaannya;
Kemungkinan penyebab munculnya data duplikat;
Jenis metode yang kamu gunakan untuk mengubah tipe data beserta alasannya;
Jenis dictionary yang kamu pilih untuk dataset ini beserta alasannya;
Datanya mungkin saja berisi data lama yang tidak lagi relevan atau nilai-nilai yang tidak sesuai dengan kenyataan, misalnya, jumlah hari kerja yang negatif. Hal semacam ini dapat terjadi ketika kamu mengelola data di dunia nyata. Kamu harus menjelaskan kemungkinan penyebab munculnya data seperti itu dan memprosesnya.

Langkah 3. Jawab beberapa pertanyaan berikut ini:

Apakah terdapat hubungan antara memiliki anak dan probabilitas seseorang melakukan gagal bayar pinjaman?
Apakah terdapat hubungan antara status perkawinan dan probabilitas seseorang melakukan gagal bayar pinjaman?
Apakah terdapat hubungan antara tingkat pendapatan dan probabilitas seseorang melakukan gagal bayar pinjaman?
Bagaimana perbedaan tujuan pinjaman memengaruhi probabilitas seseorang melakukan gagal bayar pinjaman?
Berikan jawabanmu. Jelaskan maksud dari hasil yang kamu peroleh.

Langkah 4. Tulis kesimpulannya secara keseluruhan.

Format: 

Selesaikan proyekmu pada Jupyter Notebook (akan terbuka saat kamu mengeklik Berikutnya). Ketik kode dalam sel kode dan berikan catatan yang disertai dengan penjelasan dan penjabaran dalam sel markdown. Gunakan pemformatan dan judul (heading).

Deskripsi data
children : jumlah anak dalam keluarga
days_employed: berapa lama nasabah telah bekerja
dob_years: usia nasabah
education: tingkat pendidikan nasabah
education_id: pengidentifikasi untuk tingkat pendidikan nasabah
family_status: status perkawinan nasabah
family_status_id: pengidentifikasi untuk status perkawinan nasabah
gender: jenis kelamin nasabah
income_type: jenis pendapatan nasabah
debt: apakah nasabah pernah melakukan gagal bayar pinjaman
total_income: pendapatan bulanan
purpose: alasan mengambil pinjaman
Bagaimana proses penilaian proyek dilakukan?
Peninjau kodemu akan menggunakan kriteria penilaian untuk mengevaluasi proyekmu. Sebelum memulainya, baca kriteria berikut dengan saksama. Hal ini dapat membantumu melakukan pekerjaan dengan baik.

Berikut adalah hal-hal yang dijadikan pertimbangan mentor dalam menilai proyekmu:

Bagaimana caramu mendeskripsikan masalah yang teridentifikasi dalam data?
Metode apa saja yang kamu gunakan untuk mengganti tipe data dan memproses nilai yang hilang dan data duplikat?
Apakah kamu mengategorikan datanya?
Mengapa kamu melakukannya dengan cara tersebut?
Apakah kamu mengekspor data akhir ke dalam pivot table?
Apakah kamu menggunakan try–except dalam kode untuk menangani error yang tidak terduga?
Apakah kamu mengikuti struktur proyek dengan benar dan mengetik kode dengan rapi?
Apakah kesimpulan yang kamu ambil sudah tepat dan berguna?
Apakah kamu menuliskan komentar pada setiap langkah yang kamu ambil?
Dengan mengeklik "Ayo mulai!", kamu akan diarahkan menuju JupyterHub TripleTen. Kamu bisa menyelesaikan proyekmu di sana.


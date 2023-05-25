<h1>Soal</h1>
<img src="soal.PNG" />
<br>
<h1>Jawaban</h1>
<b>2 Berikut Perbedaanya</b>
<ul>
  <li>Stateful Stream Processing berkaitan dengan keadaan keseluruhan data , sedangkan Stateless Stream Processing tidak.</ol>
  <li>Informasi tentang kejadian sebelumnya digunakan sebagai bagian dari analisis kejadian saat ini dalam konteks Stateful Stream Processing. Pembacaan suhu dari mesin industri, misalnya, lebih berharga jika dilihat secara agregat dan lintas waktu, memungkinkan tren untuk diidentifikasi saat muncul.</ol>
  <li>Data dievaluasi begitu tiba di Stateless Stream Processing, tanpa mempertimbangkan keadaan atau pengetahuan sebelumnya . Sistem Pemrosesan Aliran Tanpa Negara akan cukup jika yang Anda butuhkan hanyalah umpan waktu nyata dari suhu lingkungan tanpa mempedulikan bagaimana perubahannya. Di sisi lain, sistem Pemrosesan Arus Berstatus diperlukan jika Anda ingin memperkirakan suhu di masa mendatang berdasarkan perubahan suhu dari waktu ke waktu</ol>
</ul>
<b>3 Berikut Penjelasanya</b>
<ol>
  <li>
    <ul>
      <li>sys.argv: adalah daftar argumen baris perintah yang diberikan ke aplikasi Spark Streaming. Argumen pertama adalah nama aplikasi, dan argumen yang tersisa adalah opsi untuk aplikasi.</li>
      <li>sys.stderr: adalah aliran yang dapat digunakan untuk menulis pesan kesalahan ke konsol</li>
      <li>StreamingContext: adalah kelas yang mewakili aplikasi Spark Streaming. Ini digunakan untuk membuat dan mengelola pekerjaan streaming</li>
      <li>sc: adalah variabel yang mengacu pada objek SparkContext. Objek SparkContext digunakan untuk membuat dan mengelola pekerjaan Spark.</li>
      <li>socketTextStream: adalah metode yang membuat dataset streaming dari soket. Metode socketTextStream mengambil dua argumen: nama host atau alamat IP soket, dan nomor port soket</li>
      <li>reduceByKey: adalah fungsi yang mengurangi dataset dengan mengelompokkan elemen dengan kunci yang sama dan menerapkan fungsi ke grup. Fungsi reduceByKey mengambil dua argumen: fungsi yang mengambil dua elemen dengan kunci yang sama dan mengembalikan elemen baru, dan pembagi yang membagi dataset menjadi grup.</li>
      <li>lambda line: adalah fungsi anonim yang mengambil baris teks sebagai input dan mengembalikan jumlah kata dalam baris. Fungsi lambda line digunakan untuk menghitung jumlah kata dalam aliran teks.</li>
      <li>awaitTermination: adalah metode yang menunggu pekerjaan streaming untuk dihentikan. Metode awaitTermination mengambil dua argumen: batas waktu, dalam milisecond, dan fungsi yang dipanggil saat pekerjaan dihentikan</li>
    </ul>
  </li>
  <li>
    <ul>
      <li>nc: adalah utilitas baris perintah yang dapat digunakan untuk membuat koneksi jaringan. Perintah nc mengambil dua argumen: nama host atau alamat IP server, dan nomor port server</li>
      <li>lk: adalah fungsi Spark Streaming yang membaca data dari koneksi jaringan. Fungsi lk mengambil dua argumen: nama host atau alamat IP server, dan nomor port server.</li>
    </ul>
  </li>
  <li>
    <ul>
      <li>spark-submit</li>
      <li>master</li>
      <li>local[*]</li>
    </ul>
  </li>
  <li>
    <ul>
      <li>ssc.checkpoint</li>
      <li>parallelize</li>
      <li>updateStateByKey</li>
      <li>flatMap</li>
    </ul>
  </li>
  <li>
    <ul>
      <li>rdd.take(5)</li>
      <li>transform</li>
      <li>rdd.sortByKey(False)</li>
    </ul>
  </li>
</ol>

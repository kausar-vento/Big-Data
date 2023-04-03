<center><h1>Tugas Pratikum  2</h1></center>
<ul>
  <p>Kode 1: sc, accumulator, parallelize, lambda, value</p>
  <ul>
    <li>SC: adalah variabel yang digunakan untuk SparkContext di PySpark. SparkContext adalah objek inti untuk koneksi ke kluster Spark dan membuat RDD.</li>
    <li>Accumulator: adalah variabel yang digunakan untuk mengumpulkan nilai di seluruh kluster dalam mode read-only atau read-write.</li>
    <li>Parallelize: dalah fungsi yang digunakan untuk mengubah koleksi Python menjadi RDD. Ini membagi koleksi menjadi bagian-bagian dan mendistribusikan bagian-bagian tersebut di seluruh node dalam kluster.</li>
    <li>Lambda: adalah fungsi anonim di Python. Fungsi ini dapat digunakan untuk membuat fungsi sederhana yang hanya membutuhkan satu argumen. lambda biasanya digunakan dalam PySpark untuk mengubah nilai pada RDD</li>
    <li>Value: adalah variabel yang digunakan untuk menyimpan nilai yang bersifat tidak berubah pada PySpark</li>
  </ul>
  <br>
  <p>Kode 2: broadcast, list, range</p>
  <ul>
    <li>Broadcast: digunakan untuk mengirim data besar yang tidak berubah ke semua node tanpa mengambil sumber daya memori yang signifikan</li>
    <li>List: biasanya digunakan dalam PySpark untuk mengumpulkan data dari RDD dan melakukan transformasi data pada RDD.</li>
    <li>Range: biasanya digunakan dalam PySpark untuk membuat RDD dengan sejumlah partisi atau saat membutuhkan indeks dalam proses iterasi</li>
  </ul>
  <br>
  <p>Kode 3: textFile, filter, cache, count</p>
  <ul>
    <li>TextFile: Fungsi ini mengambil satu atau lebih nama file sebagai argumen dan mengembalikan RDD yang berisi baris teks di dalam file-file tersebut</li>
    <li>Filter: Fungsi ini mengambil argumen berupa fungsi lambda yang mengembalikan nilai True atau False dan menghasilkan RDD baru yang berisi elemen-elemen yang memenuhi kondisi tersebut</li>
    <li>Cache: Fungsi ini mengambil RDD sebagai argumen dan menyimpannya di dalam memori.</li>
    <li>Count: Fungsi ini mengambil RDD sebagai argumen dan mengembalikan jumlah elemen di dalam RDD. Fungsi ini digunakan untuk memeriksa apakah RDD berisi data atau tidak, dan juga untuk memeriksa jumlah elemen di dalam RDD setelah dilakukan operasi transformasi.</li>
  </ul>
  <br>
  <p>Kode 4: map, collect, len, keys, values</p>
  <ul>
    <li>Map: Fungsi ini mengambil argumen berupa fungsi lambda yang menghasilkan nilai baru dan mengembalikan RDD baru yang berisi elemen-elemen yang telah ditransformasi.</li>
    <li>Collect: Fungsi ini mengambil RDD sebagai argumen dan mengumpulkan semua elemen dalam RDD ke driver program</li>
    <li>Len: Fungsi built-in di Python yang mengembalikan jumlah elemen dalam sebuah objek</li>
    <li>Keys: Fungsi ini mengambil RDD sebagai argumen dan mengembalikan RDD baru yang hanya berisi kunci-kunci dalam pasangan kunci-nilai.</li>
    <li>Values: Fungsi ini mengambil RDD sebagai argumen dan mengembalikan RDD baru yang hanya berisi nilai-nilai dalam pasangan kunci-nilai.</li>
  </ul>
  <br>
  <p>Kode 5: defaultParallelism, getNumPartitions, mapPartitionsWithIndex, repartition, coalesce, toDebugString</p>
  <ul>
    <li>DefaultParallelism: variabel konfigurasi di PySpark yang menentukan jumlah partisi default yang digunakan saat memproses RDD secara paralel</li>
    <li>GetNumPartitions: Fungsi ini mengambil RDD sebagai argumen dan mengembalikan jumlah partisi dalam RDD</li>
    <li>MapPartitionsWithIndex: Fungsi ini mengambil argumen berupa fungsi lambda yang menghasilkan nilai baru dan mengembalikan RDD baru yang berisi hasil transformasi</li>
    <li>Repartition: Fungsi ini mengambil argumen berupa jumlah partisi yang diinginkan dan mengembalikan RDD baru dengan partisi yang sudah diatur ulang</li>
    <li>Coalesce: Fungsi ini mengambil argumen berupa jumlah partisi yang diinginkan dan mengembalikan RDD baru dengan jumlah partisi yang telah dikurangi</li>
    <li>ToDebugString: Fungsi ini mengambil RDD sebagai argumen dan mengembalikan representasi RDD dalam bentuk string yang mudah dibaca</li>
  </ul>
  <br>
  <p>Kode 6: flatMap, reduceByKey, split</p>
  <ul>
    <li>FlatMap: Fungsi ini mengambil argumen berupa sebuah fungsi lambda yang mengembalikan satu atau banyak elemen dan mengembalikan RDD baru dengan elemen-elemen yang telah dipetakan.</li>
    <li>ReduceByKey: Fungsi ini mengambil argumen berupa sebuah fungsi lambda yang menggabungkan nilai-nilai dan mengembalikan RDD baru dengan nilai-nilai yang telah digabungkan</li>
    <li>Split: Fungsi ini biasanya digunakan sebagai bagian dari transformasi data di PySpark untuk membagi nilai kolom dalam RDD menjadi beberapa nilai yang terpisah</li>
  </ul>
</ul>

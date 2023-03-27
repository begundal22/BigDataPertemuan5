# BigDataPertemuan5
## Nama      : Dio Aulia Ari Kurnia Sandi
## Kelas     : TI - 3C
## No. Absen : 05

BIG DATA - Chapter 3

## Hasil

![1](https://user-images.githubusercontent.com/89907128/227844749-529ebaa9-f859-40f4-b8a0-0029b66f3d16.png)
![2](https://user-images.githubusercontent.com/89907128/227844757-5bb97906-a733-4e7c-bcca-8d234377efd0.png)
![3](https://user-images.githubusercontent.com/89907128/227844774-46576ee7-18f7-4493-8493-84450a77de8c.png)
![4](https://user-images.githubusercontent.com/89907128/227844801-7274c3a2-9f41-43f5-928c-015a3e5d271a.png)
![5](https://user-images.githubusercontent.com/89907128/227844814-b0677833-6226-43db-b2e2-f665660574ac.png)
![6](https://user-images.githubusercontent.com/89907128/227844827-b828b0b6-3f5b-46c7-bff3-3b5a72dc9ae5.png)
![7](https://user-images.githubusercontent.com/89907128/227844838-f8b5b6a5-9a9f-44e7-9145-e02ac7a6ad43.png)
![8](https://user-images.githubusercontent.com/89907128/227844851-38ff033e-2384-41e9-8886-a4eaf08939a0.png)
![9](https://user-images.githubusercontent.com/89907128/227844863-ac753efa-e111-47fa-ae17-713b2dec5e58.png)

Kode 1: sc : sc adalah objek SparkContext pada Apache Spark. 
        accumulator : adalah objek SparkContext pada Apache Spark.
        parallelize : Accumulators adalah variabel yang hanya dapat diakses secara read-only oleh setiap task, tetapi dapat ditambahkan nilai dari semua task
        lambda : parallelize adalah fungsi dalam SparkContext yang digunakan untuk membuat RDD (Resilient Distributed Datasets) dari sebuah kumpulan data dalam bentuk array.
        value :lambda adalah fungsi anonim dalam Python yang sering digunakan dalam pemrograman fungsional dan memungkinkan penggunaan fungsi sebagai argumen atau nilai kembali dari fungsi lain.
Kode 2: broadcast : Fungsi broadcast digunakan untuk mengirimkan variabel yang besar dan sering digunakan pada setiap worker dalam sebuah cluster.
        list : Fungsi list digunakan untuk membuat sebuah list yang kemudian digunakan untuk membuat sebuah RDD (Resilient Distributed Dataset) pada Spark.
        range : Fungsi range digunakan untuk membuat sebuah RDD yang berisi rentang nilai tertentu.
Kode 3: textFile : baris ini digunakan untuk membaca file teks yang berada pada lokasi yang telah ditentukan dan menyimpannya dalam variabel textFile.
        filter : baris ini digunakan untuk melakukan filter pada data yang telah dibaca dari file teks. Filter dilakukan dengan mencari baris yang mengandung "kata_kunci" pada setiap baris data, dan menyimpan hasilnya dalam variabel filteredData.
        cache : baris ini digunakan untuk melakukan caching pada data yang telah difilter.
        count : baris ini digunakan untuk menghitung jumlah baris pada data yang telah difilter dan di-cache sebelumnya.
Kode 4: map : metode untuk melakukan transformasi pada setiap elemen RDD dengan mengaplikasikan suatu fungsi pada setiap elemennya.
        collect : metode untuk mengumpulkan semua elemen RDD dan mengembalikannya dalam bentuk array atau list di driver program.
        len : metode untuk mengembalikan jumlah elemen dalam RDD.
        keys : metode untuk mengembalikan RDD baru yang berisi kunci (key) dari setiap pasangan kunci-nilai (key-value) dalam RDD awal.
        values : metode untuk mengembalikan RDD baru yang berisi nilai (value) dari setiap pasangan kunci-nilai dalam RDD awal.
Kode 5: defaultParallelism : Ini adalah parameter konfigurasi pada Apache Spark yang menentukan jumlah default partisi yang digunakan dalam sebuah RDD (Resilient Distributed Dataset).
        getNumPartitions : Ini adalah metode pada RDD yang mengembalikan jumlah partisi yang ada dalam RDD.
        mapPartitionsWithIndex : Ini adalah metode pada RDD yang memungkinkan kita untuk melakukan pemetaan pada setiap partisi RDD dengan memberikan akses ke indeks partisi.
        repartition : Ini adalah metode pada RDD yang mengubah jumlah partisi dalam RDD menjadi jumlah yang baru.
        coalesce : Ini adalah metode pada RDD yang menggabungkan beberapa partisi RDD menjadi satu partisi yang lebih besar.
        toDebugString : Ini adalah metode pada RDD yang mengembalikan string yang berisi informasi mengenai RDD.
Kode 6: flatMap : Fungsi ini akan menghasilkan sebuah RDD yang terdiri dari daftar kata-kata.
        reduceByKey : Fungsi ini akan menghasilkan RDD dengan pasangan kata dan jumlah kemunculannya.
     

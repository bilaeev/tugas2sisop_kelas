# tugas 2
# Analisis proses
1. Screenshot task manager (highlight warna kuning)  
   ![CPU](https://github.com/user-attachments/assets/db2403e9-ad38-4594-aaa0-2df553b17929)  
   ![MEMORY](https://github.com/user-attachments/assets/e1d84879-8313-497c-bcec-aa83e4d5786e)  
   ![DISK](https://github.com/user-attachments/assets/3fccfa08-4590-4617-a8ee-159eab379042)  
   ![NETWORK](https://github.com/user-attachments/assets/5a969451-abeb-4eba-a4fa-b3807a14054a)  
2. Mengamati yang mana yang paling tinggi prosesnya :  
   Berdasarkan hasil pengamatan pada Task Manager, diperoleh data sebagai berikut:  
- CPU tertinggi: Google Chrome sebesar 30,3%  
- Memory tertinggi: Google Chrome sebesar 460 MB  
- Disk tertinggi: WhatsApp sebesar 40,1 MB/s  
- Network tertinggi: Visual Studio Code sebesar 0,7 Mbps  
3. Jelaskan kenapa hal tersebut terjadi :  
  - Penggunaan CPU dan Memory tertinggi terdapat pada Google Chrome. Hal ini terjadi karena browser menjalankan banyak proses secara bersamaan, seperti membuka beberapa tab, menjalankan JavaScript, serta memuat konten halaman web sehingga membutuhkan pemrosesan dan memori yang besar.  
  - Penggunaan Disk tertinggi terdapat pada WhatsApp. Hal ini kemungkinan disebabkan oleh aktivitas baca/tulis data seperti mengunduh atau menyimpan file (gambar, video, atau dokumen), sehingga penggunaan disk meningkat.  
  - Penggunaan Network tertinggi terdapat pada Visual Studio Code sebesar 0,7 Mbps. Meskipun nilainya kecil, hal ini dapat terjadi karena adanya aktivitas seperti sinkronisasi ekstensi, update, atau komunikasi dengan server.  
4. Alasan perbedaan penggunaan sumber daya :
  Perbedaan penggunaan sumber daya (CPU, Memory, Disk, dan Network) terjadi karena setiap aplikasi memiliki fungsi dan kebutuhan yang berbeda, yaitu :  
  - Pada hasil pengamatan, Google Chrome menggunakan CPU dan Memory paling tinggi. Hal ini karena Google Chrome menjalankan banyak proses seperti membuka beberapa tab, menjalankan script, dan memuat konten web sehingga membutuhkan pemrosesan (CPU) dan penyimpanan data sementara (RAM) yang besar.  
  - Sementara itu, WhatsApp memiliki penggunaan Disk tertinggi. Hal ini disebabkan oleh aktivitas baca/tulis data seperti mengunduh atau menyimpan file (gambar, video, atau dokumen), sehingga penggunaan disk menjadi tinggi.  
  - Sedangkan Visual Studio Code memiliki penggunaan Network tertinggi, walaupun nilainya kecil. Hal ini dapat terjadi karena adanya aktivitas seperti sinkronisasi data, update ekstensi, atau koneksi ke server saat proses coding.  

# Contoh Scheduling
**1. First-Come, First-Served (FCFS)**  
FCFS adalah metode penjadwalan yang menjalankan proses berdasarkan urutan kedatangan.  
● Contoh pada OS:  
   Pada sistem operasi seperti Windows dengan membuka beberapa aplikasi secara berurutan, misalnya notepad, kalkulator, lalu browser.  
   Langkah-langkah:  
   1. Buka aplikasi satu per satu secara berurutan.  
   2. Buka Task Manager.  
   3. Perhatikan urutan proses yang muncul.    
   ==> Hal ini menggambarkan konsep proses dijalankan berdasarkan urutan kedatangan.  
      
**2. Shortest Job Next (SJN)**  
SJN adalah metode penjadwalan yang memilih proses dengan waktu eksekusi paling singkat terlebih dahulu.  
● Contoh pada OS:  
   Pada sistem operasi seperti Linux dengan menjalankan aplikasi ringan seperti notepad dan aplikasi yang lebih berat seperti browser atau Visual Studio Code.  
   Langkah-langkah:  
   1. Jalankan aplikasi ringan dan aplikasi berat  
   2. Buka Task Manager atau System Monitor  
   3. Perhatikan perbedaan penggunaan CPU atau memory  
   ==>Hal ini menggambarkan bahwa proses dengan pekerjaan lebih kecil dapat selesai lebih cepat.  
    
3. Round Robin (RR)  
Round Robin adalah metode penjadwalan di mana setiap proses mendapat jatah waktu (time quantum) secara bergiliran.  
● Contoh pada OS:  
   Pada sistem operasi seperti Windows dengan membuka beberapa aplikasi secara bersamaan seperti browser, Visual Studio Code, dan WhatsApp.  
Langkah-langkah:  
1. Buka beberapa aplikasi secara bersamaan  
2. Buka Task Manager  
3. Perhatikan kolom CPU yang berubah-ubah  
==> CPU bergantian digunakan. Hal ini menunjukkan bahwa CPU dibagi ke setiap proses secara bergiliran.  

4. Priority Scheduling  
Priority Scheduling adalah metode penjadwalan berdasarkan tingkat prioritas proses.  
● Contoh pada OS:  
   Pada sistem operasi seperti Windows melalui Task Manager.  
   Langkah-langkah:  
   1. Buka Task Manager  
   2. Masuk ke tab Details  
   3. Klik kanan salah satu proses  
   4. Pilih Set Priority, amati  
   ==> Hal ini menunjukkan bahwa proses dengan prioritas lebih tinggi akan diutamakan.  

5. Multilevel Queue Scheduling  
Multilevel Queue Scheduling adalah metode yang membagi proses ke dalam beberapa antrian berdasarkan kategori tertentu.  
● Contoh pada OS:  
   Pada sistem operasi seperti Windows melalui pembagian kategori proses.  
   Langkah-langkah:  
   1. Buka Task Manager  
   2. Perhatikan kategori seperti Apps, Background processes, dan Windows processes  
   3. Amati perbedaan jenis proses  
   ==> Hal ini menggambarkan bahwa proses dikelompokkan ke dalam beberapa antrian berdasarkan jenisnya.  

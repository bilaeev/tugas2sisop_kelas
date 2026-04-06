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
1. First-Come, First-Served (FCFS)  
FCFS adalah metode penjadwalan yang menjalankan proses berdasarkan urutan kedatangan.  
● Contoh pada OS:  
Digunakan pada sistem batch di Linux, terutama pada antrian proses sederhana di mana proses yang masuk terlebih dahulu akan diproses lebih dulu tanpa prioritas khusus.  
2. Shortest Job Next (SJN)  
SJN adalah metode penjadwalan yang memilih proses dengan waktu eksekusi paling singkat terlebih dahulu.  
● Contoh pada OS:  
Digunakan dalam sistem batch pada Unix dan Linux untuk meningkatkan efisiensi waktu tunggu dengan mendahulukan proses yang lebih cepat selesai.  
3. Round Robin (RR)  
Round Robin adalah metode penjadwalan di mana setiap proses mendapat jatah waktu (time quantum) secara bergiliran.  
● Contoh pada OS:  
Digunakan pada sistem multitasking seperti Windows dan Linux untuk menjaga agar semua proses mendapatkan kesempatan menggunakan CPU secara adil.  
4. Priority Scheduling  
Priority Scheduling adalah metode penjadwalan berdasarkan tingkat prioritas proses.  
● Contoh pada OS:  
Digunakan pada Android, di mana proses sistem (seperti telepon atau notifikasi penting) memiliki prioritas lebih tinggi dibandingkan aplikasi biasa.  
5. Multilevel Queue Scheduling  
Multilevel Queue Scheduling adalah metode yang membagi proses ke dalam beberapa antrian berdasarkan kategori tertentu.  
● Contoh pada OS:  
Digunakan pada Linux, di mana proses dibagi menjadi beberapa antrian seperti proses sistem, proses interaktif, dan proses batch, dengan prioritas yang berbeda untuk setiap antrian.  

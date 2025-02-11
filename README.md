# cnn_tomato_pest_detection
Convolutional Neural Network (CNN) pada Tanaman Tomat

Convolutional Neural Network (CNN) adalah jenis jaringan saraf tiruan yang sangat efektif dalam analisis citra atau gambar. Dalam konteks tanaman tomat, CNN digunakan untuk menganalisis gambar atau foto tanaman guna mendeteksi berbagai kondisi, seperti kesehatan tanaman, keberadaan penyakit, atau bahkan memantau perkembangan buah tomat.

CNN bekerja dengan cara mengidentifikasi fitur-fitur penting dalam gambar melalui beberapa lapisan konvolusi yang secara otomatis mengekstraksi pola, tekstur, dan fitur visual lainnya. Dalam aplikasi pertanian, CNN dapat digunakan untuk:
- Mendeteksi gejala penyakit seperti jamur atau bakteri pada daun atau buah tomat.
- Mengidentifikasi tahap pertumbuhan tanaman, seperti pemantauan pembungaan atau pematangan buah.
- Menilai kualitas dan ukuran buah tomat yang siap panen.

Metode ini sangat berguna karena memungkinkan petani atau peneliti untuk melakukan pemantauan secara otomatis dan efisien tanpa perlu pemeriksaan manual yang memakan waktu, serta meningkatkan ketepatan dalam pengambilan keputusan terkait perawatan tanaman tomat.

## 📌 Fitur
1. Fitur Konvolusi (Convolution Features):
    - Filter (Kernel) digunakan untuk mengekstraksi pola dari gambar tanaman tomat, seperti tepi, tekstur, atau warna yang menunjukkan gejala penyakit atau kerusakan.
    - Lapisan Konvolusi mengaplikasikan filter untuk menghasilkan peta fitur yang memuat informasi penting seperti garis, sudut, dan bentuk dalam gambar.

2.Fitur Pooling (Downsampling Features):
    - Max Pooling memilih nilai maksimum dalam area kecil untuk mereduksi dimensi citra dan mempertahankan fitur penting, seperti bentuk buah atau pola daun.
    - Average Pooling menghitung rata-rata dalam area kecil, mengurangi kompleksitas model dan mempercepat pelatihan.
    
Fitur Aktivasi (Activation Features):
3. Fitur Aktivasi (Activation Features):
    - ReLU (Rectified Linear Unit) menambah non-linearitas pada model, memungkinkan deteksi pola yang lebih kompleks, seperti perbedaan antara daun sehat dan yang terinfeksi.
    
4. Fitur Klasifikasi (Classification Features):
    - Fully Connected Layers (FC) mengklasifikasikan gambar berdasarkan fitur yang telah diekstraksi, seperti tanaman sehat atau terinfeksi.
    - Softmax digunakan di lapisan output untuk memberikan probabilitas kelas, seperti “sehat” atau “terinfeksi jamur”.

5. Fitur Deteksi Ciri (Feature Detection):
    - Deteksi Penyakit mengenali pola yang berhubungan dengan penyakit pada tanaman, seperti bercak pada daun atau infeksi jamur.
    - Deteksi Kondisi Tanaman menganalisis kondisi pertumbuhan, termasuk pembungaan atau kematangan buah tomat.

6. Fitur Warna dan Tekstur:
    - Analisis Warna mengidentifikasi perubahan warna pada daun atau buah yang menandakan masalah seperti kekurangan nutrisi atau infeksi.
    - Analisis Tekstur digunakan untuk mendeteksi gejala penyakit, seperti tekstur abnormal pada daun atau bercak pada buah yang menunjukkan pembusukan.
    


Kelompok 2 Pemodelan dan Simulasi
Nama: 
1. Thifal Hasna Aulia Habibah 
2. Andi Septian 
3. M Irfan Fadhlurrohman


echo "# CNN" > README.md
# Download File Besar
Karena file ini terlalu besar untuk GitHub, Anda bisa mengunduhnya dari Google Drive:

🔗 [Klik di sini untuk mengunduh](https://drive.google.com/drive/folders/19ohMAbWrygBNbw3861uMnTXuTs7DnlPY?usp=drive_link)

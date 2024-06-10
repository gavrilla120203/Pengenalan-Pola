# Klasifikasi Penyakit pada Tumbuhan Durian Menggunakan Metode Convolutional Neural Network (CNN) 

![Untitled](https://github.com/gavrilla120203/Pengenalan-Pola/assets/130575657/082d2ca0-284b-4a2d-8bfb-c2f882a9ea20)

Proyek ini bertujuan untuk mengembangkan sistem klasifikasi penyakit pada tumbuhan durian menggunakan metode Convolutional Neural Network (CNN). Proyek ini dibagi menjadi beberapa tahap mulai dari pengumpulan dataset hingga dokumentasi di github. Proyek ini dikerjakan oleh Gavrilla Claudia (21110004) dan Nifelling Rosmelia Sandewa (21110014), dengan pembagian tugas sebagai berikut : 

## Pembagian Tugas

### Gavrilla Claudia
1. **Pengumpulan Data**
   - Mengumpulkan dataset gambar daun durian dari website roboflow.
   - Membagi dataset dalam 4 kelas yakni Alga Leaf Spot, No Disease,
     Leaf Blight, dan Leaf Spot. 

2. **Preprocessing Data**
   - Membagi dataset menjadi 201 data pelatihan, 100 data pengujian, dan
     119 data validasi. 
   - Menampilkan distribusi pada setiap folder (train, test,
     validation).  
   - Melakukan augmentasi data untuk meningkatkan variasi dataset
     menggunakan pipeline augmentor. 

3. **Dokumentasi**
   - Menyusun README.md dengan penjelasan lengkap mengenai proyek ini.

### Nifelling Rosmelia Sandewa
1. **Model Training**
   - Memilih arsitektur model CNN yang sesuai untuk klasifikasi penyakit
     tumbuham durian seperti Model CNN (4 Layer Conv2D, (16, 32, 64,
     64), Dense=128, lr=0.0001). 
   - Melakukan training model dengan dataset yang telah dipreproses dan
     di-augmentasi.
   - Mengoptimalkan hyperparameter model.

2. **Vakidation and Model Evaluation**
   - Pengujian model menggunakan data validasi atau data uji yang terpisah dari
     data pelatihan untuk mengukur akurasi, loss, val_accuracy, dan val_loss.
     
3. **Optimisasi Model**
   - Setelah evaluasi, perlu dilakukan optimisasi model untuk meningkatkan kinerja
     atau efisiensi model seperti hyperparameter.    

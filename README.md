# Fruits Image Classification

<!-- ![Fruits Image Classification](https://github.com/user-attachments/assets/f4ed00a1-d728-460c-8c34-97fbbf23e221) -->

## Latar Belakang:
Pengenalan citra merupakan salah satu bidang utama dalam machine learning dan computer vision. Berkat perkembangan teknologi, proses klasifikasi gambar kini menjadi lebih mudah dan dapat diaplikasikan di berbagai bidang, mulai dari sistem keamanan hingga layanan kesehatan. Pada proyek ini, fokus diberikan pada klasifikasi gambar buah untuk memahami penerapan model deep learning dalam membedakan jenis-jenis buah.

## Permasalahan Bisnis:
Dalam industri retail dan makanan, kemampuan mengenali buah secara otomatis sangat membantu dalam mengoptimalkan proses seperti penyortiran, pengepakan, dan pengawasan kualitas buah. Dengan adanya otomatisasi tersebut, perusahaan dapat mengurangi kesalahan akibat faktor manusia, meningkatkan produktivitas, serta menekan biaya operasional dan tenaga kerja.

## Tujuan Proyek:
1. Mengembangkan model klasifikasi gambar yang mampu mengidentifikasi berbagai jenis buah dengan akurasi tinggi.
2. Menyimpan model dalam berbagai format yang kompatibel dengan berbagai platform dan perangkat.
3. Menerapkan deep learning untuk meningkatkan akurasi klasifikasi gambar.

## Cakupan Proyek
1. Mencari datatset
2. Dataset Dibagi Menjadi 80% Train Set dan 20% Test Set
3. Model Menggunakan Model Sequential, Conv2D, Pooling Layer
4. Membuat Plot Terhadap Akurasi dan Loss Model
5. Menyimpan Model ke Dalam Format SavedModel, TF-Lite dan TFJS
6. Mengimplementasikan Callback
7. Melakukan inference menggunakan salah satu model (TF-Lite, TFJS atau savedmodel dengan tf serving).

## Dataset
Dataset diperoleh dari kaggle <a href="https://www.kaggle.com/datasets/moltean/fruits" target='_blank'>Fruits Dataset</a>, yang berisi 5 folder:

1. fruits-360_100x100
2. fruits-360_3-body-problem
3. fruits-360_dataset_meta
4. fruits-360_multi
5. fruits-360_original-size

Namun pada proyek ini, hanya folder **fruits-360_100x100** yang digunakan.Pada dataset ini terdapat 207 kelas.

## Setup environment:

1. Direkomendasikan untuk dijalankan di Google Colab
    - Upload file `[Klasifikasi]_Submission_Klasifikasi_Gambar_Atifa_Fiorenza.ipynb` ke Google Colab 
    - Sesuaikan dengan kode yang sudah ada atau sesuaikan dengan keinginanmu
    - Lakukan **run all** pada project

2. Jika dijalankan di local
    - Pastikan terhubung ke internet untuk dapat melakukan install module (library) 
    - Buka cmd atau powershell as administrator

    ```bash
    pip install -r requirements.txt
    ```
    - Buka file `[Klasifikasi]_Submission_Klasifikasi_Gambar_Atifa_Fiorenza.ipynb` ke Google Colab 
    - Sesuaikan dengan kode yang sudah ada atau sesuaikan dengan keinginanmu
    - Lakukan **run all** pada project

 ## Conclusion
- Berdasarkan percobaan, dihasilkan untuk:
    - Model              : Sequential
    - Akurasi            : 95 %
- Hasil model mampu memprediksi gambar buah (fruits) yang diinputkan melalui inference.

## Saran
- Melakukan eksperimen lebih lanjut dengan menggunakan pretrained model lain pada project ini. (misal VGG, ResNet dan lainnya)
- Melakukan percobaan lebih lanjut dengan original dan multi dataset
  

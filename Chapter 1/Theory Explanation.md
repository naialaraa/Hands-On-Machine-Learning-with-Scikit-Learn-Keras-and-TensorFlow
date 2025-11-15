## Theory Explanation

### 1. Konsep Dasar Machine Learning
Machine Learning mempelajari cara sistem secara otomatis mengekstraksi pola dari data untuk meningkatkan performa terhadap suatu tugas tertentu. Definisi formal menyatakan bahwa sebuah sistem “belajar” apabila performanya meningkat terhadap suatu tugas seiring bertambahnya pengalaman. Pendekatan ini efektif untuk kasus yang sulit atau tidak mungkin dirumuskan menggunakan aturan manual.

---

### 2. Aplikasi Machine Learning
ML diterapkan dalam berbagai domain, seperti:

- **Computer Vision**: deteksi objek, pengenalan wajah, segmentasi citra.
- **Natural Language Processing**: klasifikasi teks, terjemahan otomatis, sentiment analysis.
- **Recommender Systems**: prediksi preferensi pengguna.
- **Analisis Medis**: identifikasi penyakit dari citra medis.
- **Anomaly Detection**: pendeteksian transaksi mencurigakan.
- **Reinforcement Learning**: agen pengambil keputusan seperti AlphaGo.

---

### 3. Klasifikasi Machine Learning Berdasarkan Label Data

#### a. Supervised Learning
Model dilatih menggunakan data berlabel untuk mempelajari pemetaan input–output. Contohnya regresi dan klasifikasi. Algoritma umum meliputi Logistic Regression, SVM, Random Forest, dan Neural Networks.

#### b. Unsupervised Learning
Model bekerja tanpa label dan mencari struktur tersembunyi dalam data. Termasuk clustering, dimensionality reduction, dan anomaly detection.

#### c. Semi-Supervised Learning
Mengombinasikan sebagian kecil data berlabel dengan sejumlah besar data tidak berlabel. Banyak digunakan ketika proses pelabelan mahal atau kompleks.

#### d. Reinforcement Learning
Agen belajar berdasarkan reward dan penalti dari lingkungannya untuk mempelajari kebijakan optimal. Banyak digunakan dalam robotika dan sistem otonom.

---

### 4. Batch Learning dan Online Learning

#### a. Batch Learning
Model dilatih berdasarkan keseluruhan dataset dan tidak diperbarui secara real-time. Cocok untuk data yang tidak berubah.

#### b. Online Learning
Model diperbarui secara bertahap dari data yang mengalir. Cocok untuk sistem berskala besar atau yang membutuhkan adaptasi cepat.

---

### 5. Instance-Based vs Model-Based Learning

#### a. Instance-Based Learning
Model menyimpan contoh pelatihan dan membuat prediksi berdasarkan kemiripan dengan contoh tersebut. Contoh utama adalah k-Nearest Neighbors.

#### b. Model-Based Learning
Model membangun representasi matematis dari pola data melalui optimisasi fungsi biaya, lalu digunakan untuk membuat prediksi pada data baru. Termasuk regresi linear, pohon keputusan, dan neural networks.

---

### 6. Tantangan dalam Machine Learning

- **Data terbatas**: menghambat kemampuan generalisasi.
- **Data tidak representatif**: menimbulkan bias prediksi.
- **Data berkualitas rendah**: noise, outliers, dan missing values dapat mengaburkan pola sebenarnya.
- **Fitur yang tidak relevan**: menurunkan performa; memerlukan feature engineering.

---

### 7. Overfitting dan Underfitting

- **Overfitting**: model terlalu kompleks sehingga mempelajari noise pada data pelatihan.  
  Solusi meliputi regularisasi, pengurangan fitur, atau peningkatan jumlah data.

- **Underfitting**: model terlalu sederhana sehingga gagal menangkap pola penting.  
  Solusi meliputi pemilihan model yang lebih kompleks atau penambahan fitur.

---

### 8. Evaluasi Model

Evaluasi dilakukan dengan membagi data menjadi:
- **Training set**
- **Validation set**
- **Test set**

Teknik seperti cross-validation digunakan untuk meningkatkan reliabilitas evaluasi. Perbedaan distribusi antara data pelatihan dan data produksi (*data mismatch*) harus diantisipasi karena dapat menurunkan performa model.

---

### 9. No Free Lunch Theorem
Teorema ini menegaskan bahwa tidak ada algoritma ML yang selalu unggul untuk semua masalah. Pemilihan algoritma harus mempertimbangkan karakteristik data dan tujuan analisis serta dievaluasi melalui eksperimen yang sistematis.

# Comparative Study of SVM dan CNN dengan TF-IDF dan Word2Vec untuk Deteksi Ujaran Kebencian Bahasa Indonesia di Media Sosial X

## Deskripsi Proyek

Perkembangan teknologi informasi dan media sosial seperti Facebook, Instagram, WhatsApp, dan X (Twitter) telah mengubah cara manusia berkomunikasi dan berbagi informasi. Namun, pertumbuhan media sosial juga meningkatkan penyebaran ujaran kebencian (hate speech) yang dapat mengganggu keharmonisan sosial.

Penelitian ini bertujuan untuk membandingkan performa model Machine Learning dan Deep Learning dalam mendeteksi ujaran kebencian berbahasa Indonesia pada media sosial X menggunakan kombinasi metode ekstraksi fitur TF-IDF dan Word2Vec.

Model yang digunakan:
- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)

---

## Tujuan Penelitian

- Membangun sistem klasifikasi ujaran kebencian otomatis pada media sosial.
- Membandingkan performa model SVM dan CNN.
- Menganalisis pengaruh penggunaan TF-IDF dan Word2Vec terhadap performa klasifikasi.
- Menguji pengaruh variasi N-Gram dan dimensi Word2Vec terhadap hasil model.

---

## Dataset

- Sumber data: Media Sosial X (Twitter)
- Jumlah data: **11.488 data teks**
- Metode pengumpulan data: Manual Crawling
- Bahasa: Indonesia

---

## Teknologi yang Digunakan

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- TF-IDF
- Word2Vec
- CNN
- SVM
- NLP (Natural Language Processing)

---

## Tahapan Penelitian

### 1. Preprocessing Data
Tahapan preprocessing meliputi:
- Case Folding
- Cleaning Text
- Tokenization
- Stopword Removal
- Stemming

### 2. Ekstraksi Fitur
Metode ekstraksi fitur yang digunakan:
- TF-IDF
- Word2Vec

### 3. Model Klasifikasi

#### Support Vector Machine (SVM)
Kernel yang diuji:
- Linear
- Polynomial
- RBF
- Sigmoid

#### Convolutional Neural Network (CNN)
Model deep learning untuk klasifikasi teks.

---

## Skenario Pengujian

Penelitian dilakukan menggunakan beberapa skenario pengujian:
1. Variasi rasio train-test split
2. Variasi tipe N-Gram
3. Kombinasi N-Gram
4. Variasi dimensi Word2Vec

---

## Hasil Penelitian

| Model | Metode Fitur | Konfigurasi Terbaik | Akurasi |
|---|---|---|---|
| CNN | TF-IDF | Unigram + Bigram | **82.90%** |
| SVM | TF-IDF | Kernel Sigmoid | **81.94%** |

---

## Kesimpulan

- Model CNN memberikan performa terbaik dalam klasifikasi ujaran kebencian bahasa Indonesia.
- TF-IDF menghasilkan performa yang lebih baik dibandingkan Word2Vec pada penelitian ini.
- Kombinasi Unigram dan Bigram meningkatkan kemampuan model dalam memahami konteks teks.
- Model Deep Learning lebih efektif dalam menangkap pola linguistik kompleks dibandingkan metode Machine Learning tradisional.

---

## Manfaat Penelitian

Penelitian ini diharapkan dapat membantu pengembangan sistem moderasi konten otomatis pada media sosial untuk mendeteksi ujaran kebencian secara lebih cepat, akurat, dan efisien.

---

## Publikasi

Paper ini telah dipublikasikan pada konferensi internasional dan terindeks Scopus.

🔗 [IEEE Xplore Publication](https://ieeexplore.ieee.org/document/11193039)

---

## Author

**Diaz Ramzy Naufal**  

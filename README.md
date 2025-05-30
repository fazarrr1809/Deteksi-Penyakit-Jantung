# 🫀 Deteksi Penyakit Jantung dengan Decision Tree

Proyek ini merupakan implementasi pohon keputusan (*Decision Tree*) untuk memprediksi apakah seseorang berisiko terkena penyakit jantung berdasarkan data medis. Proyek ini dibuat untuk memenuhi tugas mata kuliah *Kexedasan Buatan*.

---

## 📌 Deskripsi Masalah

Penyakit jantung merupakan salah satu penyebab kematian tertinggi di dunia. Dengan data klinis sederhana, kita dapat membangun model prediksi yang membantu mendeteksi risiko penyakit jantung sejak dini.

---

## 🧪 Dataset

Dataset yang digunakan berasal dari [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci).  
Berisi 14 atribut, termasuk:
- `age`, `sex`, `cp`, `chol`, `thalach`, `exang`, dll.
- Target: `1` (berisiko penyakit jantung), `0` (tidak berisiko)

---

## 🧠 Model yang Digunakan

- **Algoritma:** Decision Tree Classifier
- **Library:** Scikit-learn, Pandas, Matplotlib, Seaborn
- **Parameter utama:**
  - `criterion="gini"`
  - `max_depth=4`

---

## 📊 Evaluasi Model

| Metric      | Score  |
|-------------|--------|
| Accuracy    | 0.80   |
| Precision   | 0.75–0.88 |
| Recall      | 0.70–0.90 |
| F1-score    | 0.78–0.82 |

Model memiliki performa cukup baik dan seimbang antara deteksi pasien yang sakit dan tidak sakit.

---

## 📈 Visualisasi

- Visualisasi struktur pohon keputusan
- Bar chart feature importance

---

## 🔧 Rekomendasi Pengembangan

- Coba algoritma lain seperti **Random Forest** atau **Logistic Regression**
- Gunakan **GridSearchCV** untuk tuning parameter
- Lakukan **normalisasi** dan preprocessing lanjutan

---

## 📁 File Terkait

- `Deteksi_Penyakit_Jantung.ipynb` – Notebook utama
- `heart.csv` – Dataset

---

## 👥 Kelompok

- Fazar Rizwanul Ikhlas 
- Firman dani

---

## 📚 Referensi

- [Kaggle Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- [Sklearn Docs - Decision Trees](https://scikit-learn.org/stable/modules/tree.html)

# Analisis Mental Health Stress pada Mahasiswa dengan Bantuan IBM Granite

## 📌 Project Overview
Stres akademik merupakan masalah umum yang dapat berdampak pada kesehatan mental mahasiswa.  
Proyek ini menggunakan dataset publik untuk menganalisis pola stres mahasiswa dan memberikan rekomendasi berbasis data dengan dukungan **IBM Granite Model**.

### 🎯 Tujuan Proyek
- Menganalisis tingkat stres mahasiswa berdasarkan data survei.  
- Mengidentifikasi pola stres & faktor penyebab utama.  
- Memberikan rekomendasi untuk intervensi kesehatan mental yang konkret.  

---

## 📂 Raw Dataset
- **Dataset**: [Student Stress Monitoring Dataset](https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets)  
- **Jumlah responden**: 843  
- **Jumlah variabel**: 26 (skala pertanyaan 1–5, termasuk Gender)  
- **Skala survei**: 1 (*tidak pernah*) → 5 (*sangat sering*)  
- **Gender**: 0 = Pria, 1 = Wanita

---

## 📊 Insight & Findings
- **Mayoritas mahasiswa berada di tingkat stres Moderate (89.44%)**.  
- **Kehadiran kelas berkorelasi signifikan** dengan tingkat stres (pertanyaan dengan skor tertinggi mean = 3.26).  
- **Tidak ada perbedaan signifikan** antara pria & wanita dalam tingkat stres.  

---

## 🤖 AI Support Explanation
Analisis dilakukan dengan **IBM Granite Model** melalui Google Colab, digunakan untuk:  
- **Classification** → mengkategorikan stres (Low, Moderate, High).  
- **Summarization** → menyusun ringkasan dataset & insight.  
- **Analisis data** → menemukan temuan & rekomendasi berbasis hasil.  
- **Visualisasi** → mendukung interpretasi pola stres dengan grafik.  

---

## 📂 Repository Structure
```
📁 student-stress-analysis
├── 📈 visualizations/
|   ├── stress_mean_hist.png
|   ├── stress_mean_by_gender.png
|   ├── corr_heatmap.png
|   ├── question_means.png
|   └── top_question_dist.png
├── 📄 README.md
├── 📊 Stress_Dataset.csv 
└── 📓 analysis.ipynb
```

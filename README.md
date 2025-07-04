# 🔍 Clustering Data dengan K-Means, Hierarchical, dan DBSCAN

Proyek ini membandingkan tiga metode clustering: **K-Means**, **Hierarchical Clustering**, dan **DBSCAN** menggunakan Python. Tujuannya adalah untuk mengeksplorasi keunggulan dan kekurangan masing-masing algoritma dalam mengelompokkan data tanpa label.

---

## 📁 File Proyek

- `KMeans_Hierachical_DBSCAN.ipynb` → Notebook utama yang memuat implementasi dan visualisasi semua metode clustering.

---

## 🎯 Tujuan

- Mengimplementasikan tiga algoritma clustering paling umum.
- Membandingkan hasil dan visualisasi dari masing-masing metode.
- Menganalisis keefektifan algoritma dalam mengelompokkan data berdasarkan bentuk cluster, noise, dan kepadatan.

---
Ikuti alur analisis dalam notebook:

Preprocessing (normalisasi data)

Clustering dengan KMeans, DBSCAN, dan Hierarchical

Visualisasi hasil clustering

Evaluasi performa menggunakan Silhouette Score

📊 Evaluasi & Visualisasi
Masing-masing metode dievaluasi berdasarkan:

Visualisasi distribusi cluster

Nilai Silhouette Score (semakin tinggi, semakin baik pemisahan cluster)


## 📦 Library yang Digunakan

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans, DBSCAN, AgglomerativeClustering
from scipy.cluster.hierarchy import dendrogram, linkage

from sklearn.metrics import silhouette_score

🚀 Cara Menjalankan
Pastikan kamu memiliki Python 3.x dan semua library di atas telah terinstal.
Jika belum, jalankan perintah berikut:

bash
Salin kode
pip install pandas numpy matplotlib seaborn scikit-learn
Buka dan jalankan file KMeans_Hierachical_DBSCAN.ipynb di Jupyter Notebook atau Google Colab.


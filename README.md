# Analisis Pola Konsumsi Energi Rumah Tangga (Smart Home Analysis)

Final Project Mata Kuliah Big Data & Data Mining - Semester 5.

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pola konsumsi energi listrik rumah tangga berbasis data *Smart Home* dan mengintegrasikan faktor cuaca menggunakan teknik Data Mining.

**Metode yang digunakan:**
- **Clustering (K-Means)**: Untuk mengelompokkan profil perilaku penggunaan listrik.
- **Predicitve Modeling (Linear Regression)**: Untuk memprediksi konsumsi energi berdasarkan cuaca dan waktu.

## 📁 Struktur File
- `Final_Project_Smart_Home.ipynb`: Notebook utama berisi seluruh pipeline data mining.

## 🚀 Cara Menjalankan
1.  **Clone Repository**
2.  **Siapkan Environment**
    ```bash
    python -m venv .venv
    .venv\Scripts\activate
    pip install pandas numpy matplotlib seaborn scikit-learn notebook
    ```
3.  **Download Dataset**
    - Karena ukuran file > 100MB, dataset tidak disertakan di repo ini.
    - Unduh dataset **"Smart Home Dataset with Weather Information"** dari Kaggle.
      Link : https://www.kaggle.com/datasets/jamshaid1202/smart-home-energy-consumption-and-weather-data
    - Simpan file `Smart Home Dataset.csv` ke dalam folder `data/`.
4.  **Jalankan Notebook**
    Buka `Final_Project_Smart_Home.ipynb` di VS Code atau Jupyter Notebook.

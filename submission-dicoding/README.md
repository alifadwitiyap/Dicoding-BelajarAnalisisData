# Bike Sharing Dashboard

Sistem berbagi sepeda adalah generasi baru dari penyewaan sepeda tradisional yang menjadikan proses dari keanggotaan, penyewaan, dan pengembalian menjadi otomatis. Dengan sistem ini, pengguna dapat dengan mudah menyewa sepeda dari satu lokasi dan mengembalikannya di lokasi lain. Saat ini, terdapat lebih dari 500 program berbagi sepeda di seluruh dunia yang terdiri dari lebih dari 500.000 sepeda. Pada projek ini, kita akan menganalisis data dari sistem berbagi sepeda dan membuat dashboard interaktif untuk memvisualisasikan hasil analisis data.

## Struktur Proyek

- **dashboard/**: Berisi kode sumber untuk dashboard berbagi sepeda.
  - **src/app.py**: File utama untuk menjalankan aplikasi dashboard.
  - **src/data/**: Berisi data yang telah dibersihkan.
  - **requirements.txt**: Daftar dependensi Python untuk proyek ini.
- **dataset/**: Berisi dataset mentah dan yang telah dibersihkan.
- **Proyek_Analisis_Data.ipynb**: Notebook Jupyter untuk analisis data.
- **requirements.txt**: Daftar dependensi Python untuk proyek ini.

## Dataset

- **day.csv**: Dataset harian mentah.
- **hour.csv**: Dataset per jam mentah.
- **day_clean.csv**: Dataset harian yang telah dibersihkan.
- **hour_clean.csv**: Dataset per jam yang telah dibersihkan.

## Cara Menjalankan

1. Pastikan Anda telah menginstal semua dependensi yang diperlukan dengan menjalankan:

    ```sh
    pip install -r requirements.txt
    ```

2. Untuk menjalankan dashboard, navigasikan ke direktori  dan jalankan:

    ```sh
   streamlit run dashboard/src/app.py
    ```

    


# final-project
### Tentang Proyek:
Proyek ini berfokus pada proses data wrangling yang dilakukan terhadap dataset hotels yang berisi data mengenai booking hotel disertai dengan EDA yang bertujuan untuk mendapatkan insight dari data yang telah diproses kembali. Ini merupakan bagian akhir dari mata kuliah Teknik Sampling dan Data Wrangling

### Kelompok 3: 
Jason Alexander Widodo | 5052241001 

Constantine Calvin | 5052241010 

Affriza Wildan | 5052241033 

Dimas Rizki Gemilang | 5052241040

### Setup Environment:
Proyek ini dirancang untuk dijalankan di Google Colab dengan lingkungan Python yang sudah siap pakai. Oleh karena itu, tidak diperlukan setup lokal
1. Semua package dan library Python sudah dicantumkan dalam requirements.txt
2. Menyiapkan lingkungan, hanya perlu menjalankan cell pertama yang tersambung ke GitHub secara langsung, ini akan melakukan instalasi semua dependensi yang dibutuhkan

### Cara Menjalankan Proyek:
1. Buka Notebook di Colab
2. Jalankan cell instalasi: pastikan cell pertama dari notebook sudah terjalankan, ini bertujuan untuk menginstalasi semua library yang dibutuhkan untuk menjalankan library dari requirements.txt
3. Untuk mendapatkan hasil dari data yang sudah dilakukan preprocessing, dapat dilihat pada bagian files di google colab dengan nama "data_clean.csv"

### Struktur File:
final-project/

├── data/

│   ├── raw/                 # Berisi data mentah awal yang diunduh.

│   └── processed/           # Berisi data hasil pembersihan (data_clean.csv).

├── notebooks/

│   └── final_project.ipynb  # Notebook utama yang berisi seluruh alur kerja (cleaning, analysis, modeling).

├── requirements.txt         # Daftar paket dan library Python yang diperlukan.

└── README.md                # Dokumentasi proyek (file ini).

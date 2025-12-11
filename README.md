# Analisis Tren Kehadiran Penonton NFL

Final Project Mata Kuliah Teknik Sampling dan Data Wrangling.

## Anggota Kelompok
1. Keira Myeisharinna Putri Pujowinarso (50522231006)
2. Muhammad Rayvan Guevhara Pinardhi (5052231029)
3. Ghalib Ibrahim Zardy (5052231028)
3. Regina Avril Putri Pribadi  (5052231021)

## Deskripsi Proyek
Proyek akhir ini bertujuan untuk melakukan Analisis Eksploratif (EDA) terhadap tren kehadiran penonton (attendance) pada pertandingan NFL (National Football League) selama periode tahun 2000 hingga 2019. Kami menggabungkan tiga dataset terpisah (attendance.csv, games.csv, dan standings.csv) untuk mendapatkan wawasan komprehensif mengenai faktor-faktor yang mempengaruhi minat penonton datang ke stadion.

Fokus Utama Analisis:
1. Tren Historis: Melihat fluktuasi rata-rata jumlah penonton dari musim ke musim.
2. Dampak Performa Tim: Menganalisis korelasi antara jumlah kemenangan (wins) dan skor pertandingan terhadap tingkat kehadiran penonton.
3. Loyalitas Fans: Mengidentifikasi tim dengan basis penonton paling stabil dan paling fluktuatif.

Highlight Proses Data Wrangling: Tantangan teknis utama dalam proyek ini yang telah diselesaikan meliputi:
- Handling Team Relocation: Menstandarisasi nama tim yang berpindah kota (contoh: San Diego Chargers disatukan menjadi Los Angeles Chargers, St. Louis Rams menjadi Los Angeles Rams) agar analisis tren tetap konsisten.
- Advanced Merging: Menggabungkan dataset kehadiran mingguan dengan data hasil pertandingan dan klasemen tahunan menggunakan teknik Left Join dengan kunci gabungan (Team, Year, Week).
- Feature Engineering: Menghitung skor tuan rumah (home score) berdasarkan status pemenang pertandingan.
- Data Cleaning: Menangani missing values akibat minggu libur (bye weeks) dan standarisasi tipe data.

## Cara Menjalankan (Reproducibility)
1. Clone repository: `git clone https://github.com/keirasharinna/nfl-attendance-analysis`
2. Install library: `pip install -r requirements.txt`
3. Buka folder `notebooks` dan jalankan `final_project.ipynb`.

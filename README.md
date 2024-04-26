# Analisis Risiko Kredit untuk Pengajuan Kartu Kredit
## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis risiko kredit bagi pelanggan yang mengajukan permohonan kartu kredit di sebuah bank. Tujuannya adalah untuk memprediksi apakah pelanggan akan gagal bayar atau tidak berdasarkan berbagai atribut demografis dan finansial.
## Tujuan Proyek
- Memprediksi kemungkinan gagal bayar pada pelanggan yang mengajukan kartu kredit baru.
- Mengidentifikasi faktor-faktor yang mempengaruhi risiko kredit.
- Mengembangkan model prediktif untuk membantu bank dalam pengambilan keputusan kredit.
- Menentukan model terbaik untuk memprediksi gagal bayar dari beberapa algoritma yang berbeda.
- Mengimplementasikan model terbaik untuk memprediksi risiko kredit pelanggan baru.
## Langkah-Langkah Proyek
1. Pemahaman Data
    - Mengimpor data dari file CSV dan meninjau struktur dan atributnya.
    - Menentukan variabel independen dan variabel dependen.
    - Mengidentifikasi nilai yang hilang dan memperbaiki inkonsistensi dalam data.
2. Analisis Eksploratif
    - Menggunakan visualisasi boxplot untuk mengidentifikasi outlier dalam data.
    - Menganalisis distribusi variabel independen dan dependen untuk memahami pola yang ada.
    - Menentukan apakah beberapa variabel memiliki korelasi dengan gagal bayar.
3. Pemodelan Data
    - Memisahkan data menjadi set pelatihan dan set pengujian (70% pelatihan, 30% pengujian).
    - Menerapkan berbagai algoritma machine learning untuk klasifikasi: Decision Tree, Random Forest, XGBoost, Logistic Regression, dan Support Vector Machine (SVM).
    - Mengukur kinerja setiap model dengan metrik akurasi, presisi, dan recall.
## Model Terbaik dan Implementasi
- Memilih model terbaik berdasarkan akurasi dan stabilitas hasil.
- Menggunakan model terbaik untuk memprediksi risiko kredit pada data pelanggan baru.
- Menyimpan hasil prediksi dalam file CSV untuk analisis lebih lanjut oleh bank.
## Hasil dan Temuan
- Model Terbaik: SVM dengan akurasi 81% dan presisi 82%.
- **Faktor-Faktor yang Mempengaruhi Risiko Kredit**: Atribut yang paling signifikan adalah usia, tingkat pendidikan, dan rasio utang terhadap pendapatan.
- **Distribusi Pelanggan**: Analisis menunjukkan bahwa sebagian besar pelanggan yang gagal bayar berada dalam rentang usia 20-35 tahun dengan tingkat pendidikan rendah.
- **Prediksi untuk Pelanggan Baru**: Dari 150 pelanggan baru yang mengajukan kartu kredit, 127 diterima, dan 23 ditolak berdasarkan prediksi model SVM.
## Kesimpulan
Proyek ini memberikan solusi efektif untuk membantu bank dalam meminimalkan risiko kredit dengan menggunakan model prediktif yang telah diuji dan terbukti akurat. Model ini membantu bank dalam menentukan apakah permohonan kartu kredit oleh pelanggan baru sebaiknya diterima atau ditolak berdasarkan atribut demografis dan finansial. Dengan informasi ini, bank dapat mengurangi risiko gagal bayar dan membuat keputusan kredit yang lebih tepat. Proyek ini juga menunjukkan bahwa analisis risiko kredit dapat memberikan wawasan yang berguna bagi bank untuk meningkatkan strategi kredit dan mengurangi kerugian akibat gagal bayar.

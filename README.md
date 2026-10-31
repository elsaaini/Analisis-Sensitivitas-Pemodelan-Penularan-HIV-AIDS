# Analisis Sensitivitas Penularan Virus HIV-AIDS dengan Pengaruh Terapi Antiretroviral
## Latar Belakang
Proyek ini bertujuan untuk mengidentifikasi parameter-parameter yang berpengaruh signifikan terhadap bilangan reproduksi dasar. ($\mathcal{R}_0$) dalam model matematika penularan virus HIV. Nilai ($\mathcal{R}_0$) merupakan rata-rata jumlah individu baru yang terinfeksi HIV akibat satu individu terinfeksi dalam populasi yang sepenuhnya rentan.
## Variabel dan Parameter
$S(t)$ & Jumlah individu sehat yang rentan terkena HIV pada waktu $t$ \\ \hline
$I(t)$ & Jumlah individu terinfeksi HIV pada waktu $t$ \\ \hline
$A(t)$ & Jumlah individu terinfeksi AIDS pada waktu $t$ \\ \hline
$C(t)$ & Jumlah individu yang sedang menjalani terapi ART pada waktu $t$ \\ \hline
[Download Dataset Excel](./main/dataset%20gojek.xlsx)
## Tools
* Excel
* SPSS
## Tahapan Analisis
1. Menentukan Skala Likert
   > Skala 1-5 (Sangat tidak setuju - Sangat setuju)
2. Menentukan Karakteristik Responden
   > Proyek mengambil ambang batas 3 yaitu akan bernilai 1 jika ≥ 3 dan bernilai 0 jika < 3.
3. Uji Validitas dan Hipotesis untuk Variabel Penelitian
4. Pembentukan Model
   * Backward Selection dan Melakukan Uji Wald
   * Uji Signifikansi Konstanta sebagai pembanding
   * Omnibus Test
   * Model Summary untuk memilih model terbaik
   * Dilakukan Hosmer dan Lemeshow test
   * Diperoleh model terbaik
5. Dilakukan ketepatan klasifikasi untuk model terbaik

## Kesimpulan
Dari hasil analisis regresi logistik berganda, dapat disimpulkan bahwa harga, kualitas pelayanan, dan promosi berkontribusi secara signifikan terhadap kepuasan mahasiswa Matematika UGM dalam menggunakan jasa Gojek. Model yang dihasilkan menunjukkan bahwa peningkatan dalam variabel-variabel tersebut berpotensi meningkatkan kepuasan pengguna.

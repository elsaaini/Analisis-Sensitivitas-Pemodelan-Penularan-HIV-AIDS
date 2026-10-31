# Analisis Sensitivitas Penularan Virus HIV-AIDS dengan Pengaruh Terapi Antiretroviral
## Latar Belakang
Proyek ini bertujuan untuk mengidentifikasi parameter-parameter yang berpengaruh signifikan terhadap bilangan reproduksi dasar ($\mathcal{R}_0$) dalam model matematika penularan virus HIV. Nilai $\mathcal{R}_0$ merupakan rata-rata jumlah individu baru yang terinfeksi HIV akibat satu individu terinfeksi dalam populasi yang sepenuhnya rentan.
## Variabel dan Parameter
* Variabel
  
| Variabel | Keterangan |
|----------|--------|
| $S(t)$ | Jumlah individu sehat yang rentan terkena HIV pada waktu $t$ |
| $I(t)$ | Jumlah individu terinfeksi HIV pada waktu $t$ |
| $A(t)$| Jumlah individu terinfeksi AIDS pada waktu $t$ |
| $C(t)$ | Jumlah individu yang sedang menjalani terapi ART pada waktu $t$

* Parameter
  
| Parameter | Keterangan |
|----------|--------|
| $\Omega$ | Laju masuk individu baru ke subpopulasi rentan |
| $\alpha_1$ | Laju penularan HIV dari individu yang terinfeksi HIV |
| $\alpha_2$ | Laju penularan HIV dari individu yang terinfeksi AIDS |
| $\alpha_3$ | Laju penularan HIV dari individu yang menjalani terapi ART |
| $\eta$ | Laju transisi individu HIV menjadi AIDS |
| $\rho_1$ | Laju individu terinfeksi HIV yang mendapatkan terapi ART |
| $\rho_2$ | Laju individu AIDS yang mendapatkan terapi ART |
| $\gamma_1$ | Laju kematian akibat HIV |
| $\gamma_2$ | Laju kematian akibat AIDS |
| $\gamma_3$ | Laju kematian saat menerima ART |
| $\mu$ | Laju kematian secara alami |

## Rumus Bilangan Reproduksi Dasar
$$ \mathcal{R}_0 = \frac{\Omega(\eta(\alpha_2K_3 +\alpha_3\rho_2) + K_2(\alpha_1K_3+ \alpha_3\rho_1))}{K_1K_2K_3\mu} $$
## Tools
* Python
## Tahapan Analisis
1. Definisi parameter sebagai simbol
2. Definisi R0
3. Menghitung turunan paarsial tiap parameter
4. Menghitung sensitivitas normalisasi
5. Visualisasi hasil normalisasi dengan grafik
6. Memilih parameter yang signifikan
7. Melihat hubungan parameter dengan $\mathcal{R}_0$

## Kesimpulan
Dari hasil analisis sensitivitas dapat disimpulkan bahwa parameter yang berpengaruh terhadap penularan virus HIV/AIDS dengan mempertimbangkan terapi antiretroviral adalah laju penularan HIV dari individu terinfeksi HIV, laju penularan HIV dari individu yang terapi, laju perpindahan individu HIV menjadi AIDS, dan laju individu terinfeksi HIV mendapatkan terapi ART. Jika laju penularan naik maka rata-rata individu terinfeksi juga akan menularkan virus ke individu rentan lebih banyak dan jika laju individu HIV menjadi AIDS serta laju individu mendapatkan terapi ditingkatkan maka akan menurunkan rata-rata penularan virus.

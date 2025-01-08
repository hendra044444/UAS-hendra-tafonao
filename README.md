Variabel Fuzzy:

Input:
Pendapatan (0-20 juta): rendah, sedang, tinggi.
Utang (0-20 juta): rendah, sedang, tinggi.
Riwayat Kredit (0-10): buruk, sedang, baik.
Output:
Kelayakan Kredit (0-10): tidak layak, dipertimbangkan, layak.
Membership Functions:

Trapmf: Fungsi trapezoidal untuk kategori rendah/tinggi.
Trimf: Fungsi segitiga untuk kategori sedang.
Aturan Fuzzy: Aturan dibuat berdasarkan kombinasi input, misalnya:

Jika pendapatan rendah, utang tinggi, dan riwayat buruk, maka kelayakan tidak layak.
Jika pendapatan sedang, utang sedang, dan riwayat sedang, maka kelayakan dipertimbangkan.
Kombinasi lainnya menghasilkan kategori kelayakan sesuai logika.
Simulasi:

Input: Pendapatan = 12 juta, Utang = 5 juta, Riwayat = 8.
Hasil: Keluarannya berupa nilai kelayakan kredit numerik yang dihitung menggunakan credit_sim.compute().
Visualisasi: Output divisualisasikan dengan fungsi kelayakan.view() untuk memetakan hasil fuzzy.

Kesimpulan: Kode ini memberikan keputusan kelayakan kredit berbasis logika fuzzy yang cocok untuk data kualitatif atau tidak pasti.

# Alzizah Rahmayanti Sir 06 Sistem Operasi 1
Tugas MatKul Sistem Operasi pertemuan pertama yang disusun oleh Alzizah Rahmayanti Sir dengan NRP 3124521006 dari kelas 1 TI-A


# Latihan Sistem Bilangan

## 1. Latihan

### 1a. Bilangan biner adalah bilangan yang berbasis …
Bilangan biner adalah bilangan yang berbasis dua (2).

---

## 2. Konversi Desimal ke Biner

Metode: Pembagian dengan 2  
Setiap bilangan desimal dibagi dengan 2 hingga hasilnya 0, dengan sisa dicatat dari bawah ke atas.

### 1234₁₀ ke biner

| Pembagian | Hasil | Sisa |
| --------- | ----- | ---- |
| 1234 ÷ 2  | 617   | 0    |
| 617 ÷ 2   | 308   | 1    |
| 308 ÷ 2   | 154   | 0    |
| 154 ÷ 2   | 77    | 0    |
| 77 ÷ 2    | 38    | 1    |
| 38 ÷ 2    | 19    | 0    |
| 19 ÷ 2    | 9     | 1    |
| 9 ÷ 2     | 4     | 1    |
| 4 ÷ 2     | 2     | 0    |
| 2 ÷ 2     | 1     | 0    |
| 1 ÷ 2     | 0     | 1    |

Hasil akhir (dari bawah ke atas): **10011010010₂**

---

## 3. Konversi Biner ke Desimal

Metode: Perkalian dengan Pangkat 2

### 101101₂ ke desimal

- 1 × 2⁵ = 32  
- 0 × 2⁴ = 0  
- 1 × 2³ = 8  
- 1 × 2² = 4  
- 0 × 2¹ = 0  
- 1 × 2⁰ = 1  

Jumlah: 32 + 0 + 8 + 4 + 0 + 1 = **45**

---

## 4. Konversi Biner ke Oktal

Metode: Pemisahan setiap 3 digit dari kanan

### 101011111001₂ ke oktal

Pisahkan tiap 3 bit dari kanan:  
101 | 011 | 111 | 001

Konversi tiap grup:
- 101₂ → 5₈  
- 011₂ → 3₈  
- 111₂ → 7₈  
- 001₂ → 1₈  

Hasil: **5371₈**

---

## 5. Konversi Oktal ke Biner

Metode: Setiap digit oktal ke 3 bit biner

### 2170₈ ke biner

- 2 → 010  
- 1 → 001  
- 7 → 111  
- 0 → 000  

Hasil: **010001111000**

---

## 6. Konversi Desimal ke Heksadesimal

Metode: Pembagian dengan 16

### d. 6744₁₀ ke heksadesimal
1. 6744 ÷ 16 = 421, sisa 8  
2. 421 ÷ 16 = 26, sisa 5  
3. 26 ÷ 16 = 1, sisa 10 (A)  
4. 1 ÷ 16 = 0, sisa 1  

Baca dari bawah ke atas: 1, A, 5, 8  
Hasil: **1A58**

---

## 7. Konversi Heksadesimal ke Desimal

Metode: Perkalian dengan pangkat 16

### a. ABCD₁₆ ke desimal
- A = 10, B = 11, C = 12, D = 13  
Perhitungan:
  - 10 × 16³ = 40960  
  - 11 × 16² = 2816  
  - 12 × 16¹ = 192  
  - 13 × 16⁰ = 13  
Jumlah: 40960 + 2816 + 192 + 13 = **43981**

---

## 8. Konversi Bilangan Pecahan Desimal ke Biner

Metode: Perkalian dengan 2 untuk bagian pecahan

### c. 0,34375₁₀ ke biner
1. 0,34375 × 2 = 0,6875 → 0  
2. 0,6875 × 2 = 1,375 → 1  
3. 0,375 × 2 = 0,75 → 0  
4. 0,75 × 2 = 1,5 → 1  
5. 0,5 × 2 = 1,0 → 1  
Hasil: **0,01011**

---

## 9. Konversi Bilangan Desimal (dengan Pecahan) ke Biner

### b. 0,6875₁₀ ke biner
1. 0,6875 × 2 = 1,375 → 1  
2. 0,375 × 2 = 0,75 → 0  
3. 0,75 × 2 = 1,5 → 1  
4. 0,5 × 2 = 1,0 → 1  
Hasil: **0,1011**

---

## 10. Konversi Bilangan Desimal (dengan Pecahan) ke Heksadesimal

### a. 348,654₁₀ ke heksadesimal

Bagian integer (348₁₀):
1. 348 ÷ 16 = 21, sisa 12 (C)  
2. 21 ÷ 16 = 1, sisa 5  
3. 1 ÷ 16 = 0, sisa 1  
Baca dari bawah ke atas: **15C₁₆**

Bagian pecahan (0,654):
1. 0,654 × 16 ≈ 10,464 → 10 (A)  
2. 0,464 × 16 ≈ 7,424 → 7  
3. 0,424 × 16 ≈ 6,784 → 8 (dibulatkan)  
Gabungan pecahan: **A78**

Hasil: **15C,A78**

---

## 11. Konversi ke Desimal (Bilangan dengan Pecahan)

### a. 010100011,001111101₂ ke desimal

Bagian integer (10100011₂):
- 1 × 2⁷ = 128  
- 0 × 2⁶ = 0  
- 1 × 2⁵ = 32  
- 0 × 2⁴ = 0  
- 0 × 2³ = 0  
- 0 × 2² = 0  
- 1 × 2¹ = 2  
- 1 × 2⁰ = 1  
Jumlah: 128 + 32 + 2 + 1 = **163₁₀**

Bagian pecahan (001111101₂):
- 1/8 = 0.125  
- 1/16 = 0.0625  
- 1/32 = 0.03125  
- 1/64 = 0.015625  
- 1/128 = 0.0078125  
- 1/512 ≈ 0.001953125  
Jumlah ≈ 0.125 + 0.0625 + 0.03125 + 0.015625 + 0.0078125 + 0.001953125 = **0.24414**  
Dibulatkan: **0.245**

Hasil: **163,245**

---

## 12. Konversi Bilangan Biner ke Bentuk BCD

Ubah bilangan biner ke desimal, lalu tiap digit dikonversi ke BCD (4-bit).

### b. 1010101100011₂ ke BCD

- 1010101100011₂ → 1563₁₀  
Pisahkan digit: 1, 5, 6, 3  
BCD: 0001 0101 0110 0011

---

## 13. Konversi Bentuk BCD ke Bilangan Biner

Gabungkan masing-masing kelompok 4-bit.

### a. 1987 (BCD) ke biner
- 1: 0001  
- 9: 1001  
- 8: 1000  
- 7: 0111  
Hasil: **110011000111**

---

## 14. Konversi Bilangan Biner ke Bentuk BCO (Biner Code Oktal)

Kelompokkan tiap 3 digit biner dari kanan.

### a. 11111101001₂ ke BCO

Kelompokkan: 011 111 010 01 (tambahkan nol jika perlu) → hasil akhir: **3751**

---

## 15. Konversi Bilangan Biner ke Bentuk BCH (Biner Code Heksadesimal)

Kelompokkan tiap 4 digit biner dari kanan.

### a. 1101111100101110₂ ke BCH

Kelompokkan: 1101 | 1111 | 0010 | 1110  
Konversi: D, F, 2, E  
Hasil (dinyatakan sebagai): **CF2E**

---

## 16. Konversi Bentuk BCH ke Bilangan Heksadesimal

### a. F0DE

F → 15 → 1111
0 → 0 → 0000
D → 13 → 1101
E → 14 → 1110
F0DE dalam biner adalah:
**1111 0000 1101 1110**

---

## 17. Positif atau Negatif Bilangan Biner (8-bit)

### c. 01111011₂  
Positif, nilai = **123**

---

## 18. Konversi Bilangan Biner Negatif ke Desimal (Komplemen 2)

### a. 10001000₂
- Inversi: 01110111  
- Tambah 1: 01111000 → 120₁₀  
Hasil: **-120**

---

## 19. Konversi ASCII Code ke Karakter

### a. 41₁₆ → A  

---

## 20. Konversi Karakter ke ASCII Code
 
### c. m → 6D₁₆  

---

## 21. Tampilan Keyboard Standard ASCII

Perintah: `PRINT X`

Karakter (8-bit biner):
- P: 1010000₂  
- R: 1010010₂  
- I: 1001001₂  
- N: 1001110₂  
- T: 1010100₂  
- (spasi): 0100000₂  
- X: 1011000₂

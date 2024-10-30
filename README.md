# Praktikum4
## 1. Membuat Class BangunDatar
<img width="298" alt="BangunDatar" src="https://github.com/user-attachments/assets/17677e10-6775-4793-856f-96d0f2bdddf9">

**Penjelasan :**

-**public abstract class BangunDatar**: Mendefinisikan kelas abstrak bernama BangunDatar.
- **public abstract float luas()**: Metode abstrak untuk menghitung luas bangun datar, yang harus diimplementasikan di kelas turunan.
- **public abstract float keliling()**: Metode abstrak untuk menghitung keliling bangun datar, yang juga harus diimplementasikan di kelas turunan.

## 2. Membuat Class Lingkaran
<img width="391" alt="Lingkaran" src="https://github.com/user-attachments/assets/cb873328-c2c9-46e1-afc7-b5c8ab3375d7">

**Penjelasan :**

- **int r**: Variabel instance yang merepresentasikan jari-jari lingkaran.
- Konstruktor **Lingkaran(int r)**: Konstruktor untuk menginisialisasi nilai jari-jari lingkaran.
- **@Override public float luas()**: Implementasi metode luas() dari BangunDatar yang menghitung luas lingkaran
- **@Override public float keliling()**: Implementasi metode keliling() dari BangunDatar yang menghitung keliling lingkaran

## 3. Membuat Class Segitiga
<img width="436" alt="Segitiga" src="https://github.com/user-attachments/assets/89b1b866-5cf3-497a-bd4e-15cfcadce12c">

**Penjelasan :**

- **int alas**: Variabel yang merepresentasikan panjang alas segitiga.
- **int tinggi**: Variabel yang merepresentasikan tinggi segitiga.
- **Konstruktor Segitiga(int alas, int tinggi)**: Konstruktor ini menginisialisasi nilai alas dan tinggi segitiga.
- **@Override public float luas()**: Metode ini menghitung luas segitiga menggunakan rumus
- **@Override public float keliling()**: Metode ini menghitung keliling segitiga dengan asumsi bahwa segitiga adalah sama sisi

## 4. Membuat Class Persegi
<img width="314" alt="Persegi" src="https://github.com/user-attachments/assets/eb30c1c1-798b-4216-8d81-7b6ca1c6f34d">

**Penjelasan :**

- **int sisi**: Variabel yang merepresentasikan panjang sisi persegi.
- **Konstruktor Persegi(int sisi)**: Konstruktor ini menginisialisasi nilai panjang sisi persegi.
- **@Override public float luas()**: Metode ini menghitung luas persegi dengan rumus sisi×sisi.
- **@Override public float keliling()**: Metode ini menghitung keliling persegi dengan rumus 4×sisi.

## 5. Membuat Class Utama
<img width="471" alt="Utama" src="https://github.com/user-attachments/assets/dbaf42ca-fe96-4839-a81a-8d4e13b442f3">

**Penjelasan :**

a. **Membuat Objek Lingkaran:**

- Membuat objek Lingkaran dengan jari-jari 7.
- Memanggil metode luas() dan keliling() untuk menghitung luas dan keliling lingkaran tersebut.

b. **Membuat Objek Segitiga:**

- Membuat objek Segitiga dengan alas 5 dan tinggi 12.
- Memanggil metode luas() dan keliling() untuk menghitung luas dan keliling segitiga (asumsi segitiga sama sisi, keliling = 3 × alas).

c. **Membuat Objek Persegi:**

- Membuat objek Persegi dengan panjang sisi 4.
- Memanggil metode luas() dan keliling() untuk menghitung luas dan keliling persegi.

## Output
<img width="298" alt="Output" src="https://github.com/user-attachments/assets/2597e1aa-a923-4c11-8da9-7b740e9a2ef8">

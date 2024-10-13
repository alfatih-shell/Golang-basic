# Penggunaan Variabel di Go

## Cara Menjalankan
1. Pastikan Go sudah terinstal di komputer Anda.
2. Buka terminal atau command prompt.
3. Arahkan ke direktori `02-variables/`.
4. Jalankan perintah berikut:
> go run main.go
5. Anda akan melihat output berikut:
> Nama: Riyan Umur: 25 Nama baru: Pratomo



## Penjelasan Program

1. **Deklarasi Variabel dengan `var`**: 
   ```go
   var nama string = "Riyan"
   ```
   - **Deskripsi**: Variabel `nama` dideklarasikan dengan tipe data `string` secara eksplisit dan diberi nilai awal "Riyan".

2. **Deklarasi Variabel dengan `:=`**: 
   ```go
   umur := 25
   ```
   - **Deskripsi**: Menggunakan notasi `:=` untuk mendeklarasikan variabel `umur`. Go otomatis mengenali tipe data dari nilai awal (dalam hal ini, `int`).

3. **Mencetak Nilai Variabel**: 
   ```go
   fmt.Println("Nama:", nama)
   fmt.Println("Umur:", umur)
   ```
   - **Deskripsi**: Kedua baris ini mencetak nilai dari variabel `nama` dan `umur` ke terminal.
   - **Output**:
     ```
     Nama: Riyan
     Umur: 25
     ```

4. **Mengubah Nilai Variabel**: 
   ```go
   nama = "Pratomo"
   ```
   - **Deskripsi**: Nilai variabel `nama` diubah dari "Riyan" menjadi "Pratomo". Kemudian, variabel ini dicetak lagi:
   ```go
   fmt.Println("Nama baru:", nama)
   ```
   - **Output**:
     ```
     Nama baru: Pratomo
     ```


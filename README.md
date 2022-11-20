# Praktikum5

## Tugas Praktikum 

Buat program sederhana untuk menambahkan data kedalam sebuah
list dengan rincian sebagai berikut:<br/>
- Progam meminta memasukkan data sebanyak-banyaknya (gunakan
  perulangan)<br/>
- Tampilkan pertanyaan untuk menambah data (y/t?),
  apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya. <br/>
- Nilai Akhir diambil dari perhitungan 3 komponen (tugas:30%,
  uts: 35%, uas: 35%)<br/>
- Buat flowchart dan penjelasan programnya<br/>


### FLOWCHART

Berikut ini adalah Flowchart dari tugas di atas 

![ss4](https://user-images.githubusercontent.com/115479946/202917254-9f3005de-9d1b-4a0e-ada6-28f0b44bbddc.png)

### Penjelasan Program 

Berikut ini adalah program yang di buat menggunakan bahasa python

<img width="959" alt="ss1" src="https://user-images.githubusercontent.com/115479946/202912931-41c9dc6e-6a40-4ade-82e8-512718920fb6.png">

<img width="958" alt="ss2" src="https://user-images.githubusercontent.com/115479946/202912940-1a3bdbc7-b350-4c94-9e08-a7b925810726.png">


Berikut ini Penjelasannya :
- Pertama instal terlebih dahulu <b>PrettyTable</b>	yang sudah disediakan di phyton untuk pembuatan tabelnya dengan cara dengan menggunakan perintah ```pip instal PrettyTable``` pada cli
- Lalu import PrettyTable terlebih dahulu kedalam program kita agar Program bisa digunakan dengan menggunakan perintah 

```python
form prettytable import PrettyTable
```
- Untuk menampilkan kalimat yang di input gunakan perintah 
```python
print("Program Input Data Mahasiswa")
```
- Setelah Program berhasil buatlah tabel dengan menggunakan perintah 

```pyhton
Tabel = PrettyTable(["No", "Nama", "NIM", "Nilai Tugas", "Nilai UTS", "Nilai UAS", "Nilai Akhir"])
a = 0
```
- Memasukkan Input Dengan Fungsi ```input()``` untuk menulis nama yang akan kita simpan dalam variabel.
```int(input())``` untuk menginput tipe data interger dalam variabel. ```a += 1``` untuk menginput nomer pada awal table.
seperti dibawah ini 

 ```python
    a += 1
    b = input("Masukkan Nama : ")
    c = input("Masukkan NIM : ")
    d = int(input("Masukkan Nilai Tugas : "))
    e = int(input("Masukkan Nilai UTS : "))
    f = int(input("Masukkan Nilai UAS :" ))
    g = "{:.2f}".format((d*.30) + (e*.35) + (f*.35))
    ```

- Selanjutnya membuat kondisi jika dimana true (y) maka program meminta user memasukan data sesuai dengan tabel yang dibuat jika Tidak (t) maka program akan menampilkan tabel datanya dimana menggunakan perintah 

```python
n = input("Tambahkan Data? y/t : ")
    if n == "T" or n == "t":
        break
``` 

- untuk menentukan nilai akhir gunakan format sebagai berikut 

```python
akhir = "{:.2f}".format((tugas*.30) + (uts*.35) + (uas*.35))
```
untuk hasilnya akan seperti ini 

<img width="958" alt="ss3" src="https://user-images.githubusercontent.com/115479946/202912946-130ed7d0-a206-4686-885b-02045f3b6839.png">


# Sekian Terima Kasih 
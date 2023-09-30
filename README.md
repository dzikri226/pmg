# Praktikum 1 - Pemograman Web
# Muhammad Dzikri Hidayat
# 312210136
# TI.22.A1

## Langkah Praktikum 
Pertama buka VS Code terlebih dahulu.
![gambar-1][def-1]

[def-1]:  ![Screenshot (13)](https://github.com/dzikri226/pmg/assets/122372727/e95c68b4-d95a-4409-ace2-31da3ba90647)


Lalu buatlah file baru dengan nama `lab1_tag_dasar.html` dan buat struktur HTML-nya lalu pada bagian title ganti dengan `Tag HTML Dasar`.
![gambar-2][def-2]

[def-2]: ![Screenshot (16)](https://github.com/dzikri226/pmg/assets/122372727/bd0a7f80-16eb-4c61-bfaf-65cb74b6f3cb)






Nah selanjutnya, buka file yang sudah dibuat tadi pada web browser.
![gambar-3][def-3]

[def-3]: ![Screenshot (17)](https://github.com/dzikri226/pmg/assets/122372727/7d8de5ca-1fd0-4885-9b93-1c3f2ca44e84)

Kenapa halamannya kosong karena didalam file `lab1_tag_dasar.html` hanya ada tag title yang hanya menampilkan judul sebuah halaman.

Selanjutnya membuat judul dan pargraf, dalam membuat judul menggunakan `tag h1 - h6` untuk membuat paragrafnya menggunakan tag `<p>`.
![gambar-4][def-4]

[def-4]: ![Screenshot (19)](https://github.com/dzikri226/pmg/assets/122372727/810e9d67-1791-44df-9926-eecb1b259cc0)


Lalu juga bisa mengubah-uabh nilai atributnya pada bagian paragraf dengan menggunakan nilai atribut `(align="right", align="left")`
![gambar-5][def-5]

[def-5]: ![Screenshot (19)](https://github.com/dzikri226/pmg/assets/122372727/b9cca0a3-38e6-4129-86d4-965fcfd41b09)


Selanjutnya akan menampilkan gambar pada halaman web, untuk menampilkan gambar/foto pastikan sudah memiliki gambar/foto yang ingin ditampilkan, kemudian buat folder baru yang berada didalam folder `Lab1Web` atau juga bisa simpan file gambar satu folder dengan file dokumen html.
![gambar-6][def-6]

[def-6]: ![Screenshot (21)](https://github.com/dzikri226/pmg/assets/122372727/1f3d09f3-66b2-4216-a537-50d03a43b6a2)



Nah selanjutnya menambahkan gambar pada halam web yang sudah di save sebelumnya dengan memanggil gambar menggunakan tag `<img src="logo_UPB.png" title="Logo Universitas Pelita Bangsa">`.
![gambar-7][def-7]

[def-7]: ![screnshoot (33)](https://github.com/dzikri226/pmg/assets/122372727/1e42a38f-9824-4af4-9221-16e056011dde)



Selanjutnya membuat `Hyperlink` untuk menghubungkan halam satu dengan halaman lain, tambahkan hyperlink sebelum heading 1 seperti berikut dan buat dokumen HTML baru didalam folder Lab1Wb.
![gambar-8][def-8]

[def-8]: ![ (ss10)](https://github.com/dzikri226/pmg/assets/122372727/23a8cb9f-309e-44cc-b0eb-cdfddc4595a8)


Halaman ke-2
![gambar-11][def-11]

[def-11]: /image/ss11.png

## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah _error_ ketika terjadi kesalahan punulisan tag?
```
Pada saat saya menuliskan kode tag <p> namun lupa memberikan tag penutup </p> maka terjadi error senggingga bahasa mesin tidak dapat mengenalinya tetapi teks akan tetap ditampilkan dalam tampilan halaman web.
```
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
```
Tag <p> digunakan untuk membuat paragraf teks yang terstruktur, sementara tag <br> digunakan untuk membuat jeda baris di dalam teks.
```
3. Apa perbedaan atribut `title` dan `alt` pada tag `<img>`, berikan penjelasannya!
```
Atribut alt digunakan untuk memberikan teks alternatif untuk gambar, sementara atribut title digunakan untuk memberikan informasi tambahan atau tooltip saat kursor mouse mengarah ke gambar.
```
4. Untuk mengatur ukuran gambar, digunakan atribut `width` dan `height`. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Jika ingin menjaga proporsional gambar lebih baik mengisi hanya satu dari kedua atribut tersebut atau bisa juga menggunakan resaiz pada gambar seuai yang diinginkan 
```
5. Pada `link` tambahkan atribut `target` dengan nilai atribut bervariasi ( `_blank`, `_self`, `_top`, `_parent` ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
target _blank membuka halaman baru
target _self membuka halam ini dijendela/ditab yang sama
target _top buka halaman utama
target _parent buka halaman di frame induk
```

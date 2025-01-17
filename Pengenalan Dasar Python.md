# 1. Instalasi IDLE untuk Python 2.7

Mari kita mulai instalasi IDLE untuk editor Python kita. 

### Untuk Linux

```
sudo apt-get install idle
```

### Untuk Windows

Unduh dan install idle dari [tautan berikut](https://www.python.org/downloads/release/python-2714/)

### Untuk MacOS

Unduh dan install dari [tautan berikut](https://www.python.org/downloads/release/python-2714/)


----

# 2. Aplikasi IDLE sebagai editor Python 2.7

Tekan tombol `Command` atau tombol `Windows` pada keyboard,  dan ketikkan `IDLE`, Pilih `IDLE (using Python-2.7) ` 

Tampilan pencarian editor IDLE seperti gambar dibawah ini.

<img src="Gambar/Idle.png">

## + Tampilan awal IDLE

Pada awal Idle dibuka, Anda akan melihat sebuah jendela dengan judul `Pyhton 2.7 Shell`. 
Jendela ini merupakan jendela perintah (console) dari Idle tersebut. 
Fungsinya adalah menjalankan perintah-perintah python diluar code python utama atau untuk memasukkan masukan data untuk diolah lagi pada code utama.

Apabila Anda langsung melakukan operasi pada console tersebut, console akan langsung memberikan keluaran dari masukan yang Anda berikan, semisal pada gambar berikut.

<img src="Gambar/Penggunaan Console.png">

## + Bermain menggunakan console Pyhton

Tanda `>>>` merupakan masukan console dalam keadaan standby dan siap untuk diberikan perintah.

Apabila Anda menekan ` Enter ` beberapa kali, maka console tidak memberikan nilai balikan.

+ ### Bagaimana jika kita memasukkan sebuah angka?

Semisal masukkan angka sesuai dengan tanggal pada hari ini. Semisal `16042019` berikut variasinya. Maka tampilan balikan dari console python tersebut seperti gambar berikut ini. 

Untuk penggunaan angka desimal, pada Python, ditandai menggunakan tanda titik ` . ` bukan koma ` , `.

<img src="Gambar/Penggunaan Console Angka.png">


## + Menggunakan Python sebagai kalkulator (alat hitung)

Coba masukkan operasi sederhana pada console Python yang ada, semisal :

```python
15 + 6

70 - 43

14 * 3

13 / 3

13. / 3.
```

Untuk hasil dari perhitungan sederhana diatas, lebih kurang akan menghasilkan operasi seperti gambar berikut

<img src="Gambar/Hitung Sederhana.png">

<b>*) </b>Agar penulisan kode lebih mudah terbaca, biasanya diberikan `[spasi]` sebelum dan sesudah operator. Seperti format berikut:
```
Angka [spasi] [operator] [spasi] Angka

```



## + Komentar pada Pyhton

Penggunaan kometar pada Python diawali dengan tanda tagar ` # ` dengan di lanjutkan dengan isi pesan komentarnya atau sekedar untuk mengabaikan kode yang tidak digunakan pada program. 

Contoh: 

```python
#Ini adalah contoh komentar pada Python

5 + 4 #Proses penambahan 5 dan 4
```

Untuk hasil penulisan diatas akan menghasilkan keluaran seperti gambar dibawah ini


<img src="Gambar/Komentar Pada Console.png">

## + Variabel

Variabel dalam Python merupakan sebuah tempat atau wadah yang di dalamnya dapat diisikan sebuah nilai atau digantikan dengan nilai yang terbaru. Sifat wadah ini tidak konstan atau dapat berubah.

Contoh penulisan variabel pada Python sebagai berikut:

```python
a = 12
b = 9

c = a + b
```

<img src="Gambar/Penulisan Variabel.png">

Pada ` a = 12 ` , nilai `12` dimasukkan pada wadah yang akan disebut dengan `a`. Begitu pula pada ` b = 9 ` , nilai `9` dimasukkan pada wadah yang akan disebut dengan `b`. Sehingga pada wadah ` c `, berisikan operasi pertambahan antara variabel ` a + b `.

<b> *) </b>Untuk menampilkan isi dari variabel pada console, dapat dituliskan nama variabel tersebut pada masukan console.


+ ### Merubah isi variabel

Untuk merubah isi dari variabel yang sudah ada sebelumnya, kita dapat mengubahnya dengan memasukkan nilai  terbaru dari variabel yang sama. Semisal kita akan merubah variabel `a` dengan nilai `15`, maka kurang lebih penulisannya seperti  berikut ` a = 15 `

Untuk hasil ` a + b ` setelah variabel `a` diperbarui menjadi `24` seperti gambar dibawah ini.

<img src="Gambar/Pengubahan Variabel2.png">

+ ### Operasi dengan variabel itu sendiri

Pada operasi ini, sebuah variabel akan dioperasikan dengan variabel yang sama hanya saja berbeda pada posisi  urutan eksekusi pada iterasi. Semisal pada kode berikut:

```python

a = 10
a = a + 5

```
<img src="Gambar/Penambahan sendiri.png">

atau dengan menggunakan `+=`, `-=`, `*=`, dan `/=`. 

```python
a = 10   #Inisialisasi variabel a

a += 3   # a = a + 3
a -= 4   # a = a - 4
a *= 5   # a = a * 5
a /= 6   # a = a / 6

```

<img src="Gambar/OperasiSendiri.png">

+ ### Variabel dalam string / kata

Pada penulisan variabel, tidak hanya dapat diisikan dengan angka, pun bisa dalam bentuk string atau kata. Semisal: 

``` python
a = 'Saya' 
b = 'Belajar'
c = 'Python' 

a + b + c
```

<img src="Gambar/Saya Belajar Pyhon.png">

Untuk variasi penulisan lainnya:

```python
a *= 3
a += 'Semangat'
a + b + c

```
<img src="Gambar/SemangatBelajar.png">

+ ### Penulisan variabel yang baik dan buruk

Untuk penulisan variabel, sebaiknya dalam format huruf kecil semua (lowercase). Ketika terdiri dari dua buah kata, sebaiknya diberi underscore `_` sebagai penghubung keduanya. 

Untuk penulisan variabel yang baik seperti berikut ini:

```python
panjang_bangunan = 100
lebar_bangunan = 50
luas = panjang_bangunan * lebar_bangunan
```

Contoh yang buruk:

```python
panjangBangunan = 1000   # Sulit terbaca
LebarBangunan = 50       # Aneh juga dalam pembacaannya
Luas =  1000 * 50        # Huruf besar pada awal variabel, biasanya digunakan pada sistem Python
x = 'Luas Keduanya'      # Variabel x sering digunakan untuk koordinat


```

+ ### Nilai Boolean

Nilai Boolean merupakan nilai yang berisikan dua tipe, yaitu  `True` dan `False`. Pada Python dan kebanyakan bahasa pemograman lainnya, tanda `=` berarti memasukkan nilai kepada variabel dan tanda `==` merupakan operator pembanding atau kondisi. `a = 3` merupakan `a` diisikan nilai `3`, sedangkan  `a == 3` merupakan kondisi "Apakah `a` berisikan `3` ?", oleh karenannya, nilai balikannya adalah `True` atau `False`. Coba kode berikut ini:

```python
a = 3
a == 3
a == 1
```

maka, hasilnya akan seperti berikut.


<img src="Gambar/aAdalah3.png">

penulisan `a == 3` memiliki fungsi yang sama dengan `(a == 3)`. Akan tetapi, `a == 3` lebih terbaca daripada `(a == 3)`. Sehingga, pada beberapa kondisi penulisan seperti `== True`.

```python
a = 2
a == 2
(a == 2)
(a == 2) == True
(a == 2) == False
(a == 1) == True
```
maka hasilnya akan seperti berikut.


<img src="Gambar/TrueFalseA.png">


+ ### Penulisan operator pembanding lainnya

Selain penggunaan `==`, ada beberapa operator pembanding lainnya, yaitu:

| Operator  | Deskripsi                         | Contoh untuk `True`   |
|-----------|-----------------------------------|-----------------------|
| `a == b`  | a sama dengan b                   | `1 == 1`              |
| `a != b`  | a tidak sama dengan b             | `1 != 2`              |
| `a > b`   | a lebih besar daripada b          | `2 > 1`               |
| `a >= b`  | a lebih besar atau sama dengan b  | `2 >= 1`, `1 >= 1`    |
| `a < b`   | a kurang dari b                   | `1 < 2`               |
| `a <= b`  | a kurang dari atau sama dengan b  | `1 <= 2`, `1 <= 1`    |


+ ### Nilai None

Nilai `None` merupakan sebuah nilai yang bermakna `Kosong` atau tanpa nilai. Nilai `Kosong` bukan berarti `Nol` atau  `0`. Nilai `None` pada Python lebih kepada `Null` pada bahasa pemograman lainnya. 

Semisal:
```python
b = None      # Beri None pada variabel b
b             # Tampilkan isi dari variabel b

print b       # Print isi dari variabel b

```
maka hasilnya akan seperti berikut.
<img src="Gambar/VariabelNone.png">

## + Fungsi `print` pada Python

`print` merupakan sebuah fungsi pada Python untuk menampilkan segala jenis hasil operasi ataupun variabel pada layar. Semua jenis data dapat ditampilkan dalam bentuk 'mentah' atau RAW data. Fungsi ini biasanya sangat berguna untuk proses debug ataupun mengetahui proses pengolahan nilai atau operasi pada tiap tahapannya. Fungsi ini sangat berguna pada kode yang lebih banyak nantinya. 

```python
c = 23

print (c)

print (c + 5)

print (c, "lebih kecil dari", c + 7)

print ("Joko Tole \nbersama temannya")

teman = "Jaka Tarub"

print ("Joko Tole \nbersama temannya\n" + teman)
```
<img src="Gambar/fungsiPrint3.png">



---


# 3. Editor Pada IDLE

Editor pada IDLE berbeda dengan consolenya. Editor ini merupakan sebuah jendela dokumen untuk menuliskan dan memodifikasi kode python kita. Dokumen ini nantinya akan disimpan menjadi format `[ *.py ]`

Untuk membuat sebuah dokumen Python baru, Anda dapat menekan tombol `Ctrl+N` pada keyboard atau klik `File > New File ` pada jendela Python Shell, setelah itu Anda akan diperlihatkan jendela editor kode. Pada jendela ini nantinya kode Python akan ditulilskan. Gambar berikut adalah perbedaan antara jendela console dengan jendela editor Python.

Untuk menyimpan dokumen tersebut, Anda dapat menekan tombol `Ctrl + S` pada keyboard atau `File > Save` pada jendela editor. Pada gambar berikut, dokumen baru yang telah dibuat, disimpan dengan nama `DokumenBaru.py`.

<img src="Gambar/EditorDanConsole.png">

## + Menjalankan program dari editor

Menjalankan program Python yang sudah ditulis pada editor, dapat menekan tombol `F5` pada keyboard atau klik `Run > Run Module` pada menu bar editor IDLE. 

Semisal kita akan menjalankan sebuah program untuk memasukkan sandi yang sederhana menggunakan fungsi `if - else` berikut ini. 

```python
print("Halo Bro!")

nama = raw_input("Namamu siapa? :")
print ("Halo " + nama + '!')

password = input("Masukkan angka sandinya... : ")
if password == 1234:
    print("Sandi benar! \nSelamat datang " + nama + " di program ini.")
else:
    print(nama + ", sandinya salah. \nAkses ditolak!")

```

Maka program Python yang telah dijalankan akan meminta masukan nama user dan password kepada user. Apabila password benar yaitu `1234`, maka program akan memberikan balikan berupa kalimat `Sandi benar! Selamat Datang...`. Sebaliknya, apabila masukan password selain `1234`, maka akan memberikan balikan berupa kalimat `Sandi salah! Akses ditolak!`.

<img src="Gambar/EditorProgram.png">

## + Beberapa fitur pada editor IDLE

Beberapa fitur pada editor IDLE yang perlu diketahui adalah:

+ ### Nomor Garis (Line Number)

Pada umumnya, ketika terjadi sebuah kesalahan pada penulisan kode di editor, semisal variabel yang digunakan belum terdeklarasi sebelumnya atau nama variabel berbeda dengan yang digunakan, maka console akan memberitahukan letak baris terjadinya eror seperti pada gambar berikut.

<img src="Gambar/ErrorLine.png">


Untuk memastikan letak eror tersebut, biasanya baris kelasahannya berada pada baris sebelumnya dari terjadinya eror. Semisal error pada gambar diatas disebabkan pada `Line 4` karena variabel `nama` pada baris 4 belum terdeklarasi, oleh karenanya error disebabkan pada `baris ke 3` yaitu terletak sebelum error terjadi. Untuk mengetahui `posisi kursor` pada editor berada pada baris ke-berapa, dapat dilihat pada bagian pojok kanan bawah editor IDLE, pada tulisan `ln:[] ` ` col:[]`. Sebagai contoh pada gambar dibawah ini, menunjukkan letak `ln: 3` dan `col:1` pada editor IDLE. 

<img src="Gambar/LetakEror.png">

+ ### Kehilangan pasangan pada penulisan (Missing Charracter)

Galat atau error yang sering terjadi pada penulisan kode di Python, adalah kehilangan pasangan pada penulisannya. Semilsal yang sering terjadi adalah 

1. Pasangan tanda kurung `( )`, tanda petik atas `' '` atau `" "`.
2. Penulisan `:` pada perulangan atau pengkondisian
3. Kekurangan `spasi` pada penulisan variabel
4. Penulisan yang kurang sejajar terutama pada perulangan dan pengkondisian

Semisal pada contoh berikut ini:

#### Kekurangan tutup kurung

```python
print("Halo Bro!")

nama = raw_input("Namamu siapa? :" #) #ini posisi kekurangan tutup kurung )
print ("Halo " + nama + '!')
```

<img src="Gambar/Error Kekurangan.png">

#### Kekurangan titik dua

```python
print("Halo Bro!")

nama = raw_input("Namamu siapa? :") 
print ("Halo " + nama + '!')

password = input("Masukkan angka sandinya... : ")
if password == 1234 #:  # ini posisi kekurangan titik dua :
    print("Sandi benar! \nSelamat datang " + nama + " di program ini.")
else:
    print(nama + ", sandinya salah. \nAkses ditolak!")
```
<img src="Gambar/ErorKekuranganTitikDua.png">

#### Kelebihan spasi

```python
print("Halo Bro!")

nama = raw_input("Namamu siapa? :") 
print ("Halo " + nama + '!')

passwor d = input("Masukkan angka sandinya... : ") # letak kelebihan spasi
if password == 1234:
    print("Sandi benar! \nSelamat datang " + nama + " di program ini.")
else:
    print(nama + ", sandinya salah. \nAkses ditolak!")
```
<img src="Gambar/KelebihanSPasi2.png">

#### Penulisan kurang sejajar secara tingkatannya

```python
print("Halo Bro!")

nama = raw_input("Namamu siapa? :") 
print ("Halo " + nama + '!')

password = input("Masukkan angka sandinya... : ")
if password == 1234:
    print("Sandi benar! \nSelamat datang " + nama + " di program ini.")
  else:  # letak kurang sejajar. Seharusnya lurus dengan tingkatan if nya
    print(nama + ", sandinya salah. \nAkses ditolak!")
```
<img src="Gambar/ErorKelebihanSPasi.png">


Pada umumnya, ketika terjadi sebuah kesalahan pada penulisan kode di editor, semisal kekurangan tanda titik dua `:`, tutup kurung `)` ataupun kekurangan `spasi`, console IDLE akan memberitahukan letak baris dan kolom terjadinya error 
atau galat yang terjadi.

+ ### Komentar dalam banyak baris

Python juga memiliki fitur untuk memberikan komentar pada banyak garis. Pada kasus ini, Anda dapat menyematkan kode `'''` pada awalan dan akhiran kode yang akan diberikan komentar, semisal, tuliskan kode berikut pada editor kalian dan `run`:

```python
'''
berikut adalah komentar
yang ada pada python
=======================
a = 6
b = 5
print (a + b)
=======================
operasi diatas tidak akan di proses
kecuali operasi dibawah ini
'''

a = 1
b = 2
print (a + b)

```

maka akan menampilkan:
```python
3
>>> 
```

# 4. Pengkondisian

Kita juga pernah menggunakan syntax berikut pada console bukan pada [Nilai Boolean](#Nilai-Boolean) ? Selain itu kita sudah melakukan beberapa pengkondisian pada bab [berikut](#+-Menjalankan-program-dari-editor). Namun, mari kita perjelas penggunaan kondisi pada Pyhton. 


```python
>>> a = 2
>>> a == 2
True
>>> (a == 2)
True
>>> (a == 2) == True
True
>>> (a == 2) == False
False
>>> (a == 1) == True
False
>>> 
```

bentuk dasar dari pengkondisian if seperti berikut:

```python
>>> kondisi = True
>>> if kondisi:
	print ("Benar")

	
Benar
>>> kondisi = False
>>> if kondisi:
	print ("Benar")

	
>>> 
>>> if kondisi:
	print ("Benar")
else:
	print ("Salah")

	
Salah
>>>
```

Kita juga bisa menambahkan `if not` pada pengkondisian untuk negasi dari kondisi seperti berikut ini. Tulis pada editor kalian, dan `run` programnya. 


```python
kondisi = False
if kondisi:
    print ("Benar")
if not kondisi:
    print ("Salah")
```

maka keluaran operasinya adalah:

```python
Salah
>>> 
```
## Hindari penggunaan kondisi bertingkat dengan `elif`
Untuk penggunaan beberapa kondisi yang bertingkat, hindari penggunaan `else` dan `if` yang berulang seperti berikut ini:

```python
print ("Hai...")
kata = raw_input("Masukkan ejaan angka: ")

if kata == "satu":
    print ("satu ejaan")
else:
    if kata == "dua":
        print ("dua ejaan")
    else:
        if kata == "tiga":
            print ("tiga ejaan")
        else:
            if kata == "empat":
                print ("empat ejaan")
            else:
                print ("salah ejaan")
              
```

sebaiknya gunakan `elif` pada penulisan kondisian bertingkat. Selain enak untuk dipandang, juga mudah dalam pengorganisasian kondisi yang kita buat. Sebagai contoh pada kode berikut ini:

```python
print ("Hai...")
kata = raw_input("Masukkan ejaan angka: ")

if kata == "satu":
    print ("satu ejaan")
elif kata == "dua":
    print ("dua ejaan")
elif kata == "tiga":
    print ("tiga ejaan")
elif kata == "empat":
    print ("empat ejaan")
else:
    print ("salah ejaan")
```

Kedua program diatas, berfungsi dengan baik, seperti berikut ini:

```python
Hai...
Masukkan ejaan angka: empat
empat ejaan
>>> 
```

Selain itu, pada penggunaan `elif` lebih memudahkan pengorganisasian kondisi yang ada seperti contoh berikut:

```python
if 1 == 1:
    print ("satu")
elif 1 == 2:
    print ("dua")
else:
    print ("banyak")
```

maka keluarannya:

```python
satu
>>> 
```


Hindari penggunaan penulisan `if` lagi pada kondisi selainnya, semisal:

```python
if 1 == 1:
    print ("satu")
if 1 == 2:
    print ("dua")
else:
    print ("banyak")
```

maka keluarannya:

```python
satu
banyak
>>> 
```

Kedua kode diatas sangatlah berbeda pada keluarannya. Untuk penggunaan `elif` sebagai pengkondisiannya, kondisi `1 == 2` merupakan bagian dari kondisi pertama `1 == 1`, yaitu `"selain kondisi pertama"`. Sedangkan pada penggunaan `if 1 == 2` pada kode dibawahnya, kondisi ini berbeda dengan kondisi `if 1 == 1`, sehingga keluaran programnya berlaku `dua kali` pengkondisian atau bukan bagian dari kondisi sebelumnya. 

## Coba benarkan kode berikut ini

```python
print ("Hai...")
kata = raw_input("Masukkan satu atau dua: ")
if kata = "satu":
    print ("sekali")
elif kata = "dua"
    print ("dua kali")
else:
    print ("Kata" kata, "tidak diketahui...")
```



# 5. List dan Tuple

`list` atau daftar merupakan sekumpulan data yang nantinya akan digunakan sebagai acuan untuk dilakukan operasi. Pada daftar ini, merupakan sebuah variabel yang bisa kita panggil tiap anggotanya sesuai dengan urutannya masing-masing.

Semisal pada kasus dibawah ini:

```python
siswa1 = "Udin"
siswa2 = "Hilman"
siswa3 = "Nanda"
siswa4 = "Eki"
siswa5 = "Rasid"
siswa6 = "Surya"

nama = raw_input("Nama Siswa SDN Candi 3: ")
if nama == siswa1 or nama == siswa2 or nama == siswa3 or nama == siswa4 or nama == siswa5 or nama == siswa6:
    print ("Siswa tersebut terdaftar di sekolah kami.")
else:
    print ("Bukan siswa kami.")
```

Program diatas dapat bekerja dengan baik. Namun, pada penulisan pengkondisiannya, terjadi penulisan yang berulang dan membosankan. Oleh karenanya, dapat digunakan `list` untuk mempersingkat penulisan. Semisal pada kode berikut ini:

```python
siswa = ['Udin','Hilman','Nanda','Eki','Rasid','Surya']
nama = raw_input("Nama Siswa SDN Candi 3: ")
if nama in siswa:
    print ("Siswa tersebut terdaftar di sekolah kami.")
else:
    print ("Bukan siswa kami.")
```

Seberapa banyak pun jumlah siswanya, maka pengkondisian tidak akan ditulis sebanyak siswa tersebut. Penambahan daftar siswa baru, hanya menambahkan pada variabel `siswa` saja yang sudah berjenis `list` atau `daftar`.

## Lalu, apa saja yang dapat kita lakukan dengan `list` ?

Pertama, kita coba buka sebuah console Python baru. Lalu tuliskan sebuah variabel dengan `list` didalamnya. Terserah Anda akan membuat sebuah daftar apa. Semisal sebuah daftar berlanjaan berikut :

```python
>>> sayur = ['Wortel','Kangkung','Cabe','Tomat','Kubis','Selada','Brokoli']
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli']
>>> 
```

Selain itu kita juga bisa mengolah isi di dalam daftar tersebut. Semisal:

```python
>>> len (sayur)
7
>>> sayur += ['Kubis','Jengkol','Ayam']
>>> len (sayur)
10
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Ayam']
>>> sayur *= 2
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Ayam', 'Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Ayam']
>>> len (sayur)
20
```

Selain itu, kita juga bisa mengambil beberapa bagiannya menggunakan `indexing` atau `slicing`, seperti berikut:

```python
>>> sayur[2] # Indexing
'Cabe'
>>> sayur[0]
'Wortel'
>>> sayur[:4] # Slicing
['Wortel', 'Kangkung', 'Cabe', 'Tomat']
>>> sayur[3:4]
['Tomat']
>>> sayur[3:8]
['Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis']
>>> 
```

Kita juga bisa mengecheck keanggotaan dari sebuah string dari datar yang sudah kita buat, semisal:

```python
>>> 'Kacang' in sayur
False
>>> 'Tomat' in sayur
True
>>> 
```

Namun, untuk kita tidak bisa menggunakan perintah dibawah ini untuk mengechek keanggotaan dari sebuah daftar.

```python
>>> ['Tomat','Kedelai'] in sayur
False
>>> ['Tomat','Jengkol'] in sayur
False
>>> ['Tomat','Kubis'] in sayur
False
>>> 
```

sebuah `list` juga memiliki fungsi tersendiri, yaitu `remove`, `append`, dan `extend`. Untuk mengetahui masing-masing fungsinya, ikuti kode berikut ini pada console.

```python
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Ayam', 'Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Ayam']
>>> sayur.remove('Ayam') # Ayam bukan anggota sayur
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Ayam']
>>> len(sayur) # Hanya Ayam pertama yang terhapus
19
>>> sayur.remove('Ayam') # Menghapus Ayam kedua
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol']
>>> len(sayur) # Ayam kedua, sudah terhapus
18
>>> sayur.remove(['Kangkung','Tomat']) # Tidak bisa digunakan

Traceback (most recent call last):
  File "<pyshell#44>", line 1, in <module>
    sayur.remove(['Kangkung','Tomat'])
ValueError: list.remove(x): x not in list
>>> 
```

Mari tambahkan beberapa sayur lagi

```python
>>> sayur.append('Kacang Panjang')
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Kacang Panjang']
>>> sayur.extend(['Daun Singkong','Bawang'])
>>> sayur
['Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Wortel', 'Kangkung', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Kacang Panjang', 'Daun Singkong', 'Bawang']
>>> 
```

Lalu bagaimana jika kita ingin menghapus seluruh nama pada daftar yang memiliki nama yang sama?

```python
>>> while 'Kangkung' in sayur:
	sayur.remove('Kangkung')

	
>>> sayur
['Wortel', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Wortel', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Kacang Panjang', 'Daun Singkong', 'Bawang']
>>> 
```

Kita juga bisa merubah sebuah nama pada daftar menggunakan `indexing` dan `slicing` seperti berikut:

```python
>>> sayur[0] = 'Kacang'
>>> sayur
['Kacang', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Wortel', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Kacang Panjang', 'Daun Singkong', 'Bawang']
>>> sayur[3:6] = 'Kecambah'
>>> sayur
['Kacang', 'Cabe', 'Tomat', 'K', 'e', 'c', 'a', 'm', 'b', 'a', 'h', 'Kubis', 'Jengkol', 'Wortel', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Kacang Panjang', 'Daun Singkong', 'Bawang']
>>> sayur[3:11] = ['Bawang Merah','Bawang Putih']
>>> sayur
['Kacang', 'Cabe', 'Tomat', 'Bawang Merah', 'Bawang Putih', 'Kubis', 'Jengkol', 'Wortel', 'Cabe', 'Tomat', 'Kubis', 'Selada', 'Brokoli', 'Kubis', 'Jengkol', 'Kacang Panjang', 'Daun Singkong', 'Bawang']
>>> 
```

## Operasi pada `list`

Untuk beberapa kasus berikut, mungkin nanti kalian akan bertemu dengannya, semisal:

```python
>>> a = [1,2,3]
>>> b = a
>>> b
[1, 2, 3]
>>> b.append(4)
>>> a
[1, 2, 3, 4]
>>> a == b
True
>>> a is b
True
>>> b
[1, 2, 3, 4]
>>>  
```

Untuk setiap penggunaan `[]` pada Python, akan ada `list baru` yang terbuat.

```python
>>> [] == []
True
>>> [] is []
False
>>> [1,2,3] == [1,2,3] # Apakah kedua list tersebut bernilai sama?
True
>>> [1,2,3] is [1,2,3] # Apakah kedua list tersebut merupakan list yang sama?
False
>>> 
```

Oleh karenanya, untuk membuat dua `list` yang bernilai sama tapi keduanya merupakan variabel yang berbeda dan tidak memiliki keterkaitan seperti `b = a` diatas, dapat diberikan fungsi `a.copy()` pada sumber variabel yang akan diduplikat. Semisal:

```python
# Hanya berfungsi pada Python 3, sedangkan Python 2.7 belum mendukung fungsi copy()
>>> a = [1, 2, 3]
>>> b = a.copy()
>>> b is a
False
>>> b.append(4)
>>> b
[1, 2, 3, 4]
>>> a
[1, 2, 3]
>>>
```

## Tuple

`tuple` mirip dengan `list`, hanya saja jika list menggunakan `[]` sedangkan tuple menggunakan `()` pada penulisannya. Semisal :

```python
>>> c = (1,2,3)
>>> c
(1, 2, 3)
>>> c = ()
>>> c
()
>>> 
```

Pada penulisan `tuple` yang berisikan satu nilai, dapat ditulis dengan `(nilai,)` bukan `(nilai)`, karena penggunaan `(nilai)` digunakan untuk `(1 + 2) * 3`. Semisal pada kode berikut:

```python
>>> (4)
4
>>> (4,)
(4,)
>>> (2 + 3) * 4
20
>>> (2 + 3,) * 4
(5, 5, 5, 5)
>>> 
```

Pada beberapa kasus khusus, penulisan berikut masih dapat digunakan namun tidak disarankan dikarenakan akan susah untuk mengidentifikasinya. 

```python
>>> 1,2,3,4
(1, 2, 3, 4)
>>> 'sayur',
('sayur',)
>>> 
```

`tuple` tidak memiliki fungsi `append()` selayaknya `list`.

```python
>>> angka = (1,2,3)
>>> angka
(1, 2, 3)
>>> angka.append(4)

Traceback (most recent call last):
  File "<pyshell#100>", line 1, in <module>
    angka.append(4)
AttributeError: 'tuple' object has no attribute 'append'
>>> 
```



---

## Penulisan Pada Python 2.7

Struktur penulisan pada Python, pada umumnya diawali dengan inisialisasi compiler dengan menambahkan kode berikut. 


```python
#!/usr/bin/env python
```

Biasanya penggunaan inisialisasi ini digunakan ketika program python dirunning menggunakan Terminal. Namun dapat diabaikan apabila running program Python menggunakan IDLE. 



---
Author : [yogidm](https://github.com/yogidm)

Merujuk dari [Akuli](https://github.com/Akuli/python-tutorial)

@April 2019

---


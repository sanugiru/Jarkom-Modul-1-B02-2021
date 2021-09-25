# LAPRES JARKOM B02 MODUL l 2021

Anggota:
- 05111940000006 	[Daffa Tristan Firdaus](https://www.github.com/DaffaTristan)  
- 05111940000086 	[Nabil Fikri Arief](https://www.github.com/alwaysyu)
- 05111940000158 	[Shahnaaz Anisa Firdaus](https://www.github.com/sanugiru)

## Soal 1
Sebutkan web server yang digunakan pada "[ichimarumaru.tech](https://www.ichimarumaru.tech)"! 

**Pembahasan:**

**Kendala:**
## Soal 2
Temukan paket dari web-web yang menggunakan basic authentication method!

**Pembahasan:**

**Kendala:**
## Soal 3
Ikuti perintah di basic.ichimarumaru.tech! Username dan password bisa didapatkan dari file .pcapng!

**Pembahasan:**

**Kendala:**
## Soal 4
Temukan paket mysql yang mengandung perintah query select!

**Pembahasan:**

**Kendala:**
## Soal 5
Login ke portal.ichimarumaru.tech kemudian ikuti perintahnya! Username dan password bisa didapat dari query insert pada table users dari file .pcap!

**Pembahasan:**

**Kendala:**
## Soal 6
Cari username dan password ketika melakukan login ke FTP Server!

**Pembahasan:**

**Kendala:**
## Soal 7
Ada 500 file zip yang disimpan ke FTP Server dengan nama 0.zip, 1.zip, 2.zip, ..., 499.zip. Simpan dan Buka file pdf tersebut. (Hint = nama pdf-nya "Real.pdf")

**Pembahasan:**
- filter: ftp-data contains Real.pdf
	![step1](/screenshots/7-1.png)  
- klik kanan > Follow > TCP Stream  
	![step2](/screenshots/7-2.png)  
- Show as Raw > Save as "Real.zip"
	![step3](/screenshots/7-3.png) 
  ![step4](/screenshots/7-4.png)  
- Isi dari Real.zip & Real.pdf
	![isi-zip](/screenshots/7-5.png)  
	![isi-pdf](/screenshots/7-6.png)  

**Kendala:** -
## Soal 8
Cari paket yang menunjukan pengambilan file dari FTP tersebut!

**Pembahasan:**

**Kendala:**
## Soal 9
Dari paket-paket yang menuju FTP terdapat inidkasi penyimpanan beberapa file. Salah satunya adalah sebuah file berisi data rahasia dengan nama "secret.zip". Simpan dan buka file tersebut!

**Pembahasan:**

**Kendala:**
## Soal 10
Selain itu terdapat "history.txt" yang kemungkinan berisi history bash server tersebut! Gunakan isi dari "history.txt" untuk menemukan password untuk membuka file rahasia yang ada di "secret.zip"!

**Pembahasan:**

**Kendala:**
## Soal 11
Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80! 

**Pembahasan:**
- Pertama-tama, masukkan `src port 80` pada capture filter
![111](/screenshots/11_1.png)
- Lalu berikut hasilnya
![112](/screenshots/11_2.png)

**Kendala:**
Perlu mencari referensi tambahan terkait port 80
## Soal 12
Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!

**Pembahasan:**
- Pertama-tama, masukkan `port 21` pada capture filter
![121](/screenshots/12_1.png)
- Lalu berikut hasilnya
![122](/screenshots/12_2.png)

*Note : Tidak ada paket yang ditampilkan karena port 21 adalah private server.*

**Kendala:**
Perlu mencari referensi tambahan terkait port 21
## Soal 13
Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!

**Pembahasan:**
- Pertama-tama, masukkan `dst port 443` pada capture filter
![131](/screenshots/13_1.png)
- Lalu berikut hasilnya
![132](/screenshots/13_2.png)

**Kendala:**
Perlu mencari referensi tambahan terkait port 443
## Soal 14
Filter sehingga wireshark hanya mengambil paket yang tujuannya ke [kemenag.go.id](https://www.kemenag.go.id)!

**Pembahasan:**
- Pertama-tama, masukkan `dst host kemenag.go.id` pada capture filter
![141](/screenshots/14_1.png)
- Lalu berikut hasilnya
![142](/screenshots/14_2.png)

**Kendala:**
Tidak ada
## Soal 15
Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

**Pembahasan:**
- Pertama-tama, kita cari IP kita sendiri denan command `ipconfig` pada `cmd`
![151](/screenshots/15_1.png)
didapat ip kita disini `192.168.100.34`
- Kemudian, masukkan `src host 192.168.100.34` pada capture filter
![152](/screenshots/15_2.png)
- Lalu berikut hasilnya
![153](/screenshots/15_3.png)

**Kendala:**
Tidak ada

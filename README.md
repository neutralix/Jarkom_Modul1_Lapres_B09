# Jarkom_Modul1_Lapres_B09
## Soal 1
##### Filter expression :  
##### Screenshot :  
##### Penjelasan :  
- aaa
- bbb
## Soal 6
##### Filter expression :
- ftp-data.command contains Answer.zip
- ftp-data.command contains zipkey.txt
##### Screenshot : 
- ![Filter 1](gambar6.1.png)
- ![Filter 2](gambar6.2.png)
- ![Password Answer.zip](gambar6.3.png)
- ![Hasil Akhir](gambar6.4.png)
##### Penjelasan :  
- Gunakan filter 1 untuk mencari packet data file Answer.zip lalu extract file zipnya dengan cara Follow TCP Stream lalu save as sebagai raw.
- Gunakan filter 2 untuk mencari packet data file zipkey.txt lalu Follow TCP Stream, terlihat passwordnya
- Buka file Answer.zip  
## Soal 7
##### Filter expression : search hex value 59 65 73 2e 70 64 66
##### Screenshot :
- ![Filter](gambar7.1.png)
- ![Hasil Akhir](gambar7.2.png)
##### Penjelasan :  
- Hex value tersebut merupakan string Yes.pdf yang dikonversikan menjadi bentuk Hex
- Extract packet yang ditemukan  
## Soal 8
##### Filter expression :
- ftp contains Microsoft
- ftp.request.command == RETR && ip.host == 198.246.117.106
##### Screenshot :
- ![Filter 1](gambar8.1.png)
- ![Filter 2](gambar8.2.png)
##### Penjelasan :  
- Gunakan filter 1 untuk mencari ip Microsoft
- Gunakan ip sebagai filter untuk mencari objek didownload dari Microsoft
- Objek yang didownload adalah "Readme"  
## Soal 11
##### Filter expression : port 21  
##### Screenshot :
- ![Filter 1](gambar11.1.png)
##### Penjelasan :  
- Packet yang muncul hanya paket yang mengandung port 21
## Soal 12
##### Filter expression : src port 80  
##### Screenshot :
- ![Filter 1](gambar12.1.png)
##### Penjelasan :  
- Packet yang muncul hanya paket yang berasal dari port 80
## Soal 13
##### Filter expression : dst port 443  
##### Screenshot :
- ![Filter 1](gambar13.1.png)
##### Penjelasan :  
- Packet yang muncul hanya paket yang menuju port 443
## Soal 14
##### Filter expression : src host 192.168.100.25  
##### Screenshot :
- ![Filter 1](gambar14.1.png)
##### Penjelasan :  
- Packet yang muncul hanya paket yang berasal dari ip sendiri
## Soal 15
##### Filter expression : dst host monta.if.its.ac.id  
##### Screenshot :
- ![Filter 1](gambar15.1.png)
##### Penjelasan :  
- Packet yang muncul hanya paket yang tujuannya ke monta.if.its.ac.id

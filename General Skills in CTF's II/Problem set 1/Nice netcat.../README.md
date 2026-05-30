<img width="1475" height="946" alt="image" src="https://github.com/user-attachments/assets/19757893-36d9-46ae-98d3-048fccfb119f" />

sebelum mengerjakan challange ini pastikan user membaca write up ini : [Lets Warm Up](https://github.com/lionelsabdani36-ai/WU-CyLab-Security/tree/main/General%20Skills%20in%20CTF's%20I/Problem%20set%201/Lets%20Warm%20Up) dan [What's a netcat?](https://github.com/lionelsabdani36-ai/WU-CyLab-Security/tree/main/General%20Skills%20in%20CTF's%20I/Problem%20set%202/what's%20a%20net%20cat%3F)

hal pertama yang harus dilakukan adalah menyalakan server untuk menjalankannya dengan menggunakan netcat di terminal :
<img width="1367" height="220" alt="image" src="https://github.com/user-attachments/assets/31fcc90a-4cab-41b3-9030-51b1d419481e" />

kalau server sudah menyala jalankan command berikut ini di terminal untuk memasuki servernya :
<img width="453" height="42" alt="image" src="https://github.com/user-attachments/assets/0a8f3f3a-ff0d-40d4-8f9a-57a9d761cf8d" />

setelah melakukan commandnya user akan mendapatkan kode ASCII seperti ini :
>> 112 
105 
99 
111 
67 
84 
70 
123 
103 
48 
48 
100 
95 
107 
49 
116 
116 
121 
33 
95 
110 
49 
99 
51 
95 
107 
49 
116 
116 
121 
33 
95 
56 
51 
54 
57 
49 
125 
10 

kita bisa memahami kode ASCII dengan melihat table ASCII dengan menjalankan command ascii :
<img width="857" height="220" alt="image" src="https://github.com/user-attachments/assets/3bb0f4e6-cdaf-498c-8247-d30a48cc474a" />
<img width="900" height="433" alt="image" src="https://github.com/user-attachments/assets/01d0cafc-0230-4bf9-b977-978865a1da48" />

daripada melakukan cek satu persatu user hanya tinggal mengubahnya ke teks biasa dengan mengunakan CyberChef. pergi ke [CyberChef](https://gchq.github.io/CyberChef/#recipe=From_Charcode('Space',10)&input=MTEyIAoxMDUgCjk5IAoxMTEgCjY3IAo4NCAKNzAgCjEyMyAKMTAzIAo0OCAKNDggCjEwMCAKOTUgCjEwNyAKNDkgCjExNiAKMTE2IAoxMjEgCjMzIAo5NSAKMTEwIAo0OSAKOTkgCjUxIAo5NSAKMTA3IAo0OSAKMTE2IAoxMTYgCjEyMSAKMzMgCjk1IAo1NiAKNTEgCjU0IAo1NyAKNDkgCjEyNSAKMTAg) dan cari operations From Charcode, geser dan pindahkan ke kolom recipes, atur ke base 10, paste kode ASCII dari netcat yang sudah dijalankan dan klik button BAKE! berwarna hijau di bawah kolom recipes :
<img width="1915" height="1031" alt="image" src="https://github.com/user-attachments/assets/4591cd77-04a8-49d7-99ce-6c39376621bb" />

setelah melakukannya maka user akan mendapatkan flag di kolom output dan hasilnya adalah : picoCTF{g00d_k1tty!_n1c3_k1tty!_83691}

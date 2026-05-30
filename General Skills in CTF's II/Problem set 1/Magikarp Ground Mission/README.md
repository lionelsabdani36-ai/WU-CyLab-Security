<img width="1473" height="863" alt="image" src="https://github.com/user-attachments/assets/cfb8218a-a79f-4e3b-b86d-308922482a1c" />
pada challange ini kita diperintahkan untuk mencari flag di dalam ssh

untuk memasuki server ssh kita perlu menyalakan servernya dengan klik button Launch Instance.
<img width="581" height="146" alt="image" src="https://github.com/user-attachments/assets/0281ea75-1072-4613-a3c0-9480ce9b80de" />

kita buka terminal dan jalankan perintah ini untuk memasuki servernya:
<img width="1210" height="732" alt="image" src="https://github.com/user-attachments/assets/7c4c19e2-a057-4f55-8496-389505bdf564" />

sesuaikan user, host dan password yang sudah di sediakan :
<img width="1005" height="43" alt="image" src="https://github.com/user-attachments/assets/79ef1905-eed9-49c4-9ffa-3c6b9ee3457e" />

lakukan pencarian file dengan menggunakan command ls dan cat, user akan mendapatkan file yang merupakan part 1 dari flag dan instruksi untuk mendapatkan part 2 flag :
<img width="698" height="183" alt="image" src="https://github.com/user-attachments/assets/f0afc495-1ca8-48d2-8542-c8e110129f6d" />
ketika user menjalankan command cat ke file instruksinya kita di perintahkan ke root atau / untuk mendapatkan part 2 flag :

jalankan command cd untuk berpindah ke /, jalankan command ls dan cat part 2 flag dan instruksi untuk mendapatkan part 3 flag :
<img width="1115" height="210" alt="image" src="https://github.com/user-attachments/assets/2f1c1adc-ff29-40d0-a50d-84576831eda8" />

ketika user menjalankan command cat ke file part 2 flag maka user akan mendapatkan flagnya, selanjutnya pada saat melakukan cat ke flag instruksinya user diperintahkan untuk berpindah direktori ke home atau ~ untuk mendpatkan part 3 flag :
<img width="1115" height="130" alt="image" src="https://github.com/user-attachments/assets/1019ff98-d8c3-4891-b000-befedfacac14" />
setelah kalian menjalankan commandnya maka kalian akan mendapatkan flag yang lengkap dan flagnya adalah : picoCTF{xxsh_0ut_0f_//4t3r_0b24fc4f}

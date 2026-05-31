<img width="1483" height="778" alt="image" src="https://github.com/user-attachments/assets/de19f9fe-4667-4e1b-8ae7-adb8a9fabe7a" />

Pada tantangan kali ini kita dipertintahkan untuk mendecode file yang berisikan flag yang terenkripsi dengan menggunakan file python yang sudah disediakan

untuk mengerjakannya kita cukup menjalankan file python di terminal menggunakan command python3 :


command line :

╰─ ls
ende.py  flag.txt.en  password.txt


╰─ python3 ende.py 
Usage: ende.py (-e/-d) [file]


╰─ python3 ende.py -e flag.txt.en 
Please enter the password:720b6ad346f84cd483c60c7464dd95d4
gAAAAABqFxBYY9fv-j7he5AndM6wG_jYYGDLzOc9WM5b0ScP58R3oMZINv9XFaxvSDBUPU0j4odplru8DmZgQ3W0mYOeTNr8VZlHTVTEkaPabYCrpw40qq8_qcVNJTogXuWEc-C9x5rjNp8OTK5uCkGGBfuyABlu_L6FsLARoet_DzK0FMGFoeFcZVEFBcF4y3Eggp-TIuL3_atGrPp9HxrlcU02FnE0dNyyzhIBTlTqLoHIZ8hBBHBbEFZmlorwjxNkMI0TgIwh%                                                                               

╰─ python3 ende.py -d flag.txt.en
Please enter the password:720b6ad346f84cd483c60c7464dd95d4
picoCTF{4p0110_1n_7h3_h0us3_9c5f9bcf}

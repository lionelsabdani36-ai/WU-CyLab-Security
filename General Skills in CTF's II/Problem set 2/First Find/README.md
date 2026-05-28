Hints :
-> Using find command

command line :
>> 
╰─ ls
files  files.zip


╰─ cd files 


╰─ ls
13771.txt.utf-8  14789.txt.utf-8  acceptable_books  adequate_books  satisfactory_books


╰─ find . -name "uber-secret.txt"
./adequate_books/more_books/.secret/deeper_secrets/deepest_secrets/uber-secret.txt


╰─ cd adequate_books/more_books/.secret/deeper_secrets/deepest_secrets/   


╰─ cat uber-secret.txt 

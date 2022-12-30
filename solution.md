# level0

 ```bash
 ssh -p 2220 bandit0@bandit.labs.overthewire.org
 password: bandit0
 
 ls
 ```
# level1

 ```bash
 ssh -p 2220 bandit1@bandit.labs.overthewire.org
 password: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
 
 ls
 cat ./-
 ```
# level2

 ```bash
 ssh -p 2220 bandit2@bandit.labs.overthewire.org
 password: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
 
# level1

 ```bash
 ssh -p 2220 bandit1@bandit.labs.overthewire.org
 password: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
 
 ls
 cat ./-
 ```
# level2

 ```bash
 ssh -p 2220 bandit2@bandit.labs.overthewire.org
 password: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
 
 ls
 cat spaces\ in\ this\ filename 
 ```
# level3

 ```bash
 ssh -p 2220 bandit3@bandit.labs.overthewire.org
 password: aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
 
 ls -a
 cd inhere
 cat .hidden
 ```
# level4

 ```bash
 ssh -p 2220 bandit4@bandit.labs.overthewire.org
 password: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

 ls
 cd inhere
 file ./*
 cat ./-file07
 ```
# level5

 ```bash
 ssh -p 2220 bandit5@bandit.labs.overthewire. org
 password: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
 
 ls
 cd inhere
 ls
 find . -size 1033c
 cat ./maybehere07/.file2
 ```
# level6

 ```bash
 ssh -p 2220 bandit5@bandit.labs.overthewire.org
 password: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
 
 cd /
 find . -size 33c -user bandit7 -group bandit6
 cat ./var/lib/dpkg/info/bandit7.password
 ```
# level7

 ```bash
 ssh -p 2220 bandit7@bandit.labs.overthewire.org
 password: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
 
 ls
 grep millionth data.txt 
 ```
# level8

 ```bash
 ssh -p 2220 bandit8@bandit.labs.overthewire.org
 password: TESKZC0XvTetK0S9xNwm25STk5iWrBvP
 
 ls
 sort data.txt | uniq -u
 ```
# level9

 ```bash
 ssh -p 2220 bandit9@bandit.labs.overthewire.org
 password: EN632PlfYiZbn3PhVK3XOGSlNInNE00t
 
 ls
 grep -e '\S\A=*\w*' -a data.txt
 ```
# level10

 ```bash
 ssh -p 2220 bandit10@bandit.labs.overthewire.org
 password: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
 
 ls
 base64 -d data.txt

 ```
# level11

 ```bash
 ssh -p 2220 bandit11@bandit.labs.overthewire.org
 password: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
 
 ls
 tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt 
 ```
# level12

 ```bash
 ssh -p 2220 bandit12@bandit.labs.overthewire.org
 password: JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
 
 ls
 mkdir /tmp/foobar
 cp data.txt /tmp/foobar
 cd /tmp/foobar
 xxd -r data.txt > data
 file data
 mv data data.gz
 gzip -d data.gz 
 file data
 mv data data.bz
 bzip2 -d data.bz
 file data
 mv data data.gz
 gzip -d data.gz
 file data
 mv data data.tar
 tar -xf data.tar
 file data5.bin
 mv data5.bin data.tar
 tar -xf data.tar
 file data6.bin
 mv data6.bin data.bz
 bzip2 -d data.bz
 file data
 mv data data.tar
 tar -xf data.tar
 file data8.bin
 mv data8.bin data.gz
 gzip -d data.gz
 file data
 cat data
 ```
# level13

 ```bash
 ssh -p 2220 bandit13@bandit.labs.overthewire.org
 password: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
 ```
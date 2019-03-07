http://rogerdudler.github.io/git-guide/index.id.html

## Create New Repository Git

``` bash
git init
```

## Clone Repository 

``` bash
git clone /jalur/ke/repositori
git clone namapengguna@host:/jalur/ke/repositori
git clone https://github.com/arthaand/training-git-2019.git
```

## Add Message

``` bash
git commit -m "Pesan komit" 
```

## Commit All

``` bash
git commit -all 
```

## Push to master

``` bash
git push origin master
```

## Add File

``` bash
git add <namaberkas>
git add *
```

## Create Branch

``` bash
git checkout -b fitur_x
```

## Back to master

``` bash
git checkout master
```

## Delete Branch

``` bash
git branch -d fitur_x
```

## Push Branch

``` bash
git push origin <cabang>
```

## Git Pull

``` bash
git pull
```

## Git Merge

``` bash
git merge <cabang>
```

## Conflig Merge
``` bash
git add <namaberkas>
git diff <cabang_asal> <cabang_tujuan>
```

## Git Tag
``` bash
git tag 1.0.0 1b2e1d63ff
1b2e1d63ff adalah 10 karakter pertama dari identitas komit yang ingin kamu referensikan ke penanda log.
```

## Git Log
``` bash
git log

Untuk melihat komit penulis tertentu:
git log --author=bob

Untuk melihat log yang dimampatkan, satu baris per komit:
git log --pretty=oneline

Atau mungkin kamu ingin melihat pohon ASCII art seluruh percabangan disertai nama dan penandanya:
git log --graph --oneline --decorate --all

Sekedar melihat berkas yang berubah:
git log --name-status

Ini baru sedikit saja dari sekian banyak parameter yang bisa kamu gunakan. Lebih jauh lagi, lihat git log --help

```


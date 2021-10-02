# 01-git-github
Langkah Langkah Praktik Github Pertemuan Pertama

Pada pertemuan kali ini kita akan mempelajari tata cara penggunaan Github
1. Melakukan Installasi Git
2. Melakukan Konfigurasi
    Konfigurasi ini diperlukan agar Git mengetahui pengaksesnya melalui user name dan user email.

        dell@DESKTOP-4LDQTDN MINGW64 ~
        $ pwd
        /c/Users/dell

        dell@DESKTOP-4LDQTDN MINGW64 ~
        $ git config --global user.name "Norma Syafitri"

        dell@DESKTOP-4LDQTDN MINGW64 ~
        $ git config --global user.email "normasyafitri5@gmail.com"

        dell@DESKTOP-4LDQTDN MINGW64 ~
        $ 



    Cara mengecek apakah konfigurasinya berjalan


        dell@DESKTOP-4LDQTDN MINGW64 ~/mdplpraktik/01-git-github/01-git-github (main)
        $ git config --list
        diff.astextplain.textconv=astextplain
        filter.lfs.clean=git-lfs clean -- %f
        filter.lfs.smudge=git-lfs smudge -- %f
        filter.lfs.process=git-lfs filter-process
        filter.lfs.required=true
        http.sslbackend=openssl
        http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
        core.autocrlf=true
        core.fscache=true
        core.symlinks=false
        pull.rebase=false
        credential.helper=manager-core
        credential.https://dev.azure.com.usehttppath=true
        init.defaultbranch=master
        core.editor="C:\Users\dell\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
        user.name=Norma Syafitri
        user.email=normasyafitri5@gmail.com
        user.emai=normasyafitri5@gmail.com
        core.repositoryformatversion=0
        core.filemode=false
        core.bare=false
        core.logallrefupdates=true
        :

3. Membuat akun github dengan melengkapi data
4. Membuat repository kosong di github baik secara private maupun public
5. Melakukan Clone repository kosong tersebut ke komputer lokal dengan menggunakan git bash

        dell@DESKTOP-4LDQTDN MINGW64 ~/mdplpraktik
        $ cd 01-git-github

        dell@DESKTOP-4LDQTDN MINGW64 ~/mdplpraktik/01-git-github
        $ git clone https://github.com/NormaSyafitri/01-git-github.git
        Cloning into '01-git-github'...
        remote: Enumerating objects: 3, done.
        remote: Counting objects: 100% (3/3), done.
        remote: Compressing objects: 100% (2/2), done.
        remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
        Receiving objects: 100% (3/3), done.

6. Merubah repo master menjadi main
        dell@DESKTOP-4LDQTDN MINGW64 ~/mdplpraktik
        $ cd 01-git-github
            
        dell@DESKTOP-4LDQTDN MINGW64 ~/mdplpraktik/01-git-github (master)
        $ git branch -m main
            
        dell@DESKTOP-4LDQTDN MINGW64 ~/mdplpraktik/01-git-github (main)
        $

7. Mengelola repo sendiri
    Semua manipulasi konten dilakukan di komputer lokal dan hasilnya akan di-push ke remote repo di GitHub.
    Selanjutnya tinggal push ke repo github


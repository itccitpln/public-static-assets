# ITCC Public Assets
This repository is used to store asset files, like photos, logos, scripts, etc publicly (accessible by anyone) and can be reused, so that those files will not consume ITCC server load.

## Structure

```
/reusable
    /reusable-topic-a
        /subfolder-c
            file1.txt
            photo.png
            ...
        asset1.png
        asset2.png
        ...
    /library-b
        file.js
        file-b.css
        ...
    ...
/project-a
    file.js
    file-b.jpg
    ...
/project-b
    file.js
    file-b.pdf
    ...
...
```

### Explanation
- Inside the root, there is only a `reusable` folder and a projects folder.
- The main folder in root is `reusable` which contain reusable files that will be used in all project and application (not specified). Ex: logo, email asset, etc. 
- Besides the `reusable` folder in root there is also a folder with the project name as the folder name which contains specified asset files specifically for the project.
- A project can be used reapetedly by taking a file path inside the `reusable` folder
- A specific file used in a project can at any time be moved into the `reusable` folder if that file is to be used in another project.

## Ketentuan
- The naming of folders in reusable project can be written based on the contents/usage of the files in the folder
- The name of each folder and file must use lowercase letters and the character *dash* (`-`) as a separator.

ex:
```
/wordpress-itcc
    /css
        animasi.css
        ...
    /foto
        postingan13.jpg
        ...
    ...
```
- Types of files that are allowed to be stored in the asset repo include:
    - *photo* (logo, supporting images for website pages, animation, etc).
    - *scripts* (library javascript, css, html, php, dsb).
    - short audio/sound effect.
- File types that may not be stored in the asset repo, among others:
    - Video files.
    - Raw File (compressed or not. ex: .PSD, .PRPROJ .ZIP, .RAR).
- The maximum size of each file that can be place in the asset file repo is 3 MB.

# Aset Publik ITCC
Repositori ini digunakan untuk menyimpan file-file aset seperti foto, logo, script, dll secara publik (dapat diakses oleh semua orang) dan dapat digunakan kembali sehingga file-file tersebut tidak akan memberatkan server ITCC.


## Struktur

```
/reusable
    /reusable-topic-a
        /subfolder-c
            file1.txt
            photo.png
            ...
        asset1.png
        asset2.png
        ...
    /library-b
        file.js
        file-b.css
        ...
    ...
/project-a
    file.js
    file-b.jpg
    ...
/project-b
    file.js
    file-b.pdf
    ...
...
```

### Penjelasan
- Dalam root hanya terdapat folder `reusable` dan folder project-project.
- Ada folder utama di root, yaitu `reusable`, dan folder `reusable` ini berisi file-file yang dapat dipakai oleh semua project & aplikasi (tidak spesifik). Contohnya, logo, asset email, dll.
- Selain folder `reusable` di root juga ada folder dengan nama sesuai projectnya, dan berisi file-file asset yang spesifik untuk project tersebut saja.
- Sebuah project dapat menggunakan file yang dipakai berulang kali dengan mengambil path file yang terdapat di folder `reusable`.
- Sebuah file spesifik yang digunakan dalam suatu project dapat suatu waktu dipindahkan ke dalam folder `reusable` jika file tersebut ingin digunakan kedalam project lain.

## Ketentuan
- Penamaan folder dalam project baik reusable dapat dituliskan berdasarkan isi/kegunaan file dalam folder tersebut
- Penamaan setiap folder dan file wajib menggunakan huruf kecil dan character *dash* (`-`) sebagai pemisah.

ex:
```
/wordpress-itcc
    /css
        animasi.css
        ...
    /foto
        postingan13.jpg
        ...
    ...
```
- Jenis file yang diperkenankan untuk disimpan dalam repo asset antara lain:
    - *file foto* (logo, gambar pendukung halaman website, animasi, dsb)
    - *file scripts* (library javascript, css, html, php, dsb)
    - file audio singkat/sound effect.
- Jenis file yang tidak boleh disimpan dalam repo asset antara lain:
    - file video
    - file mentahan (baik dalam bentuk compress atau tidak. ex: .PSD, .PRPROJ .ZIP, .RAR)
- Ukuran maksimum tiap file yang terdapat dapat repo asset file adalah 3 MB.


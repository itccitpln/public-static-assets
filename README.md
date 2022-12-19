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

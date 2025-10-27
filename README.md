*Langkah langkah bikin New Repository, Aktifin Github Pages, dan nyambungin HTML & CSS*

---

## Cara bikin Repository Baru di GitHub

1. Masuk ke [https://github.com](https://github.com) dan login.
2. Klik tanda **“+”** di pojok kiri atas → pilih **“New repository”**.
3. Isi kolom:

   * **Repository name**: misalnya `web-nama`
   * **Description** (isi bebas aja atau boleh kosong)
   * Pilih **Public**
   * Centang **Add a README file** (biar repo punya kalian nggak kosong melempeng)
4. Klik **Create repository**
5. Abis itu, kalian bisa **upload file HTML dan CSS** lewat tombol **Add file → Upload files**
6. Terakhir, klik **Commit changes** buat nyimpen perubahannya.

---

##  Cara ngaktifin GitHub Pages

Kalo repositorynya udah siap, lanjut aktifin GitHub Pages biar web kalian bisa diakses secara online:

1. Buka tab **Settings** di repository.
2. Scroll ke bawah ke bagian **Pages**.
3. Terus di bagian **Source**, pilih:

   * **Branch:** `main`
   * **Folder:** `/ (root)`
4. Klik **Save**, terus tunggu sebentar.
5. Nanti muncul link kaya gini:
    `https://username.github.io/web-saya/`

---

## Struktur Folder

```
index.html
 Halaman utama website
style.css
 File CSS untuk desain dan tampilan
```
---

## Menghubungkan CSS ke HTML

```html
<link rel="stylesheet" href="style.css">
```

letaknya sebelum tag `</head>` supaya css kalian nyambung sama html nya

---

##  Tujuan Repository ini :

* Belajar dasar **HTML & CSS**
* Cara kerja **repository GitHub**
* Coba publish web lewat **GitHub Pages**

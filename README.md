# Selamat Datang di Sistem Informasi Argajaladri

Sebelum memulai partisipasi dalam pengembangan pemrograman di web site ini. Terbih dahulu harus memenuhi role(aturan) yang sudah berlaku.

## Mulai Mengedit
Memulai mengedit silahkan klik [editor on GitHub](https://github.com/Rahman115/argajaladri.or.id) dan Anda akan di arahkan ke halaman situs GitHub.

Pengededitan bisa menggunakan aplikasi pihak ke tiga `Acode` bisa dicari di play store. 

### Pengenalan Folder
- `📁 Model` - berisi file model
- `📁 controller` - berisi function mengeksekusi perintah
- `📁 dash`
- `📁 doc`
- `📁 resources`
- `📁 src` - berisi file - file data
- `📁 vendor`
- `📁 view` - menampilkan hasil

### Sebelum melakukan edit file
`argajaladri.or.id` merupakan situs web static yang tidak memiliki Control Admin. Jadi jika ingin melakukan perubahan, maka akan dirubah secara manual.

Dibagian ini ada beberapa hal yang harus diperhatikan sebelum melakukan pengeditan.

🔸Baca petunjuk yang telah diberikan, pastikan anda telah memahami apa yang harus dilakukan.

🔸Mengisi data harus perhatikan tanda `"` _(petik dua)_ , upayakan semua data _String_ atau data teks harus di apit tanda petik du ex. `"data baru"`.

🔸`{}` _Kurung krawal_ biasa digunakan untuk memisahkan data variabel, dan di pisahkan dengan tanda `,` _koma_. Contoh

```
...
{
  id = "AGJ.00.000.XY",
  nama = "Nama Lengkap"
  },
  {
    ...next data
  }
 ...
```

Data diatas menunjukan `id` dan `nama` adalah suatu variabel.

### Menambah atau Merubah Data
#### Menambah Data Artikel

Artikel di butuhkan untuk menyampaikan pesan informasi atau berita dan lain-lain. Menambah data ada beberapa tahapan yang harus diperhatikan. 

1. Isi data artikel berupa deskripsi dan gambar. Deskripsi artikel di buat dalam bentuk format file `txt`. Contoh, Kita akan menambahkan data Info Mubes. 
    - Buat file bernama `mubes_xxi.txt`,
    - Isi file tersebut dengan informasi yang ada dan __Save__
    - Upload data `mubes_xxi.txt` yang telah di isi pada Foleder `../src/artikel/` dan
    - Upload gambar `img_mubes_xxi.jpg` di folder `../src/image`
2. Tambah list data artikel, dengan membuka file `../src/artikel.json`, dan tambahkan data untuk memanggil data yang telah di upload tadi.
  ```
  ...
  {
  // Data sebelumnya
    }, {  // Tambah data
        "id": 2,
        "date": "20/08/2021",
        "judul": "Mubes XXI",
        "write": "Penulis 1",
        "Tag": 3,
        "desk": "mubes_xxi.txt",
        "image": "image/img_mubes_xxi.jpg"
    }
  ...

```
Penjelasan Code : `// Data sebelumnya` merupakan data yang sudah ada sebelumnya. `// Tambah data` merupakan data yang akan di tambahkan di file `artikel.json`

Sebaiknya, lakukan _Copy_ dan _Paste_ data `// Tambah data`, code yang akan di tambahkan.
- `"id"` -urutan file / data 
- `"date"` -tanggal saat mengedit
- `"judul"` -judul artikel
- `"write"` -penulis dari artikel
- `"tag"` -belum di buat default 3
- `"desk"` -isikan file yang di upload
- `"image"` -isikan foto yang di upload


3. Selesai



You can use the [editor on GitHub](https://github.com/Rahman115/argajaladri/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Rahman115/argajaladri/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [@abuduchoy](https://t.me/AbuduChoy) or [WA @budu](https://wa.me/qr/KBJZXBQM6BWHH1) and we’ll help you sort it out.

## Cara ganti Token di ACODE
1. Buka aplikasi Acode
2. pilih menu `|` di pojok kanan atas, pilih `GitHub`
3. selanjutnya, pilih menu lagi `|` di pojok kanan atas, pilih `Keluar`
4. setelah keluar, lakukan hal yang sama seperti cara 2
5. Masukkan `Token` yang telah di berikan
6. Selesai
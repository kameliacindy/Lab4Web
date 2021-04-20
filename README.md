# Praktikum 4 : CSS Layout
## A. Membuat Box Element

 - **Box Element** merupakan sebuah box atau kotak yang digunakan untuk membuat layout web.
 - Sebagaimana layaknya ‘kotak’, masing-masing element HTML ini terdiri dari 4 lapisan, yaitu **Margin**, **Border**, **Padding**, dan **Content**.
 - Tag yang biasanya digunakan dalam merancang layout web adalah tag `div` dengan konsep box element.
 - Tag `div` digunakan sebagai penampung untuk mengelompokkan beberapa elemen seperti bagian header, content, sidebar, footer, dan lainnya secara terpisah namun dalam satu tampilan tertentu.

 **Perhatikan contoh di bawah ini.**
 
 Persiapan membuat dokumen HTML terlebih dahulu.
 
 ![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/html_box.PNG)

Kemudian tambahkan kode untuk membuat box element dengan tag `div` seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/box_element.PNG)

### CSS Float Property
Setelah menambahkan kode untuk membuat box element, selanjutnya tambahkan deklarasi CSS pada head seperti di bawah ini.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_float_property.PNG)

Pada deklarasi CSS di atas menggunakan `float: left;` yang berarti property float dengan nilai left, artinya elemen HTML tersebut, posisinya akan berada disebelah kanan elemen parent-nya.. Float berfungsi untuk mengatur **letak element secara horizontal**.  Ada empat value yang bisa di gunakan untuk property float, yaitu left, right, inherit dan none.

**Dan ini hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_box_element.PNG)

### Clearfix Element
**Clearfix** digunakan untuk mengatur element setelah float element. Property `clear` digunakan untuk mengaturnya.

**Contoh:**

Tambahkan elemen `div`  lainnya setelah div3 seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/clearfix_element.PNG)

Dan tambahkan deklarasi CSS untuk div4 menggunakan property clear.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_clear.PNG)

Deklarasi CSS di atas menggunakan property `clear:left;`.  **Nilai left** ini digunakan untuk membersihkan property float left.

**Hasilnya seperti berikut.**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_clear.PNG)

## B. Membuat Layout Sederhana

Kita akan membuat sebuah layout sederhana dengan kerangka layout seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/kerangka_layout.PNG)

**Berikut ini penjelasan elemen-elemen Layout Dokumen Web:**

1. **Elemen Header**
 
Merupakan elemen yang berisi judul dan penjelasan lain dokumen. Biasanya elemen ini diisikan dengan logo website, menu-menu global (seperti login dan logout), maupun nama halaman yang sedang ditampilkan.

2. **Elemen Navigation**

Elemen navigasi, yang memberikan akses navigasi ke halaman-halaman lain dalam web.

3. **Elemen Sidebar**

Elemen pendukung konten, dapat berupa pembantu navigasi konten, ataupun berbagai hal lain seperti daftar konten lain, iklan, atau menu tambahan. Sidebar dapat berada di kiri atau kanan konten, atau bahkan di kiri dan kanan konten, sesuai dengan kreatifitas perancangnya.

4. **Elemen Konten**

Isi utama dari dokumen web. Pengguna biasanya datang ke web untuk melihat teks yang berada pada bagian ini.

5. **Elemen Footer**

Bagian penutup dari website, yang dapat saja berisi informasi lain tentang website, seperti lisensi pengunaan,  _sitemap_, ataupun link ke website lain.

Dan sekarang kita akan membuat Layout Sederhana sesuai dengan kerangka layout di atas.

Pertama kali kita membuat dokumen HTML terlebih dahulu.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/html_layout.PNG)

Pada dokumen HTML di atas, terdapat link file `style.css`.

Kemudian tambahkan kode seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/header_layout.PNG)

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_header_tanpa_css.PNG)

Elemen-elemen layout di atas tanpa CSS, sehingga belum kelihatan rapi. Agar terlihat lebih rapi, pada bagian **header** tambahkan kode CSS pada file eksternal `style.css` seperti di bawah ini.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_header.PNG)

**Dan seperti ini tampilan Header Layout dengan CSS:**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_header_with_css.PNG)

### Membuat Navigasi

Navigasi dibuat dengan menggunakan tag `nav`. Dan berikut ini  merupakan kode CSS untuk bagian elemen navigasi.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/navigasi.PNG)

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_navigasi.PNG)

Tampilan navigasi pada layout di atas terdiri dari:

 - Menu Home
 - Menu Artikel
 - Menu About
 - Menu Contact
 
### Membuat Hero Panel

**Hero Panel** merupakan sebuah elemen setalah header yang isinya berupa penjelasan deskripsi pembuka web.

**Contohnya seperti di bawah ini.**

Untuk membuat hero panel tambahkan kode serta CSS seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/hero_panel.PNG)

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_hero_panel.PNG)

**Dan hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_hero_panel.PNG)

### Membuat Sidebar Widget

**Sidebar Widget** merupakan pelengkap konten utama yang letaknya ada di tengah blog. Dapat dikatakan bahwa kustomisasi _sidebar_ sebenarnya tidak wajib. Tetapi, kustomisasi _sidebar_ ini akan cukup berguna jika pemilik website ingin memberikan informasi tambahan.

Untuk membuat widget tambahkan kode seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/sidebar_widget.PNG)

Kemudian tambahkan CSS.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_widget.PNG)

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_widget.PNG)

### Menambahkan Elemen Lainnya pada Main Content
Di bawah ini merupakan kode untuk menambahkan elemen pada main content.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/main_content.PNG)

Selanjutnya tambahkan CSS pada file eksternal `style.css`

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_main_content1.PNG)

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_main_content2.PNG)

**Dan tampilannya seperti berikut.**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_maint_content.PNG)

### Menambahkan Content Artikel
Artikel juga diletakkan pada elemen content. Berikut ini kode untuk membuat artikel, serta CSS nya.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/content_artikel.PNG)

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_content_artikel.PNG)

**Dan berikut ini tampilan content artikel.**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_content_artikel.PNG)

### Mengatur Footer
**Footer** adalah bagian dasar atau paling bawah dari sebuah website. Fungsi utamanya adalah sebagai kaki dan berisi informasi hak cipta, kepemilikan, link tambahan, sumber daya, sponsor dan kredit sebuah website.

Di bawah ini merupakan kode CSS untuk mengatur footer.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_footer.PNG)

**Dan seperti ini untuk tampilan footer.**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_footer.PNG)

# Tugas pada Praktikum 4

## Membuat Layout pada Menu About yang berisi deskripsi, portofolio, dll

**Jawab:**
Kode untuk membuat content pada Menu About seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/menu_about.PNG)

Kemudian tambahkan CSS pada bagian head.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/css_menu_about.PNG)

**Dan ini adalah tampilan Layout pada Menu About.**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_menu_about.PNG)

## Membuat Layout pada Menu Contact yang berisi form isian: nama, email, message, dll

**Jawab:**
Kode untuk membuat content pada Menu Contact seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/menu_kontak.PNG)

**Dan hasilnya seperti ini tampilan Layout pada Menu Contact.**

![enter image description here](https://github.com/kameliacindy/Lab4Web/blob/main/img/ss_menu_kontak.PNG)


Terimakasih, semoga bermanfaat..

Nama	: Kamelia Cindy Astuti
NIM	: 311910104
Kelas	: TI. 19. A. 1

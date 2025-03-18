![image](https://github.com/user-attachments/assets/22469a02-3a61-43b9-84b1-88410b668fa9)# html-tutorial
html adalah bahasa markup standar untuk halaman web
dengan html kita dapat mebuat web kita sendiri
**contoh**
<!DOCTYPE html

<html>

<head>
 
<title>Page Title</title>

</head>

<h1>This is a Heading</h1>

<p>This is a paragraf.</p>

</body>

</html>

 output yang dihasilkan
 
**This is a heading**
 (ini dikarenakan h1 berfungsi sebagai pembuat judul)
This is a paragraph.

# html introduction 
**apa itu HTML?**
HTML adalah singkatan dari Hyper Teks Markup Language

HTML adalah bahasa markup standar untuk membuat halaman web

HTML menggambarkan struktur halaman web

HTML terdiri dari serangkaian elemen

elemen HTML memberi tahu browser cara menampilkan konten

elemen HTML memberi tahu label pada bagian konten seperti " ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dan lain-lain. 

## Dokumen HTML sederhana ##
contoh:
<!DOCTYPE html mendefinisikan bahwa dokumn ini adalah dokumen HTML5

<html> adalah elemn akar halaman dari HTML

<head> berisi informasi meta tentang halaman HTML
  
<title>Page Title</title> menentukan jududl untuk halaman HTML (yang ditampilkan di bilah jududl browser atau di tab tambahan)

</head> berisi tentang informasi meta tentang halaman HTML

<h1>This is a Heading</h1> mendefinisikan judul besar

<p>This is a paragraf.</p> mendefinisikan sebuah paragraf

</body>
</html>

## apa itu elemen HTML ##
elemen HTML adalah segalanya dari tag awal hingga tag akhir

<h1> judul pertama </h1>
<p> paragraf pertama </p>

artinya 
Start tag                    Elemen contect                End tag
<h1>                         My Firsh Heading               </h1>

<p>                          My firsh Paragraf              </P>

<br>                         none                           none

## peramban Web ##
tujuan peramban web (Chrome, Edge, Firefox, Safari) adalah untuk membaca dokumen HTML dan menampilkan nya dengan benar. 

## Struktur halaman HTML ##
<kepala>
 
  <title> judul halaman </title> (akan ditampilkan di bilah judul browser)
  
</kepala>

<tubuh>
 
    <h1> ini adalah judul</h1>
    
    <p> ini adalah sebuah paragraf.</p>
    
    <p> ini adalah paragraf lainnya</p>
    
</tubuh>

**catatan**
konten didalam bagian <body> akan ditampilkan di browser.

konten di dalam elemen <title> akan ditampilkan di bilah judul browser atau di tab halaman. 

# Editor HTML #
Editor teks sederhana adalah semua hal yang diperlukan ketika mempelajari HTML. 

Pelajari HTML Menggunakan Notepad atau TextEdit
Halaman web dapat dibuat dan dimodifikasi menggunakan editor HTML profesional.

Namun, untuk mempelajari HTML kami merekomendasikan editor teks sederhana seperti Notepad (PC) atau TextEdit (Mac).

Kami percaya bahwa menggunakan editor teks sederhana adalah cara yang baik untuk mempelajari HTML.

Ikuti langkah-langkah di bawah ini untuk membuat halaman web pertama Anda dengan Notepad atau TextEdit.

**Langkah 1: Buka Notepad (PC)**
Windows 8 atau lebih baru:

Buka Layar Awal (simbol jendela di kiri bawah layar). Ketik Notepad .

Windows 7 atau versi sebelumnya:

Buka Start > Program > Aksesoris > Notepad

**Langkah 1: Buka TextEdit (Mac)**
Buka Finder > Aplikasi > TextEdit

Ubah juga beberapa preferensi agar aplikasi dapat menyimpan file dengan benar. Di Preferensi > Format > pilih "Teks Biasa"

Lalu pada bagian "Buka dan Simpan", centang kotak yang bertuliskan "Tampilkan berkas HTML sebagai kode HTML dan bukan teks yang diformat".

Lalu buka dokumen baru untuk meletakkan kode.

**Langkah 2: Tulis Beberapa HTML**
Tulis atau salin kode HTML berikut ke Notepad:
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>

**Langkah 3: Simpan Halaman HTML**
Simpan berkas di komputer. Pilih File > Simpan sebagai di menu Notepad.

Beri nama file "index.htm" dan atur pengkodean ke UTF-8 (yang merupakan pengkodean yang disukai untuk file HTML).

tip: dapat menggunakan .htm atau .html sebagai ekstensi file. tidak ada perbedaan. 

**Langkah 4: Lihat Halaman HTML di Browser Anda**
Buka berkas HTML yang disimpan di peramban favorit (klik dua kali pada berkas tersebut, atau klik kanan - dan pilih "Buka dengan").

Hasilnya akan terlihat seperti ini:
**My Firsh Heading**
My firsh Paragraf

# contoh dasar HTML # 
## Dokumen HTMLM ##
Semua dokumen HTML harus dimulai dengan deklarasi tipe dokumen: <!DOCTYPE html>.

Dokumen HTML itu sendiri dimulai dengan <html>dan diakhiri dengan </html>.

Bagian yang terlihat dari dokumen HTML berada di antara <body>dan </body>.

CONTOH:
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>


OUTPUT 
**My First Heading**
My First paragraf


**Deklarasi <!DOCTYPE>**
Deklarasi tersebut <!DOCTYPE>mewakili jenis dokumen, dan membantu browser menampilkan halaman web dengan benar.

Itu hanya boleh muncul satu kali, di bagian atas halaman (sebelum tag HTML apa pun).

Deklarasi <!DOCTYPE>tidak peka huruf besar/kecil.

Deklarasi <!DOCTYPE>untuk HTML5 adalah:

**<!DOCTYPE html>**

## Judul HTML ## 

Judul HTML didefinisikan dengan tag <h1>to <h6>.

<h1>mendefinisikan judul yang paling penting. <h6>mendefinisikan judul yang paling tidak penting: 

Contoh
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

</body>
</html>

output 
# This is heading 1 #
## This is heading 2 ##
### This is heading 3 ###
#### This is heading 4 ####
##### This is heading 5 #####
###### This is heading 6 ######

# Paragraf HTML #
Paragraf HTML didefinisikan dengan <p>tag:

Contoh
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

output
This is a paragraph

This is another paragraph. 

# Tautan HTML #
Tautan HTML didefinisikan dengan <a>tag:

Contoh
<a href="https://www.w3schools.com">This is a link</a>

output 
HTML Links

HTML links are defined with the a tag:

This is a link

Tujuan tautan ditetapkan dalam hrefatribut. 

Atribut digunakan untuk memberikan informasi tambahan tentang elemen HTML.


# Gambar HTML #
Gambar HTML didefinisikan dengan <img>tag.

File sumber ( src), teks alternatif ( alt), width, dan heightdisediakan sebagai atribut:

Contoh
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

output 
HTML Images
HTML images are defined with the img tag:
## berserta gambar w3school ##


Cara Melihat Sumber HTML
Pernahkah Anda melihat halaman Web dan bertanya-tanya, "Hei! Bagaimana mereka melakukannya?"

Lihat Kode Sumber HTML:
Klik CTRL + U di halaman HTML, atau klik kanan pada halaman dan pilih "Lihat Sumber Halaman". Ini akan membuka tab baru yang berisi kode sumber HTML halaman tersebut.

Periksa Elemen HTML:
Klik kanan pada elemen (atau area kosong), dan pilih "Periksa" untuk melihat elemen apa saja yang ada (Anda akan melihat HTML dan CSS). Anda juga dapat mengedit HTML atau CSS secara langsung di panel Elemen atau Gaya yang terbuka.


# Elemen HTML #
elemen HTML didefinisikan oleh tag awal, beberapa konten, dan tag akhir. 
 
## elemen HTML adalah segalanya dari tag awal hingga tag akhir:*

<tagname> konten ada disini... </tagname>

contoh beberapa elemen HTML:

< h1 > Judul Pertamaku < /h1 >

< p > Paragraf pertama saya. < /p >

## Start tag	   Element content      	End tag
   <h1>	        My First Heading	     </h1>
   <p>	         My first paragraph.	  </p>
   <br>        	none	                 none

Catatan: Beberapa elemen HTML tidak memiliki konten (seperti elemen <br>). Elemen-elemen ini disebut elemen kosong. Elemen kosong tidak memiliki tag penutup!

## Elemen HTML Bersarang ##
Elemen HTML dapat bersarang (ini berarti suatu elemen dapat berisi elemen lain).

Semua dokumen HTML terdiri dari elemen-elemen HTML yang bertingkat.

Contoh berikut berisi empat elemen HTML ( <html>, <body>, <h1> dan <p>):

Contoh
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

output
## My Firsh Heading ##
My firsh paragraph

Contoh Dijelaskan
Elemen tersebut <html>merupakan elemen akar dan mendefinisikan keseluruhan dokumen HTML.

Ia memiliki tag awal <html>dan tag akhir </html>.

Kemudian di dalam <html>elemen tersebut ada <body> elemen:

<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
Elemen <body>mendefinisikan isi dokumen.

Ia memiliki tag awal <body>dan tag akhir </body>.

Kemudian, di dalam <body>elemen tersebut ada dua elemen lainnya: <h1>dan <p>:

<h1>My First Heading</h1>
<p>My first paragraph.</p>
Elemen ini <h1>mendefinisikan sebuah judul.

Ini memiliki tag awal <h1>dan tag akhir </h1>:

<h1>My First Heading</h1>
Elemen <p>mendefinisikan sebuah paragraf.

Ini memiliki tag awal <p>dan tag akhir </p>:

<p>My first paragraph.</p>

## Jangan Pernah Melewatkan Tag Akhir ##
Beberapa elemen HTML akan ditampilkan dengan benar, bahkan jika Anda lupa tag penutup:

Contoh
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>

output

This is a paragraph.

This is a paragraph.

Namun, jangan pernah mengandalkan ini! Hasil yang tidak diharapkan dan kesalahan dapat terjadi jika Anda lupa tag penutup!

## Elemen HTML Kosong ##
Elemen HTML tanpa konten disebut elemen kosong.

Tag ini <br> mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup:

Contoh
<p>This is a <br> paragraph with a line break.</p>

output
This is a
paragraph with a line break.

## HTML tidak peka huruf besar/kecil ##
Tag HTML tidak peka huruf besar/kecil: <P>artinya sama dengan <p>.

Standar HTML tidak mengharuskan tag huruf kecil, tetapi W3C merekomendasikan huruf kecil dalam HTML, dan menuntut huruf kecil untuk jenis dokumen yang lebih ketat seperti XHTML.

### Di W3Schools kami selalu menggunakan nama tag huruf kecil. ###

## Referensi Tag HTML ##
Referensi tag W3Schools berisi informasi tambahan tentang tag ini dan atributnya.

###             Tag	Description ###
<html>	         Defines the root of an HTML document
<body>         	Defines the document's body
<h1> to <h6>   	Defines HTML headings


# Atribut HTML #
 Atribut HTML menyediakan informasi tambahan tentang elemen HTML.

## Atribut HTML
  Semua elemen HTML dapat memiliki atribut

  Atribut menyediakan informasi tambahan tentang elemen
  
  Atribut selalu ditentukan di tag awal
  
  Atribut biasanya datang dalam pasangan nama/nilai seperti: nama="nilai"
  
## Atribut href

Tag ini <a>mendefinisikan hyperlink. hrefAtribut menentukan URL halaman yang dituju oleh tautan tersebut:

Contoh
<a href="https://www.w3schools.com">Visit W3Schools</a>

OUTPUT

 The href Attribute
HTML links are defined with the a tag. The link address is specified in the href attribute:

Visit W3Schools

## Atribut src
Tag <img>ini digunakan untuk menyematkan gambar di halaman HTML. srcAtribut menentukan jalur ke gambar yang akan ditampilkan:

Contoh
<img src="img_girl.jpg">

OUTPUT

The src Attribute
HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:

Beserta foto seorang perempuan yang menghadap ke belakang


Ada dua cara untuk menentukan URL dalam src atribut:

1. URL Absolut - Tautan ke gambar eksternal yang dihosting di situs web lain. Contoh: src="https://www.w3schools.com/images/img_girl.jpg" .

Catatan: Gambar eksternal mungkin memiliki hak cipta. Jika Anda tidak memperoleh izin untuk menggunakannya, Anda mungkin melanggar undang-undang hak cipta. Selain itu, Anda tidak dapat mengontrol gambar eksternal; gambar tersebut dapat dihapus atau diubah secara tiba-tiba.

2. URL Relatif - Tautan ke gambar yang dihosting di dalam situs web. Di sini, URL tidak menyertakan nama domain. Jika URL dimulai tanpa garis miring, URL akan relatif terhadap halaman saat ini. Contoh: src="img_girl.jpg". Jika URL dimulai dengan garis miring, URL akan relatif terhadap domain. Contoh: src="/images/img_girl.jpg".

Kiat: Sebaiknya gunakan URL relatif. URL tersebut tidak akan rusak jika Anda mengubah domain.

## Atribut lebar dan tinggi
Tag <img>juga harus berisi atribut widthdan height, yang menentukan lebar dan tinggi gambar (dalam piksel):

Contoh
<img src="img_girl.jpg" width="500" height="600">

output
Width and Height Attributes
The width and height attributes of the img tag, defines the width and height of the image:
dengan perempuan yang mengahadap kebelakang

## Atribut alt
Atribut yang diperlukan altuntuk <img> tag menentukan teks alternatif untuk gambar, jika gambar tersebut tidak dapat ditampilkan karena suatu alasan. Hal ini dapat disebabkan oleh koneksi yang lambat, atau kesalahan pada srcatribut, atau jika pengguna menggunakan pembaca layar.

Contoh
<img src="img_girl.jpg" alt="Girl with a jacket">

output
The alt Attribute
The alt attribute should reflect the image content, so users who cannot see the image get an understanding of what the image contains: 
dengan seorang perempuan yang menghadap kebelakang


Contoh
Lihat apa yang terjadi jika kita mencoba menampilkan gambar yang tidak ada:

<img src="img_typo.jpg" alt="Girl with a jacket">

output
(foto tidak muncul) Girl with a jacket
If we try to display an image that does not exist, the value of the alt attribute will be displayed instead.

## Atribut gaya
Atribut styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.

Contoh
<p style="color:red;">This is a red paragraph.</p>

output
The style Attribute
The style attribute is used to add styles to an element, such as color:

This is a red paragraph. (tulisan berwarna merah)


## Atribut lang
Anda harus selalu menyertakan langatribut di dalam <html>tag, untuk menyatakan bahasa halaman Web. Hal ini dimaksudkan untuk membantu mesin pencari dan browser.

Contoh berikut menentukan bahasa Inggris sebagai bahasa:

<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>

Kode negara juga dapat ditambahkan ke kode bahasa dalam lang atribut. Jadi, dua karakter pertama menentukan bahasa halaman HTML, dan dua karakter terakhir menentukan negara.

Contoh berikut menentukan bahasa Inggris sebagai bahasa dan Amerika Serikat sebagai negara:

<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>

## Judul Atribut
Atribut titlemendefinisikan beberapa informasi tambahan tentang suatu elemen.

Nilai atribut judul akan ditampilkan sebagai keterangan alat saat Anda mengarahkan kursor ke elemen tersebut:

Contoh
<p title="I'm a tooltip">This is a paragraph.</p>

output
The title Attribute
Mouse over this paragraph, to display the title attribute as a tooltip.

## Disarankan: Selalu menggunakan atribut huruf kecil
Standar HTML tidak memerlukan nama atribut huruf kecil.

Atribut judul (dan semua atribut lainnya) dapat ditulis dengan huruf besar atau kecil seperti title atau TITLE .

Namun, W3C merekomendasikan atribut huruf kecil dalam HTML, dan menuntut atribut huruf kecil untuk tipe dokumen yang lebih ketat seperti XHTML.

Di W3Schools kami selalu menggunakan nama atribut huruf kecil.

## Disarankan: Selalu Kutip Nilai Atribut
Standar HTML tidak memerlukan tanda kutip di sekitar nilai atribut.

Namun, W3C merekomendasikan tanda kutip dalam HTML, dan menuntut tanda kutip untuk tipe dokumen yang lebih ketat seperti XHTML.

Bagus:
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
Buruk:
<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
Terkadang Anda harus menggunakan tanda kutip. Contoh ini tidak akan menampilkan atribut judul dengan benar, karena mengandung spasi:

Contoh
<p title=Description of W3Schools>

 output

 About W3Schools
You cannot omit quotes around an attribute value if the value contains spaces.

If you move the mouse over the paragraph above, your browser will only display the first word from the title.


### Di W3Schools kami selalu menggunakan tanda kutip di sekitar nilai atribut.

### Tanda kutip tunggal atau ganda?
Tanda kutip ganda di sekitar nilai atribut adalah yang paling umum dalam HTML, tetapi tanda kutip tunggal juga dapat digunakan.

Dalam beberapa situasi, ketika nilai atribut itu sendiri berisi tanda kutip ganda, maka perlu menggunakan tanda kutip tunggal:

<p title='John "ShotGun" Nelson'>
Atau sebaliknya:

<p title="John 'ShotGun' Nelson">


output

Single or Double Quotes?
In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

Move your mouse over the paragraphs below to see the effect:

John with double quotes

John with single quotes

# Judul HTML

Judul HTML adalah judul atau subjudul yang ingin ditampilkan di halaman web.

Contoh
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

coding 
<!DOCTYPE html>
<html>
<body>

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

</body>
</html>

output
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# Judul HTML
Judul HTML didefinisikan dengan tag <h1>to <h6>.

<h1>mendefinisikan judul yang paling penting. <h6>mendefinisikan judul yang paling tidak penting.

Contoh
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
Catatan: Peramban secara otomatis menambahkan spasi (margin) sebelum dan sesudah judul.


output

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# Judul Itu Penting
Mesin pencari menggunakan judul untuk mengindeks struktur dan konten halaman web.

Pengguna sering kali membaca sekilas halaman berdasarkan judulnya. Penting untuk menggunakan judul guna menunjukkan struktur dokumen.

<h1>Judul harus digunakan untuk judul utama, diikuti oleh <h2>judul-judul, lalu yang kurang penting <h3>, dan seterusnya.

Catatan: Gunakan judul HTML hanya untuk judul. Jangan gunakan judul untuk membuat teks BESAR atau tebal .

# Judul yang lebih besar
Setiap judul HTML memiliki ukuran default. Namun, Anda dapat menentukan ukuran untuk setiap judul dengan styleatribut, menggunakan properti CSS font-size:

Contoh
<h1 style="font-size:60px;">Heading 1</h1>

output
# Heading 1
You can change the size of a heading with the style attribute, using the font-size property.


# Paragraf HTML
Sebuah paragraf selalu dimulai pada baris baru dan biasanya berupa blok teks.



# Paragraf HTML
Elemen HTML <p>mendefinisikan sebuah paragraf.

Sebuah paragraf selalu dimulai pada baris baru, dan peramban secara otomatis menambahkan spasi (margin) sebelum dan sesudah paragraf.

Contoh
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

output
This is a paragraph.

This is a paragraph.

This is a paragraph


# Tampilan HTML
kita tidak dapat yakin bagaimana HTML akan ditampilkan.

Layar besar atau kecil, dan jendela yang diubah ukurannya akan menghasilkan hasil yang berbeda.

Dengan HTML, Anda tidak dapat mengubah tampilan dengan menambahkan spasi tambahan atau baris tambahan dalam kode HTML Anda.

Peramban akan secara otomatis menghapus spasi dan baris tambahan saat halaman ditampilkan:

Contoh
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>

output 

This paragraph contains a lot of lines in the source code, but the browser ignores it.

This paragraph contains a lot of spaces in the source code, but the browser ignores it.

The number of lines in a paragraph depends on the size of the browser window. If you resize the browser window, the number of lines in this paragraph will change.

# Aturan Horizontal HTML
Tag ini <hr>mendefinisikan pemisah tematik pada halaman HTML, dan paling sering ditampilkan sebagai aturan horizontal.

Elemen ini <hr>digunakan untuk memisahkan konten (atau menentukan perubahan) di halaman HTML:

Contoh
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

output 
# This is heading 1
This is some text.

## This is heading 2
This is some other text.

### This is heading 2
This is some other text.
Tag tersebut <hr>adalah tag kosong, artinya tidak memiliki tag akhir.

# Pemutusan Baris HTML
Elemen HTML <br>mendefinisikan jeda baris.

Gunakan <br>jika Anda menginginkan jeda baris (baris baru) tanpa memulai paragraf baru:

Contoh
<p>This is<br>a paragraph<br>with line breaks.</p>
Tag tersebut <br>adalah tag kosong, artinya tidak memiliki tag akhir.

output
This is
a paragraph
with line breaks.

# Masalah Puisi
Puisi ini akan ditampilkan dalam satu baris:

Contoh
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>

output

In HTML, spaces and new lines are ignored:

My Bonnie lies over the ocean. My Bonnie lies over the sea. My Bonnie lies over the ocean. Oh, bring back my Bonnie to me.


# Solusi - Elemen HTML <pre>
Elemen HTML <pre>mendefinisikan teks yang telah diformat sebelumnya.

Teks di dalam <pre>elemen ditampilkan dalam font dengan lebar tetap (biasanya Courier), dan mempertahankan spasi dan jeda baris:

Contoh
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>

output

The pre tag preserves both spaces and line breaks:

   My Bonnie lies over the ocean.

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.
   
   Oh, bring back my Bonnie to me.

# Gaya HTML

 Atribut HTML styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.

Contoh
Aku Merah (warna merah

Aku Biru (warna biru)

# Aku Besar

# Atribut Gaya HTML
Mengatur gaya suatu elemen HTML, dapat dilakukan dengan styleatribut.

Atribut HTML stylememiliki sintaksis berikut:

<tagname style="property:value;">
Properti adalah properti CSS. Nilai adalah nilai CSS .


# Warna Latar Belakang
Properti CSS background-colormendefinisikan warna latar belakang untuk elemen HTML.

Contoh
Mengatur warna latar belakang halaman menjadi biru muda:

<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>

output
This is a heading
This is a paragraph.
(latar biru) 

Contoh
Mengatur warna latar belakang untuk dua elemen berbeda:

<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>

output
# This is a heading (warna biru)
This is a paragraph.(warna oren)
# Warna Teks
Properti CSS colormendefinisikan warna teks untuk elemen HTML:

Contoh
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

output
 # This is a heading (warna biru)
This is a paragraph. (warna merah)

# Huruf
Properti CSS font-familymendefinisikan font yang akan digunakan untuk elemen HTML:

Contoh
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>

output

# This is a heading
This is a paragraph.


# Ukuran Teks
Properti CSS font-sizemendefinisikan ukuran teks untuk elemen HTML:

Contoh
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>

output
# This is a heading
This is a paragraph.


# Penyelarasan Teks
Properti CSS text-alignmendefinisikan perataan teks horizontal untuk elemen HTML:

Contoh
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>


 output
 # Centered Heading
   Centered paragraph.

# Pemformatan Teks HTML
HTML berisi beberapa elemen untuk mendefinisikan teks dengan makna khusus.

Contoh
This text is bold

This text is italic

This is subscript and superscript

output

### This text is bold

*This text is italic

This is subscript and superscript (kecil besar tulisannya)

# Elemen Pemformatan HTML
Elemen pemformatan dirancang untuk menampilkan jenis teks khusus:

<b>- Teks tebal
<strong>- Teks penting
<i>- Teks miring
<em>- Teks yang ditekankan
<mark>- Teks yang ditandai
<small>- Teks lebih kecil
<del>- Teks dihapus
<ins>- Teks yang disisipkan
<sub>- Teks subskrip
<sup>- Teks superskrip

# Elemen HTML <b> dan <strong>
Elemen HTML <b>mendefinisikan teks tebal, tanpa kepentingan tambahan apa pun.

Contoh
<b>This text is bold</b>

output 

This text is normal.

### This text is bold.

Elemen HTML <strong>mendefinisikan teks dengan kepentingan yang kuat. Konten di dalamnya biasanya ditampilkan dalam huruf tebal.

Contoh
<strong>This text is important!</strong>

output

This text is normal.

### This text is important!

# Elemen HTML <i> dan <em>
Elemen HTML <i>mendefinisikan bagian teks dalam gaya atau suasana alternatif. Konten di dalamnya biasanya ditampilkan dalam huruf miring.

Tip: Tag ini <i>sering digunakan untuk menunjukkan istilah teknis, frasa dari bahasa lain, pemikiran, nama kapal, dll.

Contoh
<i>This text is italic</i>

output
This text is normal.

* This text is italic.
  
Elemen HTML <em>mendefinisikan teks yang ditekankan. Konten di dalamnya biasanya ditampilkan dalam huruf miring.

Kiat: Pembaca layar akan mengucapkan kata-kata <em> dengan penekanan, menggunakan tekanan verbal.

Contoh
<em>This text is emphasized</em>

This text is normal.

* This text is emphasized.

# Elemen HTML <kecil>
Elemen HTML <small>mendefinisikan teks yang lebih kecil:

Contoh
<small>This is some smaller text.</small>

output
# This is some normal text.

This is some smaller text.

# Elemen HTML <mark>
Elemen HTML <mark>mendefinisikan teks yang harus ditandai atau disorot:

Contoh
<p>Do not forget to buy <mark>milk</mark> today.</p>

output
Do not forget to buy milk today.


# Elemen HTML <del>
Elemen HTML <del>mendefinisikan teks yang telah dihapus dari sebuah dokumen. Peramban biasanya akan mencoret teks yang dihapus dengan garis:

Contoh
<p>My favorite color is <del>blue</del> red.</p>

output 
My favorite color is blue red.


# Elemen HTML <ins>
Elemen HTML <ins>mendefinisikan teks yang telah disisipkan ke dalam dokumen. Peramban biasanya akan menggarisbawahi teks yang disisipkan:

Contoh
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

output
My favorite color is blue red.

# Elemen HTML <sub>
Elemen HTML <sub>mendefinisikan teks subskrip. Teks subskrip muncul setengah karakter di bawah garis normal, dan terkadang ditampilkan dalam font yang lebih kecil. Teks subskrip dapat digunakan untuk rumus kimia, seperti H 2 O:

Contoh
<p>This is <sub>subscripted</sub> text.</p>

output 

This is subscripted text.

# Elemen HTML <sup>
Elemen HTML <sup>mendefinisikan teks superskrip. Teks superskrip muncul setengah karakter di atas baris normal, dan terkadang ditampilkan dalam font yang lebih kecil. Teks superskrip dapat digunakan untuk catatan kaki, seperti WWW [1] :

Contoh
<p>This is <sup>superscripted</sup> text.</p>

 output
 This is superscripted text. (superscripted huruf kecil)
 
 # Elemen Kutipan dan Sitasi HTML
Dalam bab ini kita akan membahas elemen <blockquote>, <q>, <abbr>, <address>, <cite>, dan <bdo>HTML.

Contoh
Here is a quote from WWF's website:

For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.

output
Here is a quote from WWF's website:

For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.


# HTML <blockquote> untuk Kutipan
Elemen HTML <blockquote>mendefinisikan bagian yang dikutip dari sumber lain.

Peramban biasanya membuat indentasi <blockquote>pada elemen.

Contoh
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

output
Here is a quote from WWF's website:

For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
# HTML <q> untuk Kutipan Pendek
Tag HTML <q>mendefinisikan kutipan pendek.

Peramban biasanya menyisipkan tanda kutip di sekitar kutipan.

Contoh
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

output
Browsers usually insert quotation marks around the q element.

WWF's goal is to: Build a future where people live in harmony with nature.


# HTML <abbr> untuk Singkatan
Tag HTML <abbr>mendefinisikan singkatan atau akronim, seperti "HTML", "CSS", "Tuan", "Dr.", "ASAP", "ATM".

Menandai singkatan dapat memberikan informasi yang berguna bagi peramban, sistem penerjemahan, dan mesin pencari.

Kiat: Gunakan atribut judul global untuk menampilkan deskripsi singkatan/akronim saat Anda mengarahkan kursor ke elemen tersebut. 

Contoh
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

output
The WHO was founded in 1948.

Marking up abbreviations can give useful information to browsers, translation systems and search-engines.

# HTML <alamat> untuk Informasi Kontak
Tag HTML <address>mendefinisikan informasi kontak untuk penulis/pemilik dokumen atau artikel.

Informasi kontak dapat berupa alamat email, URL, alamat fisik, nomor telepon, pegangan media sosial, dll.

Teks dalam <address>elemen biasanya ditampilkan dalam huruf miring, dan peramban akan selalu menambahkan jeda baris sebelum dan sesudah <address>elemen.

Contoh
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

output
The HTML address element defines contact information (author/owner) of a document or article.

* Written by John Doe.
* Visit us at:
* Example.com
* Box 564, Disneyland
* USA


# HTML <cite> untuk Judul Karya
Tag HTML <cite>mendefinisikan judul suatu karya kreatif (misalnya buku, puisi, lagu, film, lukisan, patung, dll.).

#### Catatan: Nama seseorang bukanlah judul suatu karya.

Teks dalam <cite>elemen biasanya ditampilkan dalam huruf miring .

Contoh
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

output

The HTML cite element defines the title of a work.

Browsers usually display cite elements in italic.
 (adanya gambar)
The Scream
The Scream by Edvard Munch. Painted in 1893.

# HTML <bdo> untuk Penimpaan Dua Arah
BDO singkatan dari Bi-Directional Override.

Tag HTML <bdo>digunakan untuk mengganti arah teks saat ini:

Contoh
<bdo dir="rtl">This text will be written from right to left</bdo>

output
If your browser supports bi-directional override (bdo), the next line will be written from right to left (rtl):

This line will be written from right to left

# Elemen Kutipan dan Sitasi HTML
Tag          	Description
<abbr>	       Defines an abbreviation or acronym
<address>	    Defines contact information for the author/owner of a     document
<bdo>	        Defines the text direction
<blockquote>	 Defines a section that is quoted from another source
<cite>	       Defines the title of a work
<q>	          Defines a short inline quotation

# Komentar HTML
Komentar HTML tidak ditampilkan di browser, tetapi dapat membantu mendokumentasikan kode sumber HTML Anda.

# Tag Komentar HTML
Anda dapat menambahkan komentar ke sumber HTML Anda dengan menggunakan sintaks berikut:

<!-- Write your comments here -->
Perhatikan bahwa ada tanda seru (!) di tag awal, tetapi tidak di tag akhir.

Catatan: Komentar tidak ditampilkan oleh browser, tetapi dapat membantu mendokumentasikan kode sumber HTML Anda.

# Tambahkan Komentar
Dengan komentar Anda dapat menempatkan pemberitahuan dan pengingat dalam kode HTML Anda:

Contoh
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->

output
This is a paragraph.


# Komentar HTML
Komentar HTML tidak ditampilkan di browser, tetapi dapat membantu mendokumentasikan kode sumber HTML Anda.

# Tag Komentar HTML
Anda dapat menambahkan komentar ke sumber HTML Anda dengan menggunakan sintaks berikut:

<!-- Write your comments here -->
Perhatikan bahwa ada tanda seru (!) di tag awal, tetapi tidak di tag akhir.

Catatan: Komentar tidak ditampilkan oleh browser, tetapi dapat membantu mendokumentasikan kode sumber HTML Anda.

# Tambahkan Komentar
Dengan komentar Anda dapat menempatkan pemberitahuan dan pengingat dalam kode HTML Anda:

Contoh
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->

output
This is a paragraph.


# Sembunyikan Konten
Komentar dapat digunakan untuk menyembunyikan konten.

Ini dapat membantu jika Anda menyembunyikan konten untuk sementara:

Contoh
<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>

output
This is a paragraph.

This is a paragraph too.

Anda juga dapat menyembunyikan lebih dari satu baris. Semua yang ada di antara <!--dan --> akan disembunyikan dari tampilan.

# Contoh
Sembunyikan bagian kode HTML:

<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>

output
This is a paragraph.

This is a paragraph too.


Komentar juga bagus untuk men-debug HTML, karena Anda dapat mengomentari baris kode HTML, satu per satu, untuk mencari kesalahan.


# Sembunyikan Konten Sebaris
Komentar dapat digunakan untuk menyembunyikan bagian di tengah kode HTML.

Contoh
Sembunyikan bagian paragraf:

<p>This <!-- great text --> is a paragraph.</p>

output
This is a paragraph.


# Sembunyikan Konten 
Komentar dapat digunakan untuk menyembunyikan konten.

Ini dapat membantu jika Anda menyembunyikan konten untuk sementara:

## Contoh
<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>

output
This is a paragraph.
 This is a paragraph too.
 
## Contoh
Sembunyikan bagian kode HTML:

<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>

output
This is a paragraph.

This is a paragraph too.


Komentar juga bagus untuk men-debug HTML, karena Anda dapat mengomentari baris kode HTML, satu per satu, untuk mencari kesalahan.


# Sembunyikan Konten Sebaris
Komentar dapat digunakan untuk menyembunyikan bagian di tengah kode HTML.

Contoh
Sembunyikan bagian paragraf:

<p>This <!-- great text --> is a paragraph.</p>

output
This is a paragraph.


# Warna HTML
Warna HTML ditentukan dengan nama warna yang telah ditetapkan sebelumnya, atau dengan nilai RGB, HEX, HSL, RGBA, atau HSLA.

# Nama Warna
Dalam HTML, warna dapat ditentukan dengan menggunakan nama warna:

Tomat
Oranye
Dodger Biru
SedangLautHijau
Abu-abu
Batu tulis biru
Ungu
Abu-abu Muda

## Warna Latar Belakang
Anda dapat mengatur warna latar belakang untuk elemen HTML:

Halo Dunia

Lorem ipsum dolor sit amet, pembentuk adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Dengan sedikit racun, latihan kami yang ullamcorper suscipit lobortis tidak akan keluar dari komodo yang diakibatkannya.

Contoh
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>

output

# Hello World

### Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.


# Warna Teks
Anda dapat mengatur warna teks:

Halo Dunia
Lorem ipsum dolor sit amet, pembentuk adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.

Dengan sedikit racun, latihan kami yang ullamcorper suscipit lobortis tidak akan keluar dari komodo yang diakibatkannya.

Contoh
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

output

Hello World
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.

Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.

# Warna Batas
Anda dapat mengatur warna batas:

Halo Dunia
Halo Dunia
Halo Dunia
Contoh
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>

output
### Hello World
### Hello World
### Hello World

# Nilai Warna
Dalam HTML, warna juga dapat ditentukan menggunakan nilai RGB, nilai HEX, nilai HSL, nilai RGBA, dan nilai HSLA.

Tiga elemen <div> berikut memiliki warna latar belakang yang diatur dengan nilai RGB, HEX, dan HSL:

warna merah(255, 99, 71)
#ff6347
hsl(9, 100%, 64%)
Dua elemen <div> berikut memiliki warna latar belakang yang diatur dengan nilai RGBA dan HSLA, yang menambahkan saluran Alpha ke warna (di sini kita memiliki transparansi 50%):

rgba(255, 99, 71, 0,5)
hsla(9, 100%, 64%, 0,5)
Contoh
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>

output

Same as color name "Tomato":

rgb(255, 99, 71)
#ff6347
hsl(9, 100%, 64%)

Same as color name "Tomato", but 50% transparent:

rgba(255, 99, 71, 0.5)
hsla(9, 100%, 64%, 0.5)
In addition to the predefined color names, colors can be specified using RGB, HEX, HSL, or even transparent colors using RGBA or HSLA color values.


# Warna HTML RGB dan RGBA
Nilai warna RGB mewakili sumber cahaya MERAH, HIJAU, dan BIRU.

Nilai warna RGBA merupakan perluasan dari RGB dengan saluran Alfa (opasitas).

# Nilai Warna RGB
Dalam HTML, warna dapat ditentukan sebagai nilai RGB, menggunakan rumus ini:

# rgb ( merah, hijau , biru )

Setiap parameter (merah, hijau, dan biru) menentukan intensitas warna dengan nilai antara 0 dan 255.

Ini berarti ada 256 x 256 x 256 = 16777216 kemungkinan warna!

Misalnya, rgb(255, 0, 0) ditampilkan sebagai merah, karena merah ditetapkan ke nilai tertingginya (255), dan dua lainnya (hijau dan biru) ditetapkan ke 0.

Contoh lain, rgb(0, 255, 0) ditampilkan sebagai hijau, karena hijau ditetapkan ke nilai tertingginya (255), dan dua lainnya (merah dan biru) ditetapkan ke 0.

Untuk menampilkan warna hitam, atur semua parameter warna ke 0, seperti ini: rgb(0, 0, 0).

Untuk menampilkan warna putih, atur semua parameter warna ke 255, seperti ini: rgb(255, 255, 255).

Contoh
rgb(255, 0, 0)
rgb(0, 0, 255)
rgb(60, 179, 113)
rgb(238, 130, 238)
rgb(255, 165, 0)
rgb(106, 90, 205)

output
rgb(255, 0, 0)
rgb(0, 0, 255)
rgb(60, 179, 113)
rgb(238, 130, 238)
rgb(255, 165, 0)
rgb(106, 90, 205)

# Nuansa Abu-abu
Nuansa abu-abu sering kali didefinisikan menggunakan nilai yang sama untuk ketiga parameter:

Contoh
rgb(60, 60, 60)
rgb(100, 100, 100)
rgb(140, 140, 140)
rgb(180, 180, 180)
rgb(200, 200, 200)
rgb(240, 240, 240)

output
rgb(60, 60, 60)
rgb(100, 100, 100)
rgb(140, 140, 140)
rgb(180, 180, 180)
rgb(200, 200, 200)
rgb(240, 240, 240)

abu tua ke muda

# Nilai Warna RGBA
Nilai warna RGBA merupakan perluasan nilai warna RGB dengan saluran Alfa - yang menentukan opasitas suatu warna.

Nilai warna RGBA ditentukan dengan:

#### rgba ( merah, hijau , biru, alfa )

Parameter alpha adalah angka antara 0,0 (sepenuhnya transparan) dan 1,0 (tidak transparan sama sekali):

Contoh
rgba(255, 99, 71, 0)
rgba(255, 99, 71, 0.2)
rgba(255, 99, 71, 0.4)
rgba(255, 99, 71, 0.6)
rgba(255, 99, 71, 0.8)
rgba(255, 99, 71, 1)

output

rgba(255, 99, 71, 0)
rgba(255, 99, 71, 0.2)
rgba(255, 99, 71, 0.4)
rgba(255, 99, 71, 0.6)
rgba(255, 99, 71, 0.8)
rgba(255, 99, 71, 1)

putih ke pink tua

# Warna HTML HEX
Warna heksadesimal ditentukan dengan: #RRGGBB, di mana bilangan bulat heksadesimal RR (merah), GG (hijau), dan BB (biru) menentukan komponen warna.

# Nilai Warna HEX
Dalam HTML, warna dapat ditentukan menggunakan nilai heksadesimal dalam bentuk:

###### rrggbb​

Di mana rr (merah), gg (hijau), dan bb (biru) adalah nilai heksadesimal antara 00 dan ff (sama dengan desimal 0-255).

Misalnya, #ff0000 ditampilkan sebagai merah, karena merah ditetapkan ke nilai tertingginya (ff), dan dua lainnya (hijau dan biru) ditetapkan ke 00.

Contoh lain, #00ff00 ditampilkan sebagai hijau, karena hijau ditetapkan ke nilai tertingginya (ff), dan dua lainnya (merah dan biru) ditetapkan ke 00.

Untuk menampilkan warna hitam, atur semua parameter warna ke 00, seperti ini: #000000.

Untuk menampilkan warna putih, atur semua parameter warna ke ff, seperti ini: #ffffff.

Lakukan percobaan dengan mencampur nilai HEX di bawah ini:

#ff6347

Contoh
#ff0000
#0000ff
#3cb371
#ee82ee
#ffa500
#6a5acd

output
#ff0000 (merah)
#0000ff (biru)
#3cb371 (hijau)
#ee82ee (ungu)
#ffa500 (kuning)
#6a5acd (biru muda)

# Nuansa Abu-abu
Nuansa abu-abu sering kali didefinisikan menggunakan nilai yang sama untuk ketiga parameter:

Contoh
#404040
#686868
#a0a0a0
#bebebe
#dcdcdc
#f8f8f8

output
#404040 (abu tua)
#686868 (abu tua muda)
#a0a0a0 (abu muda)
#bebebe (abu muda-muda)
#dcdcdc (abu paling muda)
#f8f8f8 (putih)

# Warna HTML HSL dan HSLA
HSL merupakan singkatan dari hue (rona), saturation (saturasi), dan lightness (kecerahan).

Nilai warna HSLA merupakan perluasan dari HSL dengan saluran Alfa (opasitas).

# Nilai Warna HSL
Dalam HTML, warna dapat ditentukan menggunakan rona, saturasi, dan kecerahan (HSL) dalam bentuk:

### hsl( rona , saturasi , kecerahan )

Rona adalah derajat pada roda warna dari 0 hingga 360. 0 adalah merah, 120 adalah hijau, dan 240 adalah biru.

Saturasi adalah nilai persentase. 0% berarti corak abu-abu, dan 100% merupakan warna penuh.

Kecerahan juga merupakan nilai persentase. 0% berwarna hitam, dan 100% berwarna putih.

Lakukan percobaan dengan mencampur nilai HSL di bawah ini:

## Contoh
hsl(0, 100%, 50%)
hsl(240, 100%, 50%)
hsl(147, 50%, 47%)
hsl(300, 76%, 72%)
hsl(39, 100%, 50%)
hsl(248, 53%, 58%)

output
hsl(0, 100%, 50%)        merah
hsl(240, 100%, 50%)      biru
hsl(147, 50%, 47%)       hijau
hsl(300, 76%, 72%)       pink
hsl(39, 100%, 50%)       kuning
hsl(248, 53%, 58%)       ungu

# Kejenuhan
Saturasi dapat digambarkan sebagai intensitas warna.

100% adalah warna murni, tidak ada nuansa abu-abu.

50% adalah 50% abu-abu, tetapi Anda masih dapat melihat warnanya.

0% sepenuhnya abu-abu; Anda tidak dapat lagi melihat warnanya.

# Contoh
hsl(0, 100%, 50%)
hsl(0, 80%, 50%)
hsl(0, 60%, 50%)
hsl(0, 40%, 50%)
hsl(0, 20%, 50%)
hsl(0, 0%, 50%)

output
hsl(0, 100%, 50%)  merah
hsl(0, 80%, 50%)   merah muda
hsl(0, 60%, 50%)   pink agak muda
hsl(0, 40%, 50%)   pink muda
hsl(0, 20%, 50%)   pink muda
hsl(0, 0%, 50%)    abu
With HSL colors, less saturation mean less color. 0% is completely gray.


# Keringanan
Tingkat kecerahan suatu warna dapat dijelaskan dengan seberapa banyak cahaya yang ingin Anda berikan pada warna tersebut, di mana 0% berarti tidak ada cahaya (hitam), 50% berarti 50% cahaya (tidak gelap maupun terang), dan 100% berarti kecerahan penuh (putih).

Contoh
hsl(0, 100%, 0%)      hitam
hsl(0, 100%, 25%)     maron 
hsl(0, 100%, 50%)     merah
hsl(0, 100%, 75%)     pink
hsl(0, 100%, 90%)     pink muda
hsl(0, 100%, 100%)    putih

# Nuansa Abu-abu
Nuansa abu-abu sering kali ditentukan dengan mengatur rona dan saturasi ke angka 0, dan menyesuaikan kecerahan dari 0% hingga 100% untuk mendapatkan nuansa yang lebih gelap/lebih terang:

Contoh
hsl(0, 0%, 20%) abu tua
hsl(0, 0%, 30%)
hsl(0, 0%, 40%)
hsl(0, 0%, 60%)
hsl(0, 0%, 70%)
hsl(0, 0%, 90%) putih

# Nilai Warna HSLA
Nilai warna HSLA merupakan perluasan dari nilai warna HSL, dengan saluran Alfa - yang menentukan opasitas suatu warna.

Nilai warna HSLA ditentukan dengan:

hsla ( rona, saturasi , kecerahan, alfa )

Parameter alpha adalah angka antara 0,0 (sepenuhnya transparan) dan 1,0 (tidak transparan sama sekali):

Contoh
hsla(9, 100%, 64%, 0)
hsla(9, 100%, 64%, 0.2)
hsla(9, 100%, 64%, 0.4)
hsla(9, 100%, 64%, 0.6)
hsla(9, 100%, 64%, 0.8)
hsla(9, 100%, 64%, 1)

output
putih sampai orange


# Gaya HTML - CSS
CSS singkatan dari Cascading Style Sheets.

CSS menghemat banyak pekerjaan. CSS dapat mengendalikan tata letak beberapa halaman web sekaligus.

## CSS = Gaya dan Warna
Memanipulasi Teks
Warna,  Kotak

# Apa itu CSS?
Cascading Style Sheets (CSS) digunakan untuk memformat tata letak halaman web.

Dengan CSS, Anda dapat mengontrol warna, font, ukuran teks, jarak antar elemen, bagaimana elemen diposisikan dan ditata, gambar latar belakang atau warna latar belakang apa yang akan digunakan, tampilan berbeda untuk perangkat dan ukuran layar berbeda, dan banyak lagi!

Kiat: Kata cascading berarti bahwa gaya yang diterapkan pada elemen induk juga akan berlaku pada semua elemen anak dalam induk. Jadi, jika Anda menyetel warna teks isi menjadi "biru", semua judul, paragraf, dan elemen teks lainnya dalam isi juga akan mendapatkan warna yang sama (kecuali Anda menentukan hal lain)!

# Menggunakan CSS
CSS dapat ditambahkan ke dokumen HTML dengan 3 cara:

     Inline - dengan menggunakan styleatribut di dalam elemen HTML
     Internal - dengan menggunakan <style>elemen di <head>bagian
     Eksternal - dengan menggunakan <link> elemen untuk menautkan ke file CSS eksternal
     
Cara yang paling umum untuk menambahkan CSS adalah dengan mempertahankan gaya dalam berkas CSS eksternal. Namun, dalam tutorial ini kita akan menggunakan gaya internal dan inline, karena cara ini lebih mudah didemonstrasikan dan lebih mudah bagi Anda untuk mencobanya sendiri.

# CSS sebaris
CSS sebaris digunakan untuk menerapkan gaya unik pada satu elemen HTML.

CSS sebaris menggunakan styleatribut elemen HTML.

Contoh berikut menetapkan warna teks <h1>elemen menjadi biru, dan warna teks elemen <p>menjadi merah:

# Contoh
<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>

output
# A Blue Heading
A red paragraph.

# CSS internal
CSS internal digunakan untuk menentukan gaya untuk satu halaman HTML.

CSS internal didefinisikan di <head>bagian halaman HTML, dalam suatu <style>elemen.

Contoh berikut menetapkan warna teks SEMUA <h1>elemen (pada halaman tersebut) menjadi biru, dan warna teks SEMUA elemen <p>menjadi merah. Selain itu, halaman akan ditampilkan dengan warna latar belakang "powderblue": 

Contoh
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

output
# This is a heading (biru)
## This is a paragraph. (merah)


# CSS Eksternal
Lembar gaya eksternal digunakan untuk menentukan gaya untuk banyak halaman HTML.

Untuk menggunakan lembar gaya eksternal, tambahkan tautan ke lembar gaya tersebut di <head>bagian setiap halaman HTML:

Contoh
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

output
# This is a heading
This is a paragraph.

Lembar gaya eksternal dapat ditulis dalam editor teks apa pun. File tidak boleh berisi kode HTML apa pun, dan harus disimpan dengan ekstensi .css.

Berikut ini adalah tampilan file "styles.css":

"gaya.css":
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
Kiat: Dengan lembar gaya eksternal, Anda dapat mengubah tampilan seluruh situs web, dengan mengubah satu berkas!

# Warna, Font, dan Ukuran CSS
Di sini, kami akan menunjukkan beberapa properti CSS yang umum digunakan. Anda akan mempelajarinya lebih lanjut nanti.

Properti CSS colormenentukan warna teks yang akan digunakan.

Properti CSS font-familymendefinisikan font yang akan digunakan.

Properti CSS font-sizemenentukan ukuran teks yang akan digunakan.

Contoh
Penggunaan properti warna CSS, font-family dan font-size:

<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

output
# This is a heading (biru)
### This is a paragraph. (merah)

# Batas CSS
Properti CSS bordermendefinisikan batas di sekitar elemen HTML.

Tip: Anda dapat menentukan batas untuk hampir semua elemen HTML.

Contoh
Penggunaan properti border CSS: 

p {
  border: 2px solid powderblue;
}

 output
 
# This is a heading
This is a paragraph.

This is a paragraph.

This is a paragraph.
(ada tabelnya)


# Tautan HTML
Tautan ditemukan di hampir semua halaman web. Tautan memungkinkan pengguna untuk mengeklik dari satu halaman ke halaman lainnya.

# Tautan HTML - Hyperlink
Tautan HTML adalah hyperlink.

Anda dapat mengeklik tautan dan melompat ke dokumen lain.

Saat Anda menggerakkan mouse pada suatu tautan, panah mouse akan berubah menjadi tangan kecil.

Catatan: Tautan tidak harus berupa teks. Tautan dapat berupa gambar atau elemen HTML lainnya!

# Tautan HTML - Sintaksis
Tag HTML <a>mendefinisikan hyperlink. Tag ini memiliki sintaks berikut:

<a href="url">link text</a>
Atribut yang paling penting dari <a> elemen adalah hrefatribut, yang menunjukkan tujuan tautan.

Teks tautan adalah bagian yang akan terlihat oleh pembaca.

Mengklik teks tautan akan mengarahkan pembaca ke alamat URL yang ditentukan.

Contoh
Contoh ini menunjukkan cara membuat tautan ke W3Schools.com:

<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
Secara default, tautan akan muncul seperti berikut di semua browser:

Tautan yang belum dikunjungi diberi garis bawah dan berwarna biru
Tautan yang telah dikunjungi digarisbawahi dan berwarna ungu
Tautan aktif digaris bawahi dan berwarna merah
Tip: Tautan tentu saja dapat diberi gaya dengan CSS, untuk mendapatkan tampilan lain!

# Tautan HTML - Atribut Target
Secara default, halaman yang ditautkan akan ditampilkan di jendela browser saat ini. Untuk mengubahnya, Anda harus menentukan target lain untuk tautan tersebut.

Atribut targetmenentukan tempat untuk membuka dokumen yang ditautkan.

Atribut targetdapat memiliki salah satu nilai berikut:

_self- Default. Membuka dokumen di jendela/tab yang sama saat diklik
_blank- Membuka dokumen di jendela atau tab baru
_parent- Membuka dokumen di bingkai induk
_top- Membuka dokumen di badan penuh jendela
Contoh
Gunakan target="_blank" untuk membuka dokumen tertaut di jendela atau tab browser baru:

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

output

# The target Attribute
Visit W3Schools!
If target="_blank", the link will open in a new browser window or tab.


# URL Absolut vs. URL Relatif
Kedua contoh di atas menggunakan URL absolut (alamat web lengkap) dalam hrefatribut.

Tautan lokal (tautan ke halaman dalam situs web yang sama) ditentukan dengan URL relatif (tanpa bagian "https://www"):

Contoh
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

output
# Absolute URLs
W3C

Google

# Relative URLs
HTML Images

CSS Tutorial


# Tautan HTML - Gunakan Gambar sebagai Tautan
Untuk menggunakan gambar sebagai tautan, cukup masukkan <img> tag di dalam <a>tag:

Contoh
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

 output
 
 Image as a Link
The image below is a link. Try to click on it.
emote

# Tautan ke Alamat Email
Gunakan mailto:di dalam hrefatribut untuk membuat tautan yang membuka program email pengguna (agar mereka dapat mengirim email baru):

Contoh
<a href="mailto:someone@example.com">Send email</a>

output
## Link to an Email Address
To create a link that opens in the user's email program (to let them send a new email), use mailto: inside the href attribute:

Send email

# Tombol sebagai Tautan
Untuk menggunakan tombol HTML sebagai tautan, Anda harus menambahkan beberapa kode JavaScript.

JavaScript memungkinkan Anda menentukan apa yang terjadi pada peristiwa tertentu, seperti mengklik tombol:

Contoh
<button onclick="document.location='default.asp'">HTML Tutorial</button> 

output
# Button as a Links
Click the button to go to the HTML tutorial.

HTML Tutorial (tabel)

# Judul Tautan
Atribut ini titlemenentukan informasi tambahan tentang suatu elemen. Informasi ini paling sering ditampilkan sebagai teks keterangan alat saat mouse bergerak di atas elemen tersebut.

Contoh
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>

output

# Link Titles
The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

Visit our HTML Tutorial

# Lebih lanjut tentang URL Absolut dan URL Relatif
Contoh
Gunakan URL lengkap untuk menautkan ke halaman web: 

<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>

output

# External Paths
This example uses a full URL to link to a web page:

HTML tutorial

Contoh
Tautan ke halaman yang terletak di folder html di situs web saat ini: 

<a href="/html/default.asp">HTML tutorial</a>

output


# External Paths
This example links to a page located in the html folder on the current web site:

HTML tutorial

Contoh
Tautan ke halaman yang terletak di folder yang sama dengan halaman saat ini: 

<a href="default.asp">HTML tutorial</a>

output

# External Paths
This example links to a page located in the same folder as the current page:

HTML tutorial

Contoh
Tautan ke halaman yang terletak di folder yang sama dengan halaman saat ini: 

<a href="default.asp">HTML tutorial</a>

output

# External Paths
This example links to a page located in the same folder as the current page:

HTML tutorial


Tautan HTML - Berbagai Warna
Tautan HTML ditampilkan dalam warna berbeda tergantung pada apakah tautan tersebut telah dikunjungi, belum dikunjungi, atau aktif.

Warna Tautan HTML
Secara default, tautan akan muncul seperti ini (di semua browser):

Tautan yang belum dikunjungi diberi garis bawah dan berwarna biru
Tautan yang telah dikunjungi digarisbawahi dan berwarna ungu
Tautan aktif digaris bawahi dan berwarna merah
Anda dapat mengubah warna status tautan dengan menggunakan CSS:

Contoh
Di sini, tautan yang belum dikunjungi akan berwarna hijau tanpa garis bawah. Tautan yang dikunjungi akan berwarna merah muda tanpa garis bawah. Tautan yang aktif akan berwarna kuning dan bergaris bawah. Selain itu, saat mengarahkan kursor ke tautan (a:hover), tautan akan berubah menjadi merah dan bergaris bawah:

<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
IKLAN

Tombol Tautan
Sebuah tautan juga dapat diberi gaya seperti tombol, dengan menggunakan CSS:

Ini adalah tautannya
Contoh
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>  
Tautan HTML - Berbagai Warna
Tautan HTML ditampilkan dalam warna berbeda tergantung pada apakah tautan tersebut telah dikunjungi, belum dikunjungi, atau aktif.

Warna Tautan HTML
Secara default, tautan akan muncul seperti ini (di semua browser):

Tautan yang belum dikunjungi diberi garis bawah dan berwarna biru
Tautan yang telah dikunjungi digarisbawahi dan berwarna ungu
Tautan aktif digaris bawahi dan berwarna merah
Anda dapat mengubah warna status tautan dengan menggunakan CSS:

Contoh
Di sini, tautan yang belum dikunjungi akan berwarna hijau tanpa garis bawah. Tautan yang dikunjungi akan berwarna merah muda tanpa garis bawah. Tautan yang aktif akan berwarna kuning dan bergaris bawah. Selain itu, saat mengarahkan kursor ke tautan (a:hover), tautan akan berubah menjadi merah dan bergaris bawah:

<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
IKLAN

Tombol Tautan
Sebuah tautan juga dapat diberi gaya seperti tombol, dengan menggunakan CSS:

Ini adalah tautannya
Contoh
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
Tautan HTML - Buat Bookmark
Tautan HTML dapat digunakan untuk membuat penanda halaman, sehingga pembaca dapat melompat ke bagian tertentu pada halaman web.

Membuat Bookmark dalam HTML
Bookmark dapat berguna jika halaman web sangat panjang.

Untuk membuat penanda buku - pertama buat penanda buku, lalu tambahkan tautan ke dalamnya.

Ketika tautan diklik, halaman akan bergulir ke bawah atau ke atas ke lokasi yang terdapat penanda halaman.

Contoh
Pertama, gunakan idatribut untuk membuat bookmark:

<h2 id="C4">Chapter 4</h2>
Kemudian, tambahkan tautan ke penanda buku ("Lompat ke Bab 4"), dari dalam halaman yang sama:

Contoh
<a href="#C4">Jump to Chapter 4</a>
Gambar HTML
Gambar dapat meningkatkan desain dan tampilan halaman web.

Contoh
<img src="pic_trulli.jpg" alt="Italian Trulli">
Contoh
<img src="img_girl.jpg" alt="Girl in a jacket">
Contoh
<img src="img_chania.jpg" alt="Flowers in Chania">
Sintaksis Gambar HTML
Tag HTML <img>digunakan untuk menanamkan gambar di halaman web.

Secara teknis, gambar tidak dimasukkan ke dalam halaman web; gambar ditautkan ke halaman web. <img>Tag tersebut menciptakan ruang penyimpanan untuk gambar yang dirujuk.

Tag tersebut <img>kosong, hanya berisi atribut dan tidak memiliki tag penutup.

Tag <img>memiliki dua atribut yang diperlukan:

src - Menentukan jalur ke gambar
alt - Menentukan teks alternatif untuk gambar
Sintaksis
<img src="url" alt="alternatetext">
Atribut src
Atribut yang diperlukan srcmenentukan jalur (URL) ke gambar.

Catatan: Saat halaman web dimuat, pada saat itulah browser mengambil gambar dari server web dan memasukkannya ke dalam halaman. Oleh karena itu, pastikan gambar benar-benar berada di tempat yang sama dalam kaitannya dengan halaman web, jika tidak, pengunjung Anda akan mendapatkan ikon tautan rusak. Ikon tautan rusak dan altteks akan ditampilkan jika browser tidak dapat menemukan gambar tersebut.

Contoh
<img src="img_chania.jpg" alt="Flowers in Chania">

Atribut alt
Atribut yang diperlukan altmenyediakan teks alternatif untuk gambar, jika pengguna karena alasan tertentu tidak dapat melihatnya (karena koneksi yang lambat, kesalahan pada atribut src, atau jika pengguna menggunakan pembaca layar).

Nilai altatribut harus menjelaskan gambar:

Contoh
<img src="img_chania.jpg" alt="Flowers in Chania">
Jika browser tidak dapat menemukan gambar, maka browser akan menampilkan nilai alt atribut:

Contoh
<img src="wrongname.gif" alt="Flowers in Chania">
Kiat: Pembaca layar adalah program perangkat lunak yang membaca kode HTML, dan memungkinkan pengguna untuk "mendengarkan" kontennya. Pembaca layar berguna bagi orang-orang yang memiliki gangguan penglihatan atau kesulitan belajar.

Ukuran Gambar - Lebar dan Tinggi
Anda dapat menggunakan styleatribut untuk menentukan lebar dan tinggi gambar.

Contoh
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
Sebagai alternatif, Anda dapat menggunakan atribut widthdan height:

Contoh
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
Atribut widthdan heightselalu menentukan lebar dan tinggi gambar dalam piksel.

Catatan: Selalu tentukan lebar dan tinggi gambar. Jika lebar dan tinggi tidak ditentukan, halaman web mungkin berkedip saat gambar dimuat.

Lebar dan Tinggi, atau Gaya?
Atribut width, height, dan stylesemuanya valid dalam HTML.

Namun, kami sarankan untuk menggunakan styleatribut ini. Atribut ini mencegah lembar gaya mengubah ukuran gambar:

Contoh
<!DOCTYPE html>
<html>
<head>
<style>
img {
  width: 100%;
}
</style>
</head>
<body>

<img src="html5.gif" alt="HTML5 Icon" width="128" height="128">

<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

</body>
</html>
Gambar di Folder Lain
Jika Anda memiliki gambar di sub-folder, Anda harus menyertakan nama folder dalam srcatribut:

Contoh
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
Gambar di Server/Situs Web Lain
Beberapa situs web menunjuk ke gambar di server lain.

Untuk menunjuk ke gambar di server lain, Anda harus menentukan URL absolut (lengkap) dalam srcatribut:

Contoh
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
Catatan tentang gambar eksternal: Gambar eksternal mungkin memiliki hak cipta. Jika Anda tidak memperoleh izin untuk menggunakannya, Anda mungkin melanggar undang-undang hak cipta. Selain itu, Anda tidak dapat mengontrol gambar eksternal; gambar tersebut dapat dihapus atau diubah secara tiba-tiba.

Gambar Animasi
HTML memperbolehkan GIF animasi:

Contoh
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">
Gambar sebagai Tautan
Untuk menggunakan gambar sebagai tautan, letakkan <img>tag di dalam <a> tag:

Contoh
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
Gambar Mengambang
Gunakan properti CSS floatuntuk membiarkan gambar melayang ke kanan atau ke kiri teks:

Contoh
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>
Peta Gambar HTML
Dengan peta gambar HTML, Anda dapat membuat area yang dapat diklik pada gambar.

Peta Gambar
Tag HTML <map>mendefinisikan peta gambar. Peta gambar adalah gambar dengan area yang dapat diklik. Area tersebut didefinisikan dengan satu atau beberapa <area>tag.

Cobalah klik komputer, telepon, atau cangkir kopi pada gambar di bawah ini:

Tempat kerja
Contoh
Berikut adalah kode sumber HTML untuk peta gambar di atas:

<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>
Bagaimana cara kerjanya?
Ide di balik peta gambar adalah Anda harus dapat melakukan tindakan yang berbeda-beda, tergantung pada bagian gambar mana yang Anda klik.

Untuk membuat peta gambar, Anda memerlukan gambar dan beberapa kode HTML yang menjelaskan area yang dapat diklik.

IKLAN

Gambar
Gambar disisipkan menggunakan <img>tag. Satu-satunya perbedaan dari gambar lain adalah Anda harus menambahkan usemapatribut:

<img src="workplace.jpg" alt="Workplace" usemap="#workmap">
Nilai usemapdiawali dengan tagar #diikuti dengan nama peta gambar, dan digunakan untuk membuat hubungan antara gambar dan peta gambar.

Tips: Anda dapat menggunakan gambar apa pun sebagai peta gambar!

Buat Peta Gambar
Lalu, tambahkan <map>elemen.

Elemen ini <map>digunakan untuk membuat peta gambar, dan ditautkan ke gambar dengan menggunakan name atribut yang diperlukan:

<map name="workmap">
Atribut nameharus memiliki nilai yang sama dengan atribut <img>'s usemap.

Daerah
Lalu, tambahkan area yang dapat diklik.

Area yang dapat diklik didefinisikan menggunakan <area>elemen.

Membentuk
Anda harus menentukan bentuk area yang dapat diklik, dan Anda dapat memilih salah satu nilai berikut:

rect- mendefinisikan wilayah persegi panjang
circle- mendefinisikan wilayah melingkar
poly- mendefinisikan wilayah poligonal
default- mendefinisikan seluruh wilayah
Anda juga harus menentukan beberapa koordinat untuk dapat menempatkan area yang dapat diklik pada gambar. 

Bentuk="persegi panjang"
Koordinat shape="rect"datang berpasangan, satu untuk sumbu x dan satu untuk sumbu y.

Jadi, koordinatnya 34,44terletak 34 piksel dari margin kiri dan 44 piksel dari atas:

Tempat kerja
Koordinat 270,350terletak 270 piksel dari margin kiri dan 350 piksel dari atas:

Tempat kerja
Sekarang kita memiliki cukup data untuk membuat area persegi panjang yang dapat diklik:

Contoh
<area shape="rect" coords="34, 44, 270, 350" href="computer.htm">
Ini adalah area yang dapat diklik dan akan mengarahkan pengguna ke halaman "computer.htm":

Tempat kerja
Bentuk="lingkaran"
Untuk menambahkan area lingkaran, pertama-tama cari koordinat pusat lingkaran:

337,300

Tempat kerja
Kemudian tentukan jari-jari lingkaran:

44piksel

Tempat kerja
Sekarang Anda memiliki cukup data untuk membuat area melingkar yang dapat diklik:

Contoh
<area shape="circle" coords="337, 300, 44" href="coffee.htm">
Ini adalah area yang dapat diklik dan akan mengarahkan pengguna ke halaman "coffee.htm":

Tempat kerja
Bentuk="poli"
Berisi shape="poly"beberapa titik koordinat, yang menciptakan bentuk yang dibentuk dengan garis lurus (poligon).

Ini dapat digunakan untuk membuat bentuk apa pun.

Mungkin seperti bentuk croissant!

Bagaimana kita bisa membuat croissant pada gambar di bawah menjadi tautan yang dapat diklik?

Makanan Perancis
Kita harus menemukan koordinat x dan y untuk semua sisi croissant:

Makanan Perancis
Koordinat datang berpasangan, satu untuk sumbu x dan satu untuk sumbu y:

Contoh
<area shape="poly" coords="140,121,181,116,204,160,204,222,191,270,140,329,85,355,58,352,37,322,40,259,103,161,128,147" href="croissant.htm">
Ini adalah area yang dapat diklik dan akan mengarahkan pengguna ke halaman "croissant.htm":

Makanan Perancis
Peta Gambar dan JavaScript
Area yang dapat diklik juga dapat memicu fungsi JavaScript.

Tambahkan clickperistiwa ke <area>elemen untuk menjalankan fungsi JavaScript:

Contoh
Di sini, kami menggunakan atribut onclick untuk menjalankan fungsi JavaScript saat area diklik:

<map name="workmap">
  <area shape="circle" coords="337,300,44" href="coffee.htm" onclick="myFunction()">
</map>

<script>
function myFunction() {
  alert("You clicked the coffee cup!");
}
</script>
Gambar Latar Belakang HTML
Gambar latar belakang dapat ditentukan untuk hampir semua elemen HTML.

Gambar Latar Belakang pada elemen HTML
Untuk menambahkan gambar latar belakang pada elemen HTML, gunakan styleatribut HTML dan properti CSS background-image:

Contoh
Tambahkan gambar latar belakang pada elemen HTML:

<p style="background-image: url('img_girl.jpg');">
Anda juga dapat menentukan gambar latar belakang dalam <style> elemen, di <head> bagian:

Contoh
Tentukan gambar latar belakang dalam <style> elemen:

<style>
p {
  background-image: url('img_girl.jpg');
}
</style>
Gambar Latar Belakang pada Halaman
Jika Anda ingin seluruh halaman memiliki gambar latar belakang, Anda harus menentukan gambar latar belakang pada <body>elemen:

Contoh
Tambahkan gambar latar belakang untuk seluruh halaman:

<style>
body {
  background-image: url('img_girl.jpg');
}
</style>
Latar Belakang Ulangi
Jika gambar latar belakang lebih kecil dari elemen, gambar akan berulang, secara horizontal dan vertikal, hingga mencapai akhir elemen:

Contoh
<style>
body {
  background-image: url('example_img_girl.jpg');
}
</style>
Untuk mencegah gambar latar belakang terulang kembali, atur background-repeatproperti ke no-repeat.

Contoh
<style>
body {
  background-image: url('example_img_girl.jpg');
  background-repeat: no-repeat;
}
</style>
IKLAN

Sampul Latar Belakang
Jika Anda ingin gambar latar belakang menutupi seluruh elemen, Anda dapat mengatur background-sizeproperti ke cover.

Selain itu, untuk memastikan seluruh elemen selalu tercakup, atur background-attachmentproperti kefixed:

Dengan cara ini, gambar latar belakang akan menutupi seluruh elemen, tanpa peregangan (gambar akan mempertahankan proporsi aslinya):

Contoh
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
</style>
Peregangan Latar Belakang
Jika Anda ingin gambar latar belakang meregang agar sesuai dengan seluruh elemen, Anda dapat mengatur background-sizeproperti menjadi 100% 100%:

Coba ubah ukuran jendela browser, dan Anda akan melihat bahwa gambar akan meregang, tetapi selalu menutupi seluruh elemen.

Contoh
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
Elemen HTML <picture>memungkinkan Anda menampilkan gambar yang berbeda untuk perangkat atau ukuran layar yang berbeda.


Elemen HTML <gambar>
Elemen HTML <picture>memberi pengembang web lebih banyak fleksibilitas dalam menentukan sumber daya gambar.

Elemen tersebut <picture>berisi satu atau beberapa <source>elemen, yang masing-masing merujuk ke gambar yang berbeda melalui srcset atribut. Dengan cara ini, browser dapat memilih gambar yang paling sesuai dengan tampilan dan/atau perangkat saat ini.

Setiap <source>elemen memiliki mediaatribut yang menentukan kapan gambar paling cocok.

Contoh
Menampilkan gambar yang berbeda untuk ukuran layar yang berbeda:

<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>
Catatan: Selalu tentukan <img>elemen sebagai elemen anak terakhir dari <picture>elemen tersebut. <img>Elemen tersebut digunakan oleh browser yang tidak mendukung <picture>elemen tersebut, atau jika tidak ada <source>tag yang cocok.

IKLAN

Kapan Menggunakan Elemen Gambar
Ada dua tujuan utama untuk <picture>elemen ini:

1. Lebar pita
Jika Anda memiliki layar atau perangkat kecil, tidak perlu memuat berkas gambar berukuran besar. Peramban akan menggunakan <source> elemen pertama dengan nilai atribut yang sesuai, dan mengabaikan elemen berikut.

2. Dukungan Format
Beberapa browser atau perangkat mungkin tidak mendukung semua format gambar. Dengan menggunakan <picture>elemen tersebut, Anda dapat menambahkan gambar dari semua format, dan browser akan menggunakan format pertama yang dikenalinya, dan mengabaikan salah satu elemen berikut.

Contoh
Peramban akan menggunakan format gambar pertama yang dikenalinya:

<picture>
  <source srcset="img_avatar.png">
  <source srcset="img_girl.jpg">
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
</picture>
Ikon HTML
Favicon adalah gambar kecil yang ditampilkan di samping judul halaman di tab browser.

Cara Menambahkan Favicon di HTML
Anda dapat menggunakan gambar apa pun yang Anda suka sebagai favicon. Anda juga dapat membuat favicon sendiri di situs seperti https://www.favicon.cc .

Tips: Favicon adalah gambar kecil, jadi harus berupa gambar sederhana dengan kontras tinggi.

Gambar favicon ditampilkan di sebelah kiri judul halaman di tab browser, seperti ini:

Contoh favicon
Untuk menambahkan favicon ke situs web Anda, simpan gambar favicon Anda ke direktori akar server web Anda, atau buat folder di direktori akar yang disebut gambar, dan simpan gambar favicon Anda di folder ini. Nama umum untuk gambar favicon adalah "favicon.ico".

Selanjutnya, tambahkan <link>elemen ke file "index.html" Anda, setelah <title>elemen, seperti ini:

Contoh
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
Judul Halaman HTML
Setiap halaman web harus memiliki judul halaman untuk menggambarkan arti halaman tersebut.

Elemen Judul
Elemen ini <title>menambahkan judul ke halaman Anda:

Contoh
<!DOCTYPE html>
<html>
<head>
  <title>HTML Tutorial</title>
</head>
<body>

The content of the document......

</body>
</html>
Tabel HTML
Tabel HTML memungkinkan pengembang web untuk mengatur data ke dalam baris dan kolom.

Contoh
Company	Contact	Country
Alfreds Futterkiste	Maria Anders	Germany
Centro comercial Moctezuma	Francisco Chang	Mexico
Ernst Handel	Roland Mendel	Austria
Island Trading	Helen Bennett	UK
Laughing Bacchus Winecellars	Yoshi Tannamuri	Canada
Magazzini Alimentari Riuniti	Giovanni Rovelli	Italy
Tentukan Tabel HTML
Tabel dalam HTML terdiri dari sel-sel tabel di dalam baris dan kolom.

Contoh
Tabel HTML sederhana:

<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
Sel Tabel
Setiap sel tabel didefinisikan oleh tag a <td>dan a </td>.

td singkatan dari data tabel.

Segala sesuatu antara <td>dan </td> merupakan konten sel tabel.

Contoh
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
Catatan: Sel tabel dapat berisi semua jenis elemen HTML: teks, gambar, daftar, tautan, tabel lain, dll.

IKLAN

Baris Tabel
Setiap baris tabel dimulai dengan <tr>dan diakhiri dengan </tr>tag.

tr singkatan dari baris tabel.

Contoh
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
Anda dapat memiliki baris sebanyak yang Anda suka dalam sebuah tabel; pastikan saja jumlah selnya sama di setiap baris.

Catatan: Ada kalanya baris dapat memiliki lebih sedikit atau lebih banyak sel daripada baris lainnya. Anda akan mempelajarinya di bab berikutnya.

Judul Tabel
Terkadang Anda ingin sel Anda menjadi sel tajuk tabel. Dalam kasus tersebut, gunakan <th>tag sebagai ganti <td>tag:

th singkatan dari table header.

Contoh
Biarkan baris pertama menjadi sel tajuk tabel:

<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
Batas Tabel HTML
Tabel HTML dapat memiliki batas dengan berbagai gaya dan bentuk.

Cara Menambahkan Batas
Untuk menambahkan batas, gunakan borderproperti CSS pada elemen table, th, dan td:

 	 	 
 	 	 
 	 	 
Contoh
table, th, td {
  border: 1px solid black;
}
Batas Tabel yang Dilipat
Untuk menghindari batas ganda seperti pada contoh di atas, atur border-collapse properti CSS ke collapse.

Ini akan membuat batas-batas tersebut runtuh menjadi satu batas tunggal:

 	 	 
 	 	 
 	 	 
Contoh
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
IKLAN

Gaya Batas Tabel
Jika Anda menetapkan warna latar belakang setiap sel, dan memberi warna putih pada batasnya (sama dengan latar belakang dokumen), Anda akan mendapatkan kesan batas yang tidak terlihat:

 	 	 
 	 	 
 	 	 
Contoh
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
th, td {
  background-color: #96D4D4;
}
Batas Meja Bundar
Dengan border-radiusproperti tersebut, batas-batasnya mendapatkan sudut yang membulat:

 	 	 
 	 	 
 	 	 
Contoh
table, th, td {
  border: 1px solid black;
  border-radius: 10px;
}
Lewati batas di sekitar tabel dengan tidak menyertakannya tablepada pemilih css:

 	 	 
 	 	 
 	 	 
Contoh
th, td {
  border: 1px solid black;
  border-radius: 10px;
}
Batas Meja Bertitik
Dengan border-styleproperti tersebut, Anda dapat mengatur tampilan perbatasan.

 	 	 
 	 	 
 	 	 
Nilai-nilai berikut diizinkan:

dotted     
dashed     
solid     
double     
groove     
ridge     
inset     
outset     
none     
hidden     
Contoh
 th, td {
  border-style: dotted;
}
Warna Batas
Dengan border-colorproperti tersebut, Anda dapat mengatur warna batas.

 	 	 
 	 	 
 	 	 
Contoh
 th, td {
  border-color: #96D4D4;
}

Ukuran Tabel HTML
Tabel HTML dapat memiliki ukuran yang berbeda untuk setiap kolom, baris, atau keseluruhan tabel.

 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
Gunakan styleatribut dengan properti widthatau height untuk menentukan ukuran tabel, baris, atau kolom.

Lebar Tabel HTML
Untuk mengatur lebar tabel, tambahkan style atribut ke <table>elemen:

Contoh
Atur lebar tabel menjadi 100%:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
Catatan: Menggunakan persentase sebagai satuan ukuran lebar berarti seberapa lebar elemen ini jika dibandingkan dengan elemen induknya, yang dalam kasus ini adalah <body> elemen tersebut.

Lebar Kolom Tabel HTML
 	 	 
 	 	 
 	 	 
Untuk mengatur ukuran kolom tertentu, tambahkan style atribut pada elemen <th>atau <td>:

Contoh
Atur lebar kolom pertama menjadi 70%:

<table style="width:100%">
  <tr>
    <th style="width:70%">Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
IKLAN

Tinggi Baris Tabel HTML
 	 	 
 	 	 
 	 	 
Untuk mengatur tinggi baris tertentu, tambahkan style atribut pada elemen baris tabel:

Contoh
Atur tinggi baris kedua menjadi 200 piksel:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr style="height:200px">
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>


Header Tabel HTML
Tabel HTML dapat memiliki tajuk untuk setiap kolom atau baris, atau untuk banyak kolom/baris.

Bahasa Indonesia: EMIL	TOBIAS	Bahasa Indonesia: LINUS
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
SENIN	SELASA	MENIKAHI	KAMIS	JUMAT
Jam 8:00	 	 	 	 	 
Jam 09.00	 	 	 	 	 
Jam 10.00	 	 	 	 	 
Jam 11.00	 	 	 	 	 
Jam 12.00	 	 	 	 	 
Header Tabel HTML
Header tabel didefinisikan dengan thelemen. Setiap thelemen mewakili sel tabel.

Contoh
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
Header Tabel Vertikal
Untuk menggunakan kolom pertama sebagai tajuk tabel, tentukan sel pertama di setiap baris sebagai <th>elemen:

Contoh
<table>
  <tr>
    <th>Firstname</th>
    <td>Jill</td>
    <td>Eve</td>
  </tr>
  <tr>
    <th>Lastname</th>
    <td>Smith</td>
    <td>Jackson</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>94</td>
    <td>50</td>
  </tr>
</table>

Sejajarkan Header Tabel
Secara default, tajuk tabel dicetak tebal dan di tengah:

Nama Depan	Nama belakang	Usia
Jill	Tukang besi	50
Malam	Jackson	94
Untuk meratakan tajuk tabel ke kiri, gunakan text-alignproperti CSS:

Contoh
th {
  text-align: left;
}
Header untuk Beberapa Kolom
Anda dapat memiliki tajuk yang mencakup dua kolom atau lebih.

Nama	Usia
Jill	Tukang besi	50
Malam	Jackson	94
Untuk melakukan ini, gunakan colspanatribut pada <th>elemen:

Contoh
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
Anda akan mempelajari lebih lanjut tentang colspan dan rowspan dalam bab Tabel colspan & rowspan .

Judul Tabel
Anda dapat menambahkan keterangan yang berfungsi sebagai tajuk untuk keseluruhan tabel.

Tabungan bulanan
Bulan	Tabungan
Januari	Rp. 100.000
Februari	Rp 50.000
Untuk menambahkan judul pada tabel, gunakan <caption>tag:

Contoh
<table style="width:100%">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>






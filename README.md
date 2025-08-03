<html>
  <body>
    Java Script

<p align = "justify">
<br> <b>*Pengertian Java Script*</b></br> 
Javascript diperkenalkan pertama kali oleh Netscape pada tahun 1995. Pada awalnya bahasa ini dinamakan "LiveScript" yang berfungsi sebagai bahasa sederhana untuk browser Netscape Navigator 2.
Pada masa itu banyak di kritik karena kurang aman, pengembangan nya terkesan buru buru dan tidak ada pemberitahuan kesalahan yang ditampilkan setiap kali kita membuat kesalahan pada saat menyusun suatu program.
Kemudian sejalan dengan sedang giatnya kerjasama antara Netscape dan Sun ( Pengembang bahasa pemprograman "Java") pada masa itu, maka Netscape memberikan nama "Java Script" kepada bahasa tersebut pada tanggal desember 1995. Pada saat yang bersamaan Microsoft sendiri mencoba untuk mengadaptasikan teknologi ini yang mereka sebut sebagai "Jscript" di browser Internet Explorer 3. </p>

<p align = "justify">
Javascript adalah bahasa yang terbentuk kumpulan skrip yang pada fungsi nya berjalan pada suatu dokumen HTML, sepanjang sejarah internet bahasa ini adalah bahas script pertama ybtuk web. Bahasa ini adalah bahasa pemprograman untuk memberikan kemampuan tambahan terhadap bahasa HTMl dengan mengijinkan peeksikusian perintah perintah di sisi user, yang artinya di sisi browser bukan di sisi server web. </p>

<p align = "justify">
Java Script bergantung kepada browser (navigator) yang memanggil halaman web yang berisi skrip dari Javascript dan tentu saja terselip di dalam dokumen HTML Javascript juga tidak memerlukan kompilator atau penterjemah khusus untuk menjalankan nya (pada kenyataan nya kompilator Javascript sendiri sudah termasuk di dakan browser tersebut). Lain halsnya dengan bahasa "Java" (dengan nama Java Script selalu di banding bandingkan) yang memerlukan kompilator khusus untuk menterjemahkan nya di sisi user/klien.</p>


<h1> 1. Keperluan Java Script </h1>
<p align = "justify"> Untuk mempelajari pemprograman Java Script, ada dua piranti yang di perlukan , yaitu :
<ul>
<li>Teks Editor</li>
  <p align = "justify">Digunakan untuk menuliskan kode-kode Java Script, teks editor yang dapat digunakan antara lain notepad dan ultra edit .</p>
  
<li>Web Browser</li>
  <p align = "justify">Digunakan untuk menampilkan halaman web yang mengandung kode-kode Java Script. Web browser yang digunakan harus mendukung Java Script. Browser yang dapat digunakan adalah internet explorer dan Netscape.</p>
</ul>
</p>

<b> 2. Penulisan Java Script </b>
<p align = "justify"> Kode Java Script dituliskan pada file HTML. Terdapat dua cara untuk menuliskan kode-kode Java Script agar dapat ditampilkan pada halaman HTML, yaitu :

<ol type = 'a'>
<li>Java Script ditulis pada file yang sama </li>
<p align = "justify"> Untuk penulisan dengan cara ini, perintah yang di gunakan adalah <SCRIPT LANGUANGE = "JavaScript"> program java script disini </SCRIPT>
Perintah tersebut biasanya diletakkan diantara Tag <BODY>.....</BODY>
Contoh Penulisan :
<br>
<HTML>
<HEAD><TITLE>.......</TITLE>
  </HEAD>
  <BODY>
  <SCRIPT LANGUANGE ="Javascript">
  kode javascript disini
  </SCRIPT>
  kode HTML disini
    </BODY>
    </HTML>
  </br>
<li>Java Script ditulis pada file yang terpisah </li>
<p>Kode Javascript bisa juga kita buata dalam file terpisah dengan tujuan agar dokumen HTML isinya tidak terlalu panjang. Atribut yang digunakan adalah </p>
<SCRIPT SRC = "namafile.js">...</SCRIPT>

  Diantara tag <SCRIPT........? dan < SCRIPT> tidak diperlukan kode Javascriptnya karena sudah dibuat dalam file terpisah. File yang mengandung kode Javascript berekstensi.js
  
<b> 3. Program Pertama Javascript </b>
Pada bagian ini kita akan membuat program dengan menggunakan Javascript. Program ini akan menampilkan teks "Belajar Pemprograman Javascript"

<HTML>
  <BODY> 
  <SCRIPT languange = " Javascript">
  <!--
    document.wite("Belajar Pemprograman Javascript!");
    //-->
  </SCRIPT>
  </BODY>
</HTML>

<HTML>
  <HEAD>
    <TITLE> Belajar Javascript Yuuuuu </TITLE>
      </HEAD>
    <BODY BGCOLOR = "gray">
      <SCRIPT language ="Javascript">
        <!--
          document.writeln("<PRE>");
          document.write("<B><FONT SIZE=5>");
          document.writeln("SELAMAT DATANG DI JAVASCRIPT");
          document.write("</B></FONT");
          document.write("<I>");
          document.writeln ("Program ini merupakan contoh sederhana menampilakan Teks!");
          document.write("</I>");
          document.writeln("Dengan Javascript !!!!!!!!");
        //-->
      </SCRIPT>
      </BODY>
</HTML>

        
 <p align = "Justify"> Objek document mempunyai dua metode untuk menuliskan teks, yaitu write dan writeln. Metode write digunakan untuk menuliskan teks tanpa ganti baris, sedangkan metode witeln digunakan untuk menuliskan teks dengan ganti baris.
 Berikut diberikan caontoh program Javascript yang diltekkan di file lain dan dipanggil melaluo suatu file HTML. </p>

 <b> 4.Komentar </b>
  <p align = "Justify"> Sama seperti bahasa pemprograman lain. Javascript juga menyediakan fasilitas untuk menuliskan komentar, komentar ini berguna bila nantinya anda atau orang lain membaca program.
  Pemberian komentar dalam Javascript dapat dilakukan dengan dua cara yatu dengan menulsikan komentar setelah tanda garis miring dua kali, contoh :
  //ini komentar
    atau
    /*ini juga komentar*/
  </p>

<h1> 2. Variabel Java Script </h1>
<br><b> 2.1 Variabel Dalam Javascript</b></br>
<p align = "justify" > Variabel adalah empat dimana kita menyimpan nilai-nilai atau informasi-informasi pada Javascript. Variabel yang di deklarasikan dapat di isi dengan nilai apa saja. Dalam Javascript pendeklarasikan sebuah variabel sidatnya opsional, artinya anda boleh mendeklarasikan atau tidak hal tersebut tidak menjai masalah. Jika anda memberi nilai pada variabel, maka Javascript dianggap bahwa anda telah mendeklarasikan variabel tersebut.</p>
Aturan penamaan variabel :
  <ul>
<li> Harus diawaki dengan karakter ( huruf atau baris bawah) </li>
<li> Tidak boleh menggunakan spasi </li>
<li> Huruf Kapital dan kecil memilki arti yang berbeda </li>
<li> Tidak boleh menggunakan kata-kata yang merupakan perintah dalam Javascript</li>
</ul>
<br> <ins>Deklarasi Variabel</ins></br> 
<b><ins>Var</ins> nama_variabel = nilai</b>
            Atau
<b>Nama_Variabel = nilai</b>
<br><ins> Contoh : </ins></br>
var nama = "Zaskia Mecca"
<br>var X  = 1998 ;</br>
var Y ;

Nama =" Bunga Lestari"
<br>X = 1990;</br>
Y = 08170223513

<br><b> 2.2 Tipe Data </b></br>
<p align = "Justify"> Tidak seperti bahasa peprograman lain nya, Javascript tidak memiliki tipe data secara explisit. Hal ini dapat dilihat dari beberapa contoh variabel diatas. Anda mendeklarasikan variabel tapi tidak menentukan tipenya.
Meskipun JavaScript tidak memeiliki tipe data secara explisit. Javascript mempunyai tipe data implisit. Terdapat empat macam tipe data implisit yang dimilki oleh JavaScript yaitu : </p>
<ul>
<li> Numerik, seperti :0222532531, 1000,45,3,146789 dsb </li>
<li> String,seperti: "Hallo","April","Jl.Setiabudi No.17A","Cece Kirani" dsb </li>
<li> Boolean, berniali true atau false </li>
<li> Null, variabel yang tidak diinisialisasi </li>
</ul>

<br><b> 2.3 Numerik </b></br>
<p align = "Justify"> Pada dsarnya Javascript hanya mengenal dua macam tipe numerik, yaitu bilangan bulat(integer) dam nilangan pecahan(real/float). Untuk bilangan bulat, kita dapat merepresentasikan dengan basis desimal, oktal atau heksadesimal. </p>

Contoh :
  var A = 100
  var B = 0x2F;
untuk pendeklarasian tipe bilangan real, dapat menggunakan tanda titik atau notasi ilmiah ( notasi E).
Contoh :
  var a = 3,14533567;
  var b = 1.23456L'+3;

<br><b> 2.4 Tipe String </b></br>
<p align = "Justify"> Untuk mendeklarasikan tipe string dapat dilakukan dengan cara menuliskan string diantara tanda petik tunggal (') atau tanda petik ganda ('') </p>
Contoh :
  var str ='Contoh deklarasi string'
  var strl =" cara ini juga bisa untuk menulis string";

<br><b> 2.5 Tipe Boolean </b></br>
<p align = "Justify"> Tipe Boolean hanya mempunyai nilai True dan False. Tipe ini biasanya digunakan untuk mengecek suatu kondisi atau keadaan. </p>
Contoh :
  var X = (Y>90);
contoh diatas menunjukan bahwa jika Y lebih besar dari 90 maka X akan bernilai True.

<br><b> 2.6 Tipe Null </b></br>
<p align = "Justify"> Tipe Null digunakan untuk merepresentasikan variabel yang tidak nilai awal (inisalisai). </p>

<br><b> 2.7 Operator </b></br>
Operator pada Javascript terbagi menajadi enam, yaitu :
<ul>
<li> Aritmatika </li>
<li> Pemberian nilai (Assign) </li>
<li> Pemanipulasian bit (bitwise) </li>
<li> Pembanding </li>
<li> Logika </li>
<li> String </li>
</ul>

<b> a. Operator Aritmatika </b>
<p align = "Justify"> Digunakan untuk operan numerik. Ada dua macam operator aritmatik, yaitu operator numerik tunggal dan operator aritmatik biner. Perbedaan kedua operator terletak pada jumlah operan yang harus di operasikan.</p>

![image](https://github.com/user-attachments/assets/a7981f14-1984-4ab7-9782-3832d1070f61)


<b> a. Operator Pemberian Nilai </b>
<p align = "Justify"> Digunakan untuk memberikan nilai ke suatu operan atau mengubah nilai suatu operan.</p>

![image](https://github.com/user-attachments/assets/b5cf11ad-4bee-4478-892a-43184ca7ad37)

<b> c. Operator Manipulasi Bit </b>
<p align = "Justify"> Operasi ini berhubungan dengan permanipulasian bit pada operan bertipe bilangan bulat. </p>

![image](https://github.com/user-attachments/assets/bf7ff675-81a4-4094-8bbf-dca8887aff45)
![image](https://github.com/user-attachments/assets/4b6a6846-8be6-4477-81d0-e52274d0c48c)

<b> d. Operator Pembanding </b>
<p align = "Justify"> Digunakan untuk membandingkan dua buah operan. Operan yang dikenal operator ini dapat bertipe string, numerik, maupun ekspresi lain. </p>

![image](https://github.com/user-attachments/assets/d2e5512b-e69f-4c84-8697-d1af8631bab0)

<b> e. Operator Logika </b>
<p align = "Justify"> Digunakan untuk mengoperasikan operan yang bertipe boolean.. </p>

![image](https://github.com/user-attachments/assets/9272e54b-c927-45b0-94c6-bf2534ca8501)
Contoh :
var A = true ;
var B = false;
var C = A&&B;//menghasilkan false
var D = A||&&B;//false
var E = !A;//false

<b> f. Operator String </b>
<p align = "Justify"> Selain operator pembanding, operator string pada Javascript juga mengenal satu operator lagi bernama PENGGABUNGAN. Operator ini digunakan untuk menggabungkan beberapa string menjadi sebuag string yang lebih panjang. </p>
Contoh :
nama = "Java" + "Script";
akan menghasilkan "Java Script pada variabel nama

<h2 style="background-color: Yellow;">Contoh Program Javascript</h2>

<img width="768" height="487" alt="image" src="https://github.com/user-attachments/assets/85ea60cc-6d9e-44a5-b35b-c4b1b3d49ec5" />

<img width="316" height="202" alt="image" src="https://github.com/user-attachments/assets/ce0f8efe-0d1b-4e3e-9ae3-ecc385fce7da" />

<br><b> 2.8 Memasukkan Data </b></br>
Untuk memasukkan data dari keyboard dapat dilakukan dengan menggunakan perintah input.

<h2 style="background-color: Yellow;">Contoh Program Javascript</h2>

<img width="662" height="568" alt="image" src="https://github.com/user-attachments/assets/030aa7f3-5e41-42eb-ac30-faaab74c2045" />

<img width="512" height="286" alt="image" src="https://github.com/user-attachments/assets/b15b113f-ab05-417f-bd9b-3f3a266ba9d9" />

<img width="610" height="208" alt="image" src="https://github.com/user-attachments/assets/a3cfc9e1-d2b7-420c-be29-52b6290b9212" />


<h1> 3. Objek Java Script </h1>

<br><b> 2.1 Objek Untuk Memasukkan Data</b></br>

<p align = "justify" > Terdapat beberapa objek yang dapat digunakan untuk memasukkan data. Objek-objek tersebut biasanya terdapat dalam suatu form. Adapun objek-objek tersebut meliputi Objek Text, Objek Radio, Objek Checkbox, Objek Textaream, dan Obejek Select. </p>

<br><b> 3.2 Objek Objek Text </b></br>

<p align = "justify" > Untuk menginputkan data kita dapat menggunakan kompenen/objek text. Contoh penggunaan nya dapat kita lihat oada contoh berikut : </p>

<h2 style="background-color: Yellow;">Contoh Program Javascript</h2>

<img width="623" height="499" alt="image" src="https://github.com/user-attachments/assets/85698046-1067-4aaf-a2c8-e309944eb719" /> 

<img width="728" height="445" alt="image" src="https://github.com/user-attachments/assets/b4a30936-fe36-4dec-9fa9-87723679ae83" /> 

<br><b> 3.3 Objek Radio </b></br>
<p align = "justify" > Objek radio adalah komponen untuk melakukan suatu pemilihan data. Karena selalu berupa Array, untuk mengakses satu tombol radio digunakan radio [indeks]. Disamping itu objek radio juga mempunyai nilai True jika dipilih dan False jika tidak. Untuk suatu objek radio menggunakan properti Checked.  </p>

<h2 style="background-color: Yellow;">Contoh Program Javascript</h2>








  

  </body>
  
Bisa cek Tag-Tag nya di repositori ya yang mau belajar...🤞
Dee-Glit1015

</html>

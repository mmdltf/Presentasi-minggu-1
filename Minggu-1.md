# **Presentasi-minggu-1**

## **Command Line dan Git/Github** ( senin, 19 September 2022)


 ## **A**. **Command Line**
 

 - Command line
Command line merupakan sebuah program yang menjembatani antara user untuk memberikan perintah untuk melakukan sesuatu kepada sebuah sistem operasi yang ada didalam perangkat komputer.
- Command Shell
Command shell merupakan sebuah program yang sudah tersedia pada sebuah *operating system* untuk memudahkan pengguna dalam berkomunikasi dengan sistem operasi sebuah perangkat. Shell sendiri memiliki berbagai macam seperti CMD, Powershell, Macintosh Finder, C shell dan lainnya.
- Terminal
Terminal merupakan sebuah space / tempat **SHELL** akan digunakan atau bisa dikatakan sebuah tempat dimana pengguna dapat memberikan perintah. 
- System Structure
System structure bisa diartikan sebagai urutan file tersimpan pada sebuah directory yang memiliki bentuk paralel. Pada CMD kita bisa Command `tree` 
![TREE](https://i.postimg.cc/sDPYvcxh/Commandline-system-structure.png)
- Command/ Perintah 
Perintah yang terdapat pada CLI beragam dan sangat banyak namun terdapat beberapa jenis perintah yang biasa digunakan, Contoh:

`pwd` untuk melihat directory yang sedang kita buka sekarang berada dimana/ *Current working directory*
![enter image description here](https://i.postimg.cc/Cxt4bKCy/Commandline-pwd.png)

`ls` untuk melihat isi/ list files yang berada pada sebuah directory
![enter image description here](https://i.postimg.cc/wvrq5DQz/Commandline-ls.png)
`cd` untuk berpindah dari satu directory ke directory lainnya
![enter image description here](https://i.postimg.cc/zDj39Pc3/Commandline-CD.png)
`mkdir` untuk membuat directory baru
![enter image description here](https://i.postimg.cc/x1rCHDkx/Commandline-mkdir.png)

`touch` untuk membuat sebuah empty file suatu direktori 
![enter image description here](https://i.postimg.cc/dQxRb1Xh/Commandline-touch.png)
`mv` untuk memindahkan satu/ lebih directory/files dari satu lokasi ke lokasi lainnya
  ## **B**. **GIT dan GITHUB**
  **GIT** merupakan sebuah *version control* yang dimana bisa mentrack seluruh perubahan pada repository/ files di suatu projek. Sebenarnya keduanya ini sama-sama *version control* tapi letak perbedaan nya terdapat pada lokasi nya, yang dimana **GIT** harus terinstall secara local pada windows sementara **GITHUB** berbentuk cloud atau bisa dibilang **GIT** adalah sebuah software sementara **GITHUB** adalah sebuah service. Sebenarnya terdapat beberapa jenis yang hampir serupa dengan GITHUB yaitu:
 1. Gitbucket
 2. AzureOps
 3. Gitlab
### Kenapa sih Version Control dalam hal ini GIT/GIT HUB penting bagi seseorang developer ?
Version Control merupakan hal yang sangat penting bagi seseorang developer karena dalam proses pengerjaan sebuah projek seseorang developer tentunya akan menghadapi suatu kondisi yang mengharuskan dirinya bekerja sama dengan developer lainnya atau *Teamwork*. Kehadiran GIT/GITHUB ini sangat membantu dalam hal menshare projek yang sedang kita kerjakan karena repository yang terdapat pada GITHUB bisa bersifat public/ private (orang-orang tertentu yang bisa mengakses projek tersebut) dan tiap-tiap perubahan / penambahan isi dari projek tersebut akan dengan mudah di track mulai dari terdapat dibagian mana, kapan dan oleh siapa.

### Membuat Repository pada GITHUB
Dalam pembuatan repository pada GITHUB seperti gambar dibawah ini
![enter image description here](https://i.postimg.cc/ZRw66Pq0/GIT-1.png)

> Diingatkan sebelum membuat repository jangan lupa Sign Up account terlebih dahulu 

Setelah repository berhasil dibuat maka langkah selanjutnya adalah membuat folder lalu jalankan CMD/ gitbash/ lainnya
> Usahakan buat terlebih dahulu sebuah file HTML, JS atau Lainnya

![enter image description here](https://i.postimg.cc/65ZfJ70S/GIT-2.png)

![enter image description here](https://i.postimg.cc/nLx1FHzk/GIT-3.png)
 
### Mengupload file local ke GITHUB
#### Prosedur yang harus dilakukan seperti dibawah ini:
Git configuration 

 1. `git config --global user.name "luthfi"`
 2. `git config --global user.email "luthfi2001@gmail.com"`
 3. `git init`
 4. `git remote add origin https://github.com/mmdltf/web-basic.git`
 5. `git add .`
 6. `git commit -m "belajar html"`
 7. `git push -u origin master`
 Ketika tahapan diatas sudah dilakukan maka file (index.html) sudah terupload pada repository yang telah kita buat pada GITHUB 
 ![enter image description here](https://i.postimg.cc/k54gtpTb/GIT-4.png)

### Cloning GITHUB ke local
Pada GITHUB terdapat fitur yang dimana kita dapat meng-cloning kan repository orang lain, yaitu dengan cara:
![enter image description here](https://i.postimg.cc/L6vbC9tG/cloning.png)

 1. Pada repository yang ingin di clone kan klik `code` kemudian copy link HTTPS yang tertera pada kotak `https://github.co...........`
 2. Buka Gitbash
 3. Ketik `git clone` kemudian paste link repository yang ingin kita clone 
![enter image description here](https://i.postimg.cc/Kv4VRK3Q/cloning-1.png)
4. Maka file akan berada pada repository yang kita tentukan 
![enter image description here](https://i.postimg.cc/4yRSMwx3/cloning-2.png)


## **HTML** ( Selasa, 20 September 2022)
### Apa itu HTML ?
HTML merupakan sebuah *markup language* yang memiliki fungsi sederhana yaitu untuk menampilkan konten pada browser. Sejatinya HTML bukanlah sebuah bahasa pemograman karena bersifat statis bukan dinamis seperti javascript, phyton, java.. dan lainnya.

HTML memiliki struktur dasar yaitu:

 1. !Doctype
 2. Tag HTML
 3. Head 
 4. Body
```
<!DOCTYPE  html>
<html  lang="en">
<head>
	<meta  charset="UTF-8" />
	<meta  http-equiv="X-UA-Compatible"  content="IE=edge" />
	<meta  name="viewport"  content="width=<device-width>, 	initial-scale=1.0" />
<title>Document</title>
</head>
<body>
	<div  id="makan">
		<h1>Makanan padang</h1>
		<h2  class="jenismakanan">Rendang</h2>
		<img
		src="https://tinyurl.com/yfmjh7rc" width="300px"/>
			<p>
			rendang merupakan makanan favorit yang menjadi 		makanan wajib ketika kita datang ke restoran padang
			</p>
		<h2  class="jenismakanan">Otak</h2>
		<img
		src="https://tinyurl.com/2p9yxenp" width="300px"/>
			<p>
			Otak juga merupakan menu yang enak namun kolesterol yang sangat tinggi :(
			</p>
		<h2  class="jenismakanan">Kikil</h2>
		<img
		src="https://tinyurl.com/2jvhssvc" width="300px"/>
			<p>
			Kikil juga merupakan salah satu menu yang terdapat pada restoran pada dengan bumbu khas nya yaitu gulai
			</p>
</div>
</body>
</html>
```
maka tampilan yang akan muncul pada browser seperti dibawah ini
![enter image description here](https://i.postimg.cc/sXzHsr8R/html-web.png)
#### Tools yang digunakan untuk membuat HTML 
Tools yang diperlukan yang pasti adalah web-browser serta code editor. Sebenarnya code editor memiliki banyak jenis, yaitu:

 1. Vscode
 2. Atom
 3. Sublime Text 
 4. Notepad ++
 5. Textmate
 6. Codeshare . io
 
Namun dari code editor diatas, yang akan saya gunakan adalah Vscode karena memiliki beberapa fitur yang sangat membantu dalam proses coding seperti extension dan built-in Git. 
#### HTML Tag
Hal yang perlu dibahas pertama-tama adalah HTML Tag Element yang dimana terdiri dari : opening tag, content, serta closing tag 
``` <h1> halo semua </h1> ```

yang dimana `<h1>` merupakan opening tag, `halo semua` merupakan content dan `</h1` merupakan closing tag. Pada HTML Tag memiliki dua jenis yaitu Single Tag `<img/>` dan Double Tag `<p> </p>`.
Terdapat beberapa jenis Tag pada HTML yang umum digunakan, yaitu:

 1. `<h1.......h6> </h1.......</h6>`Tag ini digunakan untuk membuat heading dengan ukuran besar (h1) > kecil (h6)
 2. `<p> </p>` Tag ini digunakan untuk membuat paragraf
 3. `<link/>`Tag ini digunakan untuk menghubung HTML dengan CSS
 4. `<var></var>`Tag ini digunakan sebagai container dari sebuah persamaan matematika
 5. `<ul></ul>` Tag ini digunakan untuk membuat list
 6. `<div></div>` Tag ini digunakan untuk membuat sebuah divisi agar lebih mudah dipanggil jika kita styling CSS secara external
 7. `<img/>` Tag ini digunakan untuk memunculkan gambar 

#### HTML Attribute
Attribute yang biasa kita temui pada suatu script HTML adalah id, class, src, namun masih terdapat banyak jenis attribute yang sebenar nya bisa kita gunakan seperti Charset, Accept, Accept-charset, For, Form, Media, Name dan masih banyak lagi. 




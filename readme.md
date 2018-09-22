## Everything is Object

Ada 2 Type data

### Primitive

- number
- string
- boolean
- undefined
- null

### Object

- Array
- Function
- Object
- Date

### Object Oriented Programming

- Sesama object saling berinteraktif melalui method dan property
- Menggunakan store data, structure aplikasi ke dalam module dan keep code clean.

contoh object:

	var toyota = {
		nama: 'avanza',
		tahun: 2000,
		warna: 'putih'
	}

	var suzuki = {
		nama: 'apv',
		tahun: 2005,
		warna: 'biru'
	}

	var honda = {
		nama: 'brio',
		tahun: 2015,
		warna: 'merah'
	}

	car = {
		nama
		tahun
		pabrik
		dsb
	}

**Constructor atau Prototype**

di bebeapa language ini sering disebut class, didalam javascript disebut Constructor atau Prototype.

Constructor kita bisa membuat banyak instances, contoh nya constructor car bisa membuat object baru misalnya toyota, suzuki, honda dsb.

### inheritance (turunan)

apa turunan dari car?

	sport = {
		type
		tahun
		mesin
		ukuran
	}

	family = {
		type
		tahun
		mesin
		ukuran
	}

	car = {
		nama: 'Mitsubishi'
		tahun: 2010
		pabrik: 'Sunter'
		jenis: barang = {
			type: 'Solar',
			karoseri: 'Aduhai' ,
			mesin:2000,
			kapasitas: 10 ton
		} 
	}

**Constructur function**
 
 	function(){ ... }
 
Kenapa kita membutuhkan constructor function dan pada saat apa?

Karena kita perlu membuat object object baru, pada saat kita membutuh kan new instance - new instance maka kita membutuhkan function constructor. Instance atau copy dari blue print dari sebuah object/function/class.

	function Motor(){ return object; }
	
**Membuat constructor function**	

* function nama function gunakan huruf besar.
* lewatkan (pass) parameter.
* akses parameter dengan **this**.
* gunakan new keyword untuk invoke/memanggil constructor function.
* Menambahkan value untuk parameter diatas sebagai argumen.
* Gunakan variable invoke untuk menyimpan new object tsb.
* Dengan demikian anda bisa memulai membuat instance baru dengan berbeda value, Instance (baca mengcopy).
* Tampilkan pada console

## DOM
### Document Object Model

**Apa itu DOM?**

DOM adalah reprentasi dari JavaScript untuk komunikasi dan interaktif dengan browser Object, contoh:

window

window adalah object yang memberikan detil informasi, API , hingga js bs berkomunikasi dan berinteraktif dengan window browser, antara lain Element-element seperti tree strucktur document.

	documemt

	<html>
		<head>
			<title></title>
		</head>
		<body>
			<h1></h1>
		</body>
	</html>

Document ini terdiri dari object2 yang di representasikan oleh element element spt tag tag html, head, body, p, div dsb. Sehingga kita bisa mengakses, merubah konten dari element tsb dan memberikan event, ini yg sering kita sebut **memanipulasi element (DOM element)**.

	document.title
	document.title = "Latihan Karate"

kemudian

	document.body
	
bagaimana mengakses h1, h2, div dst?

### Targeting DOM Elements

document adalah global variable, juga berlaku sebagai object dimana object memiliki method, antara lain :

	document.getElementsByTagName();
	
contoh ('p') akan muncul array [p] bila lebih dari satu p.

kemudian 

	document.getElementById()
	
	document.getElementsByClassName

maka kita harus menambahkan ID atau class pada element tsb.

Atau menggunakan querySelector()

	document.querySelector('#apa')
	
	document.querySelector('.apa')
	
	



	














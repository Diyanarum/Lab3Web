# PEMOGRAMAAN WEB

Diyan Arum Maheswari (312010133)

Teknik Informatika - UNIVERSITAS PELITA BANGSA
______________________________________________

## MEMBUAT ORDERED LIST

Pertama, disini saya akan membuat sebuah dokumen dasar Htmlnya terlebih dahulu, sebelum nantinya akan saya tambahkan kode untuk membuat Ordered Listnya.

Berikut codingan yang saya gunakan untuk membuat sebuah contoh dokumen seperti diatas.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
</body>
</html>
```
Setelah membuat dasarnya seperti diatas, selanjutnya kita harus menambahkan sebuah kode khusus untuk dapat membuat sebuha Ordered List seperti gambar dibawah ini:

![menambahka_gambar](img/ORDERED%20LIST.png)

Dan inilah kode yang dibutuhkannya

```html
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>
```

## MEMBUAT UNORDERED LIST

Setelah membuat Ordered List seperti diatas, disini saya akan mencoba untuk membuat Unordered List dengan melakukan deklarasi Ordered List pada section Unordered List, seperti berikut:

![menambahkan_gambar](img/UNORDERED%20LIST.png)

Dan untuk dapat melakukan sebuah deklarasi tersebut kalian bisa menggunakan kode seperti dibawah ini:

```html
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```

## MEMBUAT DESCRIPTION LIST

Selanjutnya, disini saya akan membuat sebuah list deskripsi atau Description List dengan menggunakan kode berikut setelah dilakukannya deklarasi untuk Unordered List.

```html
<section id="unorder-list">
    <h2>Description List</h2>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
    </dl>
</section>
```
Dan seperti ini lah tampilan yang akan kalian dapatkan.

![menambahkan_gambar](img/DESCRIPTION%20LIST.png)


## MEMBUAT TABEL

Untuk dapat membuat sebuah tabel, buatlah sebuah file baru telebih dahulu. Disini saya membuat sebuah file baru dengan judul lab3_tabel.html

Selanjutnya, masukan kode dibawah ini

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>
</body>
</html>
```
Setelah memasukan kode diatas, tambahkan kode dibawah ini untuk dapat membuat sebuah tabel sederhana seperti berikut:

```html
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
Dan berikut tampilan tabel sederhananya:

![menambahkan_gambar](img/MEMBUAT%20TABEL%20AWAL.png)

## PENGATURAN MARGIN DAN PADDING PADA TABEL

Untuk melakukan pengaturan Margin dan Padding pada cel data sebelumnya agar terlihat lebih rapih, kalian dapat menambahkan sebuah atribut cellpadding dan cellspacing pada tag tabel.

```html
<table border="1" cellpadding="4" cellspacing="0">
```
Dan seperti inilah hasil akhir dari pembuatan tabel sederhananya.

![menambahkan_gambar](img/TABEL%20INPUT%20MARGIN.png)

## PENGGABUNGAN SEL DATA

 Untuk dapat menggabungkan sebuah sle data, kalian dapat menggunakan rowspan dan colspan, yang dimana atribut rowspan untuk menggabungkan baris, dan atribut untuk menggabungkan kolom.

 ```html
 <table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td rowspan="3">Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```

Dan seperti inilah hasil akhir dari menggabungan tabel diatas.

![menambahkan_gambar](img/HASIL%20GABUNGAN%20TABEL.png)

## PEMBUATAN FORM

![menambahkan_gambar](img/FORM%202.png)

Untuk dapat membuat sebuah tabel form seperti biasa, sebelum memulai kalian dapat membuat sebuah file baru yang kemudian memasukan kode dibawah ini seperti biasa.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
</body>
</html>
```
Selanjutnya kalin tambahkan kode berikut untuk dapat membuat tabel.

```html
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Pelanggan</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label
for="jk_p">Perempuan</label>
        </p>
        <p><input type="submit" value="Login"></p>
    </fieldset>
</form>
```

## PENAMBAHAN STYLE PADA FORM

![menambahkan_gambar](img/FORM%20DESIGN%20COLOUR.png)

Agar tampilan form menarik seperti gambar diatas, kalian dapat menambahkan kode dibawah ini:

```html
<style>
    form p > label {
        display: inline-block;
        width: 100px;
    }
    form input[type="text"], form textarea {
        border: 1px solid #99053e;
    }
    form input[type="submit"] {
        border: 1px solid #940b22;
        background-color: #75163a;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
    }
</style>
```
# QUESTION AND TASK

1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.

![menambahkan_gambar](img/TASK.png)

Untuk dapat membuat tampilan seperti gambar diatas, disini saya menggunaka kode-kode seperti dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1 style="color:rgb(109, 15, 59); text-align:center"> CONCERT TICKET REGISTRATION</h1>
    </header>
</body>
</html>

<form action="proses.php" method="post">
    <fieldset>
        <legend> <h4 style="text-align: center">Data Audience</h4></legend>
    
    
    <p>
    <label for="Name">Name</label>
    <input type="text" id="Name" name="Name">
    </p>


    <p>
    <label for="adress">Adress</label>
    <textarea id="adress" name="adress" cols="50" rows="1"></textarea>
    </p>


    <p>
    <label for="identity number">Identity Number</label>
    <textarea id="identity number" name="identity number" cols="20" rows="1"></textarea>
    </p>


    <p>
        <label>Ages</label>
        <input id="ag_u17" type="radio" name="under 17" value="ag_u17" /><label
        for="ag_u17">Under (-17)</label>
        <input id="ag_ov" type="radio" name="over 17" value="ag_ov" /><label
    
        for="ag_ov">Over (+17)</label>
    </p>
    


<p>
    <!-- Dropdown Menu -->
    <h3>Seat (Dropdown)</h3>
    <label>Choose your Seat</label>
   <select name="Choose your Seat" id="Choose your Seat">
       <option value="Seat">---------Choose Here---------</option>
       <option value="VVIP (Standing 4.500.000)">VVIP (Standing 4.500.000)</option>
       <option value="Red (Standing 3.000.000)">Red (Standing 3.000.000)</option>
       <option value="Purple (Standing 2.000.000)">Purple (Standing 2.000.000)</option>
       <option value="Pink (Standing 1.500.000)">Pink (Standing 1.500.000)</option>
       <option value="Yellow (Standing 1.000.000)">Yellow (Standing 1.000.000)</option>
   </select> 
</p>


<p>
    <label for="Ticket">Ticket</label>
    <textarea id="Ticket" name="Ticket" cols="20" rows="1"></textarea>
    </p>


<p>
    <!-- Dropdown Menu -->
    <h3>Payment (Multiple Selection) </h3>
    <label>Choose your Payment</label>
   <select name="Choose your Payment" id="Choose your Payment">
       <option value="Payment">---------Choose Here---------</option>
       <option value="Bank Transfer">Bank Transfer</option>
       <option value="Credit Card">Credit Card</option>
   </select> 
</p>




<style>
    form p > label {
    display: inline-block;
    width: 100px;
    }
    form input[type="text"], form textarea {
    border: 1px solid #99053e;
    }
    form input[type="submit"] {
    border: 1px solid #940b22;
    background-color: #75163a;
    color: #ffffff;
    font-weight: bold;
    padding: 5px 15px;
    }
</style>

<p><input type="submit" value="Checkout"></p>
</fieldset>
</form>
```

# <P align="center"> THANK'S FOR YOUR ATTENTION!! SEE YOU!!

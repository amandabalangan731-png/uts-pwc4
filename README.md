# profil-mahasiswa
<!DOCTYPE html>
<html>
<head>
<title>Profil Mahasiswa</title>

<style>
body{
    font-family: Arial, sans-serif;
    background:#f4f4f4;
    margin:0;
}

.header{
    background:#2f3dff;
    color:white;
    text-align:center;
    padding:40px;
}

.foto{
    width:120px;
    height:120px;
    border-radius:50%;
    object-fit:cover;
    border:4px solid white;
}

.card{
    background:white;
    margin:20px;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
}

table{
    width:100%;
    border-collapse:collapse;
}

table,th,td{
    border:1px solid #ccc;
}

th,td{
    padding:10px;
    text-align:left;
}

input, textarea{
    width:100%;
    padding:8px;
    margin-top:5px;
}

button{
    background:blue;
    color:white;
    border:none;
    padding:10px 20px;
    border-radius:5px;
}
</style>
</head>

<body>

<div class="header">

<img src= class="foto" alt="<img width="1024" height="1024" alt="alya" src="https://github.com/user-attachments/assets/bf2c2203-6edc-4eff-b4c9-2eb472d64942" />
">

<h1>Alya Amanda Putri</h1>
<p>NIM : 240131012</p>
<p>Universitas Sapta Mandiri</p>

</div>

<div class="card">
<h2>Ringkasan</h2>
<p>
Saya adalah mahasiswa Universitas Sapta Mandiri yang memiliki minat
dalam bidang teknologi informasi dan pengembangan web.
</p>
</div>

<div class="card">
<h2>Keahlian</h2>
<ul>
<li>HTML</li>
<li>CSS</li>
<li>Microsoft Office</li>
<li>Canva</li>
</ul>
</div>

<div class="card">
<h2>Riwayat Pendidikan</h2>

<table>
<tr>
<th>Pendidikan</th>
<th>Tahun</th>
</tr>

<tr>
<td>SD</td>
<td>2013 - 2019</td>
</tr>

<tr>
<td>SMP</td>
<td>2019 - 2022</td>
</tr>

<tr>
<td>SMA</td>
<td>2022 - 2025</td>
</tr>

<tr>
<td>Universitas Sapta Mandiri</td>
<td>2025 - Sekarang</td>
</tr>

</table>
</div>

<div class="card">
<h2>Portofolio</h2>
<p>Website Profil Mahasiswa</p>
</div>

<div class="card">
<h2>Hubungi Saya</h2>

<form>

Nama:<br>
<input type="text"><br><br>

Email:<br>
<input type="email"><br><br>

Pesan:<br>
<textarea rows="5"></textarea><br><br>

<button type="submit">Kirim</button>

</form>

</div>

</body>
</html>

# tugas-websisikline
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir dan Data Mahasiswa</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Formulir Mahasiswa</h1>
        </header>

        <!-- Bagian Formulir -->
        <section id="form-section">
            <h2>Isi Data Mahasiswa</h2>
            <form id="formMahasiswa">
                <div class="form-group">
                    <label for="nama">Nama Lengkap</label>
                    <input type="text" id="nama" name="nama" placeholder="Masukkan nama lengkap">
                </div>

                <div class="form-group">
                    <label for="nim">NIM</label>
                    <input type="text" id="nim" name="nim" placeholder="Masukkan NIM mahasiswa">
                </div>

                <div class="form-group">
                    <label for="tempatLahir">Tempat Lahir</label>
                    <input type="text" id="tempatLahir" name="tempatLahir" placeholder="Masukkan tempat lahir">
                </div>

                <div class="form-group">
                    <label for="tanggalLahir">Tanggal Lahir</label>
                    <input type="date" id="tanggalLahir" name="tanggalLahir">
                </div>

                <div class="form-group">
                    <label>Jenis Kelamin</label>
                    <div class="radio-group">
                        <label><input type="radio" name="gender" value="Laki-laki"> Laki-laki</label>
                        <label><input type="radio" name="gender" value="Perempuan"> Perempuan</label>
                    </div>
                </div>

                <div class="form-group">
                    <label for="programStudi">Program Studi</label>
                    <select id="programStudi" name="programStudi">
                        <option value="">-- Pilih Program Studi --</option>
                        <option value="Manajemen">Manajemen</option>
                        <option value="Akuntansi">Akuntansi</option>
                        <option value="Teknik Informatika">Teknik Informatika</option>
                        <option value="Pariwisata">Pariwisata</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="alamat">Alamat</label>
                    <textarea id="alamat" name="alamat" rows="3" placeholder="Masukkan alamat lengkap"></textarea>
                </div>

                <div class="form-group">
                    <label for="noHp">Nomor HP</label>
                    <input type="tel" id="noHp" name="noHp" placeholder="08xxxxxxxxxx">
                </div>

                <button type="submit" class="btn-submit">Simpan Data</button>
            </form>
        </section>

        <!-- Bagian Tabel -->
        <section id="table-section">
            <h2>Data Mahasiswa Tersimpan</h2>
            <div class="table-container">
                <table id="dataTable">
                    <thead>
                        <tr>
                            <th>No</th>
                            <th>Nama</th>
                            <th>NIM</th>
                            <th>Tempat Lahir</th>
                            <th>Tanggal Lahir</th>
                            <th>Jenis Kelamin</th>
                            <th>Program Studi</th>
                            <th>Alamat</th>
                            <th>No. HP</th>
                        </tr>
                    </thead>
                    <tbody>
                        <!-- Data Dummy -->
                        <tr>
                            <td>1</td>
                            <td>Gede Wirawan</td>
                            <td>231045001</td>
                            <td>Denpasar</td>
                            <td>2004-05-17</td>
                            <td>Laki-laki</td>
                            <td>Teknik Informatika</td>
                            <td>Jl. Pulau Batanta No. 9, Denpasar</td>
                            <td>081234567890</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Ni Kadek Ayu Wulan</td>
                            <td>231045002</td>
                            <td>Tabanan</td>
                            <td>2003-11-05</td>
                            <td>Perempuan</td>
                            <td>Pariwisata</td>
                            <td>Jl. Pantai Kuta, Badung</td>
                            <td>082198765432</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Made Adi Putra</td>
                            <td>231045003</td>
                            <td>Klungkung</td>
                            <td>2004-03-22</td>
                            <td>Laki-laki</td>
                            <td>Manajemen</td>
                            <td>Jl. Raya Klungkung</td>
                            <td>085236789012</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td>Komang Rina Dewi</td>
                            <td>231045004</td>
                            <td>Gianyar</td>
                            <td>2004-09-15</td>
                            <td>Perempuan</td>
                            <td>Akuntansi</td>
                            <td>Jl. Raya Gianyar No. 20</td>
                            <td>081999334455</td>
                        </tr>
                        <tr>
                            <td>5</td>
                            <td>Ketut Bagus Mahendra</td>
                            <td>231045005</td>
                            <td>Bangli</td>
                            <td>2005-01-09</td>
                            <td>Laki-laki</td>
                            <td>Teknik Informatika</td>
                            <td>Jl. Gunung Agung, Bangli</td>
                            <td>087722334455</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>
    </div>
</body>
</html>

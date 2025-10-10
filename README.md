# Lab3Web
# nama : keysia nurhayati br panjaitan
# nim : 312410350
# kelas : TI 24.A4

# membuat list

    <section id="order-list">
        <h2>Ordered List</h2>
        <ol type="A" start="3">
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>
<img width="1920" height="1200" alt="Screenshot 2025-10-09 140924" src="https://github.com/user-attachments/assets/c98fa335-d4d2-4b9b-8b39-3874666eeac3" />

# membuat uorderan list 
    
    <section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma & Pemrograman</li>
    </ul>
</section>
<img width="1920" height="1200" alt="Screenshot 2025-10-09 133918" src="https://github.com/user-attachments/assets/400a9e66-06b9-4534-9c7e-fafa7d708b02" />

# membuat description list

    <section id="desc-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Industri</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
        </dl>
    </section>
    <img width="1920" height="1200" alt="Screenshot 2025-10-09 134013" src="https://github.com/user-attachments/assets/4fe62bde-c99c-4e38-8328-e75d171c8430" />


# membuat tabel

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
<img width="1920" height="1200" alt="Screenshot 2025-10-09 135122" src="https://github.com/user-attachments/assets/bd23c1a7-28b6-4724-8abf-e3cfcb68d2c7" />

# membuat from

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama" required>
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3" required></textarea>
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L" required> <label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P"> <label for="jk_p">Perempuan</label>
            </p>
            <p>
                <label for="kategori">Kategori Pelanggan</label>
                <select id="kategori" name="kategori">
                    <option value="reguler">Reguler</option>
                    <option value="premium">Premium</option>
                    <option value="vip">VIP</option>
                </select>
            </p>
            <p>
                <label for="produk">Produk Favorit</label><br>
                <select id="produk" name="produk[]" multiple size="4">
                    <option value="oli">Oli Mobil</option>
                    <option value="ban">Ban Mobil</option>
                    <option value="sparepart">Sparepart</option>
                    <option value="aksesoris">Aksesoris</option>
                </select>
            </p>
            <p>
                <input type="submit" value="Kirim Data">
            </p>
        </fieldset>
    </form>
 <img width="1920" height="1200" alt="Screenshot 2025-10-09 135314" src="https://github.com/user-attachments/assets/027ec95f-1240-4ef7-8584-854c1f8e5b18" />

# menambahkan CSS

    <style>
        form p > label {
            display: inline-block;
            width: 120px;
        }
        form input[type="text"],
        form textarea,
        form select {
            border: 1px solid #197a43;
            border-radius: 5px;
            padding: 5px;
        }
        form input[type="submit"] {
            border: none;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 8px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #125c32;
        }
    </style>

    
    <img width="1920" height="1200" alt="Screenshot 2025-10-09 135420" src="https://github.com/user-attachments/assets/a3727b47-8f5e-49e7-9ba6-2f04efa8b097" />

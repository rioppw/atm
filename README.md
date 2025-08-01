<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Persebaran ATM di Kelurahan Tembalang</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <div class="wrapper">
            <div class="logo"><a href=''>Persebaran ATM</a></div>
            <div class="menu">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#courses">ATM</a></li>
                    <li><a href="#tutors">WebGIS</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="wrapper">
        <section id="home">
            <img src="https://img.freepik.com/premium-vector/tm-machine-isolated-white-background-cash-machine-banking-technology_373887-2383.jpg?w=360"/>
            <div class="kolom">
                <p class="deskripsi">Otomasi Sistem Informasi Geografis</p>
                <h2>Persebaran ATM di Kelurahan Tembalang</h2>
                <p>WebGIS ini dirancang untuk mengetahui persebaran ATM di Kelurahan Tembalang. Melalui adanya website ini, diharapkan dapat membantu pengguna dalam mencari ATM terdekat, memudahkan dalam mengakses informasi detail tiap ATM, dan visualisasi persebaran ATM yang ada di Kelurahan Tembalang.</p>
            </div>
        </section>

        <section id="courses">
            <div class="kolom">
                <p class="deskripsi">ATM</p>
                <h2>Kelurahan Tembalang</h2>
                <p>ATM atau Anjungan Tunai Mandiri adalah mesin elektronik yang disediakan oleh bank untuk memudahkan nasabah dalam melakukan transaksi, setor, dan tarik tunai, tanpa perlu mengunjungi kantor cabang bank.</p>
                <p>Kelurahan Tembalang memiliki luas wilayah sebesar 3.924,60 Ha dengan total 12 kelurahan, 150 RW, dan 1.139 RT. Kelurahan Tembalang kini memiliki jumlah penduduk sekitar 195.352 jiwa.</p>
            </div>
            <img src="https://i.pinimg.com/originals/d6/fa/b9/d6fab9f9f91a1502ad413563276fd1c5.gif"/>
        </section>

        <section id="tutors">
            <div class="tengah">
                <div class="kolom">
                    <p class="deskripsi">Persebaran ATM di Kelurahan Tembalang</p>
                    <h2>WebGIS</h2>
                    <p>Berikut WebGIS persebaran ATM yang ada di Kelurahan Tembalang, beserta informasi terkait.</p>
                </div>

                <div class="tutor-list">
                    <div class="kartu-tutor">
                        <iframe  style="border: none;" height="800" width="1000" src="https://0448c743784a.ngrok-free.app/mapstore/dashboard-embedded.html#/40"></iframe>
                        <p>Peta Persebaran ATM di Kelurahan Tembalang</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="about">
            <div class="tengah">
                <div class="kolom">
                    <p class="deskripsi">Pembuat Website</p>
                    <h2>About Me</h2>
                </div>

                <div class="about-me-list">
                    <div class="kartu-about">
                        <img src="https://tse4.mm.bing.net/th/id/OIP.5GNOLesnGokWZwiKdf7lgQAAAA?rs=1&pid=ImgDetMain&o=7&rm=3"/>
                        <p>Rio Putra Permana Waskita</p>
                        <p>(21110121130039)</p>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <div id="contact">
        <div class="wrapper">
            <div class="footer">
                <div class="footer-section">
                    <h3>Teknik Geodesi</h3>
                    <p>Jurusan Teknik Geodesi, Fakultas Teknik, Universitas Diponegoro</p>
                </div>
                <div class="footer-section">
                    <h3>OSIG</h3>
                    <p>Tugas project Otomasi Sistem Informasi Geografis</p>
                </div>
                <div class="footer-section">
                    <h3>Kontak</h3>
                    <p>riopermana037@gmail.com</p>
                </div>
            </div>
        </div>
    </div>

    <div id="copyright">
        <div class="wrapper">
            &copy; 2024. <b>Rio Putra Permana Waskita</b> All Rights Reserved.
        </div>
    </div>
    
</body>
</html>

* {
    text-decoration: none;
    margin: 0px;
    padding: 0px;
}

body {
    margin: 0px;
    padding: 0px;
    font-family: 'Perpetua', sans-serif;
}

.wrapper {
    width: 1100px;
    margin: auto;
    position: relative;
}

.logo a {
    font-size: 50px;
    font-weight: 800;
    float: left;
    font-family: perpetua;
    color: #b97339;
}

.menu {
    float: right;
}

nav {
    width: 100%;
    margin: auto;
    display: flex;
    line-height: 80px;
    position: sticky;
    position: -webkit-sticky;
    top: 0;
    background: #FFFFFF;
    z-index: 1;
    border-bottom: 1px solid #743e14;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

nav ul li {
    float: left;
}

nav ul li a {
    color: black;
    font-weight: bold;
    text-align: center;
    padding: 0px 16px 0px 16px;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    margin: auto;
    display: flex;
    margin-bottom: 50px;
}

.kolom {
    margin-top: 50px;
    margin-bottom: 50px;
}

.kolom .deskripsi {
    font-size: 20px;
    font-weight: bold;
    font-family: 'cambria';
    color: #743e14;
}

h2 {
    font-family: 'cambria';
    font-weight: 800;
    font-size: 45px;
    margin-bottom: 20px;
    color: #b97339;
    width: 100%;
    line-height: 50px;
}

a.tbl-biru {
    background: #3f72af;
    border-radius: 20px;
    margin-top: 20px;
    padding: 15px 20px 15px 20px;
    color: #FFFFFF;
    cursor: pointer;
    font-weight: bold;
}

a.tbl-biru:hover {
    background: #fc5185;
    text-decoration: none;
}

a.tbl-pink {
    background: #fc5185;
    border-radius: 20px;
    margin-top: 20px;
    padding: 15px 20px 15px 20px;
    color: #FFFFFF;
    cursor: pointer;
    font-weight: bold;
}

a.tbl-pink:hover {
    background: #3f72af;
    text-decoration: none;
}

p {
    margin: 10px 0px 10px 0px;
    padding: 10px 0px 10px 0px;
}

.tengah {
    text-align: center;
    width: 100%;
}

.tutor-list {
    width: 100%;
    position: center;
    display: flex;
    flex-wrap: wrap;
}

.kartu-tutor {
    width: 100%;
    margin: 0 auto;
}

.kartu-tutor img {
    width: 80%;
    border-radius: 50%;
}

.kartu-tutor p {
    font-family: 'cambria';
    font-weight: 800;
    font-size: 25px;
    text-align: center;
    color: #364f6b;
}

.about-me-list {
    width: 100%;
    position: center;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.kartu-about {
    width: 25%; /* Adjusted width for a single card */
    margin: 0 auto;
}

.kartu-about img {
    width: 150px;
    border-radius: 50%;
}

.kartu-about p {
    font-family: 'cambria';
    font-weight: 800;
    font-size: 20px;
    text-align: center;
    color: #364f6b;
}


#contact {
    background: #dedede;
    padding: 50px 0px 50px 0px;
}

.footer {
    width: 100%;
    position: center;
    display: flex;
    flex-wrap: wrap;
    margin: auto;
}

.footer-section {
    width: 20%;
    margin: 0 auto;
}

h3 {
    font-family: 'cambria';
    font-weight: 800;
    font-size: 30px;
    margin-bottom: 20px;
    color: #743e14;
    width: 100%;
    line-height: 50px;
}

#copyright {
    text-align: center;
    width: 100%;
    padding: 50px 0px 50px 0px;
    margin-top: 50px;
}

@media screen and (max-width: 991.98px) {
    .wrapper {
        width: 90%;
    }

    .logo a {
        display: block;
        width: 100%;
        text-align: center;
    }

    nav .menu {
        width: 100%;
        margin: 0;
    }

    nav .menu ul {
        text-align: center;
        margin: auto;
        line-height: 60px;
    }

    nav .menu ul li {
        display: inline-block;
        float: none;
    }

    section {
        display: block;
    }

    section img {
        display: block;
        width: 100%;
        height: auto;
    }

    .kartu-tutor {
        width: 50%;
    }

    .kartu-about {
        width: 50%;
    }
}

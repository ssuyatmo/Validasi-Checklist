<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Sederhana</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0; /* Menghilangkan margin default */
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .header {
            background-color: #4267B2;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .sidebar {
            background-color: #f0f0f0; /* Warna latar abu-abu */
            padding: 20px;
            height: 100vh; /* Tinggi penuh viewport */
            overflow-y: auto; /* Scrollbar jika konten melebihi tinggi */
            display: none; /* Awalnya disembunyikan */
        }
        .content {
            padding: 20px;
            height: 100vh; /* Tinggi penuh viewport */
            overflow-y: auto; /* Scrollbar jika konten melebihi tinggi */
        }
        .menu-toggle {
            background-color: #4267B2;
            color: white;
            padding: 10px 20px;
            cursor: pointer;
        }
        .sidebar.open {
            display: block; /* Ditampilkan saat open */
        }
        @media (min-width: 768px) { /* Untuk layar lebar, tampilkan sidebar secara default */
            .sidebar {
                display: block;
                float: left;
                width: 20%;
            }
            .content {
                float: left;
                width: 80%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Facebook Sederhana</h1>
            <div class="menu-toggle" onclick="toggleSidebar()">☰ Menu</div>
        </div>
        <div class="sidebar" id="sidebar">
            <h3>Daftar Teman</h3>
            <ul>
                <li>Teman 1</li>
                <li>Teman 2</li>
                <li>Teman 3</li>
            </ul>
        </div>
        <div class="content">
            <h3>Beranda</h3>
            <p>Ini adalah feed berita sederhana.</p>
        </div>
    </div>

    <script>
        function toggleSidebar() {
            document.getElementById('sidebar').classList.toggle('open');
        }
    </script>
</body>
</html>

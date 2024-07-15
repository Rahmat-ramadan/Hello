<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('main.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        }

        .container {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8); /* background warna putih dengan transparansi */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px; /* Mengatur max-width menjadi lebih kecil */
            width: 90%;
            margin-top: 20px;
        }

        h1 {
            color: #1a73e8; /* warna biru google */
        }

        p {
            color: #555;
            line-height: 1.6;
        }

        .pdf-links a {
            display: block;
            color: #1a73e8;
            text-decoration: none;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #1a73e8;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        .pdf-links a:hover {
            background-color: #1a73e8;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="main1.jpg" alt="Foto Profil" class="profile-pic">
        <h1>Selamat Datang</h1>
        <p>Pilih Menu akses :</p>
        <div class="pdf-links">
            <a href="biodata.html" target="_blank">Biodata</a>
            <a href="catalog.html" target="_blank">Blog Pribadi</a>
        </div>
    </div>
</body>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warung Kopi Sederhana</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light text-dark"> <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">☕ Kedai Wenak</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menuMinimalis">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="menuMinimalis">
                <div class="navbar-nav ms-auto">
                    <a class="nav-link" href="#tentang">Tentang</a>
                    <a class="nav-link" href="#menu">Menu</a>
                    <a class="nav-link" href="#kontak">Alamat</a>
                </div>
            </div>
        </div>
    </nav>

    <header class="bg-warning text-dark text-center py-5">
        <div class="container">
            <h1 class="fw-bold">Warung Kopi Wenak</h1>
            <p class="lead">Tempat sederhana untuk sekadar rehat dan melepas lelah.</p>
            <a href="#menu" class="btn btn-dark mt-2">Lihat Menu Kami</a>
        </div>
    </header>

    <section id="tentang" class="container py-5">
        <div class="row align-items-center">
            <div class="col-md-6 mb-4 mb-md-0">
                <img src="https://images.unsplash.com/photo-1541167760496-1628856ab772?q=80&w=500&auto=format&fit=crop" class="img-fluid rounded shadow" alt="Kopi">
            </div>
            <div class="col-md-6">
                <h2 class="fw-bold">Kenalan Yuk!</h2>
                <p>Kedai ini kami buka dari teras rumah sendiri. Modalnya nekat, tapi niatnya tulus: ingin jualan kopi enak dengan harga yang tidak bikin kantong bolong.</p>
                <p>Di sini tidak ada aturan kaku. Mau nugas berjam-jam atau cuma numpang melamun sore-sore, silakan datang saja. Kami tunggu ya!</p>
            </div>
        </div>
    </section>

    <section id="menu" class="bg-white py-5">
        <div class="container">
            <h2 class="text-center fw-bold mb-4">Menu Signature Kami</h2>
            
            <div class="row g-3">
                <div class="col-md-4">
                    <div class="p-3 border rounded bg-light">
                        <h5>☕ Kopi Tubruk - Rp 10.000</h5>
                        <p class="text-muted small mb-0">Kopi hitam pekat asli tanpa drama, pas buat nemenin ngerjain tugas.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="p-3 border rounded bg-light">
                        <h5>🥛 Kopi Susu - Rp 15.000</h5>
                        <p class="text-muted small mb-0">Manis dan gurihnya pas, cocok buat yang gak terlalu suka pahit.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="p-3 border rounded bg-light">
                        <h5>🍪 Pisang Goreng - Rp 12.000</h5>
                        <p class="text-muted small mb-0">Disajikan hangat-hangat, satu porsi isinya tiga biji besar.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="kontak" class="container py-5 text-center">
        <h2 class="fw-bold mb-3">Lokasi Kedai</h2>
        <p class="mb-1">📍 Jl. Damai Selalu No. 7 (Depan Lapangan Kampung)</p>
        <p class="mb-4">📞 WhatsApp: 0812-9999-0000</p>
        <p class="text-muted small">Buka dari jam 6 pagi untuk kopag mu sampai habis.</p>
    </section>

    <footer class="bg-dark text-white text-center py-3 small">
        <p class="mb-0">© 2026 Kedai Jujur. Dibuat dengan hati dan tangan terbaik.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

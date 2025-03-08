<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duta Lingkungan & Adiwiyata Creative SMAN 6 Tambun Selatan</title>
    <style>
        :root {
            --primary-color: #1a936f;
            --secondary-color: #88d498;
            --accent-color: #3498db;
            --dark-color: #114b5f;
            --light-color: #f1f7ed;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light-color);
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        
        .logo-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            padding: 20px;
            flex-wrap: wrap;
        }
        
        .logo-container img {
            height: 100px;
        }
        
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 4rem 1rem;
            text-align: center;
        }
        
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-10px);
        }
        
        .card-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .card-content {
            padding: 1.5rem;
        }
        
        .card-content h3 {
            color: var(--dark-color);
            margin-bottom: 1rem;
        }
        
        .card-content p {
            color: #555;
            margin-bottom: 1.5rem;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }
        
        .btn:hover {
            background-color: var(--dark-color);
        }
        
        .video-container {
            position: relative;
            width: 100%;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            margin: 2rem 0;
        }
        
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
        
        .social-media {
            background-color: var(--secondary-color);
            padding: 3rem 1rem;
            text-align: center;
        }
        
        .social-media h2 {
            color: var(--dark-color);
            margin-bottom: 2rem;
        }
        
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 1.5rem;
        }
        
        .social-icon {
            background-color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            color: var(--primary-color);
            text-decoration: none;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }
        
        .social-icon:hover {
            transform: scale(1.1);
            background-color: var(--dark-color);
            color: white;
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            text-align: center;
            padding: 2rem;
        }
        
        @media (max-width: 768px) {
            .hero h2 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .card-container {
                grid-template-columns: 1fr;
            }
            
            .logo-container img {
                height: 80px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Duta Lingkungan & Adiwiyata Creative</h1>
        <p>SMAN 6 Tambun Selatan</p>
    </header>
    
    <div class="logo-container">
        <img src="/api/placeholder/150/150" alt="Logo SMAN 6 Tambun Selatan">
        <img src="/api/placeholder/150/150" alt="Logo Adiwiyata Creative">
        <img src="/api/placeholder/150/150" alt="Logo Duta Lingkungan">
    </div>
    
    <section class="hero">
        <h2>Menuju Sekolah Berbudaya Lingkungan</h2>
        <p>Melestarikan lingkungan hidup dan menciptakan generasi yang peduli akan keberlanjutan masa depan bumi.</p>
    </section>
    
    <div class="container">
        <h2>Program Kami</h2>
        <div class="card-container">
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Green Project" class="card-img">
                <div class="card-content">
                    <h3>Green Project 🌿‼️</h3>
                    <p>Program inovatif untuk lingkungan hidup yang berkelanjutan. Mari bergabung dalam berbagai kegiatan peduli lingkungan!</p>
                    <a href="http://bit.ly/4icFdFg" class="btn" target="_blank">Selengkapnya</a>
                </div>
            </div>
            
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Adiwiyata" class="card-img">
                <div class="card-content">
                    <h3>Program Adiwiyata</h3>
                    <p>Program pembinaan lingkungan hidup untuk mewujudkan sekolah yang peduli dan berbudaya lingkungan.</p>
                    <a href="#video" class="btn">Lihat Video</a>
                </div>
            </div>
            
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Duta Lingkungan" class="card-img">
                <div class="card-content">
                    <h3>Duta Lingkungan</h3>
                    <p>Para pelajar yang terpilih sebagai duta dalam menyebarkan kesadaran dan aksi nyata untuk melestarikan lingkungan.</p>
                    <a href="#social" class="btn">Media Sosial</a>
                </div>
            </div>
        </div>
        
        <div id="video" class="video-container">
            <iframe src="https://www.youtube.com/embed/Q7H7QpRoF8U" title="Video Profil Sekolah Adiwiyata SMAN 6 Tambun Selatan" allowfullscreen></iframe>
        </div>
    </div>
    
    <section id="social" class="social-media">
        <h2>Ikuti Kami di Media Sosial</h2>
        <p>Dapatkan informasi terbaru tentang kegiatan Duta Lingkungan SMAN 6 Tambun Selatan</p>
        <div class="social-icons">
            <a href="https://www.instagram.com/dutalingkungan.smansix?igsh=cHVibnpyY3p4Y3Z2" class="social-icon" target="_blank">
                <span>IG</span>
            </a>
            <a href="https://www.tiktok.com/@dutalingkungan.smansix?_t=ZS-8uWG2sTJT2g&_r=1" class="social-icon" target="_blank">
                <span>TT</span>
            </a>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 Duta Lingkungan & Adiwiyata Creative SMAN 6 Tambun Selatan</p>
        <p>Jalan Raya Mangunjaya No.1, Mangunjaya, Kec. Tambun Selatan, Kabupaten Bekasi, Jawa Barat</p>
    </footer>
</body>
</html>

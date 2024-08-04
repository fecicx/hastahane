<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Özel Hastane</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Özel Hastane</h1>
        <nav>
            <ul>
                <li><a href="#home">Ana Sayfa</a></li>
                <li><a href="#services">Hizmetler</a></li>
                <li><a href="#doctors">Doktorlar</a></li>
                <li><a href="#contact">İletişim</a></li>
                <li><a href="#appointment">Randevu Al</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Hoş Geldiniz</h2>
        <p>Özel Hastane, sizlere en iyi sağlık hizmetini sunmak için burada.</p>
    </section>
    
    <section id="services">
        <h2>Hizmetlerimiz</h2>
        <ul>
            <li>Genel Cerrahi</li>
            <li>Kardiyoloji</li>
            <li>Dahiliye</li>
            <li>Ortopedi</li>
        </ul>
    </section>
    
    <section id="doctors">
        <h2>Doktorlarımız</h2>
        <div class="doctor">
            <h3>Dr. Ahmet Yılmaz</h3>
            <p>Kardiyolog</p>
        </div>
        <div class="doctor">
            <h3>Dr. Ayşe Kaya</h3>
            <p>Genel Cerrah</p>
        </div>
    </section>
    
    <section id="contact">
        <h2>İletişim</h2>
        <p>Email: info@ozelhastane.com</p>
        <p>Telefon: (123) 456-7890</p>
    </section>
    
    <section id="appointment">
        <h2>Randevu Al</h2>
        <form>
            <label for="name">İsim:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="date">Randevu Tarihi:</label>
            <input type="date" id="date" name="date" required>
            <button type="submit">Gönder</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 Özel Hastane. Tüm hakları saklıdır.</p>
    </footer>
</body>
</html>

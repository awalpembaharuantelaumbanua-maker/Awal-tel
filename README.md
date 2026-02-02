<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>index</title>
      <link rel="stylesheet" href="Style.css">
</head>
<body>
  <header>
    <nav>
      <h3>LAPAK~PALING ™OK™👍👍. </h3>
      <a href="#">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <section id="landing">
    <div>
      <h1>Selamat Datang di Lapak Kami yang bermacam m@ca</h1>
      <p>Ini adalah salah satu menu di lapak awal serbah 13.000.00 berkesan yang minat boleh di lihat lih@t☠️</p>
    </div>
    <div>
      <img src="Kue.jpg">
    </div>
  </section>
  <section id="landing2">
    <div class="menu">
      <div class="aneka-menu">
        <img src="Pisang-goreng.jpg">
        </div>
        <div class="aneka-title">
          <h1>Menu 1 Pisang-goreng</h1>
      </div> 
      <div class="aneka-menu">
        <img src="Tahu goreng.jpg">
        </div>
        <div class="aneka-title">
          <h1>Menu 2 Tahu goreng</h1>
      </div> 
      <div class="aneka-menu serbah 13.000.00">
        <img src="Kentang-goreng.jpg">
         </div>
        <div class="aneka-title">
          <h1>Menu 3 Kentang-goreng</h1>
      </div> 
    </div>
  </section>
 </body>
</html>

footer id="footer">
            <div class="footer-container">
                <div class="footer-section">
                    <h3>kontak saya</h3>
                    <a><i class="fab fa-facebook"></i></a>
                    <a><i class="fab fa-instagram"></i></a>
                    <a><i class="fab fa-tiktok"></i></a>
                </div>
                <div class="footer-section">
                    <h3 class="class-title">HUBUNGI DI BAWAH INI</h3>
                    <ul>
                    <img src="Aaaa.jpg" width="20" height="20" alt="WhatsAAP.">
                        <a><i class="">085211885733</i></a>
                    </ul>
                    <ul class="TELAUMBANUA">
                    <img src="ppp.jpg" width="20" height="20" alt="TELEPON">
                        <a>085211885733</a>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 awal pembaharuan tel Terima kasih.</p>
            </div>
        </footer># Awal-tel
Belajar html
    



* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  
  font-family: Times New Roman;
  background-color: green;
  color: yellow;
  line-height: 1.5;

}
header {
  display: flex;
  background-color: blue;
  color: black;
  align-items: center;
  justify-content: space-between;
  position: sticky;
  top: 0;
  padding: 20px 60px;
}

header h3 {
  font-size: 30px;
}

nav a {
  color: black;
  text-decoration: none;
}

img {
  width: 100%;
  height: auto;
}

#landing {
  display: flex;
  padding: 20px 10px;
  margin: 10px 10px;
}

#section2 {
  display: flex;
  align-items: center;
  justify-content: center;
}

.aneka-menu {
  display: flex;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

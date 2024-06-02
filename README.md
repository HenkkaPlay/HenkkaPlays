<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HenkkaPlays</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            background-image: url('https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/i/d96bb958-4e6c-4ce0-9447-fbe226fbbecf/dgsa8d8-be32573a-c30f-44fe-a282-51a5b47e6ee7.jpg');
            background-size: cover;
            background-position: fixed;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        #channel-button {
            font-size: 50px;
}
.k50 {
    font-size: 20px;
    color: ghostwhite;
}
.videot {
    font-size: 30px;
    color: red;
}
abbr {
    color: red;
}
#dcbutton {
            background-color: #58cc02;
            box-shadow: 0 5px 0 #58a700;
            padding: 20px;
            margin: 20px auto;
            display: block;
            font-size: 18px;
        }
        .tietoa {
            font-size: 25px;
        }

    </style>
</head>
<body>
    <header>
        <h1 id="tervetuloa">Tervetuloa!</h1>
    </header>
    <div id="valikko">
        <button class="tietoa" onclick="naytaKauppa()">Tietoa</button>
      </div>
      
      <div id="kauppa" style="display:none;">
        <p class="k50">Jos olet tilannut kanavani, voin antaa sinulle <abbr title="testi">50k purea :]</abbr> Laita minulle Discordissa viestiä!</p>
        <a href="https://www.youtube.com/@HenkkaPlays" target="_blank" id="munkanava">Tilaahan :D</a>
        <button onclick="back()">Takaisin</button>
      </div>
    <section>
        <h2 class="videot">Videot</h2>
        <iframe width="490" height="245" src="https://www.youtube.com/embed/IzOg10Cg4aQ?si=2G74o5BQ7srjyq8k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="490" height="245" src="https://www.youtube.com/embed/Z9XpuFrRzNE?si=Q2XdmNFEoK1kffdq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="490" height="245" src="https://www.youtube.com/embed/rGWlOhGhepw?si=EiI2JbhfRIKmLJE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="490" height="245" src="https://www.youtube.com/embed/INdFay_7qKk?si=b7_TxCVNgWmab9O3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="490" height="245" src="https://www.youtube.com/embed/blIZZSiGLtI?si=ZSEjAEbcvXCdLCTZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="490" height="245" src="https://www.youtube.com/embed/CJAHaFvl54s?si=knPp01gbzKgTMhE5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </section>
    <section>
        <a href="https://www.youtube.com/@HenkkaPlays" target="_blank" id="channel-button">Mun kanava</a>
    </section>
    <button id="dcbutton">Discord<br>servu</button>
    <footer>
        &copy; Henkka Plays
    </footer>
    <script>
        const dcbutton = document.getElementById('dcbutton');
        dcbutton.addEventListener('click', function() {
            window.location.href = 'https://discord.com/channels/1246890374551834684/1246890374551834687';
        });
        function naytaKauppa() {
          document.getElementById("valikko").style.display = "none";
          document.getElementById("kauppa").style.display = "block";
        }
        
        function back() {
          document.getElementById("kauppa").style.display = "none";
          document.getElementById("valikko").style.display = "block";
        }
        </script>
        
</body>
</html>

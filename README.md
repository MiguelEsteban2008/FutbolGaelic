<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Torneig de Futbol Gaèlic 2025</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e5f5e0;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #2e7d32;
            color: white;
            padding: 1.5em;
            text-align: center;
        }
        main {
            padding: 2em 1em;
            text-align: center;
            background-color: #ffffff;
            margin-top: 2em;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .info {
            margin: 1.5em 0;
            font-size: 1.2em;
        }
        .highlight {
            color: #2e7d32;
            font-weight: bold;
        }
        footer {
            background-color: #c8e6c9;
            text-align: center;
            padding: 1em;
            margin-top: 2em;
        }
        h1, h2 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Torneig de Futbol Gaèlic</h1>
        <p>Vine a viure l'emoció del futbol gaèlic!</p>
    </header>

    <main id="main-content">
        <!-- El contingut es carregarà dinàmicament amb JavaScript -->
    </main>

    <footer>
        <p>Organitza: [Nom de l'organització o institut]</p>
    </footer>

    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const mainContent = document.getElementById("main-content");

            const data = {
                date: "20 de març de 2025",
                time: "A partir de les 10:00 h",
                location: "Camp de Futbol Pla d'en Boet, Mataró",
                format: "Equips de 7 contra 7",
                prizes: "Premis pels equips guanyadors!"
            };

            const content = `
                <div class="info">
                    <p><span class="highlight">Data:</span> ${data.date}</p>
                    <p><span class="highlight">Hora:</span> ${data.time}</p>
                    <p><span class="highlight">Lloc:</span> ${data.location}</p>
                </div>
                
                <div class="info">
                    <p><span class="highlight">Format:</span> ${data.format}</p>
                    <p>Esport, diversió i bon ambient assegurats!</p>
                    <p><span class="highlight">Premis:</span> ${data.prizes}</p>
                </div>
                
                <h2>No t'ho perdis!</h2>
                <p>Vine a animar o participa-hi!</p>
            `;

            mainContent.innerHTML = content;
        });
    </script>
</body>
</html>

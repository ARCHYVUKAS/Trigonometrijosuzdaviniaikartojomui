<!DOCTYPE html>
<html>
<body>
<h1>Testas</h1>
<a href="https://github.com/ARCHYVUKAS/Trigonometrijosuzdaviniai.git">
Spausk čia
</a>

</body>
</html>




   <!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <title>Trigonometrija</title>
</head>
<body>

    <h1>Trigonometrijos pagrindai</h1>

    <h2>Pagrindinės funkcijos:</h2>
    <ul>
        <li>sin(x) – priešpriešinis / įžambinė</li>
        <li>cos(x) – priešinė / įžambinė</li>
        <li>tan(x) – priešpriešinis / priešinė</li>
    </ul>

    <h2>Svarbios reikšmės:</h2>
    <ul>
        <li>sin(0°) = 0</li>
        <li>sin(90°) = 1</li>
        <li>cos(0°) = 1</li>
        <li>cos(90°) = 0</li>
    </ul>

    <h2>Pasitikrink:</h2>
    <p>Kiek yra sin(90°)?</p>

    <button onclick="rodyti()">Rodyti atsakymą</button>

    <p id="ats"></p>

    <script>
        function rodyti() {
            document.getElementById("ats").innerText = "Atsakymas: 1";
        }
    </script>

</body>
</html>

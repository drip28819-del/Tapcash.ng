
<!DOCTYPE html>
<html>
<head>
    <title>TapCash</title>
</head>
<body>
    <h1>TapCash 💸</h1>
    <p>Tap the button below to earn coins!</p>
    
    <h2>Score: <span id="score">0</span></h2>
    <button onclick="tapCoin()" style="font-size: 20px; padding: 15px 30px;">TAP ME 💰</button>

    <script>
        let count = 0;
        function tapCoin() {
            count += 1;
            document.getElementById("score").innerText = count;
        }
    </script>
</body>
</html>

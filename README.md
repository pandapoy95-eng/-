# <!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>سایت من</title>

    <style>
        body {
            font-family: sans-serif;
            text-align: center;
            background: #111;
            color: white;
            padding: 50px;
        }

        button {
            padding: 12px 25px;
            font-size: 18px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <h1>سلام! 👋</h1>

    <p id="text">این اولین سایت منه 🚀</p>

    <button onclick="changeText()">
        کلیک کن
    </button>

    <script>
        function changeText() {
            document.getElementById("text").innerText =
                "کد JavaScript اجرا شد! 🎉";
        }
    </script>

</body>
</html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>DASHBOARD</title>

    <style>
        body {
            background: black;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: Arial, sans-serif;
        }

        .tiles-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            width: 90%;
            max-width: 1000px;
        }

        .tile {
            text-decoration: none;
            color: rgba(255,255,255,0.7);
            border: 1px solid rgba(255,255,255,0.2);
            padding: 40px 20px;
            text-align: center;
            letter-spacing: 10px;
            text-transform: uppercase;
        }
    </style>
</head>

<body>

    <div class="tiles-grid">
        <a href="countdown.html" class="tile">Exam Tracker</a>
    </div>

</body>
</html>

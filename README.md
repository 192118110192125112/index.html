
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DASHBOARD</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #000000; /* Pure Black */
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .tiles-grid {
            display: flex;
            justify-content: center;
            width: 100%;
        }

        .tile {
            text-decoration: none;
            color: rgba(255, 255, 255, 0.7);
            border: 1px solid rgba(255, 255, 255, 0.15);
            padding: 30px 60px;
            text-align: center;
            font-size: 0.8rem;
            font-weight: 400;
            letter-spacing: 12px; /* Professional Spacing */
            text-transform: uppercase;
            transition: all 0.5s ease;
            background: transparent;
        }

        .tile:hover {
            background: #ffffff;
            color: #000000;
            border-color: #ffffff;
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

    <div class="tiles-grid">
        <a href="countdown.html" class="tile">Exam Tracker</a>
    </div>

</body>
</html>

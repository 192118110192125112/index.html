
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
            background-color: #000000;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
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
            color: rgba(255, 255, 255, 0.7);
            border: 1px solid rgba(255, 255, 255, 0.15);
            padding: 40px 20px;
            text-align: center;
            font-size: 0.75rem;
            font-weight: 400;
            letter-spacing: 10px; /* Classy Spacing */
            text-transform: uppercase;
            transition: all 0.6s cubic-bezier(0.16, 1, 0.3, 1);
            background: transparent;
        }

        .tile:hover {
            background: #ffffff;
            color: #000000;
            border-color: #ffffff;
            transform: scale(1.02);
            letter-spacing: 12px; /* Hover effect */
        }

        @media (max-width: 600px) {
            .tile { letter-spacing: 6px; }
        }
    </style>
</head>
<body>

    <div class="">
        <a href="countdown.html" class="tile">Exam Tracker</a>
        
        </div>

</body>
</html>

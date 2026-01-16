<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY PORTAL</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200;600&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #000000; /* Pure Black Background */
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #ffffff;
        }

        .wrapper {
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            font-weight: 200;
            letter-spacing: 20px; /* Elegant Spacing */
            text-transform: uppercase;
            margin-bottom: 80px;
            color: rgba(255, 255, 255, 0.8);
        }

        .tiles-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            max-width: 900px;
        }

        .tile {
            text-decoration: none;
            color: rgba(255, 255, 255, 0.6);
            border: 1px solid rgba(255, 255, 255, 0.2);
            padding: 25px 50px;
            font-size: 0.8rem;
            font-weight: 600;
            letter-spacing: 3px;
            text-transform: uppercase;
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            background: transparent;
        }

        .tile:hover {
            background: #ffffff;
            color: #000000;
            border-color: #ffffff;
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(255, 255, 255, 0.1);
        }

        @media (max-width: 600px) {
            h1 { font-size: 1.8rem; letter-spacing: 10px; }
            .tile { width: 80%; }
        }
    </style>
</head>
<body>

    <div class="wrapper">
        <h1>Portal</h1>
        
        <div class="tiles-container">
            <a href="countdown.html" class="tile">Exam Tracker</a>
            
            </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>Cihan Auto</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            height: 100vh;
            background: linear-gradient(135deg, #0f0f0f, #1c1c1c);
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Montserrat', sans-serif;
            color: #fff;
        }

        .container {
            text-align: center;
            animation: fadeIn 1.5s ease;
        }

        h1 {
            font-size: 64px;
            font-weight: 700;
            letter-spacing: 6px;
        }

        .line {
            width: 80px;
            height: 3px;
            background: #e50914;
            margin: 20px auto;
        }

        p {
            font-size: 18px;
            font-weight: 300;
            letter-spacing: 3px;
            color: #ccc;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 42px;
                letter-spacing: 4px;
            }
            p {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>CIHAN AUTO</h1>
        <div class="line"></div>
        <p>PREMIUM AUTO GALLERY</p>
    </div>

</body>
</html>

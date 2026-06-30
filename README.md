<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Agrinho 2026</title>
    <style>
        /* Fundo com degradê animado e super colorido */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(-45deg, #39ff14, #ff007f, #00e5ff, #ffea00);
            background-size: 400% 400%;
            animation: gradientAnimation 15s ease infinite;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Caixa de boas-vindas flutuante */
        .welcome-box {
            text-align: center;
            background: rgba(255, 255, 255, 0.9);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            animation: float 4s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
        }

        h1 {
            color: #2e7d32;
            font-size: 3rem;
            margin-bottom: 10px;
        }

        p {
            color: #555;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

    <div class="welcome-box">
        <h1>Agrinho 2026</h1>
        <p>Inovação, Campo e Cidade em um só lugar!</p>
    </div>

</body>
</html>

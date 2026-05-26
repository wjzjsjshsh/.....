<!DOCTYPE html>
<html lang="ku">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You</title>
    <style>
        /* ڕێکخستنا گشتی یا پەرپى */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #ffffff; /* پشتپەردەیا سپی */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
        }

        /* کانتینەرێ سەرەکی */
        .container {
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        /* ستایلێ نڤیسینێ */
        h1 {
            font-size: 3.5rem;
            color: #333333;
            margin-bottom: 10px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        /* ستایلێ دڵی و ئەنیمەیشنا لێدانێ */
        .heart {
            font-size: 5rem;
            color: #ff3838;
            margin: 20px 0;
            display: inline-block;
            animation: heartbeat 1.2s infinite;
        }

        /* ستایلێ وێنەی */
        .love-image {
            width: 300px;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            margin-top: 20px;
            transition: transform 0.3s ease;
        }

        .love-image:hover {
            transform: scale(1.05); /* دەما ماوس دچیتە سەر وێنەی دێ مەزن بیت */
        }

        /* ئەنیمەیشنا لێدانا دڵی */
        @keyframes heartbeat {
            0% { transform: scale(1); }
            20% { transform: scale(1.15); }
            40% { transform: scale(1); }
            60% { transform: scale(1.15); }
            80% { transform: scale(1); }
            100% { transform: scale(1); }
        }

        /* ئەنیمەیشنا دیاربوونا لاپەڕی */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>I Love You</h1>
        
        <div class="heart">❤️</div>
        
        <br>
        
        <img class="love-image" src="https://images.unsplash.com/photo-1518199266791-5375a83190b7?q=80&w=600&auto=format&fit=crop" alt="Love Image">
    </div>

</body>
</html>

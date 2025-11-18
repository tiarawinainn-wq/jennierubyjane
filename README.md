<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jennie Kim</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            background: url('foto.jpg') center/cover no-repeat;
            position: relative;
            font-family: Arial, sans-serif;
        }

        .overlay {
            position: absolute;
            inset: 0;
            background: rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(3px);
        }

        .content {
            position: relative;
            z-index: 10;
            text-align: center;
            padding: 40px;
            color: white;
        }

        .content h1 {
            font-size: 60px;
            margin-bottom: 20px;
        }

        .content p {
            font-size: 22px;
            line-height: 1.6;
            max-width: 900px;
            margin: auto;
        }

        /* 🌸 RESPONSIVE UNTUK HP */
        @media (max-width: 600px) {

            body {
                background-position: center;
            }

            .content {
                padding: 20px;
            }

            .content h1 {
                font-size: 28px;
            }

            .content p {
                font-size: 16px;
                padding: 0 10px;
                text-align: center;
            }

            .overlay {
                background: rgba(0, 0, 0, 0.45);
                backdrop-filter: blur(2px);
            }
        }
    </style>
</head>

<body>
    <div class="overlay"></div>

    <div class="content">
        <h1>Jennie Kim? Jendeuki</h1>
        <p>
            Smart, Creative, Inspiring.<br><br>
            Jendeuki always give me motivation for learning, for growing, and for achieving my dreams.
            even i always crying on my study journey, i always find strength in her inspiration.<br><br>
            at the sometime if i crying in my room cause i really hard to learning i always remember to keep going and never give up
            Because i want to meet my goals and make her proud.<br><br>
            i want to meet with jennie, i want she now that’s i got my goals because of her inspiration.
            i love you jendeuki, thank you for everything.<br><br>
            i promise to meet you someday.<br>
            from your biggest fan.<br>
            with love -Tiara Wina Indriani
        </p>
    </div>
</body>
</html>

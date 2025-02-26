<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>eddy_social</title>
    <style>
        @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: black url('https://img.freepik.com/free-photo/halloween-mask-decorative-rag_23-2147685548.jpg?t=st=1740433664~exp=1740437264~hmac=6305af175a98cfb2caea026ab41f41cc3270c2f3e51c439b3ffbaa26d40f547f&w=740') no-repeat center center/cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            text-align: center;
            color: white;
        }

        .container {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 15px;
            width: 90%;
            max-width: 400px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
        }

        h1 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .button {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            font-size: 20px;
            text-align: center;
            color: white;
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid white;
            border-radius: 10px;
            text-decoration: none;
            transition: 0.3s;
        }

        .button i {
            margin-right: 10px;
            font-size: 22px;
        }

        .button:hover {
            background: white;
            color: black;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 24px;
            }
            .button {
                font-size: 18px;
                padding: 10px;
            }
            .button i {
                font-size: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>eddy_social</h1>
        <a href="https://discord.gg/guxpqE5p" class="button"><i class="fab fa-discord"></i> Join My Discord</a>
        <a href="https://steamcommunity.com/profiles/76561198821538520/" class="button"><i class="fab fa-steam"></i> Visit My Steam</a>
        <a href="https://www.tiktok.com/@eddy07311" class="button"><i class="fab fa-tiktok"></i> Follow on TikTok</a>
        <a href="https://kick.com/eddy0731" class="button"><i class="fas fa-video"></i> Watch Me on Kick</a>
    </div>
</body>
</html>

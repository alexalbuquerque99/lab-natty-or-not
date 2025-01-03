<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vídeo</title>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #ffffff;
            font-family: 'Arial', sans-serif;
        }
        .video-container {
            position: relative;
            width: 80%;
            max-width: 800px;
            border: 2px solid #00ffcc;
            box-shadow: 0 0 20px #00ffcc;
            border-radius: 15px;
            overflow: hidden;
        }
        video {
            width: 100%;
            height: auto;
            display: block;
        }
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            pointer-events: none;
        }
    </style>
</head>
<body>
    <div class="video-container">
        <video controls>
            <source src="https://app.runwayml.com/creation/4a13069c-08b3-4355-84e1-4d4f13755f0b" type="video/mp4">
            Seu navegador não suporta a exibição deste vídeo.
        </video>
        <div class="overlay"></div>
    </div>
</body>
</html>

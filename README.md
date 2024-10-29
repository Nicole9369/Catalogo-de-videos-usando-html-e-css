# Catalogo-de-videos-usando-html-e-css
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Vídeos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }

        .video-catalog {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .video-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 10px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }

        .video-card:hover {
            transform: scale(1.05);
        }

        .video-card img {
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
            width: 100%;
        }

        .video-card h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .video-card p {
            padding: 0 15px 15px;
            color: #555;
        }

        .video-card button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-bottom: 15px;
            transition: background-color 0.3s;
        }

        .video-card button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Catálogo de Vídeos</h1>
    </header>
    <main>
        <div class="video-catalog">
            <div class="video-card">
                <img src="https://via.placeholder.com/300x180" alt="Título do Vídeo 1">
                <h2>Título do Vídeo 1</h2>
                <p>Descrição do vídeo 1. Uma breve introdução ao conteúdo.</p>
                <button>Assistir</button>
            </div>
            <div class="video-card">
                <img src="https://via.placeholder.com/300x180" alt="Título do Vídeo 2">
                <h2>Título do Vídeo 2</h2>
                <p>Descrição do vídeo 2. Um resumo interessante do que esperar.</p>
                <button>Assistir</button>
            </div>
            <div class="video-card">
                <img src="https://via.placeholder.com/300x180" alt="Título do Vídeo 3">
                <h2>Título do Vídeo 3</h2>
                <p>Descrição do vídeo 3. Conteúdo valioso que você não pode perder.</p>
                <button>Assistir</button>
            </div>
            <div class="video-card">
                <img src="https://via.placeholder.com/300x180" alt="Título do Vídeo 4">
                <h2>Título do Vídeo 4</h2>
                <p>Descrição do vídeo 4. Dicas e truques que serão úteis.</p>
                <button>Assistir</button>
            </div>
        </div>
    </main>
</body>
</html>

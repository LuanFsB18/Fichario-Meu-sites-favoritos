# Fichario-Meu-sites-favoritos
atividade Etec.



<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus sites favoritos</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #eef2f3;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 30px;
        }
        .galeria {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            max-width: 1000px;
            width: 100%;
        }
        .item-site {
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.2s;
        }
        .item-site:hover {
            transform: translateY(-5px);
        }
        .item-site h3 {
            margin-top: 0;
            font-size: 1.2rem;
        }
        .item-site img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 4px;
            margin: 10px 0;
        }
        .item-site a {
            display: inline-block;
            margin-top: 10px;
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }
        .item-site a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <h1>Meus sites favoritos: Luan Felipe</h1>

    <div class="galeria">

        <div class="item-site">
            <h3>YouTube</h3>
            <img src="https://via.placeholder.com/300x150?text=YouTube" alt="Thumbnail YouTube">
            <a href="https://www.youtube.com" target="_blank">Acessar YouTube</a>
        </div>

        <div class="item-site">
            <h3>GitHub</h3>
            <img src="https://via.placeholder.com/300x150?text=GitHub" alt="Thumbnail GitHub">
            <a href="https://www.github.com" target="_blank">Acessar GitHub</a>
        </div>

        <div class="item-site">
            <h3>MDN Web Docs</h3>
            <img src="https://via.placeholder.com/300x150?text=MDN+Web+Docs" alt="Thumbnail MDN">
            <a href="https://developer.mozilla.org" target="_blank">Acessar MDN</a>
        </div>

        <div class="item-site">
            <h3>Google</h3>
            <img src="https://via.placeholder.com/300x150?text=Google" alt="Thumbnail Google">
            <a href="https://www.google.com" target="_blank">Acessar Google</a>
        </div>

        <div class="item-site">
            <h3>Stack Overflow</h3>
            <img src="https://via.placeholder.com/300x150?text=Stack+Overflow" alt="Thumbnail Stack Overflow">
            <a href="https://stackoverflow.com" target="_blank">Acessar Stack Overflow</a>
        </div>

    </div>

</body>
</html>

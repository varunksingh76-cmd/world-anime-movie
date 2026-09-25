<!DOCTYPE html>
<html>
<head>
    <title>World Anime & Movie</title>

    <style>
        body {
            background-color: #111;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
        }

        header {
            background-color: #222;
            padding: 20px;
        }

        h1 {
            color: red;
            margin: 0;
        }

        .menu {
            margin-top: 15px;
        }

        .menu a {
            color: white;
            text-decoration: none;
            margin: 10px;
        }

        .movies {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            padding: 30px;
        }

        .card {
            background-color: #222;
            width: 220px;
            padding: 15px;
            border-radius: 10px;
        }

        .poster {
            height: 280px;
            background-color: #333;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            border-radius: 8px;
        }

        .card h2 {
            color: white;
        }

        .rating {
            color: gold;
        }

        button {
            background-color: red;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #222;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <header>
        <h1>🎬 World Anime & Movie</h1>

        <div class="menu">
            <a href="#">Home</a>
            <a href="#">Anime</a>
            <a href="#">Movies</a>
            <a href="#">Series</a>
        </div>
    </header>

    <h2>🔥 Popular Anime & Movies</h2>

    <div class="movies">

        <div class="card">
            <div class="poster">🎬</div>
            <h2>Anime World</h2>
            <p class="rating">⭐ 8.5/10</p>
            <button>Watch Now</button>
        </div>

        <div class="card">
            <div class="poster">🍿</div>
            <h2>World Movie</h2>
            <p class="rating">⭐ 9.0/10</p>
            <button>Watch Now</button>
        </div>

        <div class="card">
            <div class="poster">🎞️</div>
            <h2>Action Anime</h2>
            <p class="rating">⭐ 8.8/10</p>
            <button>Watch Now</button>
        </div>

    </div>

    <footer>
        <p>© 2026 World Anime & Movie</p>
    </footer>

</body>
</html>

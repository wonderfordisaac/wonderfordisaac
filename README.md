
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isaac Music Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
        }
        .player-container {
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
            width: 60%;
            border-radius: 10px;
        }
        .album-list {
            text-align: left;
            margin: auto;
            width: 60%;
        }
        .album {
            padding: 10px;
            background-color: #ffffff;
            margin-top: 10px;
            box-shadow: 0px 0px 5px rgba(0,0,0,0.2);
            border-radius: 5px;
        }
        .download-btn {
            display: block;
            margin-top: 10px;
            padding: 10px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .download-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Isaac Music Hub 🎵</h1>

    <!-- Album List -->
    <div class="album-list">
        <h2>Albums:</h2>
        <div class="album">
            <h3>Album 1: Best Hits</h3>
            <audio controls>
                <source src="album1_song1.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
            <a class="download-btn" href="album1_song1.mp3" download>⬇️ Download</a>
        </div>
        <div class="album">
            <h3>Album 2: Chill Vibes</h3>
            <audio controls>
                <source src="album2_song1.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
            <a class="download-btn" href="album2_song1.mp3" download>⬇️ Download</a>
        </div>
    </div>
</body>
</html>

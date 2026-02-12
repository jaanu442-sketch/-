<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>For My Love ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            text-align: center;
            color: white;
        }

        .container {
            padding: 60px 20px;
        }

        h1 {
            font-size: 45px;
            margin-bottom: 10px;
        }

        h2 {
            font-weight: normal;
            margin-bottom: 40px;
        }

        .message {
            max-width: 700px;
            margin: auto;
            font-size: 18px;
            line-height: 1.8;
        }

        .heart {
            font-size: 50px;
            animation: beat 1s infinite;
            margin-bottom: 20px;
        }

        @keyframes beat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        .song {
            margin-top: 40px;
            font-size: 18px;
        }

        footer {
            margin-top: 50px;
            font-size: 16px;
            opacity: 0.9;
        }

        button {
            margin-top: 30px;
            padding: 10px 25px;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
            background-color: white;
            color: #ff4d6d;
        }

        button:hover {
            background-color: #ffe6eb;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="heart">❤️</div>

    <!-- RECEIVER NAME -->
    <h1>Happy Valentine’s Day, [Receiver Name]</h1>

    <!-- NICKNAME -->
    <h2>My Dearest [Nickname]</h2>

    <div class="message">
        <!-- PARAGRAPH 1 -->
        <p>
            [Paragraph 1 goes here...]
        </p>

        <!-- PARAGRAPH 2 -->
        <p>
            [Paragraph 2 goes here...]
        </p>

        <!-- PARAGRAPH 3 -->
        <p>
            [Paragraph 3 goes here...]
        </p>
    </div>

    <!-- SONG SECTION -->
    <div class="song">
        🎵 This song is dedicated to you:  
        <br>
        <a href="[Paste YouTube Link Here]" target="_blank" style="color:white; font-weight:bold;">
            [Song Name]
        </a>
    </div>

    <button onclick="loveMessage()">Click for a Surprise 💌</button>

    <footer>
        Forever yours,  
        <br>
        ❤️ [Sender Name]
    </footer>
</div>

<script>
    function loveMessage() {
        alert("I love you more than yesterday and less than tomorrow ❤️");
    }
</script>

</body>
</html># -

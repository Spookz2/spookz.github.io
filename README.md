
        .header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .game-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .game-card {
            width: 200px;
            background-color: #222;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            overflow: hidden;
            text-align: center;
            padding: 10px;
            color: #fff;
        }
        .game-card h3 {
            font-size: 1.1em;
            margin: 10px 0 5px;
        }
        .game-card p {
            font-size: 0.9em;
            color: #ccc;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #fff;
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #ccc;
        }
    </style>
    <script>
        // Function to open a popup window
        function openPopup(url) {
            window.open(url, 'popupWindow', 'width=800,height=600,scrollbars=yes');
        }
    </script>
</head>
<body>

    <div class="header">
        <h1>+</h1>
        <p>Access your favorite games instantly!</p>
    </div>

    <div class="container">
        <h2>Featured Games</h2>
        <div class="game-list">
            <!-- Game 1 - Roblox -->
            <div class="game-card">
                <h3>Roblox</h3>
                <p>Explore the world of Roblox.</p>
                <div class="button" onclick="openPopup('https://selfstudybrain.com/')">Play Now</div>
            </div>

            <!-- Game 2 - Pool -->
            <div class="game-card">
                <h3>Pool</h3>
                <p>Join the fun in 8 Ball Pool.</p>
                <div class="button" onclick="openPopup('https://www.blipzi.com/pool-8-ball-mania.html')">Play Now</div>
            </div>

            <!-- Game 3 -->
            <div class="game-card">
                <h3>Math Puzzle</h3>
                <p>Challenge yourself with math puzzles.</p>
                <div class="button" onclick="openPopup('https://blog1201.mathematicstopvaz.site/')">Play Now</div>
            </div>

            <!-- Game 4 -->
            <div class="game-card">
                <h3>Math Whiz</h3>
                <p>Test your math skills in this fun game.</p>
                <div class="button" onclick="openPopup('https://mathwhiz.click/')">Play Now</div>
            </div>

            <!-- Game 5 -->
            <div class="game-card">
                <h3>3kh0 Projects</h3>
                <p>Explore a variety of fun projects and games.</p>
                <div class="button" onclick="openPopup('https://adfree3kh0.github.io/projects.html')">Play Now</div>
            </div>

            <!-- Game 6 -->
            <div class="game-card">
                <h3>Brain Teasers</h3>
                <p>Sharpen your mind with challenging puzzles.</p>
                <div class="button" onclick="openPopup('https://example.com/game6')">Play Now</div>
            </div>

            <!-- Game 7 -->
            <div class="game-card">
                <h3>Strategy Game</h3>
                <p>Outsmart your opponents in this strategy game.</p>
                <div class="button" onclick="openPopup('https://example.com/game7')">Play Now</div>
            </div>
        </div>
    </div>

</body>
</html>


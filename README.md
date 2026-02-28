<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kitchen Memory — African food games that stick</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            background: #faf7f2;
            color: #1a2a1f;
            line-height: 1.5;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 2rem 1.5rem 4rem;
        }
        /* header */
        .header {
            text-align: center;
            margin-bottom: 3rem;
            border-bottom: 2px solid rgba(0,0,0,0.05);
            padding-bottom: 2rem;
        }
        .header h1 {
            font-size: 3rem;
            font-weight: 800;
            letter-spacing: -0.02em;
            line-height: 1.1;
            color: #1e3a2f;
        }
        .header .tagline {
            font-size: 1.3rem;
            color: #4a5b4f;
            margin-top: 0.5rem;
            font-weight: 400;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        .header .tagline span {
            font-weight: 600;
            color: #b55b3e;
        }
        .header .intro {
            margin-top: 1.5rem;
            color: #3f4d43;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            font-size: 1.1rem;
        }
        /* about section */
        .about {
            background: #ffffffd9;
            backdrop-filter: blur(4px);
            padding: 2rem;
            border-radius: 2rem;
            margin-bottom: 3rem;
            border: 1px solid rgba(0,0,0,0.05);
            box-shadow: 0 8px 24px rgba(0,0,0,0.02);
        }
        .about h2 {
            font-size: 1.6rem;
            font-weight: 700;
            margin-bottom: 1rem;
            color: #1e3a2f;
        }
        .about p {
            margin-bottom: 1rem;
            color: #2b3a30;
        }
        .about a {
            color: #b55b3e;
            text-decoration: none;
            font-weight: 500;
            border-bottom: 1px dotted transparent;
            transition: border-color 0.2s;
        }
        .about a:hover {
            border-bottom-color: #b55b3e;
        }
        /* game grid */
        .games h2 {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 2rem;
            color: #1e3a2f;
            border-left: 6px solid #b55b3e;
            padding-left: 1rem;
        }
        .game-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.8rem;
        }
        .game-card {
            background: white;
            border-radius: 1.5rem;
            padding: 1.5rem;
            box-shadow: 0 8px 20px rgba(0,0,0,0.02);
            border: 1px solid rgba(0,0,0,0.05);
            transition: transform 0.15s, box-shadow 0.2s;
            display: flex;
            flex-direction: column;
        }
        .game-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 20px 30px rgba(0,0,0,0.05);
        }
        .game-card h3 {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 0.75rem;
            color: #1e3a2f;
        }
        .game-card p {
            color: #3a4a3f;
            margin-bottom: 1.25rem;
            flex: 1;
            font-size: 0.95rem;
        }
        .game-links {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            align-items: center;
            margin-top: auto;
            border-top: 1px solid rgba(0,0,0,0.05);
            padding-top: 1rem;
        }
        .game-links a {
            color: #1e3a2f;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.9rem;
            border-bottom: 2px solid transparent;
            transition: border-color 0.2s;
        }
        .game-links a:hover {
            border-bottom-color: #b55b3e;
        }
        .game-links .code-link {
            color: #6f4f3a;
            font-weight: 400;
            margin-left: auto;
        }
        /* footer / license */
        .footer {
            margin-top: 4rem;
            padding-top: 2rem;
            border-top: 2px solid rgba(0,0,0,0.05);
            text-align: center;
            color: #5d6e62;
            font-size: 0.9rem;
        }
        .footer a {
            color: #1e3a2f;
            text-decoration: none;
            border-bottom: 1px dotted;
        }
        .footer a:hover {
            color: #b55b3e;
        }
        .footer-links {
            margin: 1rem 0;
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
        }
        @media (max-width: 600px) {
            .header h1 { font-size: 2.4rem; }
            .header .tagline { font-size: 1.1rem; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Kitchen Memory</h1>
            <div class="tagline">
                <span>Where African food lives in your gaming hands</span>
            </div>
            <div class="intro">
                A collection of games born from the African kitchen — each one a small invitation to hold a recipe, remember a scent, or learn a dish through play.
            </div>
        </div>
        <div class="about">
            <h2>About The African Gourmet</h2>
            <p>This project is part of <a href="https://www.theafricangourmet.com" target="_blank">The African Gourmet</a> ecosphere — a digital archive dedicated to exploring and preserving African food culture, traditions, and wisdom. These games are playdates with that archive.</p>
            <p>Visit the main site for field notes, recipes, and deeper stories from the kitchen.</p>
        </div>
        <div class="games">
            <h2>The Games</h2>
            <div class="game-grid">
                <div class="game-card">
                    <h3>Recipe Rhythm</h3>
                    <p>A recipe flashes. Then it's gone. Ingredients float like bubbles — tap them in the right order before the memory fades. Can you hold the recipe in your head?</p>
                    <div class="game-links">
                        <a href="https://chicafricanculture.github.io/recipe-rhythm/" target="_blank">Play</a>
                        <a href="https://github.com/ChicAfricanCulture/recipe-rhythm" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
                <div class="game-card">
                    <h3>Spice Bubbles</h3>
                    <p>No smell, no color — just words. Pop the right spice and a scent memory appears. Over six levels, black and white becomes beautiful chaos, and your brain starts to remember how things smell.</p>
                    <div class="game-links">
                        <a href="https://chicafricanculture.github.io/spice-bubbles/" target="_blank">Play</a>
                        <a href="https://github.com/ChicAfricanCulture/spice-bubbles" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
              <div class="game-card">
                    <h3>Chicken Dish Game</h3>
                    <p>A curious chicken in African print feathers invites you to explore. Click a region, learn a dish — from Doro Wat to Poulet Yassa. Gentle, slow, and full of flavor.</p>
                    <div class="game-links">
                        <a href="https://chicafricanculture.github.io/chicken-dish-game/" target="_blank">Play</a>
                        <a href="https://github.com/ChicAfricanCulture/chicken-dish-game" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
                <div class="game-card">
                    <h3>Odd One Out</h3>
                    <p>A rapid-fire puzzle. Ten seconds per round — spot the ingredient or dish that doesn't belong. Inspired by Yoruba wisdom, it's a fun way to learn what goes with what.</p>
                    <div class="game-links">
                        <a href="#" target="_blank">Play</a>
                        <a href="#" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
                <div class="game-card">
                    <h3>The African Pantry Mahjong</h3>
                    <p>Match ingredients, discover recipes. A classic Mahjong-style journey through the continent's diverse pantry. 64 tiles per level, and every match teaches you something.</p>
                    <div class="game-links">
                        <a href="#" target="_blank">Play</a>
                        <a href="#" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
                <div class="game-card">
                    <h3>Adinkra Movers</h3>
                    <p>Symbols move. You spot the match. Fast-paced and beautiful — tap the golden window when Gye Nyame appears. Learn the meaning of each symbol as you play.</p>
                    <div class="game-links">
                        <a href="#" target="_blank">Play</a>
                        <a href="#" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
                <div class="game-card">
                    <h3>Adinkra Mahjong</h3>
                    <p>Match tiles and uncover the wisdom of West Africa's Adinkra symbols. Stacked tiles, deep proverbs — click any tile to see its meaning.</p>
                    <div class="game-links">
                        <a href="#" target="_blank">Play</a>
                        <a href="#" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
                <div class="game-card">
                    <h3>Taste the Words of Africa</h3>
                    <p>A letter grid filled with iconic African dishes. Find Jollof, Ugali, and more. A word puzzle for foodies and culture lovers.</p>
                    <div class="game-links">
                        <a href="#" target="_blank">Play</a>
                        <a href="#" target="_blank" class="code-link">View Code</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footer-links">
                <a href="https://www.theafricangourmet.com" target="_blank">The African Gourmet</a>
                <a href="https://www.theafricangourmet.com/p/african-foodways-archive.html" target="_blank">Foodways Archive</a>
                <a href="https://youtube.com/@theafricangourmet" target="_blank">YouTube</a>
            </div>
            <p style="margin-top: 1.5rem;">All games are open source. Check individual repositories for license details.</p>
            <p style="margin-top: 0.5rem; opacity: 0.7;">Maintained by The African Gourmet · Celebrating African culture through play and education.</p>
        </div>
    </div>
</body>
</html>

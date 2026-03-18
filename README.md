# FreeWebGamesOnline.com

Play 100 free original browser games online. No download, no signup required.

## Features
- 100 original self-hosted HTML5 games
- Categories: Puzzle, Arcade, Board, Card, Sports, Casino, Casual, Educational, Strategy
- Works on desktop and mobile
- No external game dependencies — all games hosted locally
- Google AdSense monetization
- Progress tracking with localStorage

## Categories
- **Puzzle**: Sudoku, Minesweeper, 2048, Wordle, Hangman, Word Search, Sokoban, and more
- **Arcade**: Snake, Tetris, Pac-Man, Frogger, Galaga, Bubble Shooter, Platformer, and more
- **Board & Card**: Chess, Checkers, Solitaire, Battleship, Reversi, Yahtzee, and more
- **Sports**: Basketball, Darts, Mini Golf, Penalty Kick, Pool/Billiards, Bowling
- **Casino**: Roulette, Slot Machine, Blackjack Pro, Craps (virtual credits only)
- **Casual**: Memory Match, Color Sequence, Gem Swap, Paint, Reaction Test, and more
- **Educational**: Math Quiz, Trivia, Spelling Bee, Typing Speed, and more

## Tech Stack
- Pure HTML5, CSS3, JavaScript (no frameworks)
- Canvas API for game rendering
- localStorage for scores/progress
- Deployed on Cloudflare Pages

## Deployment
Push to `main` branch → Cloudflare Pages auto-deploys in ~1-2 minutes.

## Pages
- `index.html` — Homepage with game catalog
- `play.html` — Game player wrapper (serves all games in iframe with ads)
- `games/*.html` — Individual game files (100 self-hosted games)
- `privacy-policy.html` — Privacy Policy (AdSense compliant)
- `terms.html` — Terms of Service
- `contact.html` — Contact page
- `about.html` — About page

## License
All games are original works created by FreeWebGamesOnline.

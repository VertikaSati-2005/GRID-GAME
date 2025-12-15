# GRID-GAME
## My Contribution (Backend)

- Designed the backend architecture using Node.js and Express, organizing the code into `controllers`, `routes`, `models`, and `config` modules.
- Implemented REST APIs for:
  - User authentication (`authController`, `auth.js` routes)
  - Level management (`levelController`, `levels.js` routes)
  - Player progress tracking (`progressController`, `progress.js` routes)
  - Game statistics and leaderboard (`statsController`, `stats.js` routes)
- Created Mongoose models for `User`, `Level`, `Progress`, and `GameStats` to store game data in the database.
- Set up the database configuration (`db.js`) and environment-based settings (`config`, `.env`) for secure connection and easy deployment.
- Added input validation and error handling to keep API responses consistent and prevent invalid data from breaking the game.

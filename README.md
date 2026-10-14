# Math Tug Triumph

Build an interactive, polished 2-player "Tug of War: Mathematics" game inspired by the attached screenshot.

Core Features & Requirements:
1. Two-player split interface:
   - Left side: Team 1 (Blue theme) with current math problem, answer display, and a large touch-friendly on-screen numeric keypad (0-9, clear/backspace, enter).
   - Right side: Team 2 (Red theme) with current math problem, answer display, and on-screen numeric keypad.
   - Also allow physical keyboard inputs if playing on desktop.

2. Center Animated Tug of War Arena:
   - Animated tug of war characters holding a rope across a center dotted boundary line.
   - Live rope displacement: When a team correctly solves a problem, the rope shifts towards their side.
   - Visual tension and dynamic pull animations.

3. Game Modes & Customization:
   - Timer selection: 30s, 1 minute, 2 minutes, or custom duration.
   - Operation types: Addition (+), Subtraction (-), Multiplication (×), Division (÷), or Mixed.
   - Difficulty tiers: Easy, Medium, Hard (number ranges).

4. Scoring, Win Condition & History:
   - Each correct answer awards points and pulls the rope toward that player.
   - When time expires (or if one player pulls the rope past a decisive threshold), trigger an exciting winning sequence with confetti, sound effects toggle, win breakdown (total solved, accuracy, speed), and local match history/leaderboard.

5. Visuals & Feel:
   - Modern, vibrant, kid-friendly and classroom-ready educational UI matching the attached reference image.
   - Audio sound effects for correct answer, incorrect buzz, rope pull tension, countdown whistle, and victory fanfare (with mute toggle).
   - Fully responsive on tablets, mobile screens, smart boards, and desktop browsers.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://math-tug-triumph.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/0a6fa09a-8168-403e-90be-d5cc101b6479).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

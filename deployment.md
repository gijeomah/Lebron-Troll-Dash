# Deployment Document for LeBron Troll Dash - Genesis Challenge

## Project Overview
**LeBron Troll Dash - Genesis Challenge** is a browser-based 2D game where players jump to collect trolls, avoid obstacles, and ultimately defeat the boss, Genesis. The project is written using HTML, CSS, and JavaScript.

## System Requirements
- A modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for background music and images)
- No additional frameworks or libraries are required

## Deployment Instructions

### 1. Download Project Files
Ensure you have the following files saved locally:
- `index.html` (the main game file)
- Any supporting assets (images, if hosted locally)

> Note: In this project, most assets are linked via URLs, so no additional local assets are required unless you wish to customize them.

### 2. Running the Game Locally
1. Open the project folder.
2. Double-click `index.html` or right-click and select **Open With** -> your preferred browser.
3. The game should load in your browser, showing the title, character selection, and start button.

### 3. Game Controls
- **Spacebar**: Jump (double jump is allowed)
- **Character Selection**: Click on the desired character in the top section
- **Start Game**: Click `Start Game` button to begin
- **Light/Dark Mode Toggle**: Click the `Light Mode` / `Dark Mode` button on the top left
- **Mute/Unmute Music**: Click `Mute Music` button on the bottom right
- **Play Again**: After winning, click `Play Again` on the celebration overlay

### 4. Gameplay Instructions
1. Press `Start Game` to initiate the game.
2. Collect **5 trolls** to trigger the boss fight against Genesis.
3. Avoid obstacles by jumping over them using the spacebar.
4. During the boss fight, survive for 20 seconds to defeat Genesis and win.

### 5. Customization Options
- **Character Images**: Replace the `background-image` URLs in the `updateCharacterImage()` function.
- **Obstacle or Troll Styles**: Modify the CSS classes `.obstacle` or `.troll` for size, color, or shape.
- **Game Speed**: Adjust the `x` decrement in `gameLoop()` for obstacles and trolls to make the game faster or slower.
- **Boss Fight Duration**: Modify `bossFightTimeLeft` in the `startBossFight()` function to increase or decrease boss fight time.

### 6. Troubleshooting
- If the game doesn't load, ensure your browser supports modern JavaScript (ES6+).
- If images or music don’t appear, check your internet connection.
- For any visual glitches, try clearing the browser cache and reloading the page.

### 7. Deployment on a Web Server
To make the game accessible online:
1. Upload `index.html` to any web server or hosting service (GitHub Pages, Netlify, Vercel, etc.).
2. Ensure any local assets are included in the upload.
3. Access the game via the hosted URL.

## Credits
- Game code: Developed using ChatGPT
- Idea & design: Collaborative effort by the project team
- Image assets: External URLs cited in the HTML code
- Background music: YouTube embed

---
**Enjoy the game and may your troll-collecting skills prevail!**


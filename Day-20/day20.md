# Day 20 – Face Puzzle Game 🧩📸

## 🚀 Project Overview

For Day 20 of my AI learning challenge, I built a **Face Puzzle Game** using Claude.

The game allows users to capture their photo using their webcam and automatically converts the captured image into an interactive puzzle. Players can choose between **3×3, 4×4, and 5×5** difficulty levels and solve the puzzle using drag-and-drop interactions.

The entire application is built as a **single self-contained HTML file** with inline CSS and JavaScript.

---

## ✨ Features

* 📷 Webcam access using `getUserMedia()`
* 🤳 Capture a photo directly from the camera
* 🧩 3×3, 4×4, and 5×5 puzzle difficulties
* 🔀 Randomized and solvable puzzle generation
* 🖱️ Desktop drag-and-drop controls
* 📱 Touch support for mobile and tablet devices
* 🎯 Automatic snapping to puzzle cells
* 🔄 Piece swapping
* 🟢 Green border for correctly positioned pieces
* 🟡 Highlighted border while dragging
* ⏱️ Live timer in `mm:ss.t` format
* 🔢 Move counter
* 📊 Correctly placed pieces counter
* 🏆 Automatic win detection
* 🎉 Results screen after completing the puzzle
* 💾 Top 5 best times saved using `localStorage`
* 📅 Leaderboard with date, time, moves, and difficulty
* 🔄 Play Again functionality
* 📸 Retake Photo functionality
* ✨ New Photo functionality
* 📱 Responsive design for desktop, tablet, and mobile
* 🌙 Modern dark UI with gradients and glassmorphism
* 🚫 Graceful handling of denied camera permissions

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* WebRTC / `getUserMedia()`
* HTML Canvas
* Pointer Events API
* Browser Local Storage

No frontend framework was used.

---

## 🧠 How the Game Works

### 1. Camera

When the application loads, it requests permission to access the user's webcam.

The live camera stream is displayed using the HTML `<video>` element.

### 2. Capture Photo

The user clicks **Take Photo**.

The current camera frame is copied to an HTML `<canvas>` and stored as an image.

### 3. Choose Difficulty

After taking the photo, the player can select:

* **3×3** → 9 pieces
* **4×4** → 16 pieces
* **5×5** → 25 pieces

### 4. Generate Puzzle

The captured image is divided visually using CSS background positioning.

Each puzzle tile represents one section of the original image.

The pieces are randomly shuffled before the game begins.

### 5. Solve Puzzle

The player can drag a piece onto another cell.

When released, the two pieces swap positions.

Both mouse and touch/pointer interactions are supported.

### 6. Track Progress

During the game, the application tracks:

* Elapsed time
* Number of moves
* Correctly positioned pieces
* Selected difficulty

### 7. Complete the Puzzle

When every piece reaches its original position, the game automatically detects the win.

The timer stops immediately and a results screen is displayed.

### 8. Leaderboard

The result is saved in browser `localStorage`.

Only the top five fastest times are retained.

Each leaderboard entry contains:

* Time
* Moves
* Difficulty
* Date

---

## 📱 Responsive Design

The application was designed to work across:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📱 Tablet

The puzzle board automatically adapts to the available screen size.

Touch interactions are supported using Pointer Events so the same interaction system works across supported desktop and mobile browsers.

---

## 🧪 Testing

I tested the following functionality:

* [x] Camera permission request
* [x] Live webcam preview
* [x] Photo capture
* [x] Retake Photo
* [x] New Photo
* [x] 3×3 puzzle
* [x] 4×4 puzzle
* [x] 5×5 puzzle
* [x] Puzzle scrambling
* [x] Mouse drag interaction
* [x] Touch/pointer interaction
* [x] Piece swapping
* [x] Correct-piece detection
* [x] Timer
* [x] Move counter
* [x] Progress counter
* [x] Win detection
* [x] Results screen
* [x] Leaderboard
* [x] `localStorage`
* [x] Responsive layout
* [x] Camera permission error handling

---

## 💡 What I Learned

This project helped me understand how AI can be used to accelerate the development of a complete interactive frontend application.

### Key learnings:

1. How to access the webcam using the browser's MediaDevices API.
2. How to capture video frames using HTML Canvas.
3. How to create image-based puzzle pieces using CSS.
4. How to implement drag-and-drop interactions without a framework.
5. How Pointer Events can support both mouse and touch interactions.
6. How to calculate puzzle progress dynamically.
7. How to implement timer-based game logic.
8. How to detect when a puzzle has been completely solved.
9. How to persist game results using `localStorage`.
10. How to build responsive interfaces with pure HTML, CSS, and JavaScript.
11. How to use Claude to generate and iterate on a complete frontend application.
12. How to test AI-generated code instead of relying only on generated output.

---

## 🤖 AI Usage

I used **Claude** as an AI coding assistant to help generate the initial implementation of the Face Puzzle Game.

The prompt focused on creating a complete application with:

* Camera functionality
* Image capture
* Puzzle generation
* Multiple difficulty levels
* Drag and touch interactions
* Timer
* Move counter
* Win detection
* Leaderboard
* Responsive UI

After generating the application, I focused on running, testing, reviewing, and validating the functionality.

---

## 🎯 Challenges

Some of the challenging parts of this project were:

* Handling webcam permissions correctly.
* Making the camera work across different browsers.
* Supporting both desktop and touch interactions.
* Ensuring puzzle pieces snap correctly to grid positions.
* Tracking piece positions after swaps.
* Detecting the completed puzzle automatically.
* Keeping the leaderboard persistent using `localStorage`.
* Making the interface responsive on smaller screens.

---

## 🔥 Improvements I Could Add Later

Future versions could include:

* 🔊 Sound effects
* 🎵 Background music
* 🥇 Separate leaderboards for each difficulty
* 👤 Player name support
* 🌐 Online leaderboard
* 🎨 Multiple puzzle themes
* ⏸️ Pause and resume
* 🌟 Difficulty-based scoring
* 🏅 Achievements and badges
* 📤 Share results
* 🖼️ Upload an image instead of only using the webcam
* 🎭 More puzzle modes

---

## 📂 Project Structure

```text
Day20/
│
├── face-puzzle.html
├── day20.md
│
└── screenshots/
    ├── camera.png
    ├── puzzle-3x3.png
    ├── puzzle-4x4.png
    ├── gameplay.png
    ├── result.png
    └── leaderboard.png
```

---

## 🏁 Final Result

Day 20 was a great hands-on exercise in combining **AI-assisted development, frontend development, browser APIs, game logic, responsive design, and user interaction**.

The final result is a fully self-contained Face Puzzle Game that turns a webcam photo into an interactive puzzle.

---

## 📌 Day 20 Takeaway

> AI can help generate a complete application quickly, but testing, debugging, understanding the generated code, and improving the user experience are what turn generated code into a real project.

#AI #Claude #60DaysOfClaude #WebDevelopment #JavaScript #HTML #CSS #FrontendDevelopment #AIChallenge #LearningInPublic

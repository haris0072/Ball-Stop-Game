# Ball-Stop-Game

## About

**Ball Stop** is a 2D reflex-based game developed in **Unity** using **C#**. A ball moves continuously back and forth (or around a path), and the player must tap/press a button at the right moment to stop it inside a target "door" zone. Precision timing is rewarded with an increasing score, while missing the target resets progress. The game runs on a **30-second timer**, challenging players to score as high as possible before time runs out.

## Features

- Classic "stop the ball" reflex gameplay
- 30-second countdown timer for each session
- Push-button control to stop the moving ball
- Progressive scoring system (see below)
- In-game pause menu with **Resume**, **Restart**, and **Quit** options
- Game Over screen with **Play Again** and **Quit** buttons
- Clean and responsive UI
- Smooth 2D ball movement and animation
- Cross-platform support — playable on **PC and Mobile devices**

## Built With

- Unity 6
- C#
- Unity 2D Physics
- Unity UI (uGUI)

## Project Structure

- `Assets`
- `Packages`
- `ProjectSettings`

## How to Play

1. Open the project in Unity (or launch the built app/APK on mobile).
2. Press **Play/Start** from the main menu to begin.
3. The ball moves automatically along its path.
4. Press the **Push Button** at the right moment to stop the ball inside the target door.
5. Successfully stopping the ball inside the door increases your score.
6. Missing the target resets your score progression back to the start.
7. Score as many points as possible before the **30-second timer** runs out.

## Scoring System

- Every time the ball is successfully stopped **inside the door**, the score increases in the following pattern:
  - `+1` → `+2` → `+3` → `+4` → `+5`
  - After reaching `+5`, every further successful stop continues adding `+5` points.
- If the ball is stopped **outside the door** (missed), the scoring sequence **resets back to `+1`**, and the player has to build up the combo again.
- This creates a risk-and-reward loop — the longer you keep hitting the door consecutively, the faster your score climbs.

## In-Game Menu

- **Pause Menu:**
  - Resume — continue the current game
  - Restart — start the level over
  - Quit — exit the game
- **Game Over Menu:**
  - Play Again — restart a fresh 30-second round
  - Quit — exit the game

## Platform Availability

This game is built to support both **Desktop and Mobile platforms**. It can be exported and installed as an **Android APK**, making it downloadable and playable directly on mobile phones, in addition to running on PC.

## Controls

| Action | Input |
|--------|-------|
| Stop Ball | Push Button (Tap on Mobile / Click on PC) |
| Pause | Menu Button |
| Resume/Restart/Quit | UI Buttons in Pause Menu |
| Play Again | UI Button on Game Over Screen |

## Future Improvements

- High score / leaderboard system
- Sound effects and background music
- Difficulty levels (faster ball speed over time)
- Visual effects on successful stop / combo streaks

## License

This project is open source and available for learning and personal use.

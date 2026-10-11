# Tachyon House Points Calculator

An interactive house-points management application that tracks scores and ranks four houses: ALPHA, INFER, MATRIX, and LAYER.

## Problem Statement

Tachyon has four houses that earn points through competitions and activities. This application records points, calculates house rankings, and displays the winning house.

## Live Demo

Try the application here: **[Tachyon House Points — Live Website]((https://jathinshetty06.github.io/Tachyon-House-Points-/))**

## Features

### 1. House Points Management
- Add points to four houses: ALPHA, INFER, MATRIX, and LAYER.
- Automatic rankings, winner detection, undo, and reset options.

### 2. Cinematic 3D Scoreboard
- Interactive 3D visuals powered by Three.js.
- Animated score pillars, dynamic camera movements, particle effects, and cinematic transitions.

### 3. Interactive Sound Effects
- Optional sound effects with on/off controls.
- Scoring sounds when points are awarded.
- Distinct celebratory sounds when a house takes the lead.

### 4. Score Replay System
- Replay previous scoring events through animated sequences.
- Visualise how the leaderboard changes throughout the competition.

### 5. Score Timeline
- Graphical representation of score progression.
- Colour-coded trends to compare all four houses.

## Technologies Used

- HTML
- CSS
- JavaScript
- Three.js
- Browser localStorage

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Ensure you have an internet connection so Three.js can load from its CDN.

## Ranking Logic

The application sorts houses by their total points in descending order. Houses with equal scores share the same rank. The house or houses with the highest positive score are displayed as the winner or joint winners.

## Data Storage

Scores are saved in the browser's localStorage. They persist in the same browser unless the relevant site data is cleared. Scores are not synchronised across devices.

## Project Structure

- `index.html` — Main application containing the interface, styling, and JavaScript logic.
- `README.md` — Project documentation.
- `RANKING_EXPLANATION.md` — Detailed explanation of the ranking algorithm.
- `presentation.pptx` — Technical assessment presentation.


## Author

Developed as part of the Tachyon Technical Team Hiring Assessment.

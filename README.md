# SE4471 Lab 1 – Tic Tac Toe Game

This repository contains a simple Tic‑Tac‑Toe web application built for SE4471 Lab 1 (Part 1). The game is fully playable in a browser and has been designed to satisfy all mandatory requirements plus one extra feature.

## Features

- **3×3 Grid:** Presents a 3×3 board on which two players take turns placing `X` and `O` markers.
- **Two‑Player Game:** Allows two players on the same device, alternating between `X` and `O`.
- **Win/Loss/Tie Detection:** Detects and clearly announces when a player wins, or when the game ends in a tie.
- **Restart Option:** Provides a **Restart** button so players can start a new game without reloading the page.
- **Keyboard Support (Extra Feature):** You can play without a mouse by pressing keys **1–9** to place a mark (cells map left‑to‑right, top‑to‑bottom). Press **R** to restart.
- **Appearance Customization:** Includes a simple **theme toggle** (light/dark) to change the look of the game.
- **Enhanced Visual Feedback:** Highlights winning cells, shows clear status text, provides hover/focus states, and disables the board when the game ends.

## Repository Structure

```
/ (project root)
├── index.html   # Main web page containing HTML, CSS and JavaScript
└── README.md    # This file
```

All logic is contained in **index.html** for simplicity. There are no external dependencies.

##  Running Locally

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, etc.).
3. Play!

Alternatively, you can serve the file via a simple HTTP server:

```bash
python3 -m http.server
```

Then navigate to `http://localhost:8000` in your browser.

## Deployment to GitHub Pages

To deploy this project using GitHub Pages:

1. Commit and push this repository to your GitHub Classroom repository.
2. Go to **Settings → Pages** in your GitHub repository.
3. Under **Source**, select the branch you want to deploy (e.g. `main`) and set the folder to `/`.
4. Save. GitHub Pages will build your site and provide a URL of the form `https://<your‑username>.github.io/<repo‑name>/`.

Your deployed Tic‑Tac‑Toe game must be accessible via that URL when you submit.

## GitHub Pages URL

Deployed site: **(paste your GitHub Pages URL here once enabled)**  
Example format: `https://<your-username>.github.io/<repo-name>/`

##  LLM Tool Usage

This application was built using **ChatGPT (OpenAI GPT‑5.x)** as the primary LLM tool. The prompts used to generate and refine the code and documentation are recorded in `LLM_Interaction_Log.txt`.

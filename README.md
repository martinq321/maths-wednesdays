# Maths Wednesdays puzzles

A static website ready for GitHub Pages. This first package contains the three linked Mastermind activities. Add other games as separate folders and link them from index.html.

## Publish

1. Create a public GitHub repository called `maths-wednesdays` (or choose your own name).
2. Extract this ZIP. Upload its CONTENTS so `index.html` is at the repository root, not inside an extra wrapper folder. Include the `mastermind` folder.
3. Commit the files to the `main` branch.
4. Open Settings → Pages → Build and deployment → Source: Deploy from a branch.
5. Select `main` and `/(root)`, then Save.
6. Wait for the deployment to finish. Use the website link shown in Settings → Pages.

The typical address is https://YOUR-USERNAME.github.io/maths-wednesdays/ . This package does not create a repository or publish a website by itself.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Add activities

Create a folder for each game; keep its assets together. Add a homepage card linking to its entry HTML file. Add a Home link pointing back to `../index.html` in each activity. Use relative paths, which work under a repository URL and offline. Commit updates to main to publish them.

## Included behaviour

- 1–6 colours and holes; colours-only pegs, no visible colour-name labels.
- Puzzle uniqueness is checked against all codes, independently of how guesses are selected.
- Clues and reset confirmations are inline; no app-triggered pop-ups.
- Strategy suggestions for large states can be sampled, not globally optimal.
- Puzzle generation uses a background worker; cancelling terminates it.

## Validation

Game and puzzle engine checks, simulated DOM/worker interactions and relative links checked. No rendered browser QA or live deployment was performed. Before sharing widely, check the deployed pages on phone and desktop.

# Maths Wednesdays

A static website: seven activities, no build step or account required.

## Update your existing GitHub Pages site

1. Extract the ZIP on your computer.
2. Open the maths-wednesdays repository on GitHub, on the main branch.
3. Choose Add file → Upload files at the repository root.
4. Drag in index.html, README.md, engineering and hanoi from the extracted folder. The existing mastermind folder is unchanged; the ZIP also contains it for a complete installation.
5. Commit the upload. Wait for the Pages deployment in Actions to succeed.
6. Open https://martinq321.github.io/maths-wednesdays/ and refresh.

Upload the contents, not the ZIP or an enclosing folder. index.html must be at the repository root. Keep spelling and capitalisation exactly as supplied.

## Pages

- index.html — homepage
- mastermind/Mastermind_Maths_Wednesdays.html — play / assistant
- mastermind/Mastermind_Strategy_Tree.html — strategy tree
- mastermind/Mastermind_Puzzles.html — unique-answer puzzles
- hanoi/index.html — Tower of Hanoi
- engineering/rigidity-2d.html — 2D Rigidity Lab
- engineering/rigidity-3d.html — 3D Rigidity Lab
- engineering/bridge-lab.html — Bridge Lab

Every activity links back to the homepage. Engineering activities also link to each other. All pages work as static HTML, including when opened locally with their folder structure intact.

To add another activity, place its HTML in a suitable folder, give it a relative Home link, and add a card to index.html. Do not upload private notes, chat exports or administrative JSON files.

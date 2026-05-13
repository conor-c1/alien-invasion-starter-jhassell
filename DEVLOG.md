# Development Log

Write a short entry after each work session. 3–5 sentences is plenty.

---

## Entry 1: Setup & First Window

**Date:**

Today I got the project set up in GitHub Codespaces and installed and verified Pygame. I created the first `alien_invasion.py` file and got the basic game loop running without errors. The main thing that took longer than expected was figuring out how Pygame displays in Codespaces, because the program runs but the window does not show normally in the browser environment. I also got the project committed and pushed to my own GitHub fork.

---

## Entry 2: Ship, Movement & Bullets

**Date:**

Today I added the main game files for the Alien Invasion project, including `settings.py`, `ship.py`, `bullet.py`, `alien.py`, and `game_stats.py`. I added ship movement, bullets, alien fleet creation, fleet movement, bullet-alien collisions, lives, and a basic game-over state. One thing I understand better now is how Pygame uses sprites, groups, rects, and update methods to manage objects on the screen. The hardest part was not being able to visually test the game window easily in Codespaces, but the code passed the Python compile check and was committed and pushed successfully.

---

## Entry 3: (Optional — for future weeks)

**Date:**

This session helped me understand that a game is built out of several smaller systems working together instead of one giant file. The ship, bullets, aliens, settings, and game stats each have their own role, and the main game file coordinates them. I also got more comfortable using Git commands like `git add`, `git commit`, `git push`, and checking the repo status. Next time I would want to test the game locally on my Mac so I can actually see the Pygame window while debugging.
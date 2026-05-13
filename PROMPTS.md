# Copilot Prompt Log

Track the prompts you give Copilot and what happens. This helps you learn what makes a good prompt and gives you a record to look back on.

---

## Exercise 1: Launch Sequence

### Prompt 1: Game Window

| | |
|---|---|
| **What I asked Copilot** | Create the first Alien Invasion game window using Pygame. |
| **What it gave me** | A basic Pygame setup with a game loop, screen settings, and a display window. |
| **Did it work on the first try?** | Mostly. The code worked, but the Pygame window would not display correctly in Codespaces. |
| **What I changed or asked next** | I verified Pygame installation and continued testing in Codespaces. |

### Prompt 2: Settings Class

| | |
|---|---|
| **What I asked Copilot** | Create a Settings class to store screen settings and game configuration values. |
| **What it gave me** | A class with screen width, screen height, background color, ship settings, bullet settings, and alien settings. |
| **Did it work on the first try?** | Yes. |
| **What I changed or asked next** | I later expanded the class with bullet speed, fleet movement, and ship lives. |

### Prompt 3: Ship Class

| | |
|---|---|
| **What I asked Copilot** | Create a Ship class that loads an image and allows movement left and right. |
| **What it gave me** | A Ship class using Pygame image loading, movement flags, update methods, and drawing methods. |
| **Did it work on the first try?** | Mostly. |
| **What I changed or asked next** | I had to replace the original BMP image with my own PNG image and update the image path. |

---

## Exercise 2: Weapons Online

### Prompt 4: Movement

| | |
|---|---|
| **What I asked Copilot** | Add keyboard movement and movement flags for the ship. |
| **What it gave me** | Movement logic using KEYDOWN and KEYUP events with left/right movement flags. |
| **Did it work on the first try?** | Yes. |
| **What I changed or asked next** | I adjusted the ship speed inside the settings file. |

### Prompt 5: Bullets

| | |
|---|---|
| **What I asked Copilot** | Create a Bullet class and allow the ship to fire bullets with the spacebar. |
| **What it gave me** | A Bullet sprite class with bullet movement, drawing methods, and bullet cleanup logic. |
| **Did it work on the first try?** | Yes. |
| **What I changed or asked next** | I later added collision detection between bullets and aliens. |

### Prompt 6: Refactoring

| | |
|---|---|
| **What I asked Copilot** | Organize the game into separate files and classes for settings, bullets, aliens, and game stats. |
| **What it gave me** | Multiple organized Python files with separate responsibilities and grouped game logic. |
| **Did it work on the first try?** | Mostly. |
| **What I changed or asked next** | I fixed image paths, added alien fleet movement, added collisions, and corrected GitHub repository configuration issues. |

---

## Reflection

- Which prompt worked best on the first try? Why do you think that is?

The settings class prompt worked best because it was specific and focused on one small task instead of several connected systems at once.

- Which prompt needed the most back-and-forth? What made it harder?

The ship and image loading prompts needed the most back-and-forth because the original textbook image files were missing and Codespaces made it difficult to visually test the game window.

- What's one thing you learned about prompting Copilot effectively?

I learned that more specific prompts usually produce better code. Breaking large features into smaller requests makes debugging and understanding the code much easier.
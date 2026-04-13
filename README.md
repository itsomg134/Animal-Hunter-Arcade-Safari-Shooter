# Animal Hunter – Arcade Safari Shooter

**Animal Hunter** is a fast-paced, reflex-based browser game where you step into the shoes of a skilled safari marksman. Your mission: track and shoot wild animals before they escape across the savannah. Built with pure HTML5 Canvas, CSS, and vanilla JavaScript — no dependencies, just instant action.

![Game Preview](https://via.placeholder.com/800x400?text=Animal+Hunter+Gameplay+Screenshot)
> * Click or tap on animals to score points. Reload wisely and beat your high score!*

##  Live Demo

##  Features

- **Dynamic Wildlife** – Five unique animals (Deer, Boar, Wolf, Rabbit, Fox), each with different speeds, sizes, and point values.
- **Realistic Shooting Mechanics** – Limited ammo (6 rounds) with a manual or auto-reload system.
- **Immersive Visual Feedback** – Hit/miss particle effects, animated crosshair, and a living savannah backdrop.
- **Score Tracking** – Real-time score, hit count, and miss counter.
- **Responsive Controls** – Mouse, touch, and click support (works on desktop & mobile).
- **Reload System** – 1.2-second reload timer with a visual progress bar.
- **Endless Gameplay** – Animals continuously spawn from left/right edges. How many can you hunt?

##  How to Play

1. **Aim** – Move your mouse (or finger on touch devices). The crosshair follows your cursor.
2. **Shoot** – Click or tap on any animal to hunt it.
3. **Reload** – After 6 shots, press the **RELOAD** button or wait 3 seconds for auto-reload.
4. **Score Points** – Each animal gives different points:
   -  Rabbit → 5 pts
   -  Deer → 10 pts
   -  Fox → 12 pts
   -  Boar → 15 pts
   -  Wolf → 20 pts
5. **Avoid Misses** – Every missed shot increases your miss counter and wastes ammo.
6. **Reset Anytime** – Click **NEW SAFARI** to restart the game.

##  Strategy Tips

- **Prioritize high-value animals** (Wolf, Boar) but watch their speed – Wolves are fast!
- **Manage your ammo** – Reload during calm moments so you’re ready for rare animals.
- **Lead your shots** – Animals move; aim slightly ahead of their direction.
- **Watch the edges** – Animals that run off-screen are gone forever.

##  Technologies Used

- **HTML5 Canvas** – Rendering game graphics and animations.
- **CSS3** – Styling, shadows, gradients, and responsive layout.
- **Vanilla JavaScript (ES6)** – Game logic, collision detection, spawn system, and reload mechanics.
- **No external libraries or frameworks** – Lightweight and fully self-contained.

##  Project Structure

```
animal-hunter-game/
├── index.html          # Complete game file (Canvas, CSS, JS)
├── README.md           # Project documentation
└── assets/             # (Optional) Add screenshots or icons
```

> **Note:** The entire game is inside a single `index.html` file for easy deployment and sharing.

##  Getting Started

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/animal-hunter-game.git
   ```
2. Navigate to the project folder:
   ```bash
   cd animal-hunter-game
   ```
3. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
4. Start hunting!

### Deploy to GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Under "Branch", select `main` (or `master`) and `/root` folder.
4. Click **Save**. Your game will be live at `https://yourusername.github.io/animal-hunter-game/`

##  Customization Ideas

Want to tweak the game? Edit these variables in the JavaScript section:

- **Animal Speed** – Change `baseSpeed` values in `ANIMAL_TYPES`.
- **Spawn Rate** – Modify `spawnGap` (lower = more animals).
- **Ammo Capacity** – Adjust `maxAmmo` (e.g., 8 for larger magazine).
- **Reload Time** – Change `1200` (milliseconds) in `startReload()`.
- **Canvas Size** – Update `width`/`height` attributes on the `<canvas>` tag.

## 📱 Browser Compatibility

| Browser | Version |Support |
|---------|---------|--------|
| Chrome  | 90+     |  Full  |
| Firefox | 88+     |  Full  |
| Edge    | 90+     |  Full  |
| Safari  | 14+     |  Full  |
| Mobile Chrome/Safari | Latest |  Touch support |

##  Contributing

Contributions, bug reports, and feature requests are welcome!  
Feel free to open an issue or submit a pull request.

**Ways to contribute:**
- Add new animals with unique behaviors.
- Implement a high-score leaderboard (localStorage).
- Introduce power-ups (e.g., rapid fire, slow motion).
- Add sound effects for shots/reloads.
- Create different biomes (forest, desert, arctic).

##  License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
TL;DR — You can use, modify, and distribute this code freely as long as you include the original license.

##  Acknowledgments

- Inspired by classic light-gun arcade games like *Duck Hunt* and *Big Game Hunter*.
- Animal emojis provided by Unicode Standard.
- Background gradient and styling crafted for a vibrant safari atmosphere.

---

##  Screenshots

*(Add your actual screenshots here)*

![Gameplay Action](https://via.placeholder.com/600x300?text=Shooting+Wolf+with+Crosshair)  
*Locked on target – a Wolf worth 20 points!*

![Reload Mechanism](https://via.placeholder.com/600x300?text=Reload+Bar+and+Ammo+Counter)  
*Visual reload bar and ammo indicator.*


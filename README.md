# ⚔ Blade of the Night — Enhanced Edition

A moonlit, retro pixel-art demon-hunting action platformer built with pure HTML5 Canvas, CSS3, and Vanilla JavaScript. Battle through four atmospheric night stages, chain 3-hit Water Breathing sword combos, revive at Blue Lantern checkpoints, and defeat the Final Demon King to bring back the dawn.

## ✨ Key Features

* **4 Atmospheric Night Stages & Bosses:**
  1. **Forest Path** — *Hand Demon*
  2. **Mountain Village** — *Spider Demon*
  3. **Snowy Temple** — *Blood Moon Demon*
  4. **Blood Moon Castle** — *Final Demon King*
* **Fluid Combat & Movement:**
  * **3-Hit Sword Combo:** Chain three consecutive slashes for a wide-arc finisher with bonus damage and knockback.
  * **Double Jump & Shadow Dash:** Traverse gaps, dodge ground shockwaves, and phase through enemy attacks with invulnerability frames.
  * **AI Companion Allies:** Two sword-wielding companions fight alongside you and deal automatic support damage to nearby demons.
* **Working Blue Lantern Checkpoints:** Activating a stage's Blue Lantern saves your soul—if your HP reaches `0`, you automatically revive at the lantern with 65% HP.
* **Demon Slayer Upgrade Shop:** Spend coins dropped by demons and bosses anytime to heal or permanently upgrade your stats.
* **Retro WebAudio Synthesizer:** Built-in procedural 8-bit/16-bit sound effects (sword slashes, hits, jumps, dashes, coin chimes, and victory fanfare) with zero external audio files required.
* **Responsive & Touch-Ready:** Supports full desktop keyboards as well as on-screen touch controls for mobile and tablet screens.

## ⌨️ Controls

| Action | Keyboard | Mobile / Touch |
| :--- | :--- | :--- |
| **Move Left / Right** | `←` `→` or `A` `D` | `◀` / `▶` buttons |
| **Jump / Double Jump** | `↑`, `W`, or `Space` | `▲` button |
| **3-Hit Sword Slash** | `E` or `J` | `⚔` button |
| **Shadow Dash** | `Z` or `Shift` | `⚡` button |
| **Pause / Resume** | `P` | Top HUD `Pause` button |
| **Restart Game** | `Enter` (on Game Over/Win) | Top HUD `Restart` button |

## 🛒 Demon Slayer Upgrade Shop

| Upgrade | Cost | Effect |
| :--- | :--- | :--- |
| **🧪 Healing Elixir** | `25 Coins` | Restores up to `+15 HP` immediately |
| **❤️ Max HP Boost** | `50 Coins` | Permanently increases Max HP by `+10` and heals `10 HP` |
| **⚔ Reforge Blade** | `50 Coins` | Permanently increases base sword damage by `+2` |
| **👟 Agility Training** | `50 Coins` | Increases movement speed and reduces Shadow Dash cooldown |

## 🚀 Getting Started

1. **Play Immediately:**
   Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari). Everything runs locally in a single self-contained HTML file—no installation, build steps, or internet connection required.

2. **Host on GitHub Pages:**
   Ensure the main file is named `index.html` in the root of your repository, then enable GitHub Pages in **Settings → Pages**.

## 📁 Project Structure

```text
├── index.html   # Complete self-contained game (HTML5 Canvas, CSS3, JS & WebAudio SFX)
└── README.md    # Game documentation, controls, and license
```

## 📄 License

This project is licensed under the **MIT License**:

```text
MIT License

Copyright (c) 2026 Blade of the Night

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
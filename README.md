# ghost-game
ghost game
# 👻 Shoot the Ghost

**A clean, dependency-free HTML5 browser game**  
Click the ghosts before they vanish. Simple. Fast. Addictive.

![Game Preview](https://via.placeholder.com/800x450/0a0a12/7CFC00?text=Shoot+the+Ghost)

---

### ✨ Features

- **Zero dependencies** — pure HTML, CSS & JavaScript
- **Web Audio API** synthesized sound effects (no external audio files)
- Progressive difficulty that ramps up as time runs out
- Combo multiplier for consecutive hits
- Smooth visual feedback (hit animations + miss flash)
- Fully responsive and works on desktop & mobile
- Single file — just open and play

---

### 🎮 How to Play

1. Click **Start Game**
2. Click the ghosts as they appear
3. Don’t miss — consecutive hits build a combo multiplier
4. Survive 30 seconds and chase a high score

**Controls**  
Mouse / touch only. No keyboard needed.

---

### 🚀 How to Run

1. Save the code as `index.html`
2. Open the file in any modern browser (Chrome, Firefox, Edge, Safari)
3. That’s it.

No build step. No server required. No packages to install.

---

### 🛠️ Technical Highlights

| Feature                    | Implementation                          |
|---------------------------|-----------------------------------------|
| Sound                     | Web Audio API (OscillatorNode)          |
| AudioContext resume       | Safe resume on first user interaction   |
| Difficulty scaling        | Dynamic spawn interval (750ms → 280ms)  |
| Visual feedback           | CSS transitions + screen flash          |
| Combo system              | Soft-capped multiplier                  |
| Compatibility             | Modern browsers (ES6+)                  |

---

### 📁 Project Structure

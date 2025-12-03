[README.md](https://github.com/user-attachments/files/23917177/README.md)
# Global Movement Research | Cyberspace Visualizations

[![Live Gallery](https://img.shields.io/badge/View-Live%20Gallery-00ffff?style=for-the-badge)](https://synckdance.github.io/gmr_space_visualizations/)

Interactive 3D motion capture visualizations of cross-cultural dance traditions, rendered in a cyberspace aesthetic environment.

![Cyberspace Visualization Preview](https://img.shields.io/badge/Visualizations-33-ff00ff?style=flat-square) ![Performers](https://img.shields.io/badge/Performers-6-00ffff?style=flat-square) ![Cultural Traditions](https://img.shields.io/badge/Traditions-6-00ff00?style=flat-square)

---

## About

The Global Movement Research (GMR) project analyzes and preserves cross-cultural dance traditions through motion capture technology and computational analysis. This repository contains interactive 3D visualizations of dance performances captured using the Captury markerless motion capture system.

**Principal Researcher:** Sinclair

---

## Cultural Traditions Represented

| Performer | Tradition | Dances |
|-----------|-----------|--------|
| **Sinclair** | West African / Nigerian | Bata, Esapkaide, Ekombi, Swange, Ugho |
| **Mustapha** | West African / Ghanaian | Adzogbo, Agbadza, Atsiagbekor, Bata, Djole, Fumefume, Kpanlongo |
| **Sudesh** | Sri Lankan / Kandyan | Gajaga Vannama, Folk/Court Dance, Kohomba Kankariya, Telme Ruhunu, Baila Kappirinna |
| **Nadia** | Afro-Cuban / Orisha | Changó, Kuele Kuele, Yemayá |
| **Kate** | Irish / Brazilian | Festival Blackbird, Slip Jig, Sean-nós, Frevo, Garden of Daisies, Molyneaux Blackbird |
| **Annie Laura** | Latin | Salsa |

---

## Visualization Features

### Display Modes
- **HUMANOID** — Glowing neon body mesh with metallic joints
- **HOLOGRAM** — Pulsing translucent joints with energy trails
- **WIREFRAME** — Clean skeletal lines
- **PARTICLES** — Joint positions as glowing points
- **ENERGY** — Glowing orbs with motion trails
- **MATRIX** — Green Matrix-style with falling characters

### Camera Views
- Free Orbit (drag to rotate, scroll to zoom)
- Front / Side / Top views
- Cinematic auto-orbit

### Controls
- **Space** — Play/Pause
- **Timeline** — Scrub to any frame
- **⏪ / ⏩** — Skip 5 seconds

---

## Technical Details

- **Capture System:** Captury Live markerless motion capture
- **Frame Rate:** 30 FPS playback (downsampled from 60 FPS source)
- **Skeleton:** 32 tracked joint positions
- **Rendering:** Three.js WebGL
- **Format:** Self-contained HTML files (no dependencies)

---

## Usage

1. Visit the [Live Gallery](https://synckdance.github.io/gmr_space_visualizations/)
2. Select a performer and dance
3. Click "Launch Visualization"
4. Use controls to explore the movement

Or download any HTML file and open locally in a web browser.

---

## Repository Structure

```
├── index.html                      # Gallery navigation page
├── GMR_Master_Documentation.docx   # Full technical documentation
├── README.md
└── visualizations/
    ├── sinclair_*.html             # 8 files
    ├── mustapha_*.html             # 7 files
    ├── sudesh_*.html               # 6 files
    ├── kate_*.html                 # 7 files
    ├── nadia_*.html                # 3 files
    └── annie_laura_*.html          # 1 file
```

---

## License

© 2024 Global Movement Research. All rights reserved.

---

## Acknowledgments

Special thanks to all the dancers who shared their cultural traditions:
- Sinclair Emoghene
- Mustapha Braimah
- Sudesh Mantillake
- Nadia Issa Milad
- Kate Spanos
- Annie Laura Irizarry Perez

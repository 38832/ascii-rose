# ASCII Rose Web

This folder contains a complete HTML/JS port of the original JIN2 ASCII Rose animation from https://github.com/JIN2-ASCII/-JIN2-ASCII.

## Features
- **Accurate 3D Math**: Faithful conversion of spiral surface petals, sepal generation, curved stem, dual leaves, ray glints, dew drops, sway kinematics, and dynamic lighting.
- **Visuals**: Phosphor trail fade (`TRAIL = 0.5`), dual bloom glow layers (`blur(5px)` and `blur(22px)`), live HUD (`bloom %`, `sway °`, `letter count`, and blinking `time` marker).
- **Controls**:
  - `Space`: Pause / Resume
  - `R`: Restart animation
  - Responsive / Auto-scales to any display or mobile phone

## How to Share as a Link

### 1. Free GitHub Pages (Recommended)
1. Create a repository on GitHub (e.g. `ascii-rose`).
2. Push this folder to GitHub:
   ```bash
   git init
   git add .
   git commit -m "feat: ASCII rose web animation"
   git branch -M main
   git remote add origin https://github.com/<your-username>/ascii-rose.git
   git push -u origin main
   ```
3. In repository **Settings -> Pages**, set source to `main` branch root.
4. Your friend can open `https://<your-username>.github.io/ascii-rose/`.

### 2. Instant Free Hosting (Vercel / Netlify / Render)
- Drag and drop this folder directly into [Netlify Drop](https://app.netlify.com/drop) or deploy via Vercel for an instant shareable link.

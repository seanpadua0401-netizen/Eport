# Sean O. Padua - Modern Tech Portfolio

A sleek, responsive, single-page developer portfolio built for **Sean O. Padua** (Future Software Engineer & Full-Stack Web Developer). Designed with a modern cyberpunk/tech aesthetic, featuring electric blue and emerald green accents, sharp edges, subtle glassmorphism, and monospace typography.

## 🚀 Features

- **Modern Tech Aesthetic**: Sleek dark mode by default (`#0b101e`), glassmorphism, electric cyan (`#00f0ff`) and emerald green (`#10b981`) accents.
- **Theme Toggle**: One-click switch between Cyber Dark and Crisp Light themes (persisted via `localStorage`).
- **Interactive Navigation**: Sticky header with technical branding `<Sean/>`, section links, and mobile slide drawer.
- **Personal Background Terminal**: Compact system identity card rendering birth details, location, email, and social links.
- **Academic Timeline**: Glowing vertical timeline tracing Primary, Secondary (STEM Strand, High Honors), and Tertiary education (BSCS-4).
- **Featured Project (Balai ti Arjud)**:
  - Interactive vanilla JavaScript image slider/carousel cycling through 5 screenshots.
  - Manual Next/Previous controls, keyboard arrow navigation (`←` `→`), touch swipe, autoplay with pause on hover, and dot indicators.
  - Fullscreen lightbox modal for high-resolution inspection.
- **Certifications Showcase**: Responsive 4-column credential grid with hover zoom, credential badges, and lightbox preview.
- **Interactive Cyber Dino Runner (HTML5 Canvas)**:
  - Mini offline runner game inspired by the Chrome Dino game.
  - **Single-input control**: Click or tap anywhere on the canvas to jump / restart (supports Spacebar on desktop).
  - Web Audio API retro synth sound effects with toggle.
  - High score tracking saved in browser `localStorage`.
- **Instant Vercel Deployment**: Pure static frontend (`index.html`, Tailwind CSS via CDN, vanilla JavaScript, zero build dependencies).

## 📁 Project Structure

```text
├── index.html            # Main single-page web app with Tailwind CDN & Vanilla JS
├── vercel.json           # Vercel deployment configuration & static caching
├── assets/
│   ├── profile/
│   │   └── sean.jpg      # Sean O. Padua profile photo
│   ├── projects/
│   │   └── balai/        # 5 screenshot slides for "Balai ti Arjud"
│   │       ├── img1.png
│   │       ├── img2.png
│   │       ├── img3.png
│   │       ├── img4.png
│   │       └── img5.png
│   └── certificates/     # 4 authentic certificates of participation & completion
│       ├── cert1.jpg
│       ├── cert2.jpg
│       ├── cert3.jpg
│       └── cert4.jpg
└── README.md
```

## ⚡ Deployment to Vercel

1. Push this repository to GitHub or GitLab.
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your repository.
4. Keep the Framework Preset as **Other** (Root Directory: `./`).
5. Click **Deploy**. Your portfolio is live instantly with global CDN caching and HTTPS!

## 💻 Local Preview

You can open `index.html` directly in any web browser, or run a local server:

```bash
# Using Node.js npx
npx serve .

# Or using PHP (via XAMPP)
# Navigate to http://localhost/newsean/ in your browser
```

# Akshith Peri | Automotive-Inspired Developer Portfolio

A responsive, car-inspired portfolio website showcasing Akshith Peri's full-stack, 3D, AI, cybersecurity, and research work.

## Design concept

- Automotive / motorsport visual styling with graphite, metallic grey, and racing-red accents
- Original SVG sports car illustration included in `assets/gt-coupe.svg`
- Car-inspired sections: Driver Profile, Spotlight Build, Project Lineup, Under the Hood, and Road Map
- Responsive desktop and mobile layouts, automotive animations, scroll reveals, a page progress bar, animated telemetry, and accessible reduced-motion support
- **AutoVerse** interactive car showroom as the featured project
- **AffordIQ** — HackerRank Orchestrate (September 2026) financial decision agent, featured in the project lineup alongside 6 other completed projects

## Featured hackathon project: AffordIQ

AffordIQ was built for the **HackerRank Orchestrate — September 2026** hackathon. It uses a deterministic Python engine to reconstruct financial events, simulate a 90-day cash-flow horizon, evaluate payment strategies and validate that essential expenses are covered and minimum balances are maintained. It also includes a separate optional interactive web demo.

Source: [AkshithPeri7/hackerrank-orchestrate-september26](https://github.com/AkshithPeri7/hackerrank-orchestrate-september26).

## Preview locally

Open `index.html` in any modern web browser. There is no build step or dependency installation required. The custom car illustration works offline; Google Fonts load when connected to the internet.

## Deploy to GitHub Pages

1. Create a repository and upload `index.html` and the `assets` folder.
2. Under **Settings → Pages**, choose **Deploy from a branch**.
3. Select your branch and `/ (root)`, then save.

## Deploy to Vercel

1. Push the website files to a GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Choose the **Other** framework preset, leave the build command blank, and deploy.

## Personalization

- Update project text, links, and social accounts in `index.html`.
- Replace or recolor `assets/gt-coupe.svg` if you want a different car style.
- Change the `--hot` CSS custom property in `index.html` to switch racing-red to another accent color.
- Double-check all resume-based details before publishing; the content is based on your uploaded resume.

## File structure

```
akshith-portfolio/
├── index.html
├── assets/
│   └── gt-coupe.svg
└── README.md
```

The sports car is an original SVG design created for this portfolio, not a photo or a brand-logo asset.

## Animations added

- Animated hero headline and sport-coupe entrance, with a subtle continuous idle motion
- Rotating wheel spokes in the original SVG car illustration
- Racing streaks, drifting grid, pulsing status light, and animated engine telemetry
- Scroll-triggered section reveals, staggered project cards, and quick-fact counters
- A reading-progress indicator at the top of the page and active navigation links
- Sleek hover effects for project cards, buttons, technology chips, and the AutoVerse spotlight
- Motion automatically disables where `prefers-reduced-motion` is enabled

All animation code is built with CSS and vanilla JavaScript. No extra dependencies or external JS libraries are required.

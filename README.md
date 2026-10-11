# weijaky.github.io

Personal site of **Jason Wei** — indie Android developer. Live at [weijaky.github.io](https://weijaky.github.io).

## Sections

- **Home** — intro, apps, latest posts, contact
- **Apps** — [BambooNode (竹节笔记)](https://weijaky.github.io/apps/bamboonode.html) support center: features, FAQ, changelog, privacy policy (19 languages)
- **Blog** — dev notes and release updates

## Structure

```
├── index.html                     # Homepage
├── style.css                      # Design system (light/dark, Material 3 inspired)
├── script.js                      # Theme toggle (system / light / dark)
├── apps/
│   └── bamboonode.html            # App support & FAQ
├── blog/                          # Blog listing + posts
└── docs/BambooNode/PrivacyPolicy/ # App privacy policies
```

## Notes

- Pure static HTML/CSS/JS — no build step. Push to `main`, GitHub Pages does the rest.
- Theme follows the system by default; users can toggle light/dark manually.
- BambooNode package id: `app.bamboonode` (Google Play link used on homepage, support page, and launch post).
- Portfolio cards: BambooNode, Literacy (识字测评), PvsZ (Cocos2d learning project), ArdTool (internal tools).

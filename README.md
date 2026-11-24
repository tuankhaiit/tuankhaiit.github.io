# Tran Dinh Tuan Khai - Portfolio

Gallery-grade single-file engineering portfolio designed for public GitHub Pages hosting ([https://tuankhaiit.github.io](https://tuankhaiit.github.io)). Uses high-abstraction architectural storytelling paired with an interactive generative `<canvas>` simulation and minimalist geometric system plates while omitting granular numbers, version boasts, and proprietary identifiers.

## Composition

- **Hero Stage** - Asymmetric editorial headline paired with a live `<canvas>` field switching interactively across three architectural modes (`01 CONTAIN`, `02 GOVERN`, `03 ROUTE`).
- **01 / Philosophy** - Condensed engineering manifesto contrasting infrastructure-enforced containment and structured delivery against naive prompting.
- **02 / Selected Systems** - Curated interactive gallery showcasing Bounded Agent Harnesses, Enterprise Tooling Fabric, Spec-Driven Agentic SDLC, and Distributed Financial Core.
- **03 / Trajectory** - Horizontal chronological progression across mobile origination, distributed backend cloud architecture, and AI-native engineering platforms.
- **04 / Connect** - Minimal closing call to action with clipboard email copy and LinkedIn profile link.

## Local Preview

```bash
cd portfolio
python3 -m http.server 8080
```

Open `http://localhost:8080` in any modern browser. Uses `Plus Jakarta Sans`, `IBM Plex Sans`, and `JetBrains Mono` via Google Fonts when online and falls back gracefully to crisp system sans/monospace stacks offline.

## Publishing to GitHub Pages

1. Create a public repository named `tuankhaiit.github.io` on GitHub (`https://github.com/tuankhaiit/tuankhaiit.github.io`).
2. Push `index.html` and `README.md` to `main`:

```bash
cd portfolio
git init -b main
git add index.html README.md
git commit -m "Publish engineering portfolio"
git remote add origin git@github.com:tuankhaiit/tuankhaiit.github.io.git
git push -u origin main
```

3. Enable GitHub Pages in repository **Settings -> Pages**: select **Deploy from a branch**, branch `main`, folder `/ (root)`. Your site will go live at `https://tuankhaiit.github.io/`.

## Public Abstraction Checklist

- Employer names, internal ticket prefixes, and proprietary system names omitted.
- Granular internal throughput numbers, latency snapshots, and version strings excluded.
- Pure gallery-white canvas with strictly upright typography and ASCII punctuation throughout.

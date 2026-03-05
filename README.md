# ksauka.github.io

Personal academic portfolio for **Kudzai Sauka** — PhD Researcher and Research Scientist at Hogeschool van Amsterdam / University of Amsterdam.

Live site: **https://ksauka.github.io**

---

## About

Research focus: Human-Centred Explainable Conversational AI — XAI, DST belief modeling, GraphRAG, KG-RAG, counterfactual faithfulness auditing, and trust calibration.

---

## Stack

Pure HTML/CSS/JS — no framework, no build step. GitHub Pages serves `index.html` directly from the `master` branch root.

---

## Structure

```
ksauka.github.io/
├── index.html          ← Main site (single-page portfolio)
├── pdf/
│   └── resume.pdf      ← Downloadable CV
├── images/
│   └── sauka.jpg       ← Profile photo
└── cv/                 ← LaTeX CV source (not served publicly)
    ├── resume.tex
    └── sections/
```

---

## Updating the site

### Publications
Edit the `const pubs = [...]` array in the `<script>` block at the bottom of `index.html`.

### Bio / About text
Edit the `<div class="about-body">` section in `index.html`.

### CV
Recompile `cv/resume.tex` with pdflatex and replace `pdf/resume.pdf`.

### Deploy
```bash
git add .
git commit -m "describe your changes"
git push origin master
```

GitHub Pages publishes automatically within ~1 minute.

---
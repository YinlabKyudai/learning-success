# LearningSuccess@ICCE2026 Workshop Website

Website for **The 1st Workshop on Reconstructing Learning Success in the GenAI Era: Proactive Support, Multimodal Evidence, and Human-AI Collaboration**, held at ICCE 2026 (Christchurch, New Zealand, 30 Nov – 1 Dec 2026).

Live site: <https://yinlabkyudai.github.io/learning-success/>

## Structure

A plain static HTML/CSS one-page site — no build step required.

| File | Purpose |
|------|---------|
| `index.html` | All page content (hero, news, about, topics, dates, submission, program, organizers, contact) |
| `css/style.css` | Design system and responsive layout |
| `js/main.js` | Mobile navigation toggle |

## How to update content

All content lives in `index.html`. Edit the relevant section and push to `main`; GitHub Pages republishes automatically within a minute or two.

- **News**: edit the `<ul class="news-list">` items in the *Latest News* section.
- **Important dates**: edit the cards inside `<section id="dates">`.
- **EasyChair link**: in `<section id="submission">`, replace the `href="#"` of the *EasyChair — Opening Soon* button with the real URL and remove the `btn-disabled` class and `aria-disabled` attribute. Also update the "Submit Paper" hero button if desired.
- **Program**: replace the *Coming soon* placeholder inside `<section id="program">` with the session schedule and accepted papers.
- **Organizers**: edit the cards inside `<section id="organizers">`.
- **Contact**: footer section `<footer id="contact">`.

## Local preview

Open `index.html` directly in a browser, or run a simple server:

```bash
python -m http.server 8000
```

then visit <http://localhost:8000>.

## Important dates

| Milestone | Date |
|-----------|------|
| Submission deadline | 11 August 2026, 23:59 GMT |
| Acceptance notification | 1 September 2026 |
| Camera-ready due | 15 September 2026 |
| Workshop day | 30 Nov or 1 Dec 2026 (per ICCE 2026 schedule) |

## Contact

yinlab2024 [at] gmail.com

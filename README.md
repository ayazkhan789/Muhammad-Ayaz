# Muhammad Ayaz — Academic Website

Source for the academic website of **Muhammad Ayaz**, Research Assistant and MS student at the Graphics Realization Lab (GRLab), Chung-Ang University, Seoul, Republic of Korea.

The site presents research in computer vision, multimodal AI, vision-language models, affective computing, fire and smoke understanding, disaster scene understanding, and medical AI.

## Local development

The repository uses the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme. The deployment workflow uses Ruby 3.2.2.

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` after the server starts.

## Content

- `_pages/about.md` — biography and homepage research overview
- `_pages/research.md` — research directions and projects
- `_pages/publications.md` and `_bibliography/papers.bib` — publications and manuscript status
- `_data/cv.yml` — web CV
- `_news/` — dated academic updates

## Deployment

GitHub Actions builds and publishes the site when changes are pushed to the configured default branch. The production URL is configured as <https://ayazkhan789.github.io/Muhammad-Ayaz/>.

## Theme attribution

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) academic theme.

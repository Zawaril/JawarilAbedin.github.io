# Portfolio redesign

This bundle contains a recruiter-friendly single-page homepage plus separate project case-study pages.

## Files
- `index.html`
- `styles.css`
- `projects/cytometry.html`
- `projects/rnn-vca.html`
- `projects/time-series.html`

## Keep your existing assets
Copy/keep your current `assets/` folder in the repository.

Expected paths used by the code:
- `assets/profile.jpg`
- `assets/CV.pdf`
- `assets/projects/rnn-architecture.png`
- `assets/projects/maxcut-results.png`
- `assets/projects/tsp-results.png`
- `assets/projects/nsp-tsp-results.png`
- `assets/publications/rnn-vca-paper.pdf`
- `assets/awards/merwin.png`
- `assets/awards/quality-journal.png`
- `assets/awards/best-ambassador.png`
- certificates referenced in `assets/certificates/`

If your actual filename differs, change the HTML path to match it exactly.

## Important
Your previous `index.html` placed the profile `<img>` inside `<head>`. This redesign moves the image into the hero section where it belongs.

## Preview
From the repository folder:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

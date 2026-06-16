# Kuberknots Quarto starter



## Files

- `_quarto.yml`: site navigation, logo-home behaviour, footer, social links, and HTML settings.
- `styles.scss`: brand palette, accessible buttons, cards, episode layout, and responsive behaviour.
- `index.qmd`: homepage with hero, latest episode cards, and learning-focused site rationale.
- `about.qmd`: flexible placeholder About page for Season 2.
- `episodes.qmd`: listing page that automatically pulls episode subpages from `episodes/ep-*.qmd`.
- `episodes/ep-001.qmd` to `episodes/ep-006.qmd`: draft episode pages with placeholders for audio, bio, transcript, quiz, and comments.
- `episodes/_episode-template.qmd`: copy this for Season 2 episodes.
- `contact.qmd`: Google Form embed placeholder.

## First edits

1. Replace `YOUR-GITHUB-USERNAME` and repository URLs in `_quarto.yml`.
2. Replace placeholder supporter chips in the footer with supporter names or logo images.
3. Replace audio URLs and transcripts in the episode pages.
4. Replace `REPLACE_WITH_YOUR_FORM_ID` in `contact.qmd` with the Google Form embed URL.
5. Choose one comment model:
   - public GitHub-authenticated comments with Giscus; or
   - private Google-account feedback forms per episode.

## Preview locally

```bash
quarto preview
```

## Render for GitHub Pages

```bash
quarto render
```

This project uses `output-dir: docs`, so GitHub Pages can serve from the `docs/` folder if you prefer that workflow.

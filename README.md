# Εισαγωγή στην επιχειρησιακή έρευνα

This repository contains the course materials for Εισαγωγή στην επιχειρησιακή έρευνα, including lecture slides and comprehensive notes.

## Structure

- `slides/` - Contains all lecture presentations (HTML slideshows)
- `notes/` - Contains course notes (available as website and PDF)
- `docs/` - Generated website files (created after rendering)

## Usage

### Building the Site

To build the entire website:
```bash
quarto render
```

### Preview During Development

To preview with live reload:
```bash
quarto preview
```

### Adding New Content

**New Lecture:**
1. Create new folder in `slides/` (e.g., `lecture-04/`)
2. Add `index.qmd` with slide content
3. Update `slides-index.qmd` to include new lecture
4. Run `quarto render`

**New Notes Chapter:**
1. Create new `.qmd` file in `notes/`
2. Update `notes/_quarto.yml` to include new chapter
3. Update `notes/index.qmd` table of contents
4. Run `quarto render`

## Deployment

The built site in `docs/` can be deployed to any web server or GitHub Pages.

---

Created with [Quarto](https://quarto.org/)

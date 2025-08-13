# CV

This repository contains Aitor Ruiz's curriculum vitae written in LaTeX.

## Structure

- `basics/` – personal details and summary.
- `experience/` – professional experience.
- `education/` – academic background.
- `projects/` – selected projects.
- `skills/` – technical skills.

The main `cv.tex` file includes these sections.

## Usage

1. Update the section files with your information.
2. Compile the PDF locally:

```bash
pdflatex cv.tex
```

Pushes to `main` and all pull requests trigger a pipeline that compiles and uploads `cv.pdf` as an artifact.


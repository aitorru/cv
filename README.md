# cv

LaTeX CV template.

## Usage

1. Edit `cv.tex` with your information.
2. Compile locally with:
   ```bash
   pdflatex cv.tex
   ```

Pushes to `main` and all pull requests trigger a pipeline that compiles and uploads `cv.pdf` as an artifact. For pull requests, the action comments with a link to the generated artifact.

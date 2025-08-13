# cv

Plantilla de CV en LaTeX.

## Uso

1. Edita `cv.tex` con tu información.
2. Compila localmente con:
   ```bash
   pdflatex cv.tex
   ```

Cada commit y cada pull request activan una pipeline que compila y publica `cv.pdf` como artefacto. En las pull requests, la acción deja un comentario con un enlace al artefacto generado.

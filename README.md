# Newton's Principia Project

## Project Description

This project presents an algebraic translation of Newton's Proposition XI from Book I of *Philosophiæ Naturalis Principia Mathematica*. The project translates Newton's geometric reasoning into modern algebraic language while preserving the logical structure of his argument.

## Proposition XI

**Statement:** "Let a body revolve in an ellipse; it is required to find the law of the centripetal force tending toward a focus of the ellipse."

**Conclusion:** The centripetal force is inversely proportional to the square of the distance from the focus.

## Contents

The document includes:

- Introduction to Proposition XI
- Statement of the proposition
- Prior results used (Proposition I - Area Law, Proposition VI - Force and Sagitta)
- Geometric properties of the ellipse with visual diagram
- Curvature and sagitta analysis
- Derivation combining geometry with Proposition VI
- Conclusion

## Course Information

- **Course:** Newton's Principia
- **Instructor:** Andrew Mclntyre
- **Author:** Mohamed Ahmed

## Compiling the Document

This project is written in LaTeX. To compile the PDF:

```bash
pdflatex project.tex
```

You may need to run the command twice to resolve all references:

```bash
pdflatex project.tex
pdflatex project.tex
```

### Requirements

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Required packages:
  - `amsmath`, `amssymb` (mathematical symbols)
  - `geometry` (page layout)
  - `setspace` (line spacing)
  - `graphicx` (graphics)
  - `hyperref` (hyperlinks)
  - `tikz` (diagrams)

## Files

- `project.tex` - Main LaTeX source file
- `project.pdf` - Compiled PDF document
- `project.aux`, `project.log`, `project.out` - LaTeX auxiliary files (generated during compilation)

## References

- Properties of Ellipse: [BYJU'S JEE Properties of Ellipse](https://byjus.com/jee/properties-of-ellipse/)

## Notes

The document uses first-person perspective and simple, verbose language to explain Newton's geometric arguments in accessible terms. It includes a TikZ diagram illustrating the ellipse with its focus, center, and key geometric properties.


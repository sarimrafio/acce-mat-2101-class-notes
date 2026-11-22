# ACCE MAT 2101 — Class Notes & Solution Book

Multivariable & vector calculus (University of Dhaka, ACCE MAT 2101), built from
Anton's *Calculus*, 10th edition, and the course lecture plan (Lectures 0–22).

## What is in here

- **Teacher-style notes for all 23 lectures** — each lecture explained from zero,
  with a one-line summary, key formulas, one worked example, the exam mistake
  that costs marks, recall questions, practice problems and video links.
- **49 real textbook figures** — 46 from Anton 10th edition, 2 from OpenStax
  Calculus Volume 3, 1 from Gilbert Strang's *Calculus* (MIT OCW). Each carries
  its printed caption and source book and page number.
- **A complete solution book** — all 558 problems from the lecture plan solved
  step by step (only Ex. 14.2-12 is unsolved: its figure is lost in the book's
  text extraction, and the method is given instead).
- **A Desmos graph in every solution** — 558 live 2D graphs, plus 300 rotatable
  Desmos 3D graphs for the problems that live in space (surfaces, helices,
  solids, flux, divergence). 2D graphs load as you scroll; 3D graphs load when
  you tap "View in 3D".
- **Visual companions** — links to CalcPlot3D, GeoGebra 3D, Desmos 3D, Falstad's
  3D vector-field simulation, NablaVis, and interactive calculus books.

## How to use it

Open `index.html` in a browser — it is a single self-contained file. The
textbook figures are embedded in it; the Desmos graphs need an internet
connection.

## Hosting it

This is a static site — one HTML file. To share it:

- **GitHub Pages:** create a repo, put `index.html` at its root, enable Pages
  (Settings → Pages → Deploy from a branch, branch `main`, folder `/ (root)`).
  The site is then live at `https://<username>.github.io/<repo>/`.
- **Vercel / Netlify:** import the same repo; no build step is needed.

## Notes on sources

- The Anton figures are reproduced with permission from the publisher, for
  study use by the course's students.
- Worked answers were verified with SymPy and against Anton's answers appendix.
  A few errors found in an earlier draft of the course guide were corrected in
  the solutions (Ex. 13.2 #3, #17, Ex. 13.3 #82, #106, Ex. 14.1-11, and the
  Ex. 14.3-8 rose remark); the guide itself was corrected too.
- The Desmos graphs use the public Desmos API demo key. For a production
  deployment under heavy traffic, obtain your own key at desmos.com/my-api
  and replace it in the `<script src="https://www.desmos.com/api/...">` line.

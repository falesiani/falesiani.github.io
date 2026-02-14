---
title: Math example page
date: 2025-02-15
math: true
# Card thumbnail on Notes summary page: only LOCAL files work (assets/media/ or page folder)
# Use a file in assets/media/ and set filename to its name, e.g. filename: "my-note.jpg"
image:
  # filename: "stacked-peaks.svg"
  filename: ""
  caption: "Math / formula (optional caption)"
  focal_point: Smart
  preview_only: false
---

This page shows how to write mathematics in your Markdown. Math is enabled site-wide in `config/_default/params.yaml`; you can also set `math: true` in a page's front matter to enable it only on that page.

Source: www.unsplash.com
![alt](https://images.unsplash.com/photo-1635070041078-e363dbe005cb?w=800)


## Inline math

Use single dollar signs: $E = mc^2$, or $\nabla \cdot \mathbf{E} = \frac{\rho}{\epsilon_0}$.

## Block (display) math

Use double dollar signs on their own line:

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

Or an equation with a label:

$$
\frac{\partial u}{\partial t} = \alpha \nabla^2 u
$$

## Multi-line (align, etc.)

Use `\begin{aligned}` or `\begin{align}` inside `$$ ... $$`:

$$
\begin{aligned}
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0 \epsilon_0 \frac{\partial \mathbf{E}}{\partial t}
\end{aligned}
$$

You can now create your own page: add a new `.md` file under `content/` (e.g. `content/my-notes/index.md`) with `math: true` in the front matter and use `$...$` and `$$...$$` for formulas.

# Javier Rodríguez Vázquez — personal website

Source for [javierrodriguezvazquez.es](https://javierrodriguezvazquez.es/), an academic and professional portfolio focused on artificial intelligence, generalizable autonomy, embodied AI, computer vision, and robotics.

The site is built with Hugo and Hugo Blox and deployed to GitHub Pages through the workflow in `.github/workflows/publish.yaml`.

## Local development

Use Hugo Extended 0.119.0:

```bash
hugo server
```

Production build:

```bash
hugo --gc --minify
```

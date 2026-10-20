# Fei Wu — Academic Homepage

Source for [cii030.github.io](https://cii030.github.io/), built with Hugo and the
[PaperMod Academic Patch](https://github.com/rayleizhu/PaperMod-academic-patch).

The repository vendors the two themes used by the site so GitHub Pages builds are reproducible:

- `PaperMod-academic-patch` at commit `692a19525ad96421d6614a7c8bd0edfe6b876f78`
- `hugo-PaperMod` at commit `969bebdc5600a1639158b5ef4eff9cf6cbb511ac`

## Local preview

Install Hugo Extended 0.158.0 or newer, then run:

```bash
hugo server --buildDrafts
```

Open `http://localhost:1313/`.

## Update content

- Profile, experience, and honors: `config.yml`
- Biography: `content/about.md`
- Publications: `content/pubs/`
- News: `content/news/`
- CV: `static/files/Curriculum_Vitae.pdf`
- Profile image: `assets/images/head.png`
- Publication previews: `content/pubs/preview/`

Pushes to `master` are built and deployed through GitHub Actions.

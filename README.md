# Andrés André Camargo Bertel, Personal Website

Source for my personal academic website, built with [Quarto](https://quarto.org), by far the easiest and most effective tool I've found for building a site.

- **Live site:** <https://camargo-aa.github.io>
- **Updates (RSS):** <https://camargo-aa.github.io/posts.xml>

## Build & publish

- Install Quarto: <https://quarto.org/docs/get-started/>
- Websites guide: <https://quarto.org/docs/websites/>
- Edit `_quarto.yml`, add pages and posts, then run `quarto render`
- Publish on GitHub Pages: <https://quarto.org/docs/publishing/>

All very straightforward to set up, follow the steps and the site runs as expected.

## Structure

- `*.qmd`, site pages (bio, publications, teaching, …)
- `posts/`, papers and news entries
- `assets/`, CSS and listing templates
- `files/`, images, profile photos, CV, and includes
- `docs/`, rendered output published to GitHub Pages

## Credits & license

This website is **adapted from the Quarto academic website of Dr. Gang He**
(<https://github.com/drganghe/drganghe.github.io>), used under the **GNU GPL-3.0**
license. I replaced all content, removed the original author's personal analytics
and tracking IDs, and restructured the sections and templates. As required by the
GPL, this derivative work is likewise released under the **GNU GPL-3.0**, see
[LICENSE](LICENSE).

If you like this layout, I recommend starting from the original
[Quarto Academic website template](https://github.com/drganghe/quarto-academic-website-template)
rather than forking this repository.

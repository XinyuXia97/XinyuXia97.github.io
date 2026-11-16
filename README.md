# Xinyu Xia — Academic Homepage

Source for [xinyuxia97.github.io](https://xinyuxia97.github.io/), a Jekyll site hosted on GitHub Pages.

## Updating the site

- Edit `_pages/about.md` for the biography, news, publications, and experience. Navigation anchors live in `_data/navigation.yml`; keep their URLs in sync with the heading IDs.
- Add publication images under `images/` as optimized WebP files. Provide descriptive `alt` text and the image's intrinsic `width` and `height` in each publication card. Leave unpublished papers without links until their actual destinations are known.
- Edit `_config.yml` for the profile and site metadata, and `assets/css/main.scss` for layout and styles.
- Build locally with `bundle install && bundle exec jekyll build`; preview with `bundle exec jekyll serve` at `http://127.0.0.1:4000/`.

The original site template is [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io). Its [Chinese setup guide](docs/README-zh.md) is retained for reference. The theme incorporates Font Awesome and draws on Minimal Mistakes and Academic Pages (see [LICENSE](LICENSE)).

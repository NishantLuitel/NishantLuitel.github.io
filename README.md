# Nishant Luitel's website

A small, dark academic site published at <https://nishantluitel.github.io/>.

## Edit the site

The homepage text is in [`index.md`](index.md). Edit its front matter to change the name or role, and edit the Markdown below it to change the biography, interests, publications, and updates. Publications are listed newest first. Blog posts appear on the separate `/blog/` page, newest first.

The portrait is [`assets/img/prof_pic.jpg`](assets/img/prof_pic.jpg). The gradient-symbol favicon is [`assets/img/favicon.svg`](assets/img/favicon.svg). Colors and spacing are in [`assets/css/reading.css`](assets/css/reading.css). The small HTML wrapper is [`_layouts/default.html`](_layouts/default.html).

## Write a blog post

Create `blog/your-post-slug/README.md` by copying [`BLOG_TEMPLATE.md`](BLOG_TEMPLATE.md). Change its title, date, summary, and permalink (`/blog/your-post-slug/`). The post appears automatically at `/blog/`, newest first. Keep images, SVG plots, or self-contained HTML plots in the same folder; relative Markdown image links such as `![Description](plot.svg)` work from the published post. Give every plot useful alt text and a short caption.

Posts support headings, tables, code fences with language names, quotes, footnotes, and LaTeX math. Use `$$...$$` for inline math and put display math between `$$` lines. MathJax loads on blog posts only. A self-contained interactive plot can be embedded with an HTML `<iframe src="plot.html" title="Description of plot"></iframe>` in the Markdown file. Only embed HTML you trust.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000/>. Pushing to `master` builds the site and publishes the generated pages to `gh-pages` through the GitHub Actions workflow.

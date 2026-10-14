# Nishant Luitel's website

A small, dark academic site published at <https://nishantluitel.github.io/>.

## Edit the site

All page text is in [`index.md`](index.md). Edit its front matter to change the name or role, and edit the Markdown below it to change the biography, interests, publications, and updates. Standard Markdown headings, lists, emphasis, and links are styled automatically.

The portrait is [`assets/img/prof_pic.jpg`](assets/img/prof_pic.jpg). Colors and spacing are in [`assets/css/style.css`](assets/css/style.css). The small HTML wrapper is [`_layouts/default.html`](_layouts/default.html).

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000/>. Pushing to `master` builds the site and publishes the generated pages to `gh-pages` through the GitHub Actions workflow.

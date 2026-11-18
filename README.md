# tikatoka.github.io

Source for Joochan Kim's academic website: https://tikatoka.github.io

Built with Jekyll on GitHub Pages. Design originally adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron_website).

## Editing

- **Bio, news, publications:** `index.html`
  - News: add a new `<li>` at the top of the `News` list. Items after the first five are folded under "Older news".
  - Papers: copy an `<article class="paper">` block. Add the `highlight` class for lead-author papers,
    and paste the BibTeX into the paper's `<pre>` block.
- **Styles:** `stylesheet.css` (colors are CSS variables at the top; dark mode under `[data-theme="dark"]`)
- **Blog posts:** `_posts/YYYY-MM-DD-title.md`

# Quantized Reasoning blog

Source for the blog post at
`https://sanaelotfi.github.io/files/blog/quantized-reasoning/`.

## Local preview

From the repo root (`sanaelotfi.github.io/`):

```
bundle exec jekyll serve
```

Then open `http://localhost:4000/files/blog/quantized-reasoning/` in a browser.

The page is a static `index.html` with no Jekyll front matter, so any plain HTTP
server works too if Jekyll is heavy:

```
cd files/blog/quantized-reasoning && python3 -m http.server 8000
```

then `http://localhost:8000/`.

## Iterating with collaborators

The page is currently unlisted (`noindex` meta tag and a banner at the top).
Workflow:

1. Edit `index.html` on a branch.
2. Push the branch. GitHub Pages builds a preview from the branch if you
   configure one, or share the file diff in PR review.
3. When a collaborator's comments come back, drop them inline in the section
   they refer to (or open an issue against the repo with the section anchor).
4. Once the paper is public, remove the `noindex` meta tags and the
   `private-banner` div, then merge to main.

If we want inline comments on the rendered page itself, the lightest option is
to add a `giscus` widget (GitHub-issues-backed comments) at the bottom.
Defer until we need it.

## Files

- `index.html` — the page.
- `images/` — all figure assets, exported from the paper's `new_figs/` directory.
- `README.md` — this file.

## Source of truth

Numbers, definitions, and curated token list come from:

- `Quantized-Reasoning-Models/arxiv.tex`
- `Quantized-Reasoning-Models/thinking_tokens.json`

If any number on the page conflicts with the latest `arxiv.tex`, the paper wins.

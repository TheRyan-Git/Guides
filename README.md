# Ryan's Guides

A collection of practical guides hosted on **GitHub Pages**.

## Site

**[https://theryan-git.github.io/guides/](https://theryan-git.github.io/guides/)**

---

## Guides

- [Scholarship Guide](https://theryan-git.github.io/guides/scholarship-guide/)
- [JHSST Survival Guide](https://theryan-git.github.io/guides/tjhsst-survival-guide/)
- [Muscle-Gaining Guide](https://theryan-git.github.io/guides/muscle-gaining-guide/)
- [Rowing Guide](https://theryan-git.github.io/guides/rowing-guide/)

---

## How GitHub Pages Works

GitHub Pages automatically builds and serves this site from the `main` branch.

### File Structure

```
guides/
├── _config.yml
├── index.md                = Home page
├── scholarship-guide.md
├── tjhsst-survival-guide.md
├── muscle-gaining-guide.md
└── rowing-guide.md
```

### How Pages Are Formatted

Each page uses **Markdown**

```markdown
---
layout: page
title: My Page Title
permalink: /my-page/
---

# My Heading

Content goes here...
```

### Linking Between Pages

```markdown
<!-- Relative link to another page -->
[Go to Scholarship Guide](./scholarship-guide)

<!-- Link back to home -->
[← Back to Home](../)

<!-- Link to an anchor/section within the same page -->
[Jump to Section](#section-name)

<!-- External link -->
[Google](https://www.google.com)
```

### Formatting Cheat Sheet

| Element | Markdown Syntax |
|---------|----------------|
| Heading 1 | `# Title` |
| Heading 2 | `## Section` |
| Bold | `**bold**` |
| Italic | `*italic*` |
| Inline code | `` `code` `` |
| Code block | ```` ```language ... ``` ```` |
| Table | `\| Col \| Col \|` with `\|---\|---\|` separator |
| Bulleted list | `- item` |
| Numbered list | `1. item` |
| Blockquote | `> text` |
| Horizontal rule | `---` |
| Link | `[text](url)` |
| Emoji | `:emoji_name:` or paste directly 🎉 |

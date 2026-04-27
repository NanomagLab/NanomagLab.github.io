# NanoMag Lab Homepage

Homepage for **Kyung Hee University Nano-Magnetism Lab**.

## Target Page

- Live page: [https://nanomaglab.github.io/](https://nanomaglab.github.io/)

## Structure

- `index.html`: layout, styles, and rendering logic
- `data/site-data.js`: structured content data
  - `members`
  - `publications`

The page renders `members` and `publications` from `data/site-data.js`.

## Update Content

Edit `data/site-data.js` only.

### Members

Use this format:

```js
{ role: "Graduate Student", name: "Your Name" }
```

Optional profile link:

```js
{ role: "Professor", name: "Changyeon Won", profileUrl: "cywon.html" }
```

### Publications

Use this format:

```js
{
  title: "Paper title",
  meta: "Authors. Journal",
  date: "YYYY-MM-DD"
}
```

Notes:
- Publications are auto-sorted by `date` (newest first).
- If only the year is known, use `YYYY-01-01` and it will display as year only.

## Local Preview

Open `index.html` directly in browser:

```text
file:///C:/Users/psm/projects/update_hompage/index.html
```

Or use GitHub Pages after pushing to the repository.

## Deployment

1. Commit changes
2. Push to `main` (or your default branch)
3. GitHub Pages updates automatically for `NanomagLab.github.io`

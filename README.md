# Navinshankar V — Portfolio

A single page personal portfolio built as one self contained `index.html` file. No build step, no frameworks, no npm. All CSS and JavaScript are inline, so GitHub Pages serves it exactly as is.

**Live site:** https://navin-shankar-v.github.io/portfolio/

## Highlights

- Warm dark mode aesthetic with earthy terracotta and amber accents
- Interactive constellation background that reacts to the cursor, shared behind every section
- Glassmorphic cards with a cursor tracking glow
- Interactive skills panel: filter by category and watch proficiency bars fill in
- Sections: Hero and About, Projects, Skills, Experience, Education, Contact
- Fully responsive, accessible (semantic HTML, focus states, keyboard navigable), and respects `prefers-reduced-motion`

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire site (HTML, CSS, and JS inline) |
| `Navinshankar_Resume.pdf` | Linked by the Resume download button |

## Run locally

Just open `index.html` in any browser. No server needed.

## Deploy to GitHub Pages

1. Create a public repo and push `index.html` and `Navinshankar_Resume.pdf` to the root.
2. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, then **Save**.
3. Your site goes live at `https://<username>.github.io/<repo-name>/` within about a minute.

## Customize

- Text content, links, and projects live directly in `index.html` inside their labeled sections.
- Colors are CSS variables in the `:root` block near the top of the `<style>` tag.
- Swap `Navinshankar_Resume.pdf` with an updated file using the same name to refresh the download.

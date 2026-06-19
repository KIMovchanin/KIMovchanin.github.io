# Igor Kondratiuk Portfolio

Static one-page portfolio for Igor Kondratiuk / KIMovchanin.

## File Structure

```text
.
|-- index.html
|-- styles.css
|-- script.js
|-- assets/
|   `-- hero-retro-desktop.png
`-- README.md
```

## Design Notes

- Dark backend-engineer interface with controlled Olderbrothercore, Y2K chrome, terminal, and cyberpunk details.
- Content positions Igor honestly as a growing Go & Python Backend Engineer, not as a senior engineer.
- Recruiter-facing sections are prioritized: hero, about, experience, projects, tech stack, strengths, and contact.
- Instagram is omitted. Facebook and Discord are included as requested.
- The generated bitmap asset is used in the hero and copied into `assets/` so the site is self-contained.

## Editing Content

- Update copy, links, project cards, and SEO metadata in `index.html`.
- Add a new project by copying one `<article class="project-card">...</article>` block in the Projects section.
- Update visual styling, colors, spacing, and responsive rules in `styles.css`.
- Mobile navigation and active section highlighting live in `script.js`.

## Deployment

### GitHub Pages

1. Push this folder to a GitHub repository.
2. In repository settings, open Pages.
3. Select the main branch and root folder.
4. Save. GitHub will publish the static site.

### Vercel

1. Import the repository in Vercel.
2. Use the default static project settings.
3. Deploy. No build command is required.

### Netlify

1. Import the repository in Netlify.
2. Leave build command empty.
3. Set publish directory to `/`.
4. Deploy.

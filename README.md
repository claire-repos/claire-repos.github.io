# Personal website (GitHub Pages starter)

Static HTML, CSS and JS. No build step.

## Publish
1. Create a GitHub repo (name it `yourusername.github.io` for a root URL).
2. Upload everything in this folder to the `main` branch.
3. Settings > Pages > Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Wait a minute, then open `https://yourusername.github.io`.

## Edit
| To change | Edit |
|---|---|
| Name, nav, social links, projects, experience, skills, testimonials | `assets/content.js` |
| Colors, fonts, spacing | tokens at the top of `assets/style.css` |
| Page layout and copy | the matching `.html` file |
| Resume download | add `assets/resume.pdf` |
| Portrait | replace the `.portrait` div with `<img>` |
| Contact form | uses your email app; swap the `<form>` to a Formspree or Netlify form for direct delivery |

Add a project: copy one entry in `projects` in `content.js`. Its page is created automatically at `project.html?p=your-slug`. Add a page: copy a `.html` file and add it to `nav`.

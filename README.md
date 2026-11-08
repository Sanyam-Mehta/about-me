# Sanyam Mehta's website

Live at https://sanyam-mehta.github.io/about-me/

- Everything on the page is in `index.html`. Each section starts with a comment like `<!-- News -->`.
- Styling is in `style.css`.
- To preview, open `index.html` in a browser. There is no build step.
- To add a news item, copy one `<li>` in the News list and change the date and text.
- To add a paper or project, copy the JEVA block (`<!-- Publication: JEVA -->`). For a video thumbnail, copy the Point Prompting block instead.
- To add a picture, put it in `images/` (around 600px wide is plenty). Set the `width` and `height` on the `<img>` to the image's real pixel size, so the page doesn't jump while it loads.
- To update the CV, replace `Sanyam_Mehta_CV.pdf`.
- GitHub Pages serves the `development` branch. Merge your changes into `development` and push, and the site updates in a minute or two.
- `.nojekyll` tells GitHub Pages to serve the files as they are.

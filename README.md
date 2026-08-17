# Vishal Ramesh portfolio

A simple, dependency-free HTML portfolio with three pages:

- `index.html` - short introduction, two-paragraph biography, and large navigation links
- `about.html` - background, skills, technologies, and contact/profile links
- `portfolio.html` - detailed case studies for four projects
- `styles.css` - all colors, spacing, type, and responsive behavior
- `project-images/` - the screenshots and diagrams shown in the project galleries
- `project-briefs/` - downloadable one-page project briefs

## Make a text change

Open any HTML file in VS Code and edit the text between its tags. Helpful comments mark the Home-page biography, navigation links, and each portfolio project.

For example:

```html
<h3>Your project title</h3>
<p>Your updated description.</p>
```

Save the file and refresh the browser. There is no build command, framework, or package installation.

## Add or remove an item

- Home links: copy or delete one complete `<a class="home-link">` link and give it one of the existing color classes.
- About-page skills: copy or delete one complete `<div class="skill-group">` block.
- Portfolio case studies: copy or delete everything between a `PROJECT START` and matching `PROJECT END` comment.

When adding a new portfolio project, give it a unique `id`, such as `id="new-project"`, and link to it with `portfolio.html#new-project`.

## Add project images

The portfolio contains two image slots for the Grant, NFL, and Wildfire projects and three image slots for the NBA Team Builder.

1. Save your PNG or JPG in the `project-images` folder.
2. Open `portfolio.html` and search for `IMAGE SLOT`.
3. Replace the placeholder `<div>` with the example `<img>` directly above it.
4. Change the filename and the `alt` description to match your image.

For example:

```html
<img src="project-images/nba-roster-builder.png" alt="NBA Team Builder player selection screen and roster">
```

Keep the `<figcaption>` below the image, or edit its text to explain what the screenshot demonstrates.

## Change the design

The most useful settings are at the top of `styles.css`:

```css
:root {
  --background: #0b1020;
  --text: #f1f4fa;
  --blue: #60a5fa;
  --green: #4ade80;
  --purple: #b69af4;
  --orange: #fb923c;
}
```

Changing these values updates both pages. The website uses the browser's default HTML font and a dark color scheme. It is designed for desktop computers only; the stylesheet intentionally has no small-screen layout rules.

## Repository links

The Grant Intelligence repository is public. The NFL repository URL is configured in the local project but is not currently public. The Wildfire project currently links to the GitHub profile until its own repository is published. Comments beside both links show exactly where to replace them later. The NBA Team Builder links to its video demo and shared project-files folder.

The LinkedIn profile URL was not available. In `about.html`, search for `LINKEDIN` and replace the clearly marked placeholder with the example link shown in the HTML comment.

## Preview

Double-click `index.html`, or open it in a browser from VS Code. Because every link is relative, the site also works as a static GitHub Pages site.

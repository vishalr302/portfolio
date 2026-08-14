# Vishal Ramesh portfolio

A simple, dependency-free HTML portfolio with three pages:

- `index.html` - home, background, experience, and short project summaries
- `about.html` - biography, working approach, and quick details
- `portfolio.html` - detailed case studies for three projects
- `styles.css` - all colors, spacing, type, and responsive behavior
- `project-briefs/` - downloadable one-page project briefs

## Make a text change

Open any HTML file in VS Code and edit the text between its tags. Helpful comments such as `HOME INTRO`, `EXPERIENCE`, and `PROJECT 1 START` mark the main editable areas.

For example:

```html
<h3>Your project title</h3>
<p>Your updated description.</p>
```

Save the file and refresh the browser. There is no build command, framework, or package installation.

## Add or remove an item

- Experience entries: copy or delete one complete `<article class="experience-entry">` block in `index.html`.
- Home project summaries: copy or delete one complete `<article class="project-preview">` block.
- Portfolio case studies: copy or delete everything between a `PROJECT START` and matching `PROJECT END` comment.
- About-page details: copy or delete one complete `<div class="fact">` row.

When adding a new portfolio project, give it a unique `id`, such as `id="new-project"`, and link to it with `portfolio.html#new-project`.

## Change the design

The most useful settings are at the top of `styles.css`:

```css
:root {
  --background: #f7f9fc;
  --text: #16213e;
  --accent: #2959c7;
  --green: #167a59;
  --purple: #7048b8;
  --orange: #bd5b24;
}
```

Changing these values updates all three pages. Color is used for navigation, section bands, and project identity while the layout remains based on whitespace and thin dividers instead of many cards.

## Repository links

The Grant Intelligence repository is public. The NFL repository URL is configured in the local project but is not currently public. The Wildfire project currently links to the GitHub profile until its own repository is published. Comments beside both links show exactly where to replace them later.

## Preview

Double-click `index.html`, or open it in a browser from VS Code. Because every link is relative, the site also works as a static GitHub Pages site.

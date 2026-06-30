# Alphabet Agency — Projects

Portfolio landing page for the data projects & experiments of
[Alphabet Agency](https://thealphabetagency.com), live at
**https://dalee9000.github.io/** (and intended for `projects.thealphabetagency.com`).

This is a single static `index.html` — no build step. It links out to each project, which lives
in its own repo.

## Add a project
Edit the `PROJECTS` array near the bottom of `index.html`:

```js
{
  title: "Project name",
  status: "live",                 // "live" | "soon"
  blurb: "One- or two-sentence description.",
  tags: ["Tag", "Tag"],
  thumb: "assets/your-thumb.png", // or "" for a placeholder tile
  url: "https://...",             // the live demo
  source: "https://github.com/...",
}
```

Drop a screenshot in `assets/`, commit, push — GitHub Pages redeploys automatically.

## Projects
- **TIDELINE — NYC Flood-Resilience Tracker** — https://dalee9000.github.io/nyc_state_capacity_hackathon/

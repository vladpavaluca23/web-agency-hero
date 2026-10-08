# Web Agency Hero

A hero section for a fictional web agency, built from scratch with HTML and CSS.
Solo project from the Scrimba "Learn HTML and CSS" course.

**Live:** https://vladpavaluca23.github.io/web-agency-hero/

## Built with

- Semantic HTML
- CSS (no frameworks)
- A full-width background image with text on top

## What I practised

- Using an image as a CSS background instead of an `<img>` element
- Positioning text and a call-to-action over a background
- Matching a design spec: colours, fonts and spacing

## What I learned

- **100vh for full-screen sections:** a `div` is only as tall as its content,
  so `background-size: cover` had nothing to cover. Setting `height: 100vh`
  made the hero fill the viewport on any screen.
- **Background on the section, not on body:** I kept the background image on
  the `.hero` div rather than on `body`, so that any section added below it
  would get its own background instead of sitting on top of the photo.
- **Margin collapsing:** the heading's default top margin pushed the whole
  hero down, leaving a white strip above it. Adding padding to the hero
  stopped the margin from escaping its parent.
- **span for partial styling:** I wrapped "come true." in a `<span>` to
  underline just that part of the paragraph

## Credits

- Design, brief and assets: Scrimba

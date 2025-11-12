# PhillFab Website

A static website for PhillFab YouTube channel.

## How to Edit

### Adding Your Details
- Open `index.html`
- In the `#about` section, edit the paragraphs to add your personal description.

### Adding Vlogs
- In `index.html`, find the `.vlog-grid` section.
- Copy one of the existing `.vlog-card` divs.
- Paste it after the last card.
- Edit the image src (replace `assets/placeholder.svg` with your thumbnail image path).
- Edit the `<h3>` for the title.
- Edit the `<p>` for the description.
- Edit the `href` in the `<a>` tag to your YouTube video URL.

### Changing Colors or Styles
- Edit `styles.css` to customize colors, fonts, etc.
- The color palette is defined in `:root` variables.

### Adding Images
- Place your images in the `assets/` folder.
- Update the `src` attributes in HTML accordingly.

## Running the Site
- Open `index.html` in a web browser, or
- Run a local server: `python3 -m http.server 8000` and visit `http://localhost:8000`

## Notes
- The site uses reactive CSS with animations and cursor effects.
- It's responsive and works on mobile and desktop.
- UK English is used throughout.
# CSS Advanced - Images

This directory contains the image assets used by the **CSS Advanced / Techium** project.

## Files

- `pic-about-01.jpg`
- `pic-article-01.jpg`
- `pic-article-02.jpg`
- `pic-article-03.jpg`
- `pic-person-01.jpg`
- `pic-person-02.jpg`
- `pic-person-03.jpg`
- `pic-work-01.jpg`
- `pic-work-02.jpg`
- `pic-work-03.jpg`

## Usage

Use relative paths from HTML files:

```html
<img src="images/pic-about-01.jpg" alt="About section visual" />
```

From CSS files in the project root folder:

```css
background-image: url("images/pic-work-01.jpg");
```

## Notes

- Keep original filenames to match project tasks and checker expectations.
- Prefer meaningful `alt` text in HTML for accessibility.
- Do not move these files unless you also update all HTML/CSS references.

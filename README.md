# CV HTML Template

This folder contains a production-ready HTML/CSS CV generated from `CV.odt`.

## Files

- `index.html` - resume content and semantic HTML structure
- `style.css` - responsive screen styles and A4 print styles
- `CV.odt` - original source document

## Open Locally

Open `index.html` in a browser. Chrome is recommended because the print styles are optimized for Chrome PDF export.

## Export To PDF

1. Open `index.html` in Chrome.
2. Press `Ctrl + P`.
3. Set destination to `Save as PDF`.
4. Use these recommended settings:
   - Paper size: `A4`
   - Margins: `Default`
   - Scale: `100`
   - Background graphics: enabled
   - Headers and footers: disabled
5. Save the PDF.

## Modify Content

Edit the resume text in `index.html`. The main sections are clearly separated:

- Header
- Summary
- Skills
- Experience
- Projects
- Education
- Courses
- Certifications
- Languages
- Interests

For visual changes, edit `style.css`. The main design values are stored as CSS variables at the top of the file, including spacing, colors, page size, and typography.

## ATS Notes

The layout uses semantic HTML, readable headings, text-based contact links, simple lists, and no JavaScript. This keeps the CV easy to parse for applicant tracking systems while preserving a clean printable design.

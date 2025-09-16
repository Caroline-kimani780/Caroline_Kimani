# Caroline_Kimani

# Master Timetable — 2024/2025 (Caroline Kimani)

## Project overview
This project recreates the provided school master timetable using an HTML table and CSS for styling. The goal is a fixed layout which closely follows the structure of the supplied image. Cells such as BREAK and LUNCH span the vertical height across the Year groups using `rowspan` to visually match the provided timetable.

Files included:
- `index.html` — Main HTML file containing the timetable implemented with semantic table markup.
- `style.css` — Stylesheet for table appearance, spacing, and highlights for breaks and activities.
- `timetable_preview.png` — Reference screenshot (the original timetable image provided).
- `Caroline_Kimani.zip` — Zipped submission ready for upload.

## Accessibility considerations
- Table headers use `<th>` elements with `scope="col"` and `scope="row"` where appropriate to assist screen readers.
- The table is placed in a `<section>` with an accessible name (`aria-labelledby`).
- An alt text description for the provided timetable image is included below.

**Alt text for timetable_preview.png**: "Photograph of the original printed master timetable for 2024/2025 academic year showing days Monday to Friday with 13 periods and rows for Year 7 through Year 11."

## Validation
- Before submission validate `index.html` with W3C Markup Validation Service and `style.css` with the W3C CSS Validator and address any reported issues.
- This implementation uses standard HTML5 semantic elements and should pass validation with minor edits if required.

## Notes
- The provided HTML table is an approximation of the printed timetable. Exact cell merging (rowspan/colspan) and final visual tweaks can be adjusted further to match pixel-perfect requirements.
- If you want a version implemented with CSS Grid (for bonus points), request it and I will produce a grid-based alternative.

# Arabicize Your Site
Set of steps to guide you through creating an Arabic version of your LTR website.
Should work mostly for other RTL languages as well.

### Duplicate Asset Files *(Optional)*
- Duplicate layout/template files (e.g. template.html, index.html, etc.)
- Duplicate and rename CSS files (e.g. styles-ar.css, bootstrap-ar.css, cover-ar.css, etc.)
- Duplicate images and other assets.
### Images & Backgrounds
- Replace English text in Logotype images with Arabic text.
- Replace English text in photos and other pictures with Arabic text.
- Flip direction of asymmetric text-free decorative images from left to right and vice versa.
### CSS Code
- `direction: rtl` <=> `direction: ltr`
- `left` <=> `right`
- `letter-spacing: 0` – Arabic text has no letter spacing.
- `en` <=> `ar` (e.g Look for: -en, en-, /en, en/, "en, en", en, etc.)
- `margin:` 1 2 3 4 => `margin:` 1 4 3 2 
- `padding:` 1 2 3 4 => `padding:` 1 4 3 2
- For Bootstrap 4 and later: `ml` <=> `mr`
- For Bootstrap 4 and later: `pl` <=> `pr`
- Replace the `font-family` font-stack values with appropriate Arabic ones (e.g. 'Amiri', 'Droid Arabic Naskh', 'Arial', etc.)
### HTML Code
- `left` <=> `right`
- `ltr` <=> `rtl`
- `en` <=> `ar` (e.g Search for: -en, en-, /en, en/, "en, en", en, etc.)
- Validate HTML element attribute values: (e.g. `title`, `alt`, `src`, `href`, `placeholder`, `value`, etc.)
- Translate English text content to Arabic.
### Test & Fix
- Quality-check font sizes of headings and paragraphs.
- Check if `font-weight` still works for all newly used Arabic font families.
- Check misspellings.
- Use better fonts if necessary.
- Adjust spacing if necessary (i.e. paddings, margins, positions, etc.)
- Debug JavaScript plugins and scripts that stopped working because of renaming and style direction change. 

______________
[*] Notice that the sign `<=>` goes both ways.

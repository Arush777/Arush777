# assets

| File | Size | Shows |
|---|---|---|
| `terminal.svg` | 7.3 KB | Hero banner, 1000×300 (10:3). Dark terminal window typing `whoami` → **Arush Sharma**, then `cat moat.txt` → "I make models **faster**. Research and engineering is my moat.", ending on an idle prompt with a blinking block cursor. |

## Embed

Recommended: centred, fills the README column, and stays sharp at any width because it is vector.

```html
<p align="center">
  <img src="assets/terminal.svg" width="100%" alt="Arush Sharma. I make models faster. Research and engineering is my moat.">
</p>
```

Plain Markdown also works. It renders at up to 1000 px and shrinks to fit.

```markdown
![Arush Sharma. I make models faster. Research and engineering is my moat.](assets/terminal.svg)
```

## Notes

- Set a width only, never a height, so the 10:3 ratio holds.
- It plays once per page load and lands on the final frame at 3.1 s. After that only the cursor blinks. With `prefers-reduced-motion`, the final frame shows at once with a solid cursor.
- It is dark in both GitHub themes by design, and has been checked on `#0d1117` and `#ffffff`.
- It uses no web fonts, only the system mono stack. Safari and iOS draw it in SF Mono, Chrome on macOS in Menlo, Windows in Consolas and Linux in Liberation or DejaVu Mono. Every line fits in all of them.
- GitHub can serve the cached image for a few minutes after a push. Hard-refresh to see edits.
- Palette for matching badges: background `#121211`, accent `#19c6a5`, soft accent `#8fe6d3`, text `#ece8e1`, dim `#857f76`. For a shields.io badge, add `&labelColor=121211&color=19c6a5`.
- There are no section-header images. A 1000×44 strip shrinks to about 15 px tall in a phone-width column, and an image heading loses its anchor link. For a terminal flavour, use Markdown headings such as `## ~/papers`, which still gets the anchor `#papers`.

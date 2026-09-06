# Photos to drop in here

The site works right now with no photos at all — every image slot falls back
to a solid color block, so nothing looks broken. Add files with the exact
names below and they'll appear automatically (no code changes needed).

| Filename | Used for | Suggested shape |
|---|---|---|
| `hero.jpg` | Full-screen photo behind your name | Wide, landscape (e.g. 2400×1600) |
| `portrait.jpg` | Photo next to the About text | Portrait, 4:5 (e.g. 1600×2000) |
| `gallery-1.jpg` | Creative gallery (wide tile) | Landscape, wide (e.g. 1600×900) |
| `gallery-2.jpg` | Creative gallery | Square or portrait |
| `gallery-3.jpg` | Creative gallery | Square or portrait |
| `gallery-4.jpg` | Creative gallery | Square or portrait |
| `gallery-5.jpg` | Creative gallery (wide tile) | Landscape, wide |
| `interest-skiing.jpg` | Skiing tile | Landscape, 4:3 |
| `interest-hiking.jpg` | Hiking tile | Landscape, 4:3 |
| `interest-sports.jpg` | Women's sports tile | Landscape, 4:3 |
| `interest-epl.jpg` | EPL/Liverpool tile | Landscape, 4:3 |
| `interest-parks.jpg` | National Parks tile | Landscape, 4:3 |
| `interest-reading.jpg` | Currently reading tile | Landscape, 4:3 |

Tips:
- JPG or WebP both work — just keep the filename (drop the extension change
  and update the matching `url(...)` in `index.html` if you use `.webp`).
- Keep files under ~500KB each if you can (export at "web quality" ~80%) so
  the site stays fast.
- The gallery is your own cinematography/photography — swap in real frames
  whenever you have them.

## Company logos (`logos/` folder)

The "Work" timeline already has real logos for all seven roles, in
`images/logos/`: `work-insight.png`, `work-washu.png`, `work-retykle.png`,
`work-browningwest.webp`, `work-lgbtvc.png`, `work-olin.png`,
`work-giftameal.png`. To swap one out, replace the file (same name) or edit
the `<img src="...">` path for that role in `index.html`.

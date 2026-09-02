# Images

Drop photos in here using these exact filenames. Each one appears automatically —
no code changes, no rebuild. Until a file exists, the deck shows a styled
placeholder that already reserves the correct space, so nothing shifts when you
add the real photo.

| File | Ratio | What it is |
|---|---|---|
| `01-hero.jpg` | 4:5 | Portrait of Anna |
| `03-oregon.jpg` | 16:9 | Oregon landscape |
| `04-denver.jpg` | 3:2 | Denver or LoHi |
| `06-outdoors.jpg` | 4:5 | Hiking, skiing, or lifting |
| `07-travel-1.jpg` | 4:5 | Oktoberfest |
| `07-travel-2.jpg` | 4:5 | Positano |
| `07-travel-3.jpg` | 4:5 | Ireland |
| `08-family.jpg` | 16:9 | The full family group photo |

Every image is cropped with `object-fit: cover`, so the ratios above are a guide
for what will stay in frame, not a hard requirement.

To remove a slot you don't want to fill, delete its `<figure class="slot">`
element in `index.html` and the layout reflows.

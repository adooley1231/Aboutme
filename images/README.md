# Images

Drop photos in here using these exact filenames. Each one appears automatically —
no code changes, no rebuild. Until a file exists, the deck shows a styled
placeholder that already reserves the correct space, so nothing shifts when you
add the real photo.

| File | Ratio | What it is | Status |
|---|---|---|---|
| `01-hero.jpg` | 4:5 | Portrait of Anna | filled |
| `03-lake-oswego.jpg` | 4:5 | The Oregon coast | filled |
| `03-bend.jpg` | 4:5 | Floating the Deschutes | filled |
| `03-scottsdale.jpg` | 4:5 | Scottsdale or the desert | **needed** |
| `03-denver.jpg` | 4:5 | Denver or LoHi | **needed** |
| `04-denver.jpg` | 3:2 | Denver or LoHi, wide | **needed** |
| `05-movies.jpg` | 2.4:1 | The Drafthouse, or a marquee | **needed** |
| `05-art.jpg` | 2.4:1 | A drawing in progress | filled |
| `05-music.jpg` | 2.4:1 | A concert | filled |
| `05-ancient-history.jpg` | 2.4:1 | Ruins, a museum, a book stack | **needed** |
| `05-reading.jpg` | 2.4:1 | Your shelf, or what you are on now | **needed** |
| `05-sports.jpg` | 2.4:1 | A game | filled |
| `06-making-1.jpg` | 4:5 | Something you made | filled |
| `06-making-2.jpg` | 4:5 | Sourdough | filled |
| `06-making-3.jpg` | 4:5 | Whatever you are making now | **needed** |
| `07-moving-1.jpg` | 4:5 | Hiking | filled |
| `07-moving-2.jpg` | 4:5 | Skiing | filled |
| `07-moving-3.jpg` | 4:5 | Running | filled |
| `08-travel-1.jpg` | 4:5 | Oktoberfest | filled |
| `08-travel-2.jpg` | 4:5 | Positano | filled |
| `08-travel-3.jpg` | 4:5 | Ireland | filled |
| `09-place-1.jpg` | 1:1 | Capri | filled |
| `09-place-2.jpg` | 1:1 | Venice | filled |
| `09-place-3.jpg` | 1:1 | Florence | filled |
| `09-place-4.jpg` | 1:1 | Galway | filled |
| `09-place-5.jpg` | 1:1 | The Cliffs of Moher | filled |
| `09-place-6.jpg` | 1:1 | Dublin | filled |
| `09-place-7.jpg` | 1:1 | Forks, Washington | filled |
| `09-place-8.jpg` | 1:1 | Somewhere you want to add | **needed** |
| `10-family.jpg` | 16:9 | The full family group photo | filled |
| `11-parents.jpg` | 4:5 | Mom and Dad | filled |
| `11-brother.jpg` | 4:5 | Anna and her brother | filled |
| `11-sister.jpg` | 4:5 | Anna and her sister | filled |
| `11-group.jpg` | 4:5 | The smaller family group | filled |
| `15-friends.jpg` | 4:5 | The friends | filled |
| `15-dog.jpg` | 4:5 | The family dog | filled |

Every image is cropped with `object-fit: cover`, so the ratios above are a guide
for what will stay in frame, not a hard requirement.

Press `P` in the deck to hide all placeholder chrome — both the image slots and
the dashed copy blocks — for a clean screenshot or a run-through.

To remove a slot you don't want to fill, delete its `<figure class="slot">`
element in `index.html` and the layout reflows.

# Reading Room Handbook

A quick-reference website for radiology: CT, mammography, MRI, ultrasound, X-ray, fluoroscopy, contrast safety and reporting systems (BI-RADS, TI-RADS, Fleischner, Lung-RADS, Bosniak, adrenal washout).

- Two files: `index.html` (content and code) and `styles.css` (all styling). No build step. Open it in a browser or host it on GitHub Pages.
- Each topic has a **department notes** box. Notes and custom protocols are saved in the browser (localStorage). Use **Back up** and **Restore** to move them between devices.
- TI-RADS and adrenal washout calculators are built in.
- **CT protocols** and **MRI protocols** sections give scan-by-scan parameters (position, coverage, contrast volume, rate and delay, slices, sequences). They are summarised from Bhargava & Bhargava, *CT and MRI Protocol: A Practical Approach*, 3rd ed. (2018), and each of those topics names the source. Where the book is older than current ACR guidance, the Contrast & safety topics take precedence.

## Editing content

All reference topics are in the `TOPICS` array inside `index.html`. Each topic has an `id`, a modality (`mod`), a `title`, a `sum`mary, `tags`, and a list of sections (`secs`). A topic can also carry `src` (a source credit shown under the title). A section can be a `list`, `steps`, `table`, `note`, paragraph (`p`) or diagram (`fig`, an inline SVG function).

- **Diagrams**: the `fig…()` functions draw the diagrams and are added to topics in the list below them.
- **See it & watch it**: the `MEDIA` map sets the Radiopaedia and YouTube search phrase for each topic.
- **Videos and images in notes**: paste a YouTube link or an image link (.png, .jpg, .gif, .webp) into a topic's notes and it shows as a player or picture. YouTube embeds need the site to be served over http(s), such as GitHub Pages. When it's opened as a local file, use the "Open on YouTube" link instead.

## Disclaimer

General reference only. Protocols, doses and thresholds vary between institutions, and guidelines change. Department protocols and current source documents (ACR, Fleischner Society, etc.) take precedence.

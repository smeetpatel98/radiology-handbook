# Reading Room Handbook

A quick-reference website for radiology: CT, mammography, MRI, ultrasound, X-ray, fluoroscopy, contrast safety and reporting systems (BI-RADS, TI-RADS, Fleischner, Lung-RADS, Bosniak, adrenal washout).

- One file, `index.html`. No build step. Open it in a browser or host it on GitHub Pages.
- Each topic has a **department notes** box. Notes and custom protocols are saved in the browser (localStorage). Use **Back up** and **Restore** to move them between devices.
- TI-RADS and adrenal washout calculators are built in.

## Editing content

All reference topics are in the `TOPICS` array inside `index.html`. Each topic has an `id`, a modality (`mod`), a `title`, a `sum`mary, `tags`, and a list of sections (`secs`). A section can be a `list`, `steps`, `table`, `note` or paragraph (`p`).

## Disclaimer

General reference only. Protocols, doses and thresholds vary between institutions, and guidelines change. Department protocols and current source documents (ACR, Fleischner Society, etc.) take precedence.

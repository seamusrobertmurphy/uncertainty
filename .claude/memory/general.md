# General

- 2026-09-02. The live Quarto Pub site is https://seamusrobertmurphy.quarto.pub/redd-uncertainty-training (id 764ca84c in `_publish.yml`). The older `uncertainty` entry in the same file returns 404 and is dead. Publish with `quarto publish quarto-pub --id 764ca84c-6ffb-41a9-9654-b4f6773c5541 --no-prompt`.
- 2026-09-02. A full `quarto render` takes about 15 minutes and must run bare, never with `--to`. The Word pass screenshots the `sits_view()` leaflet maps in chapter 3 with headless Chrome through chromote, which failed once with "Chrome debugging port not open after 10 seconds"; the chapter 3 setup chunk now sets `options(chromote.timeout = 60)` for that reason.
- 2026-09-02. The chapter 3 data cube figure (`fig-datacube`) is drawn live by a ggplot2 chunk in `03-activity-data/index.qmd`; the old static `assets/images/png/datacube_static_clean.png` is no longer referenced.
- 2026-09-02. The bibliography lacks `Atkinson2012` and `Zhou2016`, which the render reports as citations not found.

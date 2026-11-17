# KOL Shot Assets

KOL model-shot images for the Reel2Pin Pinterest shop (Alice / Frances / Stella).

Hosted here so the 'Quản lý pin' Space can fetch them: the Space's server can
read `raw.githubusercontent.com` but cannot read `muse.ai` file links
(its egress proxy refuses them, 403).

Layout:
- `shots/<design_id>_<kol_id>.jpg` — verified KOL model shots
  (KOL wearing the design, or holding the mug with its message facing camera)
- `flats/<design_id>_flat.jpg` — flat design art on a white background
  (2nd image of the Pinterest carousel; KOL shot is the cover)

Source of truth: `~/workspace/work-reel2pin/kol-import-staging/`
(`import-manifest.json` maps each shot to its campaign, product link and title).
Do not edit files here by hand; regenerate from the pipeline and re-upload.

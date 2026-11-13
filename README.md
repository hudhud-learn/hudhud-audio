# hudhud-audio

Lesson audio for **Hudhud («هدهد»)**, the German/English learning app for Arabic speakers, served with GitHub Pages.

No code here. Layout: `<pack>/<file>.m4a` for the 8 packs (`de_a1` … `en_b2`), each with its own `manifest.json`, plus the full `manifest.json` (size of every file; the app checks sizes after each download).
The iPhone app downloads from `https://hudhud-learn.github.io/hudhud-audio/<pack>/<file>.m4a`. Android gets the same files through Google Play Asset Delivery.

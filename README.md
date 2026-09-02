# blog-assets

Static image assets for the blog series on pathology and AI
(Japanese: https://path-ai-note.blogspot.com / English: separate Blogger site).

Images are hotlinked from the blog posts, e.g.

    https://raw.githubusercontent.com/MrDog1biz/blog-assets/main/003_cot-faithfulness/inline_mentor_fog_nb.webp

## Layout

    <NNN_slug>/<name>.webp   one folder per article, mirroring AI_note/3_articles/drafts/<NNN_slug>/assets/

## Rules

- WebP only, quality 85, max width 1600 px (typically 5-15 KB per illustration).
- ASCII file names. New images (2026-09-02 onward) carry no Japanese text, because one image
  serves both the Japanese and the English blog; text-free illustrations are preferred, English text is fine.
  Legacy figures made before that date with Japanese labels (article 002) are kept for the Japanese
  blog only; their English counterparts carry the `_nb` suffix (Nano Banana 2 remakes).
- Source PNGs (Nano Banana 2 output, Pillow scripts) stay in the AI_note repository.
  This repository holds only the published derivatives.
- Files are generated and pushed with `AI_note/tools/publish-images.py`; do not edit by hand.

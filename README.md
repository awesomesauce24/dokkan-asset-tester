# Dokkan Asset Tester

A GitHub Pages–compatible viewer for **18 known images** associated with Super Saiyan Goku (card 1034871; asset ID 1034870).

## Features
- Nine card artwork images and nine battle LWF texture images
- Filters and filename/path search
- Preview and direct asset links
- Original internal asset paths displayed for each file

## Deploy
On GitHub, open **Settings → Pages → Deploy from a branch → main → /(root)** and save. After GitHub publishes it, the site should be available at:

https://awesomesauce24.github.io/dokkan-asset-tester/

## Important limitations
This is a static GitHub Pages build. It does not use the Python backend, so it cannot create bulk ZIP files or automatically search DokkanDB's authenticated asset catalog. The **Save image** link opens the original file; use your browser's Save Image As option.

The observed battle folder is `ingame/battle/character/00387_folder/`. These are LWF texture images, not complete animations or SFX. Asset URLs may be unavailable or access-controlled by DokkanDB. Respect their access limits and terms.

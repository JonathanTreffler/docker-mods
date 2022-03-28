# Tesseract - Docker mod for nextcloud

This mod adds tesseract-ocr, ocrmypdf and all available language data packages to nextcloud, to be installed/updated during container start.

These dependecies are necessary for the "Full text search - Files - Tesseract OCR" and "Workflow OCR" apps.

In nextcloud docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:nextcloud-tesseract`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:nextcloud-tesseract|linuxserver/mods:nextcloud-mediadc`

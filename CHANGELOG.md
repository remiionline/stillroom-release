# Changelog

All notable changes to Stillroom. Downloads are on the
[releases page](https://github.com/remiionline/stillroom-release/releases).

# Stillroom 0.5.0 — 2026-10-19

## New
- Copy image: press Ctrl+C on an image (or use "Copy image" in its menu or the viewer) and paste it straight into Krita, Photoshop, a chat or anywhere else.
- Quick look: press Space on an image to open it in the viewer, and Space again to close it.
- Source: each image has a Source field in the viewer for where it came from. Web addresses get a button to open them, and "Open source link" appears in the image's menu.
- Search by colour: the palette button next to search filters the view to images whose main colours match the one you pick. Choose a preset or any colour.
- Shift-click a colour in the viewer's palette to find other images with that colour.

## Improved
- Search also looks in each image's source.
- Changing an image's source can be undone with Ctrl+Z.

## Known issues
- The first colour search in a large library takes a while, because Stillroom works out the colours of images you haven't opened yet. Matches appear as it goes, and a note beside the filter shows how many images are left.
- Colour search goes by an image's main colours, so a small accent (a red flower on a mostly white page) doesn't count as a match.
- Copy image works for PNG, JPEG, WebP, GIF and BMP images. AVIF, SVG and ICO can't be copied yet.

# Stillroom 0.4.0 — 2026-10-12

## New
- The Lightbox: a tray on the right edge of the window for gathering references while you work. Drag images in, or use "Add to Lightbox" in an image's menu.
- Show on screen: each Lightbox image floats in its own small window above every other app.
- Drag a floating image to move it; drag its corner or scroll over it to resize it, keeping its proportions.
- Hover over a floating image for an opacity slider; faded images let whatever is underneath show through.
- Lock floating images with the lock button or Ctrl+Alt+L (from any app): they stay put and clicks pass through to the app underneath.
- The Lightbox tray, and each image's position and opacity, are remembered between sessions.
- Automatic updates: Stillroom checks for new versions and installs them when you agree. Settings → Check for updates… checks on demand.
- "New folder…" in the sidebar's + menu creates a folder inside the one you're viewing.

## Improved
- The Open in Explorer button in the top bar now has a folder icon and also works in The Cellar.
- Right-clicking an image, folder, collection or tag opens Stillroom's own menu for it, at the pointer.
- Find duplicates has been removed from the library menu.

## Fixed
- Adding or removing a tag on a single image, changing its author, or starring it can now be undone with Ctrl+Z.
- Right-clicking no longer shows the web browser's menu (with options like Share).

## Known issues
- 0.3.0 can't update itself: install 0.4.0 by hand once, and later updates arrive automatically. Your libraries, tags and notes are kept.
- The beta warnings still apply: back up first, avoid cloud-synced and network folders, and attach Settings → Show log file when reporting a bug.

# Stillroom 0.3.0 — 2026-10-08

First public beta.

## New
- Organize the images already on your disk: your folders are the boards.
- Tags, notes, authors, favorites and collections, all saved alongside your images.
- Search titles, authors, notes and #tags; sort, filter and resize thumbnails.
- A viewer with zoom, pan and each image's colour palette, plus video playback.
- The Cellar sets images aside safely instead of deleting them; Delete moves files to the Recycle Bin.
- Fast with big collections: tested with 30,000-image libraries.
- A log file for bug reports (Settings → Show log file) and a list of third-party licenses (Settings → Third-party licenses).

## Known issues
- Not code-signed: Windows shows "Windows protected your PC" (More info → Run anyway), and PCs with Smart App Control on can't run it.
- Avoid cloud-synced folders and network drives for libraries for now.
- No automatic updates in this version.

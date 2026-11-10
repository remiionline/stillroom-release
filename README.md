<h1 align="center">Stillroom</h1>

<p align="center">
  <strong>A quiet, local library for your visual references.</strong><br>
  Your folders are the boards. Tags, notes and collections on top. Nothing uploaded, no account.
</p>

<p align="center">
  <a href="https://github.com/remiionline/stillroom-release/releases/latest"><strong>⬇ Download Stillroom for Windows</strong></a>
  &nbsp;·&nbsp; Windows 10 / 11 (64-bit) &nbsp;·&nbsp; Free<br>
  <a href="https://stillroom.cc">stillroom.cc</a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stillroom-hero-dark.jpg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stillroom-hero-light.jpg">
  <img src="assets/stillroom-hero-dark.jpg" alt="Stillroom: a library of engravings and celestial charts, with folders, tags and collections in the sidebar and four references gathered in the Lightbox tray">
</picture>

> **New in 0.9.0, the release candidate for 1.0:** drag images out into other apps, drop
> images in from your browser (with the page saved as their Source), grayscale and flip,
> export your library data, and libraries in cloud folders. See the [changelog](CHANGELOG.md)
> for everything.

---

## What it is

Stillroom is a reference manager for artists, designers and anyone who collects
images. It works with the folders already on your disk: point it at a folder and
every subfolder becomes a board. Stillroom adds tags, notes, favorites and
collections on top, without moving your files into a hidden database. Your
images stay ordinary files, and you can still open them in Explorer.

Everything stays on your computer. Stillroom doesn't need an account, doesn't
upload anything, and works offline.

> **Release candidate:** 0.9.0 is the last step before 1.0. Please read
> [Before you start](#before-you-start) before adding a collection you care about.

## Features

**The Lightbox**
- A tray on the right edge of the window. Drag images in from any board, or right-click → **Add to Lightbox**.
- **Show on screen** floats each image in its own small window above every other app, so it stays in view while you paint, model or design.
- Drag to move. Drag the corner or scroll to resize, keeping the proportions. Hover for an opacity slider so the work underneath shows through, and for grayscale and flip buttons.
- **Lock** with the button or **Ctrl+Alt+L** from any app: images stay put and clicks pass straight through to the app underneath.

![The Lightbox: four reference images floating over Krita while an etching is open on the canvas. One reference is faded so the canvas shows through it](assets/stillroom-lightbox-krita.jpg)

![The Lightbox tray on the right of the Stillroom window, holding four references gathered from the board](assets/stillroom-lightbox-tray.jpg)

**Your folders are the library**
- Any folder becomes a library; its subfolders are boards. Keep several libraries open at once.
- Create, rename, move and delete folders from inside Stillroom; the changes happen on disk.
- Live updates: change files in Explorer and Stillroom catches up. Tags and notes follow files that move inside the library.
- Drag files in from Explorer, paste with Ctrl+V, or **drag an image straight from a web page**: it's saved into the folder you're viewing, with the page it came from as its Source.
- Works in **OneDrive, Dropbox, Google Drive and iCloud** folders. Images that are only in the cloud aren't downloaded just to make previews.

**Organize**
- Tags with suggestions, notes that save as you type, author credits, and favorites.
- A **Source** for every image: paste the link it came from and open it again with one click.
- Collections group references from different folders without moving or copying files.
- Drag items into folders and collections, or drag to arrange them in your own order.
- Multi-select for bulk tagging and moving, right-click menus, and **Ctrl+Z** to undo.
- **Drag images out** into Krita, Photoshop, Blender, a chat or a folder: drag a card past the edge of the window, or drag the picture in the viewer.
- **Copy image** (Ctrl+C) puts the picture on the clipboard, ready to paste into Krita, Photoshop or a chat.
- **Export library data:** save every tag, note, author, source, favorite and collection to one readable file.

![A library of engravings and charts: folder tiles, cards with authors and tags, and the sidebar with libraries, collections and tags](assets/stillroom-board.jpg)

![The right-click menu on an image, with Add to Lightbox, Copy image and Open source link](assets/stillroom-right-click.jpg)

**Find**
- Search titles, authors, notes and tags. Type `#tag` to match tags only.
- **Search by colour:** pick a colour and see the images whose main colours match.
- Include subfolders, sort several ways, resize thumbnails.

![Search by colour: "Black" picks out the three darkest prints in the library](assets/stillroom-colour-search.jpg)

![A tag view showing everything tagged "celestial" across folders](assets/stillroom-tag.jpg)

**View**
- A full viewer with zoom, pan, arrow-key browsing and each image's colour palette.
- **Quick look:** press Space on an image to open it, and Space again to close it.
- **Grayscale (G) and flip (H)** for checking values and composition.
- Video playback, with first-frame thumbnails.

![The viewer: Dürer's Rhinoceros, with its tags, its source link, colour palette and file details on the right](assets/stillroom-viewer-source.jpg)

**The Cellar**
- Set media aside instead of deleting it. It leaves boards and search but keeps its tags and notes.
- Every library has its own Cellar, kept inside that library's folder, so set-aside images stay with their library. The Cellar in the sidebar shows them all together.
- Restore it later, back into its own library, or delete it to the Recycle Bin.

![The Cellar: two set-aside images, with Restore and Delete buttons on hover](assets/stillroom-cellar.jpg)

**Built for big collections**
- Tested with 30,000-item libraries. Thumbnails are made in the background.
- Dark, light, or match-your-system theme.

<p>
  <img src="assets/stillroom-light.jpg" width="49%" alt="The board in the light theme">
  <img src="assets/stillroom-viewer-light.jpg" width="49%" alt="The viewer in the light theme">
</p>

## Install

1. Download `Stillroom_X.Y.Z_x64-setup.exe` from the [latest release](https://github.com/remiionline/stillroom-release/releases/latest).
2. Run it. Stillroom isn't code-signed yet, so Windows shows **"Windows protected your PC"**:
   click **More info**, then **Run anyway**.
3. No admin rights are needed. Stillroom installs just for your user account.

If there's no "Run anyway" option, your PC has **Smart App Control** turned on.
It blocks unsigned apps, and Stillroom can't run there until a signed version is
available.

**Requirements:** Windows 10 or 11, 64-bit. Stillroom has so far been tested on Windows 11.

**Uninstall** from *Settings → Apps*. Your folders and images are left untouched.

## Before you start

Stillroom works with real files on your disk.

- **Back up first.** Renaming, moving and deleting in Stillroom changes the real files.
  Keep a copy of any collection you can't replace.
- **Cloud folders work; use each library on one PC at a time.** In OneDrive, Dropbox,
  Google Drive or iCloud, two PCs saving the same library at once can lose tags and
  notes (never images). Stillroom warns you if a library is already open on another PC.
  Network drives aren't recommended.
- **Deleting** from The Cellar moves the file to the Recycle Bin and removes its
  tags and notes. On network drives and some external drives, Windows skips the
  Recycle Bin, so those deletes are permanent.
- **Updates.** From 0.4.0, Stillroom checks for new versions and installs them when you
  agree (or use **Settings → Check for updates…**). If you're on 0.3.0, install the latest version once
  by hand. Updating always keeps your libraries, tags and notes.

## FAQ

**Does Stillroom change or move my files?**
Only when you ask it to: renaming, moving, importing or deleting. Browsing,
tagging and writing notes never touch your images.

**Where are my tags and notes stored?**
In a hidden `.stillroom` folder inside each library, next to your images, so they
travel with the folder. Deleting that folder removes the tags and notes, never the images.

**Does it upload anything or need the internet?**
No. Stillroom works fully offline and has no account, no analytics and no crash
reporting. Nothing about your images, tags or notes leaves your computer. The only
connection it makes (from 0.4.0) is a check here on GitHub for a newer version.

**Which file types are supported?**
PNG, JPEG, WebP, GIF, BMP, AVIF, SVG and ICO images, plus MP4, WebM, M4V, OGV,
MOV and MKV video. Which video codecs play depends on Windows.

**Can I use it on Mac, Linux or iPad?**
Not yet. Windows comes first, and other platforms may follow.

**Can I use my library on two computers?**
Yes, through a cloud folder, as long as only one of them has it open at a time. Close
Stillroom on one PC before opening the library on the other; Stillroom warns you if you forget.

## Report a bug or suggest a feature

Open an [issue](https://github.com/remiionline/stillroom-release/issues/new/choose).
The bug form asks for what we need to fix it.

For bugs, please attach your **log file**: in Stillroom, open **Settings (sliders icon)
→ Show log file**, and drag `stillroom.log` into the issue. It records errors and
may include file and folder names, but never image contents or notes.

## Credits

Stillroom is built with [Tauri](https://tauri.app), [Svelte](https://svelte.dev) and
[SQLite](https://sqlite.org), with icons from [Lucide](https://lucide.dev) and the
[DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) typeface.
The full list of open-source licenses is in the app under **Settings → Third-party licenses**.

The artworks in these screenshots are public-domain works from
[The Metropolitan Museum of Art](https://www.metmuseum.org/about-the-met/policies-and-documents/open-access)
and [Cooper Hewitt](https://www.cooperhewitt.org/open-access-at-cooper-hewitt/) open-access collections.
The Lightbox screenshot shows the free painting app [Krita](https://krita.org).

---

<p align="center"><sub>© 2026 remiionline · Free to download and use</sub></p>

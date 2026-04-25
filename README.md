# Spore-sort
A sh file for spore that copies every PNG inside a file and moves them to their respective places (e.g.: Creature.png goes to creatures folder)
# Installation:
1. Save script as 'spore_sort'
2. Move to /.local/bin
3. Make executable:
```bash
chmod +x spore_sort
```
3. Edit the CREATIONS variable near the top of the script if your 'My Spore Creations' directory is different than what it lists.
# Usage:

1. Download + sort a single adventure and all it's assets by its asset ID:
```bash
spore_sort 123456789012
```
2. Sort all PNGs in a folder:
```bash
spore_sort /path/to/folder
```
(Answer N in prompt)

3. Sort sporecasts (Sorts both any PNGs and extracts all assets from adventures, sorting those too.):
```bash
spore_sort /path/to/folder
```
(Answer Y in prompt)

4.  Dry-run to preview actions (append --dry-run as second argument):

```bash
./spore_sort 123456789012 --dry-run
```
OR
```bash
./spore_sort /path/to/folder --dry-run
```
Meant to be used with SADL or my 'Sporecast-downloader'

SADL: https://github.com/Red-Lattice/spore_adventure_downloader

Sporecast-downloader: https://github.com/Gor995/Sporecast-downloader



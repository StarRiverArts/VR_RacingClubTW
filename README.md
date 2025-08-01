# VRChat WorldInfo by StarRiver

This repository contains two separate toolsets:

## Track Results
Utilities that download racing records from a Google Spreadsheet and
build text or HTML leaderboards. See [`track_results/README.md`](track_results/README.md)
for full usage instructions.

## World Info
A workflow for collecting VRChat world information and approving entries.
It exports a JSON file for use on a website or inside Unity and includes a
simple Tkinter interface for reviewing worlds.
See [`world_info/README.md`](world_info/README.md) for details.
Additional background is available in
[`world_info/complete_guide.zh_TW.md`](world_info/complete_guide.zh_TW.md) (Chinese).

Install dependencies with::

  pip install -r requirements.txt

If creator-world scraping is required, run ``playwright install`` after installing the packages.

For Traditional Chinese instructions, read
[`README.zh_TW.md`](README.zh_TW.md).

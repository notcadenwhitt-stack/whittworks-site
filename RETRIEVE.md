# Corkboard bug screenshots

67 screenshots (`corkboard-bug-screenshots.zip`, ~26MB) of the WhittWorks
Studios corkboard site (`notcadenwhitt-stack.github.io/whittworks-CorkboardTesting-site/`)
showing a scroll-position rendering glitch — the board's tiles fail to
paint as it scrolls, leaving content cut off against a flat orange
background.

Captured 2026-08-09 around 3:27–3:28 PM in Opera on macOS. The originals
were ~7MB retina PNGs (439MB total, over GitHub's 100MB per-file limit);
these are JPEGs scaled to 1800px on the long edge, which keeps the glitch
plainly legible. Files are numbered `shot-01.jpg` … `shot-67.jpg` in the
capture order of the original filenames.

This branch exists purely to move the files between machines. It has no
relation to the site's actual codebase and should not be merged.

## To retrieve

```bash
git clone --branch corkboard-bug-screenshots --single-branch https://github.com/notcadenwhitt-stack/whittworks-site.git corkboard-bug-screenshots
cd corkboard-bug-screenshots
unzip corkboard-bug-screenshots.zip
```

That extracts a `corkboard-bug-screenshots/` folder with all 67 JPEGs
(macOS `__MACOSX` metadata cruft already stripped).

## To delete this branch once retrieved

```bash
git push origin --delete corkboard-bug-screenshots
git branch -D corkboard-bug-screenshots
```

The branch is an orphan — it shares no history with `main` or the corkboard
work — so deleting it leaves the rest of the repo untouched.

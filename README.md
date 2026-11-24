# muse-vacuum-entry

[![Competition](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![Rank](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/tachyon0215/muse-vacuum-entry/rank.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![Reward](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/tachyon0215/muse-vacuum-entry/reward.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)

Entry for the make.fun competition [The Robot Vacuum's Best Excuse](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214).

## The entry

> I skipped the corner because my map says a sock lives there now, and frankly, it has earned the territory.

Three candidates were drafted and compared against the judge brief (a one-line excuse from the vacuum itself, rooted in its sensors, map and dock, funny on first read with a clean turn at the end). This one won: the excuse comes straight from the vacuum's own map, keeps a small machine's straight face, and turns on 'earned the territory' at the close. The alternatives (a cliff sensor fearing the void; load-bearing dust) were broader gags less rooted in the vacuum's world.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks the character limit, not only whitespace, no padding spaces, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 8bf03248c62e57e390f2fdf8e9a12257a01e3c2d09c00d902276dd6fead2da18).

## License

MIT — see [LICENSE](LICENSE).

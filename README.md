# GPROXY Scoop bucket

[![Tests](https://github.com/LeenHawk/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/LeenHawk/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/LeenHawk/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/LeenHawk/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) manifests for [GPROXY](https://github.com/LeenHawk/gproxy),
an open-source AI API gateway. They install the portable ZIPs from the stable
GitHub releases, for x64 and ARM64. Excavator checks for new stable releases
every four hours.

```pwsh
scoop bucket add gproxy https://github.com/LeenHawk/scoop-bucket
scoop install gproxy/gproxy            # CLI with the web console: gproxy
scoop install gproxy/gproxy-headless   # CLI without the web console: gproxy-headless
scoop install gproxy/gproxy-desktop    # Desktop application (Start menu shortcut)
```

Update with `scoop update`, not with GPROXY's own updater. GPROXY Desktop and
GPROXY CLI are also in the Microsoft Store:
`winget install --id 9P2FJRB9RS4Z --source msstore` (Desktop),
`winget install --id 9NBMH3S5K0L9 --source msstore` (CLI).

Report problems with GPROXY itself at <https://github.com/LeenHawk/gproxy/issues>.

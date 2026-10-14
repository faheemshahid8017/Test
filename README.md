# all-repos-code

Source-code dump of multiple open-source repositories.

## Contents

The archive is split into **6 volumes** (`.001` - `.006`) because the
original `all-repos-code.txt` is 219.5 MB, which exceeds GitHub's 100 MB
per-file limit.

| File | Size |
|------|------|
| all-repos-code.7z.001 - .005 | 5,242,880 bytes each |
| all-repos-code.7z.006 | 2,840,359 bytes |

Total: 29,054,759 bytes = `all-repos-code.7z` (contains all-repos-code.txt, 230,162,774 bytes)

## How to extract

1. Download **all 6** files into the same folder.
2. Double-click `all-repos-code.7z.001` - 7-Zip handles the volumes automatically.

No manual joining is required.

### CLI alternative

```bash
cat all-repos-code.7z.00? > all-repos-code.7z
7z x all-repos-code.7z
```

## Note on source

The archive contains code from third-party open-source projects. Their
respective licenses and copyright notices are retained inside the archive.

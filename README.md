# 35196

## Current behavior

Despite using `separateMinorPatch=true`, Renovate skips patch versions and jumps to the next minor version.

Current update path: `3.4.7` -> `3.5.22`

The same would apply to `3.5.0` -> `3.5.22`


## Expected behavior

Expected update path: `3.4.7` -> `3.5.0`

The same would be expected for `3.5.0` -> `3.5.1`

## Link to the Renovate issue or Discussion

👉 https://github.com/renovatebot/renovate/discussions/35196
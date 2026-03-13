# scipp-pixi-macos-install

Minimal reproduction when installing `scipp>25.12.0` via `pixi` on macOS.

## Goal

Provide a small public repository with a failing GitHub Actions workflow that can
be linked from an upstream issue.

## Expected result

The macOS CI job successfully installs `scipp>25.12.0` via `pixi`.

## Actual result

The macOS CI job fails during installation `scipp>25.12.0` via `pixi`.

## Files

- `.github/workflows/scipp-pixi-macos-install.yml` — dedicated CI workflow

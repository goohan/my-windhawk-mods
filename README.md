# DockLike: available-space layout comparison

Raw taskbar-region captures from 2026-11-14, using Windows 11 Taskbar Styler 1.11.1. The thin yellow outline is a screen-capture indicator.

- `docklike-before-1200-center.png`: current upstream theme, taskbar parent temporarily constrained to 1200 DIPs for overflow testing.
- `docklike-after-1200-center.png`: proposed theme in the same 1200-DIP test area. Start, Task View and overflow are excluded from the app counts: 1 visible app before, 13 after.
- `docklike-before-full-center-clean.png`: current upstream theme at the primary monitor's full 2560-pixel width.
- `docklike-after-full-center-clean.png`: proposed theme at full width, centered in the space left of the tray.

These captures use the guide theme, rather than the user's cosmetic overrides. The full-width captures were taken after closing Settings, so there is one fewer running app than in the 1200-DIP comparison. No app icons were resized to force overflow; only the parent test area was constrained. No screenshot content was retouched.
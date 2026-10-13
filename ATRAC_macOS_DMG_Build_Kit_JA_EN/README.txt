ATRAC macOS DMG build kit (Japanese + English)

This is a BUILD KIT, not a finished DMG. A real macOS app and DMG must be built on macOS.

1. Upload the two .pyw files to the root of your GitHub repository.
2. Upload .github/workflows/build-macos-dmg.yml preserving the folders.
3. In GitHub > Actions > Build ATRAC macOS DMG > Run workflow.
4. After successful completion, download two separate DMG artifacts from the run.

The source files come from the latest CD one-button launcher archive.
Requirements: GitHub Actions macOS runner, access to internet for Python packages.
This workflow does not sign or notarize the app. macOS Gatekeeper may block first launch.
This build does not bundle FFmpeg, ffprobe, ffplay, or atracdenc. Features relying on these binaries may need them installed separately.
No macOS runtime testing has been performed here. CD launcher uses the macOS Music app.

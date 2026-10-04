# AI Fotograaf Pro

Offline Android photo-processing app foundation.

## GitHub APK build
The workflow in `.github/workflows/build-apk.yml` installs the required Android SDK packages on the GitHub runner, installs Gradle 8.9, builds the debug APK, and uploads it as a workflow artifact.

## Current app
- Up to 100 images can be selected.
- Processing is local/offline.
- Results are written to `Pictures/AI Fotograaf Pro`.
- The current image engine is a basic local enhancement foundation. The advanced offline AI models still need to be integrated as a separate next step.

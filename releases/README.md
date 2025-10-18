# Releases Directory

This directory contains APK files for Checkingo application releases.

## Directory Structure

Each version should follow this naming convention:
```
checkingo-v<version>.apk
```

Example:
- `checkingo-v1.0.0.apk`
- `checkingo-v1.1.0.apk`
- `checkingo-v2.0.0-beta.apk`

## Adding a New Release

1. Place the APK file in this directory with the appropriate version name
2. Create a GitHub release with:
   - Version tag (e.g., v1.0.0)
   - Release title
   - Release notes describing changes
   - Attach the APK file as a release asset

## Version Numbering

Follow semantic versioning:
- MAJOR.MINOR.PATCH (e.g., 1.0.0)
- Add suffixes for pre-releases: `-alpha`, `-beta`, `-rc` (e.g., 1.0.0-beta)

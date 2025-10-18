# Contributing to Checkingo Releases

## Purpose

This repository is exclusively for hosting APK releases of the Checkingo application. 

## Guidelines

### What Belongs in This Repository
- ✅ Official Checkingo APK files (.apk)
- ✅ Release notes and documentation
- ✅ Version information

### What Does NOT Belong in This Repository
- ❌ Source code (belongs in main application repository)
- ❌ Build scripts or configuration files
- ❌ Development tools or dependencies
- ❌ Test files
- ❌ Documentation unrelated to releases

## Adding a New Release

### Step 1: Prepare the APK
1. Build and test the APK thoroughly
2. Name the file using the convention: `checkingo-v[VERSION].apk`
   - Example: `checkingo-v1.0.0.apk`

### Step 2: Create a GitHub Release
1. Go to the [Releases](../../releases) page
2. Click "Draft a new release"
3. Create a new tag with version number (e.g., `v1.0.0`)
4. Set the release title (e.g., "Checkingo v1.0.0")
5. Use the template from `.github/RELEASE_TEMPLATE.md` for release notes
6. Attach the APK file to the release
7. Mark as pre-release if applicable (alpha, beta, RC)
8. Publish the release

### Step 3: Verification
- Verify the APK downloads correctly
- Test installation on an Android device
- Ensure release notes are complete and accurate

## Version Numbering

Follow [Semantic Versioning](https://semver.org/):
- **MAJOR**: Incompatible API changes or major updates
- **MINOR**: New functionality in a backwards-compatible manner
- **PATCH**: Backwards-compatible bug fixes

Examples:
- `v1.0.0` - Initial release
- `v1.1.0` - New features added
- `v1.1.1` - Bug fixes
- `v2.0.0-beta` - Major update beta version

## Security

- Only authorized maintainers should publish releases
- All APKs must be signed with the official signing key
- Include checksums (MD5/SHA256) in release notes for verification

## Questions?

For questions about the release process, please contact the repository maintainers.

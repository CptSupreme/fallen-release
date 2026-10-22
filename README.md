# Fallen Covenant — game downloads

This public repository distributes downloadable game packages for the existing Fallen Covenant Electron launcher. Game source and development remain in the project repository.

## Testing channel

- `game-testing` is a prerelease containing the current signed `manifest.json`.
- Immutable `game-v<version>` prereleases contain `manifest.json` and SHA-256-named `.gz` objects.
- Launcher clients verify the Ed25519 manifest signature and each compressed and installed file before running game code.
- Game packages do not contain player saves or account profiles.

No game release has been published by this initialization commit. Publishing a testing package requires a separately approved, signed build. Stable releases must not be published without owner approval.

The repository must remain public for anonymous launcher downloads. Never upload private signing keys, repository access tokens, player saves, or private development logs.

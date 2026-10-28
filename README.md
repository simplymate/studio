# Simplymate Studio

Releases der Desktop-App Simplymate Studio für macOS und Windows. Der Quellcode ist nicht öffentlich; dieses Repository enthält nur die
veröffentlichten Fassungen (Reiter Releases) und die Kanaldateien des Updaters (`channels/`).

Releases of the Simplymate Studio desktop app for macOS and Windows. The source code is not public; this repository only holds the
published versions (Releases tab) and the updater channel files (`channels/`).

- Jede Datei eines Releases steht mit ihrer SHA-256 in `SHA256SUMS`; Update-Dateien tragen eine Ed25519-Signatur (`.sig`).
- Every release file is listed with its SHA-256 in `SHA256SUMS`; update files carry an Ed25519 signature (`.sig`).
- Homebrew (`brew install --cask simplymate/tap/studio`) folgt mit der ersten signierten Fassung / follows with the first signed version.

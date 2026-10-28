# Homebrew tap for Thumbdesk

Installs the Thumbdesk host agent on a Mac (Apple Silicon, macOS 13 or later), as the Thumbdesk app with its menu-bar item, plus the `thumbdesk` command:

```
brew install --cask yashagldit/thumbdesk/thumbdesk
```

Then pair it with the Thumbdesk mobile app: `thumbdesk pair`.

The cask installs the notarized disk image from each release, which carries SHA-256 checksums and Sigstore (cosign) bundles. It is updated by the release workflow; do not edit it here.

Website: https://thumbdesk.com

# Homebrew tap for Trickle

[Trickle](https://github.com/swsususu/Trickle) is a macOS menu bar power
monitor: live power flow, battery health, and charging status.

```bash
brew install --cask swsususu/tap/trickle
```

Trickle is not notarised, so macOS refuses to open it the first time.
Homebrew does not work around this. Right-click the app and choose Open, or:

```bash
xattr -dr com.apple.quarantine /Applications/Trickle.app
```

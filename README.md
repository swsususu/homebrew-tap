# swsususu/tap

Homebrew casks for my macOS apps.

| App | Install | What it is |
|---|---|---|
| [GifTrim](https://github.com/swsususu/GifTrim) | `brew install --cask swsususu/tap/giftrim` | GIF maker with screen and iPhone recording, captions, a `giftrim` CLI and an MCP server for AI agents |
| [Trickle](https://github.com/swsususu/Trickle) | `brew install --cask swsususu/tap/trickle` | Menu bar power monitor: live power flow, battery health, charging status |

Neither app is notarised, so macOS refuses to open them the first time.
Homebrew does not work around this. Right-click the app and choose Open, or:

```bash
xattr -dr com.apple.quarantine /Applications/GifTrim.app
xattr -dr com.apple.quarantine /Applications/Trickle.app
```

# lw-zsh-versions
Version information of development tools used by Lunar Way developers

## file formats
Supports the following formats:
* Raw binary executable
* tar.gz archive where the extracted binary name executable corresponds to the `$BINARY` variable in lw-zsh

Examples:
```bash
# Direct raw binary fetched from lunarway/shuttle
lunarway/shuttle shuttle
# tar.gz archive fetched from bitnami-labs/sealed-secrets where the executable is named kubeseal
bitnami-labs/sealed-secrets kubeseal
```
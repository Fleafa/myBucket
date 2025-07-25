# My Scoop Bucket

[![Tests](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml)

My bucket for [Scoop](https://scoop.sh), the Windows command-line installer.
- For [NewRecruit](https://www.newrecruit.eu/), the wargames list-building web app
  - [NewRecruit Builder](https://www.newrecruit.eu/download/): desktop app
  - [NewRecruit Editor](https://www.newrecruit.eu/download/): desktop data editor
- [OneTagger](https://onetagger.github.io/) ID3 tagging software
- [Zen Browser](https://zen-browser.app/) Firefox-based browser with vertical tabs, and other innovations.

## How do I install these manifests?

```pwsh
scoop bucket add <bucketname> https://github.com/Fleafa/myBucket
scoop install <bucketname>/<manifestname>
```

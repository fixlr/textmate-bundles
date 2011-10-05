A collection of TextMate bundles that I use
distributed as a git repo.

## Getting Started

Backup or delete your current TextMate bundles if you have already installed
some manually. The instructions below assume you are setting up a fresh
TextMate install.

```shell
mkdir -p ~/Library/Application\ Support/TextMate
cd ~/Library/Application\ Support/TextMate
git clone git://github.com/fixlr/textmate-bundles.git Bundles
cd Bundles
git submodule init
git submodule update
osascript -e 'tell app "TextMate" to reload bundles'
```

## Updating

```shell
git pull
git submodule init
git submodule update
```

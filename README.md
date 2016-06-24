# macosx-finder-hidden-files
MacOSX show/hide hidden files. Automator workflows.

Helpers to fast show/hide hidden files in Finder.

To show hidden files need execute next bash script
```bash
defaults write com.apple.finder AppleShowAllFiles YES
killall Finder
```

To hide hidden files it's the same script but `AppleShowAllFiles NO`.


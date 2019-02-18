# MAC-Free-and-Lock-the-Dock

## Lock the dock
Open a terminal and enter
```
defaults write com.apple.Dock position-immutable -bool yes; killall Dock
```

## Free the dock
Open a terminal and enter
```
defaults write com.apple.Dock size-immutable -bool no; killall Dock
```

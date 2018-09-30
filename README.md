# Xcode-Themes

## A Nascent Collection of Xcode Colour Themes

## Installation

1. Make sure `~/Library/Developer/Xcode/UserData/FontAndColorThemes` exists, if it doesn't, create it:

```bash
DIR="${HOME}/Library/Developer/Xcode/UserData/FontAndColorThemes"

if [[ ! -d "$DIR" ]]; then
    echo "Does not exist. Create and cd to dir"
    mkdir "$DIR" && cd "$_"
else
    echo "Already exists, cd..."
    cd "$DIR" >/dev/null  2>&1 || echo "Error: failed to cd to $DIR!"
fi
```

2. Copy a `.xccolortheme` file into the directory mentioned above.
3. Restart Xcode.
4. Select the new theme in the Fonts and Colors pane in Xcode's Preferences.

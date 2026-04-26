# Iosevka Custom

This repository contains packaged TrueType builds of a custom Iosevka font family.

## Contents

The repository is organized into two distributable font sets:

- `TTF/`: hinted TrueType fonts
- `TTF-Unhinted/`: unhinted TrueType fonts

Both directories currently contain these styles:

- `IosevkaCustom-Regular.ttf`
- `IosevkaCustom-Italic.ttf`
- `IosevkaCustom-Bold.ttf`
- `IosevkaCustom-BoldItalic.ttf`
- `IosevkaCustom-Condensed.ttf`
- `IosevkaCustom-CondensedItalic.ttf`
- `IosevkaCustom-CondensedBold.ttf`
- `IosevkaCustom-CondensedBoldItalic.ttf`

## Which Folder To Use

Use `TTF/` if you want the standard hinted build for general desktop usage.

Use `TTF-Unhinted/` if you prefer unhinted outlines for environments where hinting is unnecessary or handled differently by the renderer.

## Why Use It For Coding

This font family is well suited to programming work for a few practical reasons:

- Clear monospace alignment helps code blocks, indentation, and terminal output stay easy to scan.
- Distinct letterforms reduce confusion between commonly mixed characters such as `0` and `O`, or `1`, `l`, and `I`.
- Narrower shapes, especially in the condensed styles, let you fit more code on screen without switching to an unreadably small size.
- Italic and bold variants make syntax highlighting, emphasis, and editor UI states more consistent.
- Iosevka-style geometric forms tend to stay crisp in editors with dense text layouts and long coding sessions.

## Installation

### macOS

1. Open either `TTF/` or `TTF-Unhinted/`.
2. Select the `.ttf` files you want.
3. Double-click a font file and choose **Install Font**, or drag the files into Font Book.

### Linux

1. Copy the desired `.ttf` files into `~/.local/share/fonts/`.
2. Refresh the font cache with `fc-cache -f`.

### Windows

1. Open the target font directory.
2. Select the `.ttf` files.
3. Right-click and choose **Install** or **Install for all users**.

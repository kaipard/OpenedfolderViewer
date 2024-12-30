# Openedfolder Viewer

A VSCode extension that displays the files in the currently opened folder in Windows Explorer style.

## Features

- Flat view of files and folders
- Customizable file icons
- File extension filtering
- Easy navigation

## Custom Icons

You can customize file icons by placing SVG files in the `resources` folder. The extension will automatically match icons based on file extensions.

### How to use custom icons:
1. Create a `.svg` file named after the file extension (e.g., `json.svg`, `ts.svg`)
2. Place the SVG file in the `resources` folder
3. The extension will automatically use the custom icon for matching file types

Example:
- For `.json` files: `resources/json.svg`
- For `.ts` files: `resources/ts.svg`

## Ignoring File Types

You can configure the extension to ignore specific file types by modifying the settings.

### How to ignore file types:
1. Open VSCode settings (`Ctrl+,`)
2. Search for "Openedfolder Viewer"
3. Find the "Ignored Extensions" setting
4. Add or remove file extensions as needed

Example:
- To ignore `.meta` files: `.meta`
- To ignore `.log` files: `.log`
- To ignore multiple extensions: `.meta`, `.log`, `.tmp`

## Installation

1. Open the Extensions view in VSCode (`Ctrl+Shift+X`)
2. Search for "Openedfolder Viewer"
3. Click Install

## Usage method
1. Find "Openedfolder Viewer" in the sidebar explorer view
2. Click to view the current workspace file
3. Click the file to open for editing
4. click the back button to navigate back
5. click the forward button to navigate forward
6. click the home button to navigate to the root folder

## License

[MIT](LICENSE) 
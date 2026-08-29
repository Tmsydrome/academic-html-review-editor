# Academic HTML Review Editor

A lightweight, offline, single-file HTML editor for academic revision tracking and structured AI comments.

## Features

- Runs locally in a modern browser with no installation or server.
- Tracks additions and deletions with semantic `<ins>` and `<del>` markup.
- Supports Chinese IME input, selection replacement, undo/redo, and change visibility.
- Provides persistent text-marking mode with seven high-visibility color presets.
- Includes a freehand drawing pen with adjustable stroke width, arbitrary color selection, and a size-matched circular cursor.
- Attaches structured editing requests to selected text as comments.
- Exports either a revision-and-comments HTML or a clean-and-comments HTML.
- Provides light, eye-care green, wood, dark, and custom editor themes.
- Exports with a white document background regardless of the editor theme.
- Uses a compact start screen and reveals the complete editing toolbar after import.

## Usage

1. Download `index.html`.
2. Open it with Chrome, Edge, or Firefox.
3. Drag an HTML manuscript into the page or choose **Import HTML**.
4. Revise text or select text and add an AI editing comment.
5. Choose the desired export type and export the HTML.

All processing occurs locally in the browser. No document content is uploaded.

## Notes

- The undo/redo history lasts for the current browser session.
- Imported HTML files that use relative image paths should remain beside their original asset folders after export.
- Only import HTML from sources you trust. Imported scripts are blocked inside the editor sandbox, but the original HTML content is retained in exported files.

## 中文说明

这是一个离线运行的单文件 HTML 学术修订工具，支持增删留痕、中文输入、撤销重做、连续文本标记、自由画笔、定点批注，以及修订批注版和清洁批注版导出。双击 `index.html` 即可使用，无需安装或联网。

## License

MIT

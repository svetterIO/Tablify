# Tablify

Turn raw lists into ready-to-paste tables. Tablify is a static GitHub Pages tool for converting values such as `IP:port` lists into formats for Excel, Word, CSV, or custom delimiters.

## Features

- Comma- or semicolon-separated lists
- One item per line
- Direct paste from Excel / Google Sheets ranges (tab-separated cells and rows)
- Mixed whitespace/table input is flattened left-to-right, top-to-bottom
- Preserves original order
- Configurable 1-20 columns
- One-click format buttons for Excel, Word, CSV, and Custom
- Built-in usage guides for Excel, Word, CSV, and Custom modes
- Excel / TSV copy and download
- Rich Word table copy and HTML download
- CSV with proper quoting
- Custom delimiters, including `TAB`, `\t`, and `SPACE`
- No server and no dependencies
- Input data stays in the browser

## Publish on GitHub Pages

1. Create a repository.
2. Upload `index.html` to the repository root.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose your main branch and `/ (root)`.
6. Save.

The site will then be available at the GitHub Pages URL shown in the Pages settings.

## Local use

You can open `index.html` directly. Clipboard functionality is most reliable when the page is served over HTTPS (GitHub Pages does this automatically).

## Excel note

The Excel mode uses TSV because it pastes cleanly into spreadsheet cells and opens in Excel. It does not create a binary legacy `.xls` workbook.

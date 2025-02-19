# CSV Vertical Merger

[![ja](https://img.shields.io/badge/lang-japanese-blue.svg)](README.ja.md)
[![en](https://img.shields.io/badge/lang-english-blue.svg)](README.md)

A simple, single-file HTML application to vertically merge multiple CSV files.

## Features

*   **Merge multiple CSV files:** Combine multiple CSV files with different columns.
*   **Handle different column structures:**  Automatically handles CSV files even if they have different columns. Missing values are filled with blanks.
*   **Preview:** Preview the merged data before downloading.
*   **Sort:** Sort the merged data by any column (ascending or descending).
*   **File Name Column:** Adds a "file" column to indicate the original file of each row.
*   **Drag and Drop:** Drag and drop CSV files to upload.
*   **File List Ordering**:  Change the file merging order by dragging and dropping the files in the file list.
*   **Error Handling:** Displays error messages for invalid files or CSV parsing errors.
*   **Preview Row Control:** You can select to preview the "First N rows", "Last N rows" or "All rows".
*   **Single HTML file:** No external dependencies, just a single HTML file.
*   **Client-side processing:** No server-side processing, all merging is done in your browser.
*   **Bilingual (English/Japanese):** UI is in both English and Japanese.

## Demo
(Add a link to a live demo if you have one, e.g., using GitHub Pages)

## Usage

1.  Open `CSV Vertical Merger.html` in your browser.
2.  Drag and drop CSV files into the designated area, or click "Select Files" to upload.
3.  (Optional) Drag and drop files in the file list to change the merging order.
4.  Click the "Merge" button.
5.  (Optional) Select a column and order to sort the preview.
6.  Click "Apply Sort" or "Do Not Apply Sort" and "Save as CSV" button to download the merged CSV file.

## Screenshots

![Initial State](images/screenshot1.png)  
*Initial State*

![Files Uploaded](images/screenshot2.png)  
*Files Uploaded*

![After Merging](images/screenshot3.png)
*After Merging, Preview is shown*

![After Sorting](images/screenshot4.png)
*After Sorting*

![Error Example](images/screenshot5.png)
*Example of an error message*

## Requirements

*   A modern web browser (Chrome, Firefox, Safari, Edge, etc.)

## How it Works

This application is built with HTML, CSS, and JavaScript. It uses the following:

*   **HTML:** Structure of the application.
*   **CSS:** Styling and layout.
*   **JavaScript:** File handling, CSV parsing, merging, sorting, preview, and download.
*    **SortableJS**: For the drag and drop file list
*   **Google Fonts (Zen Maru Gothic):** For a modern and readable font.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

## License
MIT License (or your preferred license).

---
## 日本語

# CSV Vertical Merger (CSV縦結合ツール)

複数のCSVファイルを縦方向に結合する、シンプルな単一HTMLファイルのアプリケーションです。

## 特徴

*   **複数CSVファイルの結合:** 異なる列を持つ複数のCSVファイルを結合できます。
*   **異なる列構造に対応:** 列が異なる場合でも、すべての列を保持したまま自動的に結合します。 欠損値は空白で埋められます。
*   **プレビュー:** ダウンロード前に結合されたデータをプレビューできます。
*   **ソート:** 結合されたデータを任意の列でソートできます (昇順/降順)。
*   **ファイル名列:** 各行の元のファイルを示す "file" 列を追加します。
*   **ドラッグ＆ドロップ:** CSVファイルをドラッグ＆ドロップしてアップロードできます。
*   **ファイルリストの並び替え:** ドラッグ＆ドロップでファイルリストの並び順を変えることで、結合順を変更できます。
*   **エラー処理:** 無効なファイルやCSV解析エラーの場合にエラーメッセージを表示します。
*    **プレビュー行数制御:** 「先頭からN行」「末尾からN行」「すべて」を選択してプレビュー表示を調整できます。
*   **単一HTMLファイル:** 外部依存関係なし、単一のHTMLファイルのみ。
*   **クライアントサイド処理:** サーバーサイド処理なし、すべての結合はブラウザ内で行われます。
*   **バイリンガル (英語/日本語):** UIは英語と日本語の両方に対応しています。

## デモ
(GitHub Pagesなどを使用してライブデモがある場合は、ここにリンクを追加してください)

## 使用方法

1.  ブラウザで `CSV Vertical Merger.html` を開きます。
2.  CSVファイルを指定された領域にドラッグ＆ドロップするか、「ファイルを選択」をクリックしてアップロードします。
3.  (オプション) ファイルリスト内のファイルをドラッグ＆ドロップして、結合順序を変更します。
4.  「結合」ボタンをクリックします。
5.  (オプション) 列と順序を選択して、プレビューをソートします。
6.  「ソートを反映」または「ソートを反映しない」ボタンと「CSV保存」ボタンをクリックして、結合されたCSVファイルをダウンロードします。

## スクリーンショット

![初期状態](images/screenshot1.png)
*初期状態*

![ファイルアップロード後](images/screenshot2.png)
*ファイルアップロード後*

![結合後](images/screenshot3.png)
*結合後、プレビュー表示*

![ソート後](images/screenshot4.png)
*ソート後*

![エラー例](images/screenshot5.png)
*エラーメッセージの例*

## 動作環境

*   モダンなウェブブラウザ (Chrome, Firefox, Safari, Edgeなど)

## 仕組み

このアプリケーションは、HTML、CSS、JavaScriptで構築されています。以下のものを使用しています。

*   **HTML:** アプリケーションの構造
*   **CSS:** スタイルとレイアウト
*   **JavaScript:** ファイル処理、CSV解析、結合、ソート、プレビュー、ダウンロード
*   **SortableJS**: ドラッグ＆ドロップ可能なファイルリストのため
*   **Google Fonts (Zen Maru Gothic):** モダンで読みやすいフォントのため

## 貢献

貢献は大歓迎です！ issueのオープンやプルリクエストの送信をお気軽にどうぞ。

## ライセンス

MITライセンス (またはお好みのライセンス)

---
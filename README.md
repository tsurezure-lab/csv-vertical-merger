# CSV Vertical Merger | CSV縦結合ツール

<!-- 言語選択リンク -->
[English](#english) | [日本語](#日本語)

---

<!-- English Section -->

<a id="english"></a>
## CSV Vertical Merger (English)

This is a simple, single-file HTML application that allows you to merge multiple CSV files vertically (appending rows).  It's designed to be user-friendly and handle various CSV formats, even with differing columns.

### Features

*   **Drag and Drop:** Easily add CSV files by dragging and dropping them onto the designated area. You can also click the drop area to select files.
*   **File List Reordering:** Change the order in which files are merged by dragging and dropping them in the file list.
*   **Handles Different Column Structures:**  Automatically merges CSV files even if they have different columns. Missing values are filled with blanks.
*   **Preview:**  Preview the merged data before downloading, with options to show the first N rows, last N rows, or all rows.
*   **Sorting:** Sort the merged data by any column (ascending or descending) before downloading.
*   **"file" Column:**  Automatically adds a "file" column to the merged data, indicating the source file for each row.
*   **Error Handling:** Displays error messages for invalid files or CSV parsing errors, and identifies the problematic file.
*   **Single HTML File:**  No external dependencies, just a single, self-contained HTML file.
*   **Client-side Processing:**  All merging and processing happens within your browser; no data is sent to a server.
*   **Bilingual (English/Japanese):** The user interface is presented in both English and Japanese.

### Usage

![CSV Vertical Merger Screenshot](images/screenshot.png)
*CSV Vertical Merger in action*

1.  Open `CSV Vertical Merger.html` in a modern web browser (no server required).
2.  Add CSV files using either:
    *   **Drag and Drop:** Drag CSV files from your file explorer and drop them onto the area labeled "Drop CSV files here | または | or Select Files".
    *   **File Selection:** Click the "Select Files | ファイルを選択" label to open a file selection dialog.
3.  (Optional) Reorder files in the list by dragging them. This determines the order in which they will be merged.
4.  Click the "Merge | 結合" button.
5.  (Optional) Preview and sort the merged data:
    *   **Preview Options:** Choose to preview "First N rows", "Last N rows", or "All rows". Enter the number of rows (N) in the input box.
    *   **Sort:** Click on a column header in the preview to sort by that column.  Click again to reverse the sort order.  You can also use the "Sort by" and "Order" dropdowns and the "Sort" button.
6.  Choose whether to apply the sorting to the downloaded file using the "Apply Sort | ソートを反映" / "Do Not Apply Sort | ソートを反映しない" button.
7.  Click the "Save as CSV | CSV保存" button to download the merged CSV file.

### Technologies Used

*   HTML
*   CSS (with Google Fonts - Zen Maru Gothic)
*   JavaScript (using SortableJS for drag-and-drop functionality)

### License

This project is licensed under the MIT License.

### Author

tsurezure_lab

---

<!-- Japanese Section -->

<a id="日本語"></a>
## CSV Vertical Merger (日本語)

これは、複数のCSVファイルを縦方向（行を追加する形）に結合できる、シンプルで単一のHTMLファイルで構成されたアプリケーションです。異なる列を持つCSVファイルでも、ユーザーフレンドリーに扱えるように設計されています。

### 特徴

*   **ドラッグ＆ドロップ:** CSVファイルを指定された領域にドラッグ＆ドロップすることで簡単に追加できます。 ドロップエリアをクリックしてファイルを選択することも可能です。
*   **ファイルリストの並べ替え:** ファイルリスト内でファイルをドラッグ＆ドロップすることで、結合する順序を変更できます。
*   **異なる列構造に対応:** 列が異なるCSVファイルでも、自動的に結合します。欠損値は空白で埋められます。
*   **プレビュー:** ダウンロード前に結合されたデータをプレビューできます。「先頭からN行」、「末尾からN行」、または「すべて」の行を表示するオプションがあります。
*   **ソート:** ダウンロード前に、結合されたデータを任意の列でソートできます（昇順/降順）。
*   **"file" 列:** 各行のソースファイルを示す "file" 列が自動的に追加されます。
*   **エラー処理:** 無効なファイルやCSV解析エラーが発生した場合、エラーメッセージを表示し、問題のあるファイルを特定します。
*   **単一HTMLファイル:** 外部依存関係なし、単一のHTMLファイルで完結します。
*   **クライアントサイド処理:** すべての結合と処理はブラウザ内で行われます。データがサーバーに送信されることはありません。
*   **バイリンガル (英語/日本語):** ユーザーインターフェースは英語と日本語で表示されます。

### 使用方法
![CSV Vertical Merger スクリーンショット](images/screenshot.png)
*CSV Vertical Mergerの動作中の様子*

1.  モダンなウェブブラウザで `CSV Vertical Merger.html` を開きます (サーバーは不要です)。
2.  CSVファイルを以下のいずれかの方法で追加します。
    *   **ドラッグ＆ドロップ:**  CSVファイルをファイルエクスプローラーから「ここにCSVファイルをドロップ | Drop CSV files here」と書かれたエリアにドラッグ＆ドロップします。
    *   **ファイル選択:** 「ファイルを選択 | Select Files」ラベルをクリックして、ファイル選択ダイアログを開きます。
3.  (オプション) リスト内のファイルをドラッグして、ファイルの順序を並べ替えます。 これは、ファイルが結合される順序を決定します。
4.  「結合 | Merge」ボタンをクリックします。
5.  (オプション) 結合されたデータをプレビューし、ソートします。
    *   **プレビューオプション:** 「先頭からN行」、「末尾からN行」、「すべて」のいずれかを選択してプレビューします。 行数 (N) は入力ボックスに入力します。
    *   **ソート:** プレビュー内の列ヘッダーをクリックすると、その列でソートします。 もう一度クリックすると、ソート順が逆になります。 「ソート列」と「順序」のドロップダウンと「ソート」ボタンを使用することもできます。
6.  「ソートを反映 | Apply Sort」/「ソートを反映しない | Do Not Apply Sort」ボタンを使って、ダウンロードするファイルにソートを適用するかどうかを選択します。
7.  「CSV保存 | Save as CSV」ボタンをクリックして、結合されたCSVファイルをダウンロードします。

### 使用技術

*   HTML
*   CSS (Google Fonts - Zen Maru Gothic を使用)
*   JavaScript (ドラッグ＆ドロップ機能に SortableJS を使用)

### ライセンス

このプロジェクトはMITライセンスの下で公開されています。

### 作者

tsurezure_lab
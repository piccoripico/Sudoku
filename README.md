# Sudoku (Single HTML Concept)

> **開発コンセプト / Development Concept**  
> このプロジェクトは、**`Sudoku.html` 単体を開くだけでローカル環境で遊べる**ことを最優先に設計しています。  
> This project is designed with one priority: **you can play locally by simply opening `Sudoku.html`**.

---

## 日本語

### 概要
この Sudoku は、インストール不要・ビルド不要・サーバー不要で動く、ブラウザ向けの数独ゲームです。  
`Sudoku.html` を直接ブラウザで開けば、そのままプレイできます。

### 起動方法（ローカル）
1. このリポジトリをダウンロードします。
2. `Sudoku.html` をダブルクリック、またはブラウザにドラッグ＆ドロップします。
3. すぐにプレイ開始できます。

### 操作方法
- **数字入力**: `1`〜`9`
- **消去**: `0` / `Backspace` / `Delete`
- **セル移動**: 矢印キー
- **メモ切替**: `Enter`（✏️ボタンでも切替可）
- **Undo / Redo**: `Ctrl+Z` / `Ctrl+Y`（`Ctrl+Shift+Z`）

### 主な機能
- 新しい盤面の生成（ヒント数・シード指定）
- タイマー計測
- メモ入力
- 重複警告
- 完成ハイライト
- ヒント / リセット / 解答表示

### このプロジェクトが向いているケース
- 「HTML 1ファイルで完結するサンプル」を探している
- 教育用途や配布用途で、実行手順を最小化したい
- オフラインでも手軽に数独を遊びたい

---

## English

### Overview
This Sudoku game runs directly in your browser with **no installation, no build process, and no local server**.  
Just open `Sudoku.html` and start playing.

### How to Run (Local)
1. Download this repository.
2. Open `Sudoku.html` by double-clicking it, or drag & drop it into your browser.
3. Play immediately.

### Controls
- **Input numbers**: `1` to `9`
- **Clear a cell**: `0` / `Backspace` / `Delete`
- **Move selection**: Arrow keys
- **Toggle notes mode**: `Enter` (or the ✏️ button)
- **Undo / Redo**: `Ctrl+Z` / `Ctrl+Y` (`Ctrl+Shift+Z`)

### Key Features
- Generate new puzzles (hint count / seed)
- Timer tracking
- Pencil notes
- Duplicate conflict warning
- Completion highlight
- Hint / Reset / Show solution

### Best For
- People looking for a **single-file HTML Sudoku** example
- Educational or distribution use cases with minimal setup
- Quick offline play without any tooling

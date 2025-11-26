# プロジェクトをZIP化してGitHubにアップロード

## 📁 プロジェクトの場所

プロジェクトフォルダは以下にあります：
- `C:\Users\kiris\.cursor\study-abroad-comparison`

---

## 📦 ステップ1: エクスプローラーでフォルダを開く

### 方法A: アドレスバーから直接開く

1. **エクスプローラーを開く**（Windowsキー + E）
2. **アドレスバーをクリック**
3. **以下のパスを入力してEnter**：
   ```
   C:\Users\kiris\.cursor\study-abroad-comparison
   ```

### 方法B: 順番にフォルダを開く

1. **エクスプローラーを開く**（Windowsキー + E）
2. **左側のナビゲーションパネルで**：
   - 「PC」→「C:」→「Users」→「kiris」→「.cursor」→「study-abroad-comparison」
   - ⚠️ `.cursor`フォルダは隠しフォルダの可能性があります

### 方法C: ファイル名で検索

1. **エクスプローラーを開く**（Windowsキー + E）
2. **検索ボックスに「study-abroad-comparison」と入力**
3. **フォルダが見つかったら開く**

---

## 📦 ステップ2: フォルダをZIP化

1. **`study-abroad-comparison`フォルダが開いた状態で**：
   - フォルダ内で何も選択しない（フォルダ全体をZIP化するため）

2. **フォルダをZIP化**：
   - **方法A**: フォルダの親フォルダ（`.cursor`）に戻る
     - アドレスバーで「.cursor」まで戻る
     - `study-abroad-comparison`フォルダを右クリック
     - 「送る」→「圧縮（zip形式）フォルダー」を選択
   
   - **方法B**: フォルダ内のすべてのファイルを選択
     - `Ctrl + A` で全選択
     - 右クリック → 「送る」→「圧縮（zip形式）フォルダー」

3. **ZIPファイルが作成される**
   - ファイル名：`study-abroad-comparison.zip`
   - 場所：`.cursor`フォルダ内、または同じ場所

---

## 🌐 ステップ3: GitHubでリポジトリを作成

1. **ブラウザで以下を開く**：
   - https://github.com/new

2. **リポジトリ情報を入力**：
   - Repository name: `sappy-study-abroad`（好きな名前）
   - Description: （空欄でもOK）
   - Public または Private を選択
   - ⚠️ **重要**: 以下のチェックボックスは**すべて外す**
     - ❌ Add a README file
     - ❌ Add .gitignore
     - ❌ Choose a license

3. **「Create repository」をクリック**

---

## 📤 ステップ4: ZIPファイルをアップロード

1. **リポジトリページで「uploading an existing file」をクリック**
   - または、ページに表示されるリンクをクリック

2. **ZIPファイルをドラッグ＆ドロップ**
   - 作成した`study-abroad-comparison.zip`ファイルを
   - ブラウザウィンドウにドラッグ＆ドロップ
   - ブラウザが自動的に展開します

3. **「Commit changes」をクリック**

---

## ✅ 完了！

これで、プロジェクトがGitHubにアップロードされました！

---

## 🆘 フォルダが見つからない場合

もし`study-abroad-comparison`フォルダが見つからない場合：

1. **Cursorでプロジェクトを開いているか確認**
   - Cursorでファイルが開いている場合、そのファイルの場所を確認

2. **Cursorのファイルエクスプローラーから確認**
   - Cursorの左側のファイルエクスプローラーで
   - プロジェクトのルートフォルダを右クリック
   - 「Reveal in File Explorer」や「フォルダーをエクスプローラーで表示」を選択

---

**まずは、エクスプローラーのアドレスバーに `C:\Users\kiris\.cursor\study-abroad-comparison` と入力して開いてみてください！**


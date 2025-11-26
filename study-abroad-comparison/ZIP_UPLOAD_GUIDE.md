# ZIPファイルからGitHubにアップロードする方法

## 🎯 最も簡単な方法

この方法なら、Gitコマンドを使わずにアップロードできます。

---

## 📦 ステップ1: プロジェクトフォルダをZIP化

1. **エクスプローラーを開く**
   - Windowsキー + E

2. **以下のフォルダに移動**
   - `C:\Users\kiris\.cursor\study-abroad-comparison`

3. **フォルダ全体を選択**
   - `Ctrl + A` を押す

4. **ZIP化**
   - 右クリック → 「送る」→ 「圧縮（zip形式）フォルダー」
   - または、フォルダを右クリック → 「送る」→ 「圧縮（zip形式）フォルダー」

5. **ZIPファイルが作成される**
   - 場所：`C:\Users\kiris\.cursor\study-abroad-comparison.zip`
   - または、デスクトップなど

---

## 🌐 ステップ2: GitHubで新しいリポジトリを作成

1. **ブラウザで以下を開く**
   - https://github.com/new

2. **リポジトリ情報を入力**
   - Repository name: `sappy-study-abroad`（好きな名前）
   - Description: （空欄でもOK）
   - Public または Private を選択
   - ⚠️ **重要**: 以下のチェックボックスは**すべて外す**
     - ❌ Add a README file
     - ❌ Add .gitignore
     - ❌ Choose a license

3. **「Create repository」をクリック**

---

## 📤 ステップ3: ZIPファイルをアップロード

1. **リポジトリページで「uploading an existing file」をクリック**
   - または、直接 https://github.com/kirishio1019-jpg/リポジトリ名/upload にアクセス

2. **ZIPファイルを展開してアップロード**
   - 方法A: ZIPファイルをドラッグ＆ドロップ
     - ブラウザが自動的に展開します
   - 方法B: ZIPファイルを解凍して、フォルダ内のファイルをアップロード
     - 解凍したフォルダから、すべてのファイルを選択
     - ドラッグ＆ドロップ

3. **「Commit changes」をクリック**

---

## ✅ 完了！

これで、プロジェクトがGitHubにアップロードされました！

---

## 📝 注意事項

- **`.git`フォルダはアップロードしないでください**
  - アップロード前に削除するか、`.gitignore`で除外
- **`node_modules`フォルダも大きいので除外推奨**
  - 通常、`.gitignore`で除外されます

---

## 🔄 今後の更新方法

今後、コードを更新する場合：

1. **GitHub Desktopでリポジトリをクローン**
   - または、Cursorで直接GitHubからクローン

2. **変更をコミット＆プッシュ**

---

**この方法なら、Gitコマンドで悩む必要がありません！試してみてください！**


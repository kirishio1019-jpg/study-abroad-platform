# 不要なフォルダを除外してZIP化

## 🎯 問題

`.next`や`node_modules`などのフォルダが原因でZIP化が失敗する場合があります。

---

## ✅ 解決方法：必要なファイルだけをZIP化

### 方法1: ターミナルで除外してZIP化

以下のコマンドを実行します（`.next`と`node_modules`を除外）：

```powershell
cd C:\Users\kiris\.cursor
$files = Get-ChildItem -Path study-abroad-comparison -Exclude .next,node_modules,.git | Where-Object { $_.Name -ne '.next' -and $_.Name -ne 'node_modules' -and $_.Name -ne '.git' }
Compress-Archive -Path $files.FullName -DestinationPath study-abroad-comparison.zip -Force
```

---

### 方法2: GitHubに直接ファイルをアップロード

ZIP化が難しい場合、GitHubのWebインターフェースから直接ファイルをアップロードすることもできます。

---

### 方法3: GitHub Desktopで解決

GitHub Desktopを使えば、Gitの問題を回避して簡単にアップロードできます。

1. **GitHub Desktopをダウンロード**
   - https://desktop.github.com/

2. **リポジトリを追加**
   - File → Add local repository
   - `C:\Users\kiris\.cursor` を選択

3. **変更をコミット**
   - 変更されたファイルをステージング
   - コミットメッセージを入力
   - 「Commit to main」をクリック

4. **GitHubリポジトリを作成**
   - 「Publish repository」をクリック
   - リポジトリ名を入力

---

## 🎯 推奨：GitHub Desktopを使用

ZIP化で問題が発生する場合、**GitHub Desktop**を使うのが最も簡単です。


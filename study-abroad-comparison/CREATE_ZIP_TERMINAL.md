# ターミナルでZIPファイルを作成する方法

## 🎯 最も簡単な方法：PowerShellでZIP化

Cursorのターミナルを使って、ZIPファイルを作成します。

---

## 📦 ステップ1: Cursorのターミナルを開く

1. **Cursorの下部のターミナルパネルをクリック**
   - または `Ctrl + ~` を押す

2. **ターミナルが開きます**

---

## 📦 ステップ2: ZIPファイルを作成

以下のコマンドをコピー＆ペーストして実行：

```powershell
cd C:\Users\kiris\.cursor
Compress-Archive -Path study-abroad-comparison -DestinationPath study-abroad-comparison.zip -Force
```

これで、`C:\Users\kiris\.cursor\study-abroad-comparison.zip` ファイルが作成されます。

---

## 📦 ステップ3: ZIPファイルの場所を確認

作成されたZIPファイルは以下にあります：
- `C:\Users\kiris\.cursor\study-abroad-comparison.zip`

このファイルをGitHubにアップロードします。

---

## 🌐 ステップ4: GitHubにアップロード

1. **ブラウザで以下を開く**
   - https://github.com/new

2. **新しいリポジトリを作成**
   - Repository name: `sappy-study-abroad`
   - Public または Private を選択
   - チェックボックスはすべて外す

3. **「Create repository」をクリック**

4. **リポジトリページで「uploading an existing file」をクリック**

5. **ZIPファイルをドラッグ＆ドロップ**
   - ファイル：`C:\Users\kiris\.cursor\study-abroad-comparison.zip`
   - ブラウザが自動的に展開します

6. **「Commit changes」をクリック**

---

## ✅ 完了！

これで完了です！

---

## 🆘 コマンドが実行できない場合

もしコマンドが実行できない場合、以下の手順を試してください：

1. **ターミナルで現在のディレクトリを確認**
   ```powershell
   pwd
   ```

2. **プロジェクトフォルダに移動**
   ```powershell
   cd C:\Users\kiris\.cursor
   ```

3. **フォルダが存在するか確認**
   ```powershell
   Test-Path study-abroad-comparison
   ```
   - `True` と表示されれば存在します

4. **ZIPファイルを作成**
   ```powershell
   Compress-Archive -Path study-abroad-comparison -DestinationPath study-abroad-comparison.zip -Force
   ```

---

**まずは、Cursorのターミナル（`Ctrl + ~`）を開いて、上記のコマンドを実行してみてください！**


# GitHubパーソナルアクセストークンの作成方法

## 🔐 ステップバイステップガイド

### ステップ1: GitHubにアクセス

1. **ブラウザで以下を開く**
   - https://github.com/settings/tokens
   - または、GitHub → 右上のアイコン → **Settings** → 左下の **Developer settings** → **Personal access tokens** → **Tokens (classic)**

### ステップ2: 新しいトークンを作成

1. **「Generate new token (classic)」をクリック**
   - または、「Generate new token」→「Generate new token (classic)」

2. **情報を入力**
   - **Note**: 「Cursor Git」や「Git Push」など、分かりやすい名前
   - **Expiration**: 
     - 「90 days」（90日間有効）
     - または「No expiration」（無期限）⚠️ セキュリティ上、期限を設定することを推奨

3. **権限（Scopes）を選択**
   - ✅ **repo** にチェック
     - これでリポジトリへの読み書きアクセスが許可されます
   - 他は不要です（デフォルトのままでもOK）

4. **「Generate token」をクリック**

### ステップ3: トークンをコピー

1. **表示されたトークンをコピー**
   - 例：`ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxx`
   - ⚠️ **重要**: このページを離れると、もうトークンを見ることができません！
   - テキストエディタなどに一時的に保存してください

---

## 🔑 トークンの使用例

Cursorで認証が求められたら：

- **ユーザー名**: `kirishio1019-jpg`
- **パスワード**: コピーしたトークンを貼り付け

通常のGitHubのパスワードではなく、このトークンを使用します。

---

## ✅ 作成完了後

トークンを作成したら：

1. **Pullを実行**（`Ctrl + Shift + P` → 「Git: Pull」）
2. **認証情報を入力**
   - ユーザー名：`kirishio1019-jpg`
   - パスワード：作成したトークン
3. **成功したら、Pushを実行**

---

**トークンを作成したら、Pullを再試行してください！**


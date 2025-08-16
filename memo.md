# Git 日常操作メモ

日常的な push/pull の手順をまとめています。

---

```bash
# 1. 最新状態を取得 (Pull)
git pull origin main
# ※ブランチ名は master または main を使用

# 2. 変更をステージ (Add)
git add .
# ※特定ファイルだけ追加する場合は git add <ファイル名>

# 3. コミット (Commit)
git commit -m "変更内容の説明"
# ※日本語ファイル名や特殊文字がある場合は " " で囲む

# 4. GitHub に反映 (Push)
git push origin master
# ※初回 push の場合は -u オプションを付けると便利
# git push -u origin master

# 💡 ポイント
# - 作業の基本は「Pull → Edit → Add → Commit → Push」
# - ブランチ名を間違えないように注意
# - Markdown やコードファイルも同じ手順で管理可能
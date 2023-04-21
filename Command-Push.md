# Gitのプッシュ

## リポジトリ作成時のみ
```sh
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin "<リポジトリのSSH>"
git push -u origin main
```

## ブランチをつくる場合（推奨）
```sh
git switch -c "<git-flow>/<ブランチ名>"
git add "<file>"
git commit -m "<メッセージ>"
git push --set-upstream origin "<git-flow>/<ブランチ名>"
```

## 既存のブランチを使う場合
```sh
git switch "<git-flow>/<既存のブランチ名>"
git add "<file>"
git commit -m "<メッセージ>"
git push --set-upstream origin "<git-flow>/<既存のブランチ名>"
```

## ゴミ
```sh
git switch -c "<git-flow>/<ブランチ名>"
git add "<file>"
git commit -m "<メッセージ>"
git remote add origin "<リポジトリのSSH>"
git push --set-upstream origin "<git-flow>/<ブランチ名>"
```

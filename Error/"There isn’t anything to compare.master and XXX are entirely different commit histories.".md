# There isn’t anything to compare.master and XXX are entirely different commit histories.
## 原因
「git clone」をしないで、pushしたからだと考えられる
## 解決方法
素直にcloneする
```sh
git switch -c "<git-flow>/<ブランチ名>"
git add "<file>"
git commit -m "<メッセージ>"
git remote add origin "<リポジトリのSSH>"
git push --set-upstream origin "<git-flow>/<ブランチ名>"
```

## 参考
[Githubでプルリクをするとき"There isn't anything to compare"といわれたときの対処法](https://qiita.com/mikumikumikumiku/items/3353018c72a1bf306f21)

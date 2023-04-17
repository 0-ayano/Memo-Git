# fatal: Not a valid object name: 'master'.
## 原因
- 新しいリポジトリに初めてpushする際には、最低1回はマスターブランチにコミットする必要があるから
- 新しいリポジトリに初めてpushする際に、新しいブランチでpushしようとしたから
## 解決方法
1. 空コミットを送る
2. 初期ブランチがmainなら、masterのところを変えて実行
```sh
git commit --allow-empty -m "xxx"
git push origin master
```

## 参考
[【Git】fatal: Not a valid object name: 'master'.の解決方法](https://qiita.com/Sakuya_wd/items/b83161111b1b28098008)

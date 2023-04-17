# fatal: unable to access 'https://github.com/username/location.git/': The requested URL returned error: 403
## 原因
- Gitのアクセストークンの生成をしていない、または条件を間違えて生成したから
## 解決方法
1. Gitの「Settings > Developer settings > Personal access tokens (classic)」に移動する
2. Generate new token の Generate new token(classic)を選択する
3. NoteとExpiration timeを決めたら、Select scopesの全てにチェックを入れる（本当は考えてチェックを入れないといけない）
4. Generate tokenを押してから、一度だけ表示されるアクセストークンをコピーする
5. このエラーが起こったコマンドを再度入力して、Github名とアクセストークンの記入が求められるので記入する

## 参考
[[Solved] fatal: unable to access 'https://github.com/username/location.git/': The requested URL returned error: 403](https://namespaceit.com/blog/fatal-unable-to-access-the-requested-url-returned-error-403)

# Github/Gitに関する設定
## Gitの初期設定
```sh
git config --global user.namse "<Name>"             
git config --global user.email "<MailAdress>"
git config --global http.proxy "<HttP_Proxy:Port>"
git config --global https.proxy "<HttPs_Proxy:Port>"
git config --list
```

## プロキシの設定
### 追加
```sh
git config --global http.proxy http://cproxy.okinawa-ct.ac.jp:8080
git config --global https.proxy http://cproxy.okinawa-ct.ac.jp:8080
```

### 削除
```sh
git config --global --unset http.proxy
git config --global --unset https.proxy
```

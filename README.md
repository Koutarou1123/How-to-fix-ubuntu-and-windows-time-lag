# How-to-fix-ubuntu-and-windows-time-lag

## 概要
このリポジトリは私がwindowsにubuntu20.04をデュアルブートした際時間がずれてしまったのでそのズレの解消のコマンド．
---

### 環境
- Linux
- Ubuntu20.04

---
1.手順 [ubuntuとwindowsをデュアルブートしたとき時間がずれたらこれを打つ](https://qiita.com/yoshinyan/items/d56a56414f2d21814f88)

command
```
sudo timedatectl set-local-rtc true
```

# REFERENCE
---
1. https://qiita.com/yoshinyan/items/d56a56414f2d21814f88

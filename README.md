# Windows利用Fileサーバ構築

## Linuxサーバを構築

### 必要サービス
- samba
- owncloud

### セキュリティ面
- firewallは起動しておく
- rootログイン禁止
- パスワードポリシー
- 準管理アカウント追加
- モデムのポートは起動しない
- sshは基本的にポートを開かない

### 設計案
- google Driveをマウントする

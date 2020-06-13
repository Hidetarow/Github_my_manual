# Github my manual
## ローカルリポジトリ
- ローカルリポジトリを新規作成する。  
git init
- リポジトリの状態を確認する。  
git status
- ステージングエリアに登録する。  
git add file_name
- コミットを実行する。  
git commit  
git commit -m "text"
- 履歴を確認する。  
git log

## 公開鍵の設定(Github)
- 公開鍵の設定  
ssh-keygen -t rsa b 4096 -C "mail_address@_"  
 - 注意_パスワードはGithubとは別もの
- 公開鍵をクリップボードにコピー  
clip < /c/Users/folder/.ssh/id_rsa.pub
- 設定できているか確認  
ssh -T git@github.com

ブランチを作成する。
## git branch branch_name

ブランチを確認する。
## git branch

ブランチをチェックアウトする。
## git checkout branch_name

ブランチに対する操作を確認する。
#" git diff master

## git init > .gitフォルダが作成される。
## git init > .gitフォルダが作成される。
## git init > .gitフォルダが作成される。
.

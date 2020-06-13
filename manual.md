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

## リモートリポジトリ
- 公開鍵の設定(ssh)  
ssh-keygen -t rsa b 4096 -C "mail_address@"  
 - 注意_パスワードはGithubとは別もの
- 公開鍵をクリップボードにコピー  
clip < /c/Users/folder/.ssh/id_rsa.pub
- githubの設定で SSH Keysを設定する。
- 設定できているか確認  
ssh -T git@github.com
- Github上のリポジトリを複製する(Fork;フォーク)
- リモートリポジトリをクローンする(ローカルに落とす)  
サイトからclone URLをコピー。  
https/ssh はclone with sshを選択。  
git clone コピーしたURL  

## ローカルリポジトリ→リモートリポジトリ
- GithubサイトからNewリポジトリ作成, httpsのurlをゲットする。
- Git bush で以下を入力  
git remote add origin ゲットしたurl
- 確認  
git remote -v


## ブランチ
- ブランチを作成する。  
git branch branch_name

- ブランチを確認する。  
git branch

- ブランチをチェックアウトする。  
git checkout branch_name

- ブランチに対する操作を確認するよ。  
git diff master

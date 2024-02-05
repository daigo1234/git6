# git6
｛リポジトリのプッシュ｝
git init
git add README.md
git add compose.yml
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:daigo1234/git7.git
git push -u origin main
[error]
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.

｛リポジトリに講師を招待｝
git6にながの先生を招待済み
git tag 3.1
git push --tags
[error]
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.

{データベースサーバの構築}
mySQLにログイン
Dockerfileを作成
docker-compose.ymlを作成
接続確認手順書（docker-mysql.md)とする
　→構築したデータベースサーバへの接続手順
  →mysqlへの接続手順


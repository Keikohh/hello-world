# これまで学んだgitの機能とコマンド
git init
gitの初期化
git status
ワークツリーのステータスを表示
git config 
設定周りの確認・変更
git log
ログを表示
-- onelineでコミットメッセージの1行のみの一覧表示
git diff
ファイルの差分を表示
git add
ステージングエリアに追加
git commit 
コミットの実行
git commit --amend --no-edit
コミットの修正
git checkout
削除されたファイルを復旧や過去コミットの復元など
git reset
コミットのリセット
git revert
「コミットの変更を打ち消す」コミット
git rm
ファイルとindex情報の削除
git clone
レポジトリをコピー
git pull
リモートレポジトリの同期	
git push
変更をアップロードする
git request-pull
プルリクエスト：変更依頼
git remote
リモートレポジトリの設定
git branch
ブランチの作成
git checkout
ブランチの切り替え
git merge
ブランチの統合
--ff-only: fast forward only. 変更のない統合先ブランチにマージ（参考）
git clone
レポジトリをコピー
git push
変更をアップロードする

**githubフローについて**

githubフローとは，mainブランチから開発用のブランチを分岐させ，変更をmainブランチにマージする流れのことである．
開発用のブランチで変更を行った後にプルリクエストを送信し，レビューを依頼する．
そして，承認されたらmainブランチにマージし，変更を反映させる．

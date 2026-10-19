ここにgithubまとめを入れる
変更したファイルを記録対象に追加します。　git add .  →　確認したい　git status 緑色で表示される
git log 　　Author(作者) アカウント名<メールアドレス> Date(日付) 最後に改行があって : で終わる :を抜け出したい q　を押す
ユーザー変更  git config --global user.name "アカウント名" そのアカウントでのメアドを入れる（変える）
git commit --amend --reset-author --no-edit 直前のコミット内容を、エディタを開かずに（Author）情報や日時をリセットして上書き修正するコマンド(pushしている場合)は原則NG
git push origin fix/remove/opening-link  fix/remove/opening-link という作業用ブランチを、GitHub（origin）へ送信して保存する」 という意味


git init リポジトリの初期化と作成
git add .　全てのファイルをまとめて追加  
git add ファイル名　　　特定のファイルを追加する場合
git commit -m "コメント" 何を変更したのかを"?/?"書く　-mはmessageの略
git status 今どのファイルが変更されて、ステージされているか　緑色で表示される
git remote -v リポジトリ名を確認する時
git pull origin main リモートの最新状態を取得
git stash   作業途中で別の枝へ一時退避
git stash pop 退避させた作業を復元
git branch -a　他の人が作ったブランチを確認
git log 1 --format="%an <%ae>" コミット名義を確認


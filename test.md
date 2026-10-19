ここにgithubまとめを入れる
変更したファイルを記録対象に追加します。　git add .  →　確認したい　git status 緑色で表示される
git commit -m "test.mdを追加した"  -mはmessageの略 "コメント"
git log 　　Author(作者) アカウント名<メールアドレス> Date(日付) 最後に改行があって : で終わる :を抜け出したい q　を押す
ユーザー変更  git config --global user.name "アカウント名" そのアカウントでのメアドを入れる（変える）
git commit --amend --reset-author --no-edit 直前のコミット内容を、エディタを開かずに（Author）情報や日時をリセットして上書き修正するコマンド(pushしている場合)は原則NG
git push origin fix/remove/opening-link  fix/remove/opening-link という作業用ブランチを、GitHub（origin）へ送信して保存する」 という意味


git pull origin main リモートの最新状態を取得
git stash   作業途中で別の枝へ一時退避
git stash pop 退避させた作業を復元
git branch -a　他の人が作ったブランチを確認

|コマンド等|説明| 
| :--- | :--- |
|git --version|バージョン確認|
|git blame <ファイル名>|ファイルの中身を表示する|
|git config --unset <キー>|ローカルで設定したキーを削除する(※キー:user.nameなど)|
|git config --global --unset <キー>|グローバルで設定したキーを削除する(※キー:user.nameなど)|
|git config --list|ローカルのconfig設定値を確認する|
|git config --global --list|グローバルのconfig設定値を確認する|
|git add --dry-run .|git addで何が実行されるか表示|
|git citool|GUIのコミット画面が表示される|
|git add -p|変更があったファイルの編集画面が開き、各行を部分的にaddする|
|git reset <ファイル名>|ステージングエリアの変更を無かったことにする|
|git reset HEAD <ファイル名>|ステージングエリアの変更を無かったことにする(HEAD付き)|
|git branch <新ブランチ名> <元ブランチ or SHA1 ID>|元ブランチまたはSHA1 IDの地点から新ブランチを作成する|
|git branch -d <ブランチ名>|ブランチを削除する|
|git branch -m <旧ブランチ名> <新ブランチ名>|ブランチ名をリネームする|
|git branch --contains <タグ名>|指定したタグを含むブランチを表示する|
|git reflog|git操作をした直後のHEADの地点をSHA1 IDで表示する|
|git checkout -b <新ブランチ> <元ブランチ or SHA1 ID>|元ブランチまたはSHA1 IDの地点から新ブランチを作成してチェックアウトする|
|git checkout -- <ファイル名>|そのファイルに最後にコミットされた状態にチェックアウトする|
|git checkout <SHA1 ID>|SHA1 IDのコミットにチェックアウトする|
|git checkout master|master(最後にコミットしたところ)にチェックアウトする|
|git checkout <タグ名>|タグのコミットにチェックアウトする|
|git checkout HEAD <ファイル名>|ワークツリーの<ファイル名>の変更分を削除してHEADにチェックアウトする|
|git stash|現在ブランチの作業中の内容を一時保存する|
|git stash list|一時保存した作業内容を一覧表示する|
|git stash pop|一時保存した作業内容を復活させる|
|git rm <ファイル名>|ファイルを削除しステージングエリアに反映する|
|git mv <ファイル1> <ファイル2>>|ファイル1をファイル2にリネームしてステージングエリアに反映する|
|git log --stat|ログと共に、変更されたファイルを表示|
|git log --shortstat --oneline|履歴をコミットごとに1行で表示して、各コミットで変更されたファイルのリストを1行で表示する|
|git log --parents --abbrev-commit|SHA1 IDを省略して親コミットと共にログを表示する|
|git log --patch|パッチ(変更内容)と共にログを表示する|
|git log --stat|ファイルの変更量と共にログを表示する|
|git log --patch-with-stat|git log --patchとgit log --statを合わせてログを表示する|
|git log --reverse|逆順でログを表示する|
|git log -N|N番目までのログを表示する|
|git log --relative-date|何日前にコミットされたかでログを表示する|
|git log <ファイル名>|特定のファイルのログのみ表示|
|git log --graph --decorate --pretty=oneline --all --abbrev-commit|ブランチ分岐も表現しつついい感じに全てのコミットログを表示する|
|git config --global alias.lol "log --graph --decorate --pretty=oneline --all --abbrev-commit"|git lolでいい感じのログを出すようにエイリアスをグローバルに設定する|
|git log --oneline --decorate --simplify-by-decoration --all|「どのブランチで」「どのタグで」の情報と共にログを表示する|
|git rev-parse HEAD|HEADををSHA1 IDに変換する|
|git rev-parse master|masterをSHA1 IDに変換する|
|git rev-parse :/"コメント"|指定したコメントを含むコミットのSHA1 IDを表示する|
|git rev-parse --tags=<タグ名>|<タグ名>に該当するSHA1 IDを表示する(<タグ名>は正規表現も可能)|
|git show <SHA1 ID>|SHA1 IDのコミット内容を表示する|
|git show <タグ名>|タグのコミット内容を表示する|
|git tag <タグ名> -m "コメント" <SHA1 ID>|SHA1 IDのコミットにコメント付きでタグを打つ|
|git tag -d <タグ名>|タグを削除する|
|git commit --amend -m "コメント"|直前のコミットを上書きする形でコミットする|
|git branch -v|SHA1 IDと共にブランチを表示する|




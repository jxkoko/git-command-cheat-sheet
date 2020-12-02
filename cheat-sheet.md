|コマンドなど|説明| 
| :--- | :--- |
|git --version|バージョン確認|
|git blame <ファイル名>|ファイルの中身を表示する|
|git config --global --unset <キー>|設定したキーを削除する(※キー:user.nameなど)|
|git add --dry-run .|git addで何が実行されるか表示|
|git citool|GUIのコミット画面が表示される|
|git add -p|変更があったファイルの編集画面が開き、各行を部分的にaddする|
|git reset <ファイル名>|ステージングエリアの変更を無かったことにする|
|git checkout -- <ファイル名>|そのファイルに最後にコミットされた状態にチェックアウトする|
|git checkout <SHA1 ID>|SHA1 IDのコミットにチェックアウトする|
|git checkout master|master(最後にコミットしたところ)にチェックアウトする|
|git checkout <タグ名>|タグのコミットにチェックアウトする|
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
|git rev-parse HEAD|HEADををSHA1 IDに変換する|
|git rev-parse master|masterをSHA1 IDに変換する|
|git rev-parse :/"コメント"|指定したコメントを含むコミットのSHA1 IDを表示する|
|git show <SHA1 ID>|SHA1 IDのコミット内容を表示する|
|git show <タグ名>|タグのコミット内容を表示する|
|git tag <タグ名> -m "コメント" <SHA1 ID>|SHA1 IDのコミットにコメント付きでタグを打つ|
|git tag -d <タグ名>|タグを削除する|
|git commit --amend -m "コメント"|直前のコミットを上書きする形でコミットする|



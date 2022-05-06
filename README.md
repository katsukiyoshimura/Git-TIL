# Git-TIL
学んだことのアウトプット
5/2
リポジトリの作成

5/4 Atomをインストール
cd: ディレクトリの移動
ls: ディレクトリの内容を表示
mkdir: ディレクトリを新規作成
echo: 文字の入力　echo "hello" >>readme.md と入力するとatomに反映される
　　　　　　　　　　echo "hello" と入力するとターミナルに表示される
cat: cat readme.mdとするとatomに反映されている内容が表示される

5/6 git init: gitディレクトリを作成する
　　 git clone: GitHub上にあるプロジェクトをコピー
   　git add: 変更をステージに追加する
    git commit: 変更を記録する
    git status: 変更を確認する
   git diff: 何を変更したかを確認する
   (git add前: git diff 後: git diff --staged)
   git log: 変更履歴を確認する
   git rm <ファイル名>: ファイル削除を記録する
   git rm --cached <ファイル名>: リポジトリの見から削除
   git mv <旧ファイル> <新ファイル>: ファイルの移動を記録する
   git push origin master: GitHubにプッシュする

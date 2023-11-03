# vitaを使ってweb制作の開発環境を構築する
## node.jsをインストールする。
nodenv、homebrewなどのバージョン管理ツールを使うと後々便利。
推奨バージョンを選択してインストールする。
## vscodeでnode.jsのバージョンを確認する
今回はv20.7.0を使用（2023/10月最新）
`node -v`
上記のコマンドをたたいてバージョンが表示されたらnode.jsが入っているとこになる。
バージョンが出ない時はインストールされてないので確認する。
## vscodeのターミナルでviteをインストール
yarnコマンドを使用（npmでもOKだがコマンドが違うので注意する）
``
`npm init vite@latest`


Ok to proceed? (y) y
√ Project name: ... test-project
√ Select a framework: » Vanilla
√ Select a variant: » JavaScript

Done. Now run:

  cd test-project
  npm install
  npm run dev

npm install

npm run dev


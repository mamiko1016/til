# vitaを使ってweb制作の開発環境を構築する
## node.jsをインストールする。
今回はバージョン管理のツールは使わずにグローバルのインストールした。
推奨バージョンを選択。
## vscodeでnode.jsのバージョンを確認する→v20.7.0
`node -v`
上記のコマンドでエラーが出て、npmコマンドも認識されなかった。
▼ターミナルのエラーの記述
npm : 用語 'npm' は、コマンドレット、関数、スクリプト ファイル、または操作可能なプ
ログラムの名前として認識されません。名前が正しく記述されていることを確認し、パスが
含まれている場合はそのパスが正しいことを確認してから、再試行してください。
発生場所 行:1 文字:1
調べたとこと


npm : 用語 'npm' は、コマンドレット、関数、スクリプト ファイル、または操作可能なプ
ログラムの名前として認識されません。名前が正しく記述されていることを確認し、パスが
含まれている場合はそのパスが正しいことを確認してから、再試行してください。
発生場所 行:1 文字:1

npm init vite@latest

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


# TryGitHubOsakana
## はじめに
※この辺は既に読んでいる前提
- [サルでもわかる Git入門 〜バージョン管理を使いこなそう〜](https://backlog.com/ja/git-tutorial/)
- [今日からはじめるGitHub 〜 初心者がGitをインストールして、プルリクできるようになるまでを解説](https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000)
  - [自分用 Git For Windowsのインストール手順](https://qiita.com/toshi-click/items/dcf3dd48fdc74c91b409)

## やってほしいこと
- 自分のローカルに，このリポジトリを`clone`する
- 自分の名前（ローマ字）で`branch`を作成する  
例：「**佐藤太郎（TaroSato）**」の場合，ブランチ名は「**TaroSato**」
- 適当な名前のtxtファイルを作る  
- 作ったテキストファイルを`add`する
- 以下のルールに従ってコミットメッセージを記入し，`commit`する （左端は行番号）  
```
1 add [作ったテキストファイル名]
2 [空行]
3 [自分の名前]
```
例：「**佐藤太郎**」が，「**hogehoge.txt**」を作った場合  
  ```
  add hogehoge.txt

  佐藤 太郎
  ```
- リモートに`push`する
- 自分が`push`したブランチに対し，自分の名前（ローマ字）をタイトルにした`Pull request`を立てる  
例：「**佐藤太郎（TaroSato）**」の場合，`Pull request`のタイトルは「**TaroSato**」
- 他の誰かにレビューをお願いする
- レビューした人 or 自分が，`merge`された`branch`を削除する
### おしまい

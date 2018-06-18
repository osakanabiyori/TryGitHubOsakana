# TryGitHubOsakana
## はじめに
※取り敢えずこれやって，GitHubに関する基本的な操作を覚えましょう
- [今日からはじめるGitHub 〜 初心者がGitをインストールして、プルリクできるようになるまでを解説](https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000)（これやれば「やってほしいこと」の内容は出来るはず）
  - [自分用 Git For Windowsのインストール手順](https://qiita.com/toshi-click/items/dcf3dd48fdc74c91b409)（環境構築の参考に，Macは純正Terminalか**iTerm2**で良いです）

※↑の各所に出てくるGitコマンドの詳細が知りたかったり，忘れたりした時は↓をどうぞ
- [サルでもわかる Git入門 〜バージョン管理を使いこなそう〜](https://backlog.com/ja/git-tutorial/)（割ととっつきやすい）
- [Git](https://git-scm.com)（ガチなやつ，以下一部紹介）
  - [Reference](https://git-scm.com/docs)（コマンドの全てが書かれている，全部読んでも良いけど膨大な時間がかかるので，分かんない時に頼る位で良いと思う）
  - [Book](https://git-scm.com/book/ja/v2)（概念から基本，応用まで色々書いてある，日本語なので読みやすいしためになるので時間あれば是非）

## やってほしいこと
1. 自分のローカルに，このリポジトリを`clone`する
2. 自分の名前（ローマ字）で`branch`を作成する  
例：「**佐藤太郎（TaroSato）**」の場合，ブランチ名は「**TaroSato**」
3. 適当な名前のtxtファイルを作る  
4. 作ったテキストファイルを`add`する
5. 以下のルールに従ってコミットメッセージを記入し，`commit`する （左端は行番号）  
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
6. リモートに`push`する
7. 自分が`push`したブランチに対し，自分の名前（ローマ字）をタイトルにした`Pull request`を立てる  
例：「**佐藤太郎（TaroSato）**」の場合，`Pull request`のタイトルは「**TaroSato**」
8. 他の誰かにレビューをお願いする
9. レビューした人 or 自分が，`merge`された`branch`を削除する
10. おしまい

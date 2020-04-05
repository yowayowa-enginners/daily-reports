# 2020/04/05
## やったこと
* annict SPA Client作り
  * Redux
    * redux(package)を使おうとしたけどreactとの連携がよくわからなかったのでhooksのuseReducerを使うことにした
      * 具体的な不明点は、store.subscribe経由でのコンポーネントへの反映がわからなかった
          * 見た記事は全部のコンポーネントをレンダリングしなおしていた。バーチャルDOMとはいえ普通そんな実装しなくない？？？？
    * annictとのAPI通信でaxiosを使っている。このaxiosはasync/awaitな実装になっているのだが、僕はasync/awaitをよくわかっていないせいでコピペでは動かず原因調査に時間がかかった
      * 未だにasync/awaitをよくわかっていないんですけど、めちゃくちゃむずいのでは？
    * 調べるとreduxでは非同期な処理は扱えないそうでredux-thunkが必要ということがわかった

## 次の日にやること
* annict SPA Client作り
  * Reduxを組み込む

## 所感
* 今日はコミットなしです
* 盛大に昼寝してしまった
* async/awaitの理解を深めようとしたり、実質sleep関数を動かすために時間がかかった
* nodejsはエラーメッセージがわかりにくすぎると思う、、、

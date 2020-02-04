# プログラミング初心者による100DaysOfCode:smile:

## Challenge & Commitment

**Commitment:** _毎日、プログラミングの学習！🖥️_

| Start Date | End Date   |
| ---------- | ---------- |
| 2020-01-23 | 2020-05-01 |

## Goals

- [x] 継続しよう
- [x] React メインでやっていこう
- [x] 周辺知識を増やしていこう(Git, アルゴリズム, WEB 技術)

## 学習の進め方

- 主に Udemy の英語講座を進めていく。以下のやり方で字幕で学習しています。
- [英語字幕しかない講座を日本語字幕にして勉強する方法を解説する【Udemy セールとおすすめ講座】
  ](https://kaleido01.com/udemy-zimaku/)
- 動画の再生スピード
  - chrome 拡張　 VideoSpeedController
  - Remember Playback Speed にチェック
    - 新しいページに移動しても、前回ページの設定が引き継がれる

## 実行予定

## 実行済

<!--

---

## 理解できない部分は、わかるところだけつまみ食い

### Day 011: 2020/02/02

**Project:**

-　[]()

**Progress:chart_with_upwards_trend::**

- ✅

**Thoughts:**

-
-->


---

## ReactPortalの学習

### Day 012: 2020/02/03

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)
- Udemy [Git： もう怖くない Git！チーム開発で必要な Git を完全マスター](https://www.udemy.com/course/unscared_git/)
- [イラスト図解式 この一冊で全部わかる Web 技術の基本 Kindle 版]

**Progress:chart_with_upwards_trend::**

- ✅ReactPortalについて
  - z-index使って親要素より上/手前に表示させたい場合？　モーダル・popup
- ✅イベント伝播の止め方
  - e.stopPropagation()
- ✅Fragmentとは
  - [React.Fragment の活用タイミング](https://qiita.com/bayarea-techblog/items/3c43c0fb545b570ef9a0)

**Thoughts:**

- 動画見る>>わからない部分はQiitaで概要掴む>>公式ドキュメント読む　の流れを作りたい


---

## 理解できない部分は、わかるところだけつまみ食い

### Day 011: 2020/02/02

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)
- Udemy [Git： もう怖くない Git！チーム開発で必要な Git を完全マスター](https://www.udemy.com/course/unscared_git/)

**Progress:chart_with_upwards_trend::**

- ✅ProgrammaticNavigation
- ✅RouterのhistoryObjectについて
  -  ProgrammaticNavigationを実現するには、独自にhistoryObject作る
- ❓URL-based selection
  - よくわからない
- ✅入力フォームに初期値入れたい
  - ReduxFormからのinitialValues活用
- ✅REST: putとpatchの違い

**Thoughts:**

- 難しくなってきた。わかる部分だけで進めていこう
- ライブラリ？使う時は公式読むべきだ

---

## ストリーム作成して一覧を画面に出力するところまで

### Day 010: 2020/02/01

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)

**Progress:chart_with_upwards_trend::**

- ✅ComputedPropertyName
  - オブジェクトの定義時、プロパティ名に変数使える。　[]
- ✅オブジェクトからあるキーバリューペアを削除して、新オブジェクトを作るには？
- ✅配列から、idをキーとした新たなオブジェクトを作る
- ✅オブジェクトを配列に変換　Object.values()
  - オブジェクトのバリューだけで配列作る
- ✅Googleでログインする時、一瞬でpopup消えるの解決

**Thoughts:**

- ES6やvanillaJSの部分での知らない知識たくさん出てきた
- 動画でわからないことあっても、他の受講者の質問で解決したりなるほどと思うところあり
- 今のところ、動画見る・書き写す・調べる・メモするなどで、1日に進むのは動画1.5h分くらい

---

## §20長いな :cry:

### Day 009: 2020/01/31

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)
- [イラスト図解式 この一冊で全部わかる Web 技術の基本 Kindle 版] 少し

**Progress:chart_with_upwards_trend::**

- ✅REST Conventions(REST-ful API?)について
  - こうしたい時はこう書け的な慣習・ルール？
- ✅JsonServer立て方
- ✅ReduxFormとconnect 両立させる書き方
- ✅コマンド:ファイルの中身出力するには？　>>　cat db.json
- ✅axios書き方--復習した

**Thoughts:**

- 動画を再生速度上げて２回目の視聴をすると、理解が進む感じ
- 理解・コード写し・全体構築手順　いっぺんにやりすぎない方が良さそう
- twitterでの報告もやっていこう
  - twitterだと、ごちゃごちゃ書くのは向いてなさそう
  - その日の一言感想とgithubへのリンク貼っていくのが良さそうかな

---

## github にリポジトリ作成！

### Day 008: 2020/01/30

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)
  - ReduxForm を使ったフォーム作成の流れ
- [Git： もう怖くない Git！チーム開発で必要な Git を完全マスター](https://www.udemy.com/course/unscared_git/)
  - §4-§5#35
- GitHub に 100DaysOfCode 用のリポジトリ作成

**Progress:chart_with_upwards_trend::**

- ✅ReduxForm 使うことで、store-component 間のやりとりが自動化される
- ✅formProps というのを受け取り、それに必要事項を記入して提出すると処理してくれるイメージか？
- ✅ フォーム送信時には handleSubmit というのを呼び出す必要あり
- ✅ バリデーション関数作ったら、reduxForm ヘルパーに渡す必要あり(connect みたいなやつ)
- ✅ エラーメッセージは meta.error で出力できる
- ✅ フォーカスが当たったら... >> meta.touched

**Thoughts:**

- リポジトリ出来たので、学習報告を毎日していこう

---

## GoogleAuth の復習

### Day 007: 2020/01/30 Wed

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)　--- §17,18

**Progress:chart_with_upwards_trend::**

- ✅ GoogleAuth を使った全体の流れ

**Thoughts:**

- 今日は復習のみ

---

## Git 三昧!

### Day 006: 2020/01/28 Tue

**Project:**

- [Git： もう怖くない Git！チーム開発で必要な Git を完全マスター](https://www.udemy.com/course/unscared_git/)
- 3 章まで一気に

**Progress:chart_with_upwards_trend::**

- ✅Git/GitHub ローカルリポジトリ作成-add-commit-GitHub に push するまで

**Thoughts:**

- Udemy ディスカウント中だったので、git 講座購入:moneybag:
- 日本語講座だと 1.5 倍速で見られるので捗る。

---

## Google でログイン的なもの　+ フォーム処理

### Day 005: 2020-01-27 Mon

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)　--- §17,18,19

**Progress:**

- よく見る Google でログインの実装。
- ユーザーからの入力を Redux のストアで管理。軽いバリデーション

**Thoughts:**

- ReduxForm のところはライブラリ使ってるからか、いろいろ出て来て理解が難しい。。。
-

---

## シングルページアプリの謎、解明！

### Day 004: 2020-01-26 Sun

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/) - \$16 ReactRouter を使ったナビゲーション
- アプリ： [アルゴリズム図鑑]　少し
- [イラスト図解式 この一冊で全部わかる Web 技術の基本 Kindle 版] 少し

**Progress:**

- ReactRouter 内で a タグ使わないこと！　新しいページを撮りに行ってしまって、state とか api 情報とか捨てられる
- ページ内移動はアドレス変わってるけど、コンポーネントが入れ替わってるだけ　>>　シングルページアプリ

**Thoughts:**

- なぜシングルページアプリと呼ばれているのか理解。
- 今回のセクションから twitch っぽいアプリ制作開始。
- ページ遷移やら認証、フォーム処理などよくあるパターン学ぶ。面白そう

---

## state 変えるな！の話。userId オーバーフェッチの話。

### Day 003: 2020-01-25 Sat

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/) - §15 　通しで / 1 回目

**Progress:**

- Reducer のルール。配列・オブジェクトは参照先変えないと同じものと判断される。
- state 変えたいなら、新しい配列・オブジェクトで！

**Thoughts:**

- 配列・オブジェクトを変更するときの書き方に ES6 出てきた。要復習
- userId オーバーフェッチの話はよくわかってない。

---

## Udemy §14 - Modern React with Redux

### Day 002: 2020-01-24 Fri

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)
- §14 通しで / １回目の視聴
- アプリ： [アルゴリズム図鑑]　少し
- [イラスト図解式 この一冊で全部わかる Web 技術の基本 Kindle 版] 少し

**Progress:**

- Redux で API リクエストを行うときの問題点。
- 非同期のアクションクリエーターに関して。
- それを解消するためのミドルウェア Redux-thunk.

**Thoughts:**

- 非同期アクションクリエーターに関しては、向こうでは面接の質問とかでもあるみたい？
- thunk 使ったリクエストの書き方を確認・復習すること

---

## Udemy §13-Modern React with Redux

### Day 001: 2020-01-23 Thu

**Project:**

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/)
- §13 通しで / 3 回目の視聴

**Progress:**

- Redux の基本的なサイクルを学習：ユーザーの選択により state が変更され、その値を取得して表示するまで
- 各登場人物の役割・仲良しグループ・全体の流れ確認
- まだ自力での output は無理そう。。。

**Thoughts:**

- 最初は何やってんだ？？？って感じだったが、復習する度に新たな発見がある感じ。
- ミニマム構成での全体処理の流れを確認・復習すること

---

## DAY 000

- Udemy [Modern React with Redux](https://www.udemy.com/course/react-redux/) --- 2020-01-12 から開始---

- [【世界で 2 万人が受講】JavaScript エンジニアのための ES6 完全ガイド](https://www.udemy.com/course/javascriptes6/) --- 2020-01-07 から 1 週間くらいで軽く

**参考教材**

- [【5 ヶ月でインターン、累計 50 以上の講座を経験】おすすめ React 講座を紹介します【Udemy セール】
  ](https://kaleido01.com/udemy-react/#st-toc-h-6)
- [英語字幕しかない講座を日本語字幕にして勉強する方法を解説する【Udemy セールとおすすめ講座】
  ](https://kaleido01.com/udemy-zimaku/)

**参考ロードマップ**

- [React 開発者ロードマップ
  ](https://github.com/adam-golab/react-developer-roadmap/blob/master/README-JA.md)
- [The 2018 React JS RoadMap
  ](https://hackernoon.com/the-2018-react-js-roadmap-4d0a43814c02)

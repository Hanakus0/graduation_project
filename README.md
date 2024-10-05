# ■ サービス概要
- "本気ではない"アイデアを投稿・評価しアイデアの質の向上を手助けするサイト


# ■ このサービスへの思い・作りたい理由
* 自分が制作物のアイデアが全く出てこない現状から「なんでもいいからアイデアの種があればなぁ」と思ったため
* 考えられている質の高いアイデアはその発案者が既にモノ・サービスとして形にしてしまっていたりする (そもそも自分でそこまで練ったアイデアを他人に教えるなんてことは無いと思う)
  * それならばアイデアの質は伴っていない段階で提示してもらって、そこから個人がアイデアを練った方が良いのではと考えた
  * 質の高いアイデアなんてものは何個も出てこないので、アイデアの質を求めてしまうとそもそもアイデアの提案が出てこないと考えた
* アイデアが気軽に公表できる場を設けることで無駄にならずに済むと思った

"思い出は億千万"というニコニコ動画のオリジナル楽曲が誰がどういった意図で投稿したかも分からない創作歌詞コメントから盛り上がっていき、結果として CD 化される程の一つの名曲の歌詞が出来上がった過程から当アプリの着想を得た

# ■ ユーザー層について
* 年齢・性別問わず
* ~~何か制作するにあたってアイデアに困っている人~~
* 開発規模に関係なくアプリ開発のアイデアに困っている人
* アイデアを考えるのが苦手もしくはアイデアの他候補が何もアイデアが無い状況の方
* 関心のあるジャンルはもちろん、特定の分野以外からのアイデアも確認できて新しい視点を得たい方

# ■サービスの利用イメージ
* ユーザーは練っていない段階のアイデア、誰かに実現してほしい他力本願的なアイデアや実現可能性を度外視した投稿が許される
  * 「完成されたアイデアではなくても良い」とすることでどんな形であれアイデアを出しやすくする
* 他の投稿から別のアイデアが思いついた場合のために、アイデアの引用元を示す情報を投稿に持たせる
  * 始めはアイデアの質が伴わなくても何度か案を練る過程を経ればアイデアの質が伴ってきたり、着眼点が変わったアイデアに変わる機会になると考えた
* スタンプ機能、コメント機能でアイデアのフィードバックを得られる
  * 没にしかけた案をフィードバックしてもらうことで本当に没にするようなアイデアなのか精査する機会となる

# ■ ユーザーの獲得について
* X(旧Twitter)での告知
* Qiita の開発記事による宣伝

# ■ サービスの差異化ポイント・推しポイント
* 没になるはずだったアイデアを気軽に他の人に評価してもらったり参考にしてもらう機会を提供できる点が差異ポイントと考える
* KJ法であったりブレーンストーミングなどアイデアを練る手法はたくさんあるがアイデアを精査したり整理したりする過程が面倒である
  * それら手法を用いて労力を割く必要が無い程の質の低いアイデア、もしくは実現可能性が低い非現実的なアイデアであっても問題ない。寧ろ大歓迎。
    * 自由度という点においてはブレーンストーミングの同じ長所を有しているといえる
* 生成 AI がかなり強力であるが、過去のデータに基づいて処理を行うことを得意としているため常識から外れたような'外れ値'(ぶっとんだ案)のようなアイデアは期待できない
  * 提案されるアイデアも基本定型文で生成 AI から生まれるアイデアには限界を感じる
* SNS やブログでは情報がアイデアに関する記述以外も混在してしまい探しづらいがこのアプリではアイデアだけに特化しているため探しやすい
  * SNS で"#アイデア"などで調べても何気ない呟きや個人日記など全くの無関係な内容もヒットしてしまう
    * そこから特定のジャンルに関してだけを絞るのも困難
* 用途とジャンルを指定可能にすることで「特定のジャンル」についてのアイデアを閲覧しやすくする
  * 「特定のジャンル」以外のアイデアも無作為ランダム表示欄を設けることで無関係なジャンルのアイデアにも触れられるようにする
* 評価・コメントする側はアイデアに対してのコメントを通じて自分の意見を共有することでコミュニティに貢献している感覚を得られる
  * ユーザー同士のフォロー機能も設けることでコミュニティ感が生まれ継続的な参加意欲を高める
* 自分の投稿に対するスタンプの数やコメントした数などを集計して表示することで参加意欲を高める
* コメントへの"いいね機能"を実装することで評価する側の参加意欲を高める
  * 投稿した側としてもそのコメントがアイデアに対しての周りからの評価が高い有力な意見として認識できる

# ■ 機能候補
* CRUDを含む基本機能
  * 会員登録
    * 性別、年齢などの設定は任意とする
  * ログイン
  * 投稿一覧表示
    * 無作為ランダム表示
    * ページング
  * 投稿 (登録)
    * タグ
    * 下書き登録
    * 画像
  * 引用投稿 (登録)
    * どの投稿から着想を得たかを表示
  * 投稿詳細
    * スタンプ (いいねボタン)
    * コメント欄
      * コメントのスタンプ (いいねボタン)
  * 投稿削除
  * 投稿編集
* ブックマーク
* ユーザー同士のフォロー
* 検索
  * キーワード検索
  * タグ検索
* 投稿ランキング
  * スタンプ数
  * コメント数
* Twitter共有

# ■ 機能の実装方針予定
| 実装機能 | 実装方法 |
|:--|:--|
| 会員登録 | Google認証 |
| タグ | Stimulus Autocomplete、Tagify |
| ユーザー画像、投稿内容貼付画像 | CarrierWave |
| ページング | kaminari |
| 検索 | ransack, FormObject |
| グラフ関連 | Chartkick |
| 投稿ランキング | 投稿に関する情報で並び替え |

---
- 【関連情報リンク】
  1. https://dic.nicovideo.jp/a/%E6%80%9D%E3%81%84%E5%87%BA%E3%81%AF%E5%84%84%E5%8D%83%E4%B8%87#:~:text=%E4%BB%8A%E5%9B%9E%E3%81%AE%E3%80%8C,%E3%81%82%E3%82%8B%E3%81%93%E3%81%A8%E3%81%A7%E3%81%99%E3%80%82
  2. https://nol-share.com/130
  3. https://w.atwiki.jp/nicoten/pages/191.html
  4. https://ameblo.jp/a6web/entry-12719767412.html

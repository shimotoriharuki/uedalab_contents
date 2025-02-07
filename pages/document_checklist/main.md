---
Copyright: (C) Ueda Lab. 2022
---

# 論文、スライド、プレゼンのチェックリスト

文責: 上田研院生のみなさん & 上田

* お断り
    * アレしちゃダメこれしちゃダメと否定形で書くより、「○○したほうがいいですよ」と書いたほうがいいんですが、まどろっこしくなるのでここではド直球で記述します。
    * 場所が変わればルールも変わるので、あくまで赤を入れる回数を減らすための上田研ルールということで。
    * ここに書いてあることより研究のほうが大事だけど、結局ここから逸脱すると研究する時間が削れるし、他の人の時間も気力も削れるので、ちゃんと守りましょう。世の中の文章は、他人に勘違いさせずに気持ちよく読んでもらうために、超絶に細かい配慮がされています。消費者側、評論家側ではなく、生産者側、表現者側にまわるということは、そういうことです。

## 共通

* 先人や出資者、協力者に敬意を払う（他人様のことを話すときはどれだけ気をつけても気をつけ足りないと思うこと）
    * 比較対象として主要な論文については、「誰が」その先行研究をしたのかを書く
        * 所属を書くとなおよい
        * 文献リストに書いてあれば省略してもよいけど、なるべく名前を本文に入れる。
    * 先行研究をぶった切るときは貢献についても言及を
        * 例: 〇〇は達成したが☓☓は疑わしい/未だなされていない
    * 外部資金の場合、どこから研究費が出ているのか必ず書く
    * 協力者には謝辞を
        * 「どこの実験環境を利用したのか」を必ず書く
        * 「誰に手伝ってもらったのか」を必ず書く
    * 「どの会社が」実験に使ったその製品を作ったのかもなるべく書く
* 数式
    * 変数や関数はイタリック体、「物体A」みたいに名前に相当するものはローマン体。
         * 添字のイタリック体、ローマン体も使い分けること
            * \\(a_t\\): \\(t\\)が時刻だとするとイタリック体
            * \\(a_\text{TOKYO}\\): TOKYOは変数ではないのでローマン体
         * sinやcos、maxとかは関数とみなせるけど、名前扱いでローマン体（\\(sin\\)と書くと\\(s, i, n\\)を掛け算したものになる。）
* 半角カンマやコロンを使う場合は、後ろに半角スペースを入れる。詰めない。
    * ダメな例:このように:の後ろを詰めると,ダメ
    * まともな例: こういうふうに, 開ける. 
    * たまに例外があるけど原則開けること
* 日本語のスライドでは、（）は全角のものを原則使用。収まりが悪いので。
    * ダメ: スカイライン(SKYLINE)
    * よい: スカイライン（SKYLINE）
* 英語の固有名詞の大文字小文字、スペースあけて表記するか等は、ちゃんと調査してから書く
    * ピンとこないかもしれないけど、漢字を間違える程度の恥ずかしさなので全力回避で
    * 商標の表記を間違えると叱られる。
        * 例: NVIDIA、GitHub、MathWorks、Movable Type、Sony（参考: http://fuwhat.com/feature/knowledge/entry-517.html ）
* 日本語の名前もなるべく忠実にするようにがんばる。公式が諦めているときは諦めてもいい。
    * 人名は不可能でなければ忠実に（山﨑は山崎と書かない。）
    * キヤノンをキャノンと書かない。
    * 吉野家の吉は上が士じゃなくて土なので「𠮷野家」と書くとよい。けど、[公式サイト](https://www.yoshinoya.com/)を見ると「吉野家」と書いてあるのでそこまでこだわらなくていい。（どっちでもいいけど一応こういう感じで頭の中で葛藤すること）
    * 鉄道会社の鉄はたまに右側が矢のことがある。UTF-8にも「鉃」がある。（さすがに細かすぎるのでどうするかは任せます。）
* むやみに漢字を使わない
    * 特に、「出来る」と書くと上田が「できる」と直すので、最初から「できる」と書いてください。
        * 年に100以上指摘しており無駄。
        * 注意: 出版社によっては「出来る」を使うところもあります。
    * 次の例は単純に使う漢字を間違っているのでどこにいってもNG
        * 「〇〇というセンサ」の「という」を「と言う」と書かない。ひらがな。
        * 「〇〇にしてみる。」の「みる」を「見る。」と書かない。ひらがな。
* ちゃんと辞典をひく
    * え？辞典なしで文章書けるんですか？すごい能力をお持ちですね。私は無理です。（上田）

## 論文

* 参考文献のリストの書式を守る。
    * 学会のテンプレートを参考のこと。
    * 間違いやすい点
         * 本まるごと引用する場合と、予稿など一部の記事を引用する場合には表記を分けることが一般的
             * 記事はダブルクォートで囲み、イタリック体にすることが多い
             * 本はダブルクォートで囲まず、イタリック体にしないことが多い
         * 学会の名前と講演会（イベント）の名前を区別のこと
    * ウェブ上のリストは表現に制限があるので、少し本来のルールから外れている場合が多い
        * 例: [このサイトの文献リスト](/?page=publication)は諸事情あって上のルールに従っていない。
        * 投稿論文のものを参考にする。（学会側で校正をかけている。）

## スライド作成

### 必須事項

* スライドにページ番号を記述
    * 表紙からページ数をカウント
    * 表紙にはページ番号を記述しない
* トップダウンで
    * こういう箇条書きは全力回避
        * ○○した
        * →○○した
        * →こうなった
    * こういう書き方に
        * ○○を試したらこうなった
            * 詳細の説明・・・
            * 詳細の説明・・・
* 引用や事例を紹介するときは[人名 西暦年]を付加
    * 例1: Uniform Monte Carlo Localization [Ueda et al. 2002]
    * 例2: Woven City [TOYOTA 2020]
    * 例3: 作物の隠れた枝の補間 [三上ら2022]
        * 日本語の論文を指す場合は日本語
    * ↑対応する論文やサイトは予稿等に書いてあればよい
* 他の人が作った手法やソフトウェアをフィーチャーしすぎない
    * 自分のやったことを話すのが筋
    * 人様のものについては、[人名 西暦年]を書いて敬意を表しつつ、自分のやったことを話すために最低限に必要な説明を書く
* 24ポイント以上のフォントを使用
    * 日本語スライドの目安（英語だと2ポイントくらい小さくしてもいいかも）
        * タイトル: 32ポイント以上
        * トップレベルの箇条書き: 28ポイント以上
        * トップより下の箇条書き: 24ポイント以上
        * 図の中は20ポイントまでオッケーだけどなるべく大きく
    * パワーポイントはテキストボックス内のフォントを自動的に小さくしようとするので注意

### 8割くらい守ること

たまにそうなってないスライドがあっても良い事項。

* なるべく体言止めに
* 「背景」、「実験」などの漠然としたタイトルは回避
    * 「背景: 移動ロボットの実用化」など、そのスライドの要旨を記述
    * 目的のスライドだけは、目的を真ん中にでかく書いて、タイトルは「目的」だけでもよい
* 各スライドの下に、そのスライドで言いたいことを四角で囲って大きく記述
    * 最初のうちは守ること
* スライド1枚60秒目安
    * 発表時間が5分以内の場合は要相談
* 行数は7行以内
* 特に事情がなければ慣れないうちはMicrosoft PowerPointを使う
    * ほかのものを使うのもいいんだけど、視覚的におとなしいスライドになりがち

### その他気をつけること

* スライドとスライドの間で話がぶった切られる構成は全力回避
    * スライドの最後の四角囲みを読めば次のスライドがだいたい何の話なのか分かるように
    * 発表練習で、スライド切替時に次のような話し方になる場合、構成を再考のこと
        * 「序論です。」
        * 「従来研究です。」
        * 「目的です。」
        * 「実験です。」
    * 構成がよい場合「前のスライドの話から、必然的にこういう話になりますよね？」という状態になるので、スライドを切り替えるときに、つなぎの言葉が入るようになる。
        * 「この研究は〇〇の話です。」
        * 「こういう背景から、過去にこのような研究が行われました。」
        * 「ただ、従来研究ではこの点が未解決なので、目的をこうしました。」
        * 「目的に対して、こう考えてこう実装しました。」
        * 「目的が達成されているか確認するために、こういう実験をします。」
        * 「結果はこうでした。」
        * 「この結果から、このようなことが言えます。」
* 慣れないうちは頭の中が飛んでしまっても、スライドを読めば要点はつかめるようなスライドを
    * 多少字が多くなってもしょうがないが、7行ルールは遵守
* 先輩にもスライド作るのが得意な人と苦手な人がいるので、得意な人のものを参考にする。
    * このまえ、無断転載で失格になった人のスライドを参考にしている3年生がいて、なぜそうなるんだと・・・

### あまり気にしなくてよいこと

* 図の図番やキャプションはつけてもつけなくてもよい

## プレゼンで話すとき

* どこを読んでいるのか指し示しながら説明
    * 聞いている方は目と耳の情報がずれるとパニックを起こす。
    * スライドに書いてないことを話していいけど、そのときは「とりあえずスライドは見ないで・・・」などと指示出し
* 台本を作らない
    * 台本ではなくスライドと、話を聞いている人を見て話す。究極的には、話を聞いている人と同じものを見て話す。
        * 上記の「指し示しながら」を台本を読みながらすることはほぼ不可能。聴衆はパニックを起こし、寝るか内職するか激怒する。
            * 激怒する人が一番他人に関心があるわけで、そういう人を悪者にしない。
        * 台本を作るとスライドに不備があっても流暢に話してしまって何も伝わらなくなる。不備は避けるべきだが、不備を見つけたら話している方も言葉に詰まったり、訂正しないといけない。
    * 慣れてきたら、聞いている人の顔を様子を見ながら説明の細かさを変える。
* 図や表を掲載した場合は、図や表を掲載した意図をまず話し、図表の中のどこを見てほしいか指し示しながら話す。
* TEDの真似をしない
    * あれは演技。練りに練った台本を読んでるだけで、インタラクティブなプレゼンではない。話をしている方もなんらかの対価を得るために出演している。（あの手のものは、裏側の利害関係までよく考えて楽しみましょう。）
    * 表面だけ真似しても雰囲気で人を騙すことにしかならない
* 学生のプレゼンでありがちだけど避ける表現集
    * 「序論です。」「目的です。」「実験です。」: 前のスライドから話がつながってないとこういう話し方になる。
    * 「その中で私は○○に注目しました。」: なんでそれが注目に値するかを説明していないときにこういう口調になる。あと、殺伐としたところでのプレゼンだと、「貴様のような知らん奴が注目してなんになる。」と思われる。
    * 「話させていただきます。」: 「話します。」
        * 「させていただきます。」は大抵「します。」で十分。
    * 外部での発表で「○○先生（指導教員）が・・・」
        * 外では基本、身内は呼び捨て。「共同研究者の上田が」「指導教員の上田が」でよい。
        * 最近はオッケーになっている気もするけど、一応気をつける。（上田は身内も全部敬称をつけてます。）

### プレゼンの際にあまり気にしなくてよいこと


* 流暢である必要は全くない。
    * 聞いている人と同じ目線で考えながら話していれば印象は悪くならないし、助けてもらえる。




# 背景・動機
カタカナ語ばかりが次々に出てきて、よく分からなくなり、やる気を無くしてしまった経験はないでしょうか。また、カタカナ語の解説がなされていなくて、結局英語まで遡って調べた経験はないでしょうか。

日本語版MDNや他の解説で、私は幾度となく経験しました。これは学習者、特に初学者の学習意欲を大きく削ぎます。「翻訳である+解説不備」が相まって、プログラミングではない部分で学習者の意欲が削がれてしまいます。

解説が不十分であるのに、「理解できない自分の頭が悪い」と結論づけてしまった人は少なくはないと思います。ただ、解説者も時間を割いて、しかもMDN等は無償で時間を割いて翻訳を作成されていたりして、結局誰も悪くないのに、学習者(初学者)への理不尽な壁が存在してしまっていると、私は感じています。

実際僕も初期の頃何度か経験しました。それもあり、今はプログラミングに関して、インプットは全て英語でしています。


何にせよ、プログラミング以外の部分で学習意欲が削がれてしまう事は、非常に勿体なく、また、無駄な機会損失だと思います。

この様な事を少しでも軽減できたらと思いこのプロジェクトを立ち上げました。


# 語彙理解までの手数(てかず)

```js
// カタカナ語の場合
(ja) カタカナ語 --> 語彙(概念)説明 [!理解!] // 2 steps

// 英語の場合
(en) term --> explanation [!理解!] // 2 steps
```




## 標準化すべき理由
上の手数表の`(ja)`が「常に漏れなく完全に」行われるなら、翻訳基準は必要ない。なぜなら、英語の場合も手数が同じだからだ。

ただ、現実問題として、(ja)が「常に漏れなく完全に」行われる事は99.9999...%ない。なぜなら、解説者のトピックに関する理解度、英語(日本語)への習熟度、説明の仕方、が千差万別だから。また、私経験にはなりますが、語句・概念の説明がなかったり、間違った説明をしているものがありました。


また、私が経験した様に、語彙の説明が不十分・曖昧な場合、理解までに更に長い手数が必要になる。

```js
(ja-2) カタカナ語 --> 語句説明(??) --> english --> definition [!理解!] // 4 steps
```




## 解決策
そこで、どの言語にもおおよそ共通して使用される基礎的用語に関し、「訳語の基準」の設定を提案します　


草案として、いくつかの翻訳語が記述してありますが、最終的には1つにまとめられれば理想だと思います。また、日本に概念が存在しないものは、そのままカタカナ語にしてあります。

<a href='https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/terms_en_ja.md'>🚀対訳語テーブル🚀</a>



### メリット
- 漢字から語彙の意味が憶測でき、なるべくネイティブに近い感覚で用語を理解できる
- よって、例え用語の解説がなくても、留まる事なく学習が進められる

### デメリット
- 




## 標準化した場合: 例1
初学者が読むと想定して…

### ×
```js
JavaScriptの値の種類は、オブジェクト、配列、文字、真偽値...
      //--> オブジェクトって何だ?? 学習が止まる
```

### ◯
```js
JavaScriptの値の種類は、物体、配列、文字、真偽値...。
      //-> 各文字の意味は理解できる。全体はまだ良く分からずとも、そのまま次に進める
```





「誤り」・「リクエスト」・「提案」など気軽にコメ飛ばして下さい~L( •̤ㅂ•̤)┘三└(•̤ㅂ•̤)」



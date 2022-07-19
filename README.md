<a href="https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/README.en.md">English version</a>

# 動機

プログラミング学習中に、「オブジェクト」「プロパティ」などの「カタカナ翻訳」が次々と現れ、圧倒されたことはないでしょうか。 また、その意味が掴めないカタカナ翻訳の説明も不足しているため文章が理解出来ず、それを解決するためにカタカナ翻訳から元の英単語を探し意味を調べる事を繰り返し、物凄く学習作業量が増えた経験はないでしょうか。

実際、僕はMDN（ja）や他のWebサイトで何度も経験しました。文章の理解が非常に困難に感じたり、学習作業量が増大して苦痛を感じた事を覚えています。結局、その後はプログラミング学習は全て英語で行なっています。


カタカナ翻訳の解説がなされないままそれらが乱用されると、学習作業量が極度に増大したり、文章やトピック全体の理解を困難にします。また、これらは学習者、特に初学者のやる気を相当に削ぐことにになります。

もしかしたらこれを読んでいるあなたも、似たような経験を既にしているかもしれませんね。


その様な出来事が起こってしまう根本的な理由は、<b>カタカナ翻訳の乱用とその解説不足が原因</b>なのです。

意味が掴めないカタカナ翻訳を乱用し、しかもその用語の説明がないのであれば、誰が読んでも、文章やトピックの意味を十分に理解することはできません。

例えば、高校英語を学習をした事がある人なら、文章の意味を理解する際に、全ての単語の意味が分かる事の重要性を体感していると思います。数パラグラフの文章中に意味の知らない単語が2,3個出現し、しかもその単語が文章全体の理解に重要な役割を果たす場合、正確にその文章を理解する事は極めて困難になります。これは日本語でも同じ事です。


カタカナ翻訳が乱用された解説文のせいで、プログラミング学習が困難なものだと感じている人が多いのではないかと僕は推察しています。ですが、本来プログラミング学習は難しいものではありません。概念が難しい訳でも複雑な訳でもありません。至ってシンプルで、論理的で、楽しいものです。プログラミングを趣味で英語ではじめて4年になる、僕の率直な感想です。


上記の様なプログラミング学習における悲劇が起こるのは、しかしながら、誰のせいでもないと僕は考えています。翻訳作成者も、親切心で、無料で、後学者のために時間を割いて翻訳を作成しています。ですが、上記の様な出来事は、間違いなく学習者にとって不条理な壁になってしまっていると感じています。


僕はコーディングやプログラミングが大好きです！だからこそ、それらの不条理な壁を取り除き、初学者や学習者がプログラミングを難しく感じ離れていくのを減らしたいと思っています。プログラミングは非常に魅力的で楽しいのだぜ！XD


因みに、英語でプログラミング学習をした場合、上記の様な事は起こりません。なぜなら、プログラミング用語や解説文は日常会話で使う平易な英単語で構成されているため、単語の意味が分からないという事がないからです。

日本語翻訳で上記の様な問題が起こってしまうのは、恐らく、英語に堪能でない日本の開発者が、日本語への翻訳作業を適切にこなせずカタカナに翻訳してしまい、意味の分からない単語が出来上がり、その結果、意味の分からない文章が出来上がってしまった、のだと思います。。


# 日本語翻訳の標準化が必要な理由
英語ネイティブが英語を読む時、日本語ネイティブが適切な日本語翻訳を読む時、日本語ネイティブがカタカナ翻訳を読む時、それぞれ3つのシチュエーションでの読者の理解までの手数を、以下に明確にしてみました。


***英語ネイティブが英語を読む時***

```js
// 英語
  用語（en）                         [理解！] // 1ステップ
```


***日本語ネイティブが適切な日本語翻訳を読む時***
```js
// 日本語
用語（js）                           [理解！] // 1ステップ

// 学習者は翻訳された日本語を知っているため、
// もしくは、日本語翻訳された「漢字」から用語の意味を推測出来るため、
// ネイティブのように用語を理解することができる
```


***日本語ネイティブがカタカナ翻訳を読む時***
```js
カタカナ翻訳（ja）
  -> 単語の定義(辞書的意味)（en/ja)   [理解！] // 2ステップ
```


上記の比較から分かる通り、適切な日本語翻訳を行えば、英語ネイティブが英語を読む時と同じ様に用語を理解する事ができます。手数も増える事はありません。


# 解決策
プログラミング用語の日本語翻訳の標準化を提案します。つまり、複数のプログラミング言語において基礎となる用語をリスト化し、リスト化された用語を「<b>適切な</b>」日本語に翻訳します。「適切な」日本語翻訳は1つ以上でもOKです。というのは、用語の意味を日本語で「適切に」表現するには、翻訳を1つに絞らない方が良い場合があるからです。日本語翻訳が2つ以上存在する場合は、解説の作成者や使用書の翻訳者が、文脈に応じ、任意に選択します。

また、例外として、日本語翻訳がカタカナのままの方が適切な場合があります。それは、

❶概念が日本語に存在しない場合  
❷カタカナ翻訳が日本でも「和製英語」として受け入れられている場合

です。以下の「基礎用語英日対訳テーブル」内でも、カタカナ翻訳を容認している単語があります。その場合、カタカナ翻訳の解説を必ず行う必要があります。


<a href='https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/terms_en_ja.md' target ='_blank'>🚀英日対訳 テーブル🚀</a>


## 例
  初学者が次の文章を読んだとしましょう...

### ×
```js
  JavaScriptの値の種類は、オブジェクト、配列、文字列、真偽値…
        //-> オブジェクトとは?? 学習が止まってしまう
```

### ◯
```js
  JavaScriptの値の種類は、物体、配列、文字列、真偽値…
        //-> 単語の意味は理解でき、とりあえず次に進める
```



# プルリクエスト、提案
プルリクエストや提案お待ちしております！やはり僕一人では、適切な翻訳を作成するのは極めて難しいと考えています。視点が偏るからです。様々な方の意見や議論を通して、質の高い、誰にでも分かりやすい適切な翻訳表現が可能になる、と考えているからです。

これが実現できれば、日本語でプログラミングを学ぶ人も、英語でプログラミングを学ぶ僕や他の方達の様に、プログラミングを学ぶのが面白くてワクワクすることになるだろうと確信しております！(*≧∀≦*)

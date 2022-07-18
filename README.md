<a href="https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/README.ja.md">日本語版</a>

# Motivation
Have you ever been overwhelmed by encountering 'katakana-translated terms', e.g., 'オブジェク', 'プロパティ', one after another. Or, Have you ever searched repeatedly from Japanese to English to understand the terms or concepts due to katakana-translated term and no explanation of the those, and did it lead you to consume a lot of time?

In fact, I had experirenced many times in MDN(ja) or other websites. This made me difficult to understand the sentence or topic, and, in additon, this also made me feel pain. So, I've been learning programming in English as of those event. 

Almost all tutorials in Japanese website uses 'katakana-translated term' with no explanation of those, and this makes the learner ,especially beginner, difficult to understand the sentence and the topic. Also, This makes the learner consume more and more time due to repetitive searching to understand the meaning of those. As a result, the learner lose motivation to continue to learn programming.

You may already experience those event.

The reason that those event occured is essentially the heavy use of katakana translations and no explanations of those terms.

Anybody else don't understand sentences that heavily contain katakana translation and no explanations of those terms.

For instance, if you'd ever learned English at high school, you may noticed the importance of knowledge of the meaning of all terms to understand the sentences. If you find two or three unknown terms in a paragraph and, in addition, if those unknown terms play important roles to grasp the whole sentence, you probably won't understand the whole sentence. This will also occur in your mother language, i.e. Japanese.

I assume that many programming learners feel difficult to learn programming as a result of heavy use of katakana translation. But, basically, neither learning programming nor the concepts in programming are difficult. It's very simple, logical and enjoyable! This is my honest feelings as I've been learning programming in four years.

This is nobody else's faultness. For creators of tutorials, those are kind enough to spare times making tutorials without fees for learners that follow. However, such deficiency definitely creates unreasonable wall for learners. 

I absolutely love coding and learning programming! So, I want to take the wall away and prevent beginners or learners from leaving programming world. Programming is compelling and enjoyable! XD

By the way, if you learn programming in English, such deficiency doesn't occur at all. The reason is that tutorials or explanations are fully composed of ordinary words, so easy to understand, not difficult at all.

The reason that such problem occur is that japanese developer who isn't proficient in English create 'katakana-translated terms' and, as a result, it led to the words or sentences that nobody understand.


# The reason why we should standardize en-ja translation of terms
below shows the steps for each language natives to understand the term in each situation; English native in English, Japanese native in proper translation, and Japanese native in katakana-translation.

***English native in English***

```
term(English)               [got it!]   // 1 step
```


***Japanese native*** in ***proper translation***
```
term(Japanese)               [got it!]   // 1 step
```


***Japanese native*** in ***katakana-translation***
```
katakana-translated-term(Japanese)
  ---> defintion(English)   [got it!]   // 2 steps
```






According to above comparison, both steps of English native and Japanese native in proper translation are the same.



# Solution
I suggest standardizing translation of terms for programming. That is, list the terms that are fundamental in any programming languages and arrange tranlsations. The translated Japanese term may be only one or more, and if those are two or more, those could be picked by the user, creator of the tutorial or translator of the documentation, according to its context.


If the concept essentially doesn't exist in Japanese, or the katakana translation is usually accepted as 'WASEI EIGO', I've tranlsated those term as 'katakana translation'.

<a href='https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/terms_en_ja.md' target='_blank'>🚀Parallel en-ja Translation Table🚀</a>



## Merit
1. It enables learners to guess the meaning of the term from the 'kanji' and to understand the term like a native
2. (1) enables learners to proceed learning even if the tutorial lacks explanation of the term



## Exmaple
Suppose beginners read the following sentence...

### ×
```js
JavaScriptの値の種類は、オブジェクト、配列、文字、真偽値...
      //--> オブジェクトって何だ?? 学習が止まる
```

### ◯
```js
JavaScriptの値の種類は、物体、配列、文字、真偽値...
      //-> 各文字の意味は理解できる。全体はまだ良く分からずとも、そのまま次に進める
```



# Pull Requests, Suggestions
Welcome to any pull requests or suggestions! I convince that this makes those who learn programming in Japanese feel interesting and exciting to learn programming, too!

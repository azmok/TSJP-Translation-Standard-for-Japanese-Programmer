# Motivation
Have you ever been overwhelmed by encountering 'katakana-formed term', e.g., 'オブジェク', 'プロパティ', one after another. Or, Have you ever searched recursively from Japanese to English to understand the terms or concepts due to katakana-formed and lack of explaination of the 'katakana-formed term'.

In fact, I had experirenced many times in MDN(ja) or other websites (So, I've been learning programming in English as of those event). This extremely discourage learners, especially beginners, and it makes extremely difficult to grasp the whole about topics. Due to this, you may concluded that it was your inability not to understand the topics. But those distress is caused by 'katakana-formed term' and lack of explanation of the terms.

In addition, those distress are essentially not relevant to programming itself.

This is not anybody else's faultness, but such deficiency definitely creates unreasonable wall for learners. For creators of tutorials, those are kind enough to spare times making tutorials for learners that follows without fees. 


I absolutely love coding and learning programming! So, I want to take the wall away and prevent beginners or learners from leaving programming world. Programming is compelling and enjoyable! XD




# General steps to understand terms in Japanese and in English

```js
// katakanaFormed-term
katakanaFormed-term(ja) 
--> explanation(ja) [Got it!] // 2 steps

// English
term(en) 
--> explanation(en) [Got it!] // 2 steps
```




# The reason why we should standardize en-ja translation of terms
Standardization is not necessary if all Japanese tutorials fulfill the two steps like above flows. The number of the steps both in Japanese and English are equal, and no problem when terms is translated into katakana-formed.

But, in fact, almost all websites don't fulfill the above condition. In worse case, the explanation about katakana-formed terms that is rare in Japanese website, do exists, but it's incorrect.

If we encounter the situation that the tutorial or the documentation contains katakana-formed term and no explanation of that term, we certainly follow the flow below:


```js
// katakanaFormed-term
katakanaFormed-term(ja) 
--> (  )
--> definition(en)
--> explanation(en) [Got it!] // 3steps
```




# Solution
I suggest standardizing translation of terms for programming, that is, listing the terms those are fundamental in any programming language, and terms listed is tranlsated from English to Japanese in parallel. The translated Japanese term may be only one or more, and if the translated Japanese are two or more, those is picked by user(creator of tutorials) accoding to context.


If the concept essentially doesn't exist in Japanese, finaly, I've tranlsated those terms to 'katakan-formed'.

<a href='https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/terms_en_ja.md'>🚀Parallel en-ja Translation Table🚀</a>



## Merit
1. Possible to guess the meaning of the term and enable to understand the term like a native
2. (1) enable learners to proceed learning if tutorial lacks explanation of the term



## Exmaple
Suppose beginners read the following sentence...

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



# Pull Requests, Suggestions
Welcome to any pull requests or suggestions! But I hope you are biligual or more(｡•ㅅ•｡)
# Motivation
Have you ever been overwhelmed encountering 'katakana translation' one after another. Or, Have you ever searched recursively from Japanese to English to understand words or concepts due to 'katakana translation' and loss of explanation of the words.

In fact, I had experirenced many times in MDN(ja) or other websites (So, I've been learning programming in English only as of those event). This extremely discourage learners, especially beginners, and it makes extremely difficult to grasp the whole. So, you may concluded that it was your inability. But those distress is caused by 'katakana translation' and loss of explanations.

In addition, those distress are essentially not relevant to programming itself.

This is not anybody else's faultness, but such deficiency definitely creates unreasonable wall for learners. For creators of tutorials, those are kind enough to spare times making tutorials for learners that follows without fees. 


For now, I absolutely love coding and learning programming! So, I want to take away the wall and prevent beginners or learners from leaving programming. Programming is compelling and enjoyable! XD




# General steps to understand terms in Japanese and English

```js
// PERFECT-katakanaTerm-translation
katakana term(ja) 
--> explanation(ja) [Got it!] // 2 steps

// English
term(en) 
--> explanation(en) [Got it!] // 2 steps
```




# The reason why we should standardize en-ja translation of terms
Standardization is not necessary if all Japanese tutorials fulfill the steps like 'perfect-katakana-translation'. The reason is that the number of the steps in both Japanese and English are same.

But, in fact, almost all websites don't fulfill the above condition. In worse case, the explanation that is rare in Japanese website exists, but the wrong explanation.


```js
// BAD-katakanaTerm-translation
katakana term(ja) 
--> ( explanation(ja) )? 
--> explanation(en) 
--> definition(en) [Got it!] // 3|4 steps
```




# Solution
そこで、どの言語にもおおよそ共通して使用される基礎的用語に関し、「用語翻訳の基準」の設定を提案します　


草案として、一つの用語に対し、いくつかの翻訳語が記述してありますが、最終的には1つにまとめられれば理想だと思います。また、日本語に概念が存在しないものは、そのままカタカナ語にしてあります。

<a href='https://github.com/azmok/TSPJ-Translation-Standard-for-Programming-in-Japan-/blob/master/terms_en_ja.md'>🚀対訳語テーブル🚀</a>



## Pros
- 漢字から語彙の意味が憶測でき、なるべくネイティブに近い感覚で用語を理解できる
- よって、例え用語の解説がなくても、留まる事なく学習が進められる

## Cons



## Exmaple
Suppose beginner reads the following...

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



# pull request, suggestion
Welcome to any pull request or suggestion! But I hope you are biligual or more(｡•ㅅ•｡)
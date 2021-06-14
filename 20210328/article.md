---
title: Qiita Markdown CheatSheet
tags: Qiita qiita-markdown Markdown CheatSheet
author: 2f0833e717
slide: false
---
本書は筆者がよく使うQiitaのMarkdownのチートシートとして`%yyyy/MM/dd% %hh:mm:ss%`にまとめたものである。

C 2021 2f0833e717

https://qiita.com/2f0833e717/items/7b1277fb50935ee2d04d

* <font color="Red">[!注意] </font>この物語はフィクションです。登場する人物・団体・名称等は架空であり、実在のものとは関係ありません。

---

↓もってけセーラー服
https://qiita.com/2f0833e717/7b1277fb50935ee2d04d.md

---

markdown中のコメント

```
<!-- This is comment. -->
```

---

## menu
[to header1](#header1)

---

# a
## aa
### aaa
#### aaaa

---

*italic*
_italic_

**bold**
__bold__

~~取り消し線~~

`囲うやつ`

<font color="Red">Red</font>

---

$\mathbb{Blackboard Bold}$

---

テキスト[^1]

[^1]: 注釈内容

テキスト[^2]

[^2]: 注釈内容

---

↓URL直貼り
https://www.google.co.jp/

↓URL直貼り（上下に空行）　➡カードになる

https://www.google.co.jp/

↓URL変えたやつ
[Google](https://www.google.co.jp/)

↓画像　※リンクではない
![Google](https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png)

↓画像サイズ指定版 width="200"　※リンクではない
<img width="200" alt="google" src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png">

---

> a
>> aa
>>> aaa

---

- a
- a
    - aa
    - aa
        - aaa
        - aaa
            - aaaa
            - aaaa

---

1. a
1. a
    1. a
    1. a
        1. a
        1. a
            1. a
            1. a
                1. a
                1. a
                    1. ...
                    1. ...

---

- [ ] タスク1
- [x] タスク2

---

|a|b|c|
|-|-|-|
|e|f|g|

| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       | This        | This         |

---

```bash
cd /var/tmp
```

---

折りたたみの 折りたたみの 折りたたみの...
<details open>
	<summary>折りたたみ1</summary>
	<details>
		<summary>折りたたみ2</summary>
	        <pre><code>cd /var/tmp</code></pre>
	</details>
	<details open>
		<summary>折りたたみ3</summary>
	</details>
</details>

---

Qiita記事のURLの末尾に「.md」をつけるとマークダウン

---

[return to menu](#menu)
### header1

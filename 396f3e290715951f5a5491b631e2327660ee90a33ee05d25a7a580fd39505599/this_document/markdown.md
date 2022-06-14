---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Markdown記法について
description: Markdownの書き方

# Micro navigationq
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: 前のページ
        url: '../thisDocument'
    next:
        content: 次ページ
        url: '#'
---
---

## Markdown記法について

これらのドキュメントは、一部を除いてMarkdown記法というフォーマットで構成されています。
Markdown記法の特徴は、文章の装飾が自動的に行われるので見た目の調整に取られる時間が減り、コンテンツの作成に集中できるようになります。
もしあなたがこのドキュメントを加筆・修正する場合は、Markdown記法を用いてページを編集、追加してください。
このページでは、Markdown記法の基本的な文法を紹介します。

[しょこるみ公式サイト](https://chocolatlumiere.com)

#### 箇条書き
Markdown記法では、HTMLをテキストエディタのように作成することが可能です。例えば箇条書きを作りたい時、

- わこ
- ゆいぽむ
- みなるん

ソースコード
```
- わこ
- ゆいぽむ
- みなるん
```

のように`-`を単語の頭につけるだけで実現できます。 

#### 表の作成
また表を作成するときも、

||るなち|みゆち|
|:---:|:---:|:---:|
|得点|18|20|

ソースコード
```
||るなち|みゆち|
|:---:|:---:|:---:|
|得点|18|20|
```

たったこれだけの直感的な入力で実現できます。

そしてそのMarkdownファイル群をまとめて、GitHub Pages(github.io)で公開しています。GitHub Pagesは、Markdown記法やHTMLで作成した文書を簡単にウェブサイトとして公開できるサービスです。ソースをGitHubで管理することにより、誰でもこの文書を加筆・修正することができます。

画像も挿入できます。
![集合写真](/assets/FUPu928VEAEGLlA.jpeg)
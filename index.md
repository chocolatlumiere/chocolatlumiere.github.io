---
# Page settings
layout: default
keywords:

# Hero section
title: chocolatlumiere document
description: パスワードを入力してください。
buttons:
    - content: Confirm
      url: 'homepage'
      external_url: false
---

<head>
<link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />
<script defer src="https://pyscript.net/alpha/pyscript.js"></script>
</head>

<p id="title" class="text-center text-7xl"></p>
<py-script output="title">
    title = 'I love PyScript'
    pyscript.write('title', title)
</py-script>

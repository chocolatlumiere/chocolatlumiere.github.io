---
# Page settings
layout: homepage
keywords:

# Hero section
title: chocolatlumiere document
description: パスワードを入力してください。
buttons:
    - content: Confirm
      url: '/homepage'
      external_url: false
---

<head>
<link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />
<script defer src="https://pyscript.net/alpha/pyscript.js"></script>
</head>

<input id="password" class="border">
<py-button id="passtest_btn" label="confirm" pys-onClick="test_pass"></py-button>
<p id='test'></p>
<py-script>
def test_pass(*ags, **kws):
    password_element = Element("password")
    input_word = password_element.element.value
    pyscript.write("test","input_word : " + input_word)
    password_element.clear()
    Window.open('https://docs.github.com/ja/pages/getting-started-with-github-pages/creating-a-github-pages-site','_blank')
</py-script>

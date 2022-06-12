<head>
  <link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />
  <script defer src="https://pyscript.net/alpha/pyscript.js"></script>
</head>
# Page settings
layout: homepage
keywords:

# Hero section
title: chocolatlumiere document
description: パスワードを入力してください。
buttons:
    - content: Confirm
      url: 'homepage'
      external_url: false

<main class="py-5 grid gap-y-4 grid-cols-1 place-items-center">
    <p id="title" class="text-center text-7xl"></p>
</main>
<py-script output="title">
    title = 'I love PyScript'
    pyscript.write('title', title)
</py-script>
